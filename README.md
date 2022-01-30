# mc-modpack-template
A template for a mc modpack with an intergrated buildscript written in python

## instructions for use
1. you need to have python3 and requests installed
2. you need to supply a manifest.json, generated or handmade
3. create override folders, in the format `<root>/scripts, <root>/config`

## custom deps
the format for custom deps is
in manifest.json
```
{
    ...,
     "externalDeps":[
        {
            "url" : "the url of the jar file",
            "hash" : "the hash of the mod, generated by build/getHash.py path/to/mod.jar",
            "name": "the name of the mod"
        }
    ],
    ...
}
```
