## Building Modules
todo

## Rebuilding Existing Modules

Everything in Ghidra is basically a module project. The XXX-src packages that you see inside all of the module libs are there through the gradle build configurations. This allows for easy modular rebuilding.

For this Example I'll be using //Features//Base//

+ Extract the current //Features//Base//lib//Base-src.zip to //Features//Base//src//
![explorer_sbm9i3wcah](https://user-images.githubusercontent.com/47341117/53952265-536a5a00-409e-11e9-84b7-ce9c9990fe8c.png)

+ Just open as a new module project and copy contents of //Features//Base// to it
![eclipse_5d5cu4qxru](https://user-images.githubusercontent.com/47341117/53952214-3cc40300-409e-11e9-863d-fe0ec9ecfc85.png)

+ Re-Link
![inyogr5tot](https://user-images.githubusercontent.com/47341117/53952185-2ddd5080-409e-11e9-9828-c77ec8c315d3.png)

+ Add in any new or no additional features

+ Export Module Extension
![eclipse_v6rrdcfdly](https://user-images.githubusercontent.com/47341117/53952318-6c730b00-409e-11e9-9c2a-631dee4d4f91.png)

+ Export JAR
![eclipse_armxgwdlnm](https://user-images.githubusercontent.com/47341117/53952144-143c0900-409e-11e9-9571-57a5f66b39b7.png)

+ Check your //Base//dist//
![winrar_njqrqlrdmx](https://user-images.githubusercontent.com/47341117/53952380-8f9dba80-409e-11e9-9662-873eccca4df4.png)

+ Copy and Extract Accordingly back to Ghidra
