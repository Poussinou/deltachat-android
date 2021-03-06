Delta Chat Android Client
================================================================================

This is the android client for Delta Chat.  For the core library and other common
information, please refer to [Delta Chat Core Library](https://github.com/deltachat/deltachat-core).
For ready-to-use binaries, please go to https://delta.chat .

<a href="https://f-droid.org/packages/com.b44t.messenger/" target="_blank">
<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="90"/></a>

![Logo](https://delta.chat/assets/features/start-img4.png)


Build
--------------------------------------------------------------------------------

If the core library (https://github.com/deltachat/deltachat-core) is not checked
out together with this deltachat-android, you must check out it manually using
`git submodule update --init --recursive` for this purpose.  There is no need to 
build the core library itself, deltachat-android just references them.

After that, call `ndk-build` in the `MessengerProj` directory to build the C-part
and run the project in Android Atudio.

With chance, that's it :)

---

Copyright © 2017 Delta Chat contributors
