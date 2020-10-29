# DisableRecipeBookCrafting

**Compatible with Minecraft 1.12+ (Tested on Minecraft 1.16.3)**

**Requires [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) to be installed on the server**

## Description
This plugin will disable players ability to use the crafting functionality of the Recipe Book. This applies to all non-opped players by default.

Allow specific users or groups this functionality with the `disablerecipebookcrafting.exempt` permission (default: OPs)

This functionality is blocked on the packet level. This plugin is useful for... reasons.

## How do I obtain it?

You can compile it yourself by using Maven and simply running the following command in the project folder:
(The jar file will be located in /targets/)

```
mvn package
```

You can also download the latest pre compiled binary over on the releases section of Github, located here:

https://github.com/Puremin0rez/DisableRecipeBookCrafting/releases

## Can I use your code?

Yes! This project is licensed as MIT. Refer to the project license here: [LICENSE.md](LICENSE.md)

Basically, yeah, do whatever you'd like. Giving credit would be appreciated :)

## Acknowledgements

* dmulloy2 and aadnk for creating the extremely useful ProtocolLib library
* You, for reading this and checking out the project.
