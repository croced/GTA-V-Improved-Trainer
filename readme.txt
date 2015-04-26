; THIS ARCHIVE REDISTRIBUTION IS NOT ALLOWED, USE THE FOLLOWING LINK INSTEAD
; http://www.dev-c.com/gtav/scripthookv/


							SCRIPT HOOK V SDK

v1.0.335.2

1. General concept
The main concept is that your compiled script plugin depends only on ScriptHookV.dll,
so when the game updates the only thing that user must do in order to make your
script working again is to update script hook runtime (i.e. ScriptHookV.dll).
							
2. Compilation
All samples here are being compiled using MSVC 2013, you may also use MSVC 2010
with the same *.vcxproj files but this will require changing the platfrom toolset
in project settings.

3. Native declarations
You can always get the newest version of natives.h from NATIVEDB:
http://www.dev-c.com/nativedb/

4. Terms of use
-	You are allowed to use this SDK only for writing scripts intended to work offline.
-	You are not allowed to redistribute ScriptHookV.dll with your script plugins, 
	provide the link to the latest runtime instead:
	http://www.dev-c.com/gtav/scripthookv/

5. Samples
The only one sample included is NativeTrainer, 
more detailed description is available in NativeTrainer\script.cpp

						(C) Alexander Blade 2015
								