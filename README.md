# Expo CLI Error: Undefined Native Module or Constant

This repository demonstrates a common, yet often tricky, error in Expo projects involving native modules.  The issue stems from improper installation or linking of a library containing native code. This example focuses on `expo-camera` but the solution applies more broadly.

## Problem
The core problem is attempting to use a native module (like `expo-camera`) before it's correctly integrated into your Expo project. This results in runtime errors indicating the module or its constants are undefined.

## Solution
Properly installing and linking the native module (if required by the specific module) or ensuring that the module is compatible with Expo's managed workflow (using prebuilt modules where applicable). Check module documentation for specific installation instruction.