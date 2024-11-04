# qt servr source codes
qtat source code with some modifications (hacks). The code is obfuscated, but i am slowly deobfuscating things that i want to modify. So in future the code will come more readable, but it will never be fully deobfuscated. 

## Compiling
#### Preparing the SDKs
We need two SDKs, AIR SDK for debugging and FLEX SDK for compiling.

For compiling you should use flex_sdk_4.6.0.23201. It can be found here: https://github.com/JamesMGreene/node-flex-sdk/blob/master/FlexSDKs.md After extracting the SDK, you should replace "flex_sdk_4.6.0.23201/frameworks/libs/air/airglobal.swc" file with "this_repo/tools/airglobal.swc" file. The tools folder is on this repository. Tools folder can be deleted after the swc file is replaced.

Next download air SDK (https://airsdk.harman.com/download). Extract it where ever you want.

Finish !!