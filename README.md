## Hex and Replace (but with files)

This is a modified version of HexAndReplace that finds and replaces hex sequences using entire files instead of strings.

The replacement file must be identical in length to the find file.

The file will be replaced as is, so make a backup first if you are not sure.

As of 2.0.0 release, files of unlimited length are supported.

Usage:

```
HexAndReplace <file> <find hex> <replace hex>

General Example:
HexAndReplace mybinaryfile.bin findfile.dat replacefile.dat

```

