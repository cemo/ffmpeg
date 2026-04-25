# ffmpeg

Self-hosted FFmpeg build artifacts for the [cropper](https://github.com/cemo/cropper) app.

Sources are arthenica/ffmpeg-kit with iOS SDK 26 patches. Releases attached as xcframework / aar binary bundles.

## Releases

- iOS xcframework — narrow LGPL build with libwebp + libvpx (VP8/VP9)
- Android aar — TODO

## Why this exists

arthenica/ffmpeg-kit was officially retired Jan 2025 and all release binaries were deleted by April 2025. This repo hosts our own custom-built artifacts so the cropper app can keep building.

## Build instructions

See `ffmpeg-kit-build-config.md` (TODO).
