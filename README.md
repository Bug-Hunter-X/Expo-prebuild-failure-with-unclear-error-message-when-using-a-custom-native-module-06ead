# Expo Prebuild Failure with Unclear Error Message

This repository demonstrates a bug encountered when using Expo's `expo prebuild` command with a custom native module. The error message from `expo prebuild` is vague and doesn't offer enough information to troubleshoot effectively.

## Bug Description

When attempting to run `expo prebuild`, the build process fails with an unclear error, preventing the successful creation of a standalone app. This occurs specifically when integrating a custom native module.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run `expo prebuild`. Observe the unclear error message.

## Solution

The solution involves carefully reviewing the native module's build process, particularly the configurations in the `android` and `ios` directories. Examine build logs to identify the root cause of the failure.  Common causes include missing dependencies, incorrect linking, or platform-specific build configurations.