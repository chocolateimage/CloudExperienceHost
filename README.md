# OOBE from Windows 11

Windows 11 Build 26200.7171

## Navigation

Experiences and nodes found in [data/prod/navigation.json](data/prod/navigation.json)

To open an experience you can run this in either a run box, or anything with a URL entry:

- `ms-cxh://<experience name>`. Opens the cloud experience in a window.
- `ms-cxh-full://<experience name>`. Opens the cloud experience full screen.

The experience name may contain up to one slash, but the slashes don't matter, as they get removed when searching anyways.

You can append `?start=` to go to a specific point (called node?) in an "experience". Do not use `cxid`, but the name of the JSON object.

Experiences are case-insensitive, but nodes are case-sensitive.

Some examples:

- `ms-cxh-full://frxinclusive` - Opens the OOBE full screen.
- `ms-cxh://test?start=Bing` - Opens Bing in a window.
