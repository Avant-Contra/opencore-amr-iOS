
update -miphoneos-version-min=5.0 to 6.1
if -miphoneos-version-min=5.0, then: "configure: error: C++ compiler cannot create executables", on Mac 10.10, Xcode 6.1



opencore-amr-iOS
================

iOS port of opencore-amr

Refer to README which is from original package.
Refer to build_ios_xcode5.sh for build details. Please note arm64 and x86_64 requires Xcode5.

Build_ios_*.sh is modified from http://blog.csdn.net/favormm/article/details/6772097

Note that AMR-NB is for narrow band http://en.wikipedia.org/wiki/Adaptive_Multi-Rate_audio_codec

For AMR-WB encoding, refer to http://sourceforge.net/projects/opencore-amr/files/vo-amrwbenc/ or AMR Codecs as Shared Libraries http://www.penguin.cz/~utx/amr
