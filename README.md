# CI Toolkit

This repository had some useful tools for CI/CD, if you like or need it, just fork it.

## Change Version

This tool can change assembly verion with specific version, now only support C# project.

It looks for the two attributes, `AssemblyVersion` and `AssemblyFileVersion`, in all *.cs files under the directory and sub-directories we specified.

```
Usage: change-version [version-number] [options]

version-number:
    the specific version you want to replace with. must follow C# version pattern.

options:
    -d      The directory where tool searches.
```