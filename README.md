# vaultc
A tool for unpacking and repacking Fields of Mistria `.sav` files.

Run:

```
path/to/vaultc-x86_64-pc-windows-msvc-v0.1.0.exe --help; 
```

To see usage instructions:

```
A tool for unpacking Fields of Mistria `.sav` files. You can pack and unpack saves as needed. Made by Jonathan Spira and NPC Studio. Note: no warranty is gives given, use at your own risk

Usage: vaultc.exe <COMMAND>

Commands:
  pack      Packs a directory of JSON + Farm Buffer data into single .sav file, which Fields of Mistria has been using since 0.11.5
  unpack    Unpacks a .sav file into a directory of JSON + Farm Buffer data. This resembles the only save files
  help      Print this message or the help of the given subcommand(s)

Options:
  -h, --help     Print help
  -V, --version  Print version
```

You can also run:

```
path/to/vaultc-x86_64-pc-windows-msvc-v0.1.0.exe pack --help;
path/to/vaultc-x86_64-pc-windows-msvc-v0.1.0.exe unpack --help;
```

to get instructions on each subcommand.
