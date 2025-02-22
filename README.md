# RealTimeCutVADLibrary Distribution Repository

Dummy repository for distributing XCFrameworks and Android shared libraries, including ONNX Runtime, APM, and a C++ library utilizing APM for real-time Voice Activity Detection (VAD) in iOS and Android projects.

## Common Libraries (iOS/macOS & Android)



1. **RealTimeCutVADCXXLibrary**\
   This C++ library provides advanced real-time VAD funct[ionalities.](https://github.com/helloooideeeeea/RealTimeCutVADLibrary)\
   **[Build Source:](https://github.com/helloooideeeeea/RealTimeCutVADLibrary)**\
   [RealTimeCutVADLibrary](https://github.com/helloooideeeeea/RealTimeCutVADLibrary)

2. **webrtc\_audio\_processing**\
   WebRTC-based audio processing library featuring noise suppression and echo ca[ncellation.](https://github.com/helloooideeeeea/webrtc-audio-processing)\
   **[Build Source:](https://github.com/helloooideeeeea/webrtc-audio-processing)**\
   [WebRTC Audio Processing](https://github.com/helloooideeeeea/webrtc-audio-processing)

3. **onnxruntime.xcframework**\
   ONNX Runtime XCFramework optimized for running machine learning models re[lated to VAD.](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)\
   **[Source ZIP:](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)**\
   [ONNX Runtime Download](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)\
   The XCFramework is created by zipping the xcframework folder located one level down from the extracted directory.

## Platform-Specific Packages

### XCFrameworks (iOS/macOS)
For iOS and macOS, these libraries are distributed as XCFrameworks.

1. **RealTimeCutVADCXXLibrary.xcframework.zip**  
   Pre-built XCFramework providing advanced real-time VAD functionalities.  
   **Build Source:** [RealTimeCutVADLibrary](https://github.com/helloooideeeeea/RealTimeCutVADLibrary)

2. **webrtc_audio_processing.xcframework.zip**  
   WebRTC-based audio processing library featuring noise suppression and echo cancellation.  
   **Build Source:** [WebRTC Audio Processing](https://github.com/helloooideeeeea/webrtc-audio-processing)

3. **onnxruntime.xcframework.zip**  
   ONNX Runtime XCFramework optimized for running machine learning models related to VAD.  
   **Source ZIP:** [ONNX Runtime Download](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)  
   The XCFramework is created by zipping the xcframework folder located one level down from the extracted directory.

### Android Shared Libraries
For Android, pre-built `.so` files are included in `jniLibs.zip`.

1. **jniLibs.zip**\
   This archive contains pre-built shared libraries for Android.\
   **Structure:**

   ```
   jniLibs/
   ├── Headers
   │   ├── absl
   │   ├── onnxruntime
   │   └── webrtc_audio_processing
   ├── arm64-v8a
   │   ├── libRealtimeCutVadLibrary.so
   │   ├── libonnxruntime.so
   │   └── libwebrtc-audio-processing-1.so
   ├── armeabi-v7a
   │   ├── libRealtimeCutVadLibrary.so
   │   ├── libonnxruntime.so
   │   └── libwebrtc-audio-processing-1.so
   └── x86_64
       ├── libRealtimeCutVadLibrary.so
       ├── libonnxruntime.so
       └── libwebrtc-audio-processing-1.so
   ```

2. **webrtc\_audio\_processing for Android**\
   WebRTC-based audio processing is now available for Android, providing the same noise suppression and echo cancellation features as in iOS/macOS.

With these additions, **RealTimeCutVADLibrary** now supports both iOS/macOS and Android through XCFrameworks and shared libraries.

Additionally, ONNX Runtime for Android can be obtained from Maven Repository:
[ONNX Runtime Android AAR](https://repo1.maven.org/maven2/com/microsoft/onnxruntime/onnxruntime-android/1.20.0/onnxruntime-android-1.20.0.aar).

