## Description
This project consist of the emgage documentation.

## How to run 
### Under Windows
#### Install from Nuget
* Install [Nuget.exe](https://dist.nuget.org/index.html)
* Create a folder, e.g. *C:\Tools\docfx*, under the folder, `nuget install docfx.console`
* Open command line: 

or install via zip
Download [docfx.zip](https://github.com/dotnet/docfx/releases/download/v2.59.4/docfx.zip)

Extract docfx.zip file to C:\Tools\docfx\docfx.console\tools

# Test the documentation changes locally before publishing

```batch
set PATH=%PATH%;C:\Tools\docfx\docfx.console\tools
git checkout https://github.com/emgage/emgage-docs
docfx emgage-docs\docfx.json --serve
```
To access the local document changes, Open browser with http://localhost:8080/

# Publish the document to [docs.emgage.com](https://docs.emgage.com)
Please execute the release [Argocd - emgage-docs](https://dev.azure.com/ateraplat/Emgage%20Platform/_release?_a=releases&view=mine&definitionId=53)

# Docfx docuentation 
Please refere the official documentation of [docfx tool](https://dotnet.github.io/docfx/tutorial/intro_toc.html)
