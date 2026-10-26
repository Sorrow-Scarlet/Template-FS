# Rimworld Mod Template FS

> [!IMPORTANT]
> Sharplsp & ionide requires add specific source file in .fsproj.
>
> Wildcard is not available for extensions too parse.

A template derived from [Rimworld-Mods/Template](https://github.com/Rimworld-Mods/Template).

A mod template for F# developers

## Setup

- vscode / vscodium
- sharplsp extension
- Clone the folder and start coding

## Addtions

- Removed `extensions.json` and `launch.json`

Remind that .NET is not like `golang with taskfile`. It is not easy to support 1.6 and 1.7 in the same time. If you want to update 1.6 and 1.7...

Because 1.6 uses unity and 1.7 uses waylith, you need to make 2 `.fsproj` in one repo. Share their library with .NET STANDARD... This is somehow disgusting.

What you usually see if they support both at same time. They will not update 1.6 anymore.

## Credits

- **Original Template** [Rimworld-Mods/Template](https://github.com/Rimworld-Mods/Template).
