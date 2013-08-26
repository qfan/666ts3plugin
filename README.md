666ts3plugin
============

Since planetside2 crashes almost everytime ALT+TAB is used when the ts3overlay is enabled, it is very difficult for a squad leader in 666 to enable/disable Radio Ops and Squad Leader server groups. So I wrote this plugin.

You can compile it yourself by 
  1. Install latest TS3 client
  2. Find the pluginsdk folder in your TS3 installation
  3. Use Visual Studio to open (possibly also upgrade) the project file
  4. Compile to x64 platform if you are using 64bit TS3.
  5. Find the compiled "test_plugin.dll" file, rename it to 666.dll, and put it in TS3/plugins folder

Or, you can simply use the 666.dll (x64 version) pre-compiled.


To use: 

1. enable the plugin in TS3 Settings -> plugins
2. Add hotkeys in Settings-> Options -> Hotkeys
  2.1 "Add" -> "Show Advanced Actions"  -> Plugins -> Plugin Hotkey -> 666 -> set your keys for each function you want
3. Use them.

Note that the server group keys ignores the current states of the server groups, and only alter between "enable", "disable"  states blinedly. So listen to your voice feedback for actual states.
