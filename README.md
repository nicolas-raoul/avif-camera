# AVIF Camera User Manual

## Goal
AVIF Camera is a specialized photography application designed to capture high-quality images and save them in the advanced AVIF (AV1 Image File Format). AVIF provides superior compression and better image quality compared to JPEG, allowing you to save space without sacrificing detail.

## Main Activities
1. **Camera Preview**: Upon launching the app, you will see a live preview from your device's back camera.
2. **Permission Request**: The first time you open the app, it will ask for Camera permission. This is required to see the preview and take photos.
3. **Capture**: A large, circular capture button with a camera icon is located at the bottom center of the screen.

## How to Use
1. **Launch**: Open the "AVIF Camera" app from your launcher.
2. **Grant Permission**: If prompted, allow the app to use your camera.
3. **Frame your shot**: Point the device at your subject.
4. **Capture**: Tap the large white button at the bottom.
5. **Confirmation**: A small notification (Toast) will appear saying "Saved AVIF to gallery".

## What to Expect
- **Format**: Every photo you take is saved as a `.avif` file.
- **Location**: Photos are saved in your device's standard "Pictures" folder, under a subfolder named "AVIFCamera".
- **Gallery**: Most modern gallery apps (like Google Photos) will automatically detect and display these images.
- **Quality**: The app uses a high-quality encoding (80% quality) which balances file size and visual fidelity.

## Technical Details
- **Architecture**: Built using Jetpack Compose and CameraX.
- **Encoding**: Uses the `avif-coder` library for high-performance AVIF encoding even on older Android versions.
- **Storage**: Uses `MediaStore` API for seamless integration with the Android file system.
