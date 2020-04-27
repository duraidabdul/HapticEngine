# HapticEngine
Easy way to trigger transient haptics on iOS 13 and up, based on Apple's sample code.

https://developer.apple.com/documentation/corehaptics/updating_continuous_and_transient_haptic_parameters_in_real_time

### How to use HapticEngine

Create an instance of HapticEngine() sometime *before* you need to use it.

When you need to trigger a tap call ```hapticEngine.playHapticTransient(intensity: Float, sharpness: Float)```, where intensity and sharpness are values between 0 and 1.
