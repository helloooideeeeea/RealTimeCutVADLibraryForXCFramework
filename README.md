# RealTimeCutVADLibrary Distribution Repository

Dummy repository for distributing XCFrameworks and Android shared libraries, including ONNX Runtime, APM, and a C++ library utilizing APM for real-time Voice Activity Detection (VAD) in iOS and Android projects.

Latest Release is 2025/04/06

## Common Libraries (iOS/macOS & Android)

1. **RealTimeCutVADCXXLibrary**\
   This C++ library provides advanced real-time VAD functionalities.[here](https://github.com/helloooideeeeea/RealTimeCutVADLibrary)\
   [RealTimeCutVADLibrary](https://github.com/helloooideeeeea/RealTimeCutVADLibrary)

2. **webrtc\_audio\_processing**\
   WebRTC-based audio processing library featuring noise suppression and echo cancellation.[here](https://github.com/helloooideeeeea/webrtc-audio-processing)\
   [WebRTC Audio Processing](https://github.com/helloooideeeeea/webrtc-audio-processing)

3. **onnxruntime.xcframework**\
   ONNX Runtime XCFramework optimized for running machine learning models related to VAD.[here](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)\
   [ONNX Runtime Download](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)\
   The XCFramework is created by zipping the xcframework folder located one level down from the extracted directory.

## Platform-Specific Packages

### XCFrameworks (iOS/macOS)
For iOS and macOS, these libraries are distributed as XCFrameworks.

1. **RealTimeCutVADCXXLibrary.xcframework.zip**  
   Pre-built XCFramework providing advanced real-time VAD functionalities.
   
   **Source ZIP:** [RealTimeCutVADCXXLibrary.xcframework.zip](https://github.com/helloooideeeeea/RealTimeCutVADLibraryForXCFramework/releases/download/v1.0.1/RealTimeCutVADCXXLibrary.xcframework.zip)

3. **webrtc_audio_processing.xcframework.zip**  
   WebRTC-based audio processing library featuring noise suppression and echo cancellation.
   
   **Source ZIP:** [webrtc_audio_processing.xcframework.zip](https://github.com/helloooideeeeea/RealTimeCutVADLibraryForXCFramework/releases/download/v1.0.0/webrtc_audio_processing.xcframework.zip)

5. **onnxruntime.xcframework.zip**  
   ONNX Runtime XCFramework optimized for running machine learning models related to VAD.  
   **Source ZIP:** [ONNX Runtime Download](https://download.onnxruntime.ai/pod-archive-onnxruntime-c-1.20.0.zip)
   
   The XCFramework is created by zipping the xcframework folder located one level down from the extracted directory.

### Android Shared Libraries
For Android, pre-built `.so` files are included in `jniLibs.zip`.

1. **jniLibs.zip**\
   This archive contains pre-built shared libraries for Android.\
   **Source ZIP:** [jniLibs.zip Download](https://github.com/helloooideeeeea/RealTimeCutVADLibraryForXCFramework/releases/download/v1.0.1/jniLibs.zip)
   
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

3. **webrtc\_audio\_processing for Android**\
   WebRTC-based audio processing is now available for Android, providing the same noise suppression and echo cancellation features as in iOS/macOS.

With these additions, **RealTimeCutVADLibrary** now supports both iOS/macOS and Android through XCFrameworks and shared libraries.

Additionally, ONNX Runtime for Android can be obtained from Maven Repository:
[ONNX Runtime Android AAR](https://repo1.maven.org/maven2/com/microsoft/onnxruntime/onnxruntime-android/1.20.0/onnxruntime-android-1.20.0.aar).

