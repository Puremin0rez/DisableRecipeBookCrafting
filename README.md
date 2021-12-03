# DisableRecipeBookCrafting

**Compatible with Minecraft 1.12+ (Tested on Minecraft 1.18)**

**Requires [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) to be installed on the server**

## Description
This plugin will disable players ability to use the crafting functionality of the Recipe Book. This applies to all non-opped players by default.

Allow specific users or groups this functionality with the `disablerecipebookcrafting.exempt` permission (default: OPs)

This functionality is blocked on the packet level. This plugin is useful for... reasons.

## How do I obtain it?

You can download stable releases via Github Releases, [located here.](https://github.com/Puremin0rez/DisableRecipeBookCrafting/releases)

You can download development builds via Github Actions, [located here.](https://github.com/Puremin0rez/DisableRecipeBookCrafting/actions?query=branch%3Amaster+is%3Asuccess) (Github Account Required)

You can compile it by running the following command in the project directory:

```
./gradlew clean build
```

(The jar file will be located in `/build/libs/`)

## Can I use your code?

This project is licensed as [GPL-3.0](LICENSE) and may be used in any way that respects the aforementioned license.

## Acknowledgements

* [dmulloy2](https://github.com/dmulloy2) and [aadnk](https://github.com/aadnk) for creating the extremely useful [ProtocolLib](https://github.com/dmulloy2/ProtocolLib/) library
* [Contributors](https://github.com/Puremin0rez/DisableRecipeBookCrafting/graphs/contributors) for helping improve the project.
* You, for reading this and checking out the project.
