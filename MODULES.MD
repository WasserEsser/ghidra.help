```diff
- Some errors may exist / tutorial maybe uncompleted. Use at your own risk.
```

## Rebuilding Existing Modules

Everything in Ghidra is basically a module project. The XXX-src packages that you see inside all of the module libs are there through the gradle build configurations. This allows for easy modular rebuilding.

For this Example I'll be using //Features//Base//

1. Extract the current //Features//Base//lib//Base-src.zip to //Features//Base//src//

![explorer_sbm9i3wcah](https://user-images.githubusercontent.com/47341117/53952265-536a5a00-409e-11e9-84b7-ce9c9990fe8c.png)

2. Just open as a new module project and copy contents of //Features//Base// to it

![eclipse_5d5cu4qxru](https://user-images.githubusercontent.com/47341117/53952214-3cc40300-409e-11e9-863d-fe0ec9ecfc85.png)
 
3. Re-Link

![inyogr5tot](https://user-images.githubusercontent.com/47341117/53952185-2ddd5080-409e-11e9-9828-c77ec8c315d3.png)

4. Add in any new or no additional features

5. Export Module Extension

![eclipse_v6rrdcfdly](https://user-images.githubusercontent.com/47341117/53952318-6c730b00-409e-11e9-9c2a-631dee4d4f91.png)

6. Export Current Project as JAR to //Base//dist//

7. Check your //Base//dist//

![winrar_njqrqlrdmx](https://user-images.githubusercontent.com/47341117/53952380-8f9dba80-409e-11e9-9662-873eccca4df4.png)

8. Copy and Extract Accordingly back to Ghidra

9. Run Ghidra again

10. ???

11. Profit

