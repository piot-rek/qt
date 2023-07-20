# qt
Settings worked out

##CMakeSettings.json

Helps with errors like:

Error	C1189	#error:  "Qt requires a C++17 compiler, and a suitable value for __cplusplus. On MSVC, you must pass the /Zc:__cplusplus option to the compiler."

A CMake settings file for Visual Studio containing ready-to-go configuration (might need paths fine-tuning) when opening a QCMake project in VS. Just drop it in project folder, clean the build and rebuild.