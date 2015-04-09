The Master Plan
===============

Overview (15 minutes)             (17)
--------
Effectively just a table of contents. Not much to see here.


Background
----------
- Developer View                  (10)
- System Architeture              ( 2)
  - Android Linux Kernel          (31)
  - Hardware                      (16)
  	- ****** Intermission LAB ******
  - System Services               ( 9)
  - Application Framework         ( 3)
  - User Space                    (19)
  - Application Layer             ( 6)
- System Startup                  (16)
- ****** Study LAB ******
  - ### build the kernel
    - haven't looked at build system yet
    - kernel not part of sources anyway
    - git overview?
    - git clone kernel source
    - build instructions... must write them


AOSP
----
- Getting the Code                ( 6)
- Understanding the codebase      ( 7)
- Build Environment               (13)
  - ### familiarize with build/envsetup.sh commands
- ADB in depth                    (15)
- Emulator in depth               ( 4)
- ****** LAB build AOSP, run emulator, test telnet commands ******
  - ### Familiarize yourself with the code
    - look for...
      - where OS calls an app
      - what happens when user taps icon
        - similar question to "what happens when you click a link"
      - source code for interesting system apps
        - system settings
        - calculator
        - Phone dialer
        - Launcher
      - SDK
        - adb
          - where does it get serial number
        - fastboot
        - monitor (DDMS)
        - emulator
        - apkbuilder
          - preview for Reverse Engineering class

AOSP Build System
-----------------
- AOSP Build System               (10)
  - Go a little deeper
  - Look at a lot of code
- Customizing AOSP                ( 8)
  - ### build Cyanogenmod?

Hardware
--------
- Basics                          ( 8)


User Space
----------
- Filesystems and Partitions      (17)
  - ****** imgtool LAB ******
    - ### 
- Exploring Android User Space    ( 8)
- Daemons                         (25)
  - Core
  - Network
  - Graphics & Media
  - Other


NDK/JNI (no slides! yet...)
-------
- 
- ### Develop Native JNI C method
  - better to be in Advanced Android Development course?
