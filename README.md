# Scoop Arbitrariae Bucket [![Build status](https://ci.appveyor.com/api/projects/status/cx5wfxjavur7hasc/branch/master?svg=true)](https://ci.appveyor.com/project/pigsflew/scoop-arbitrariae/branch/master)

This is a [Scoop](https://scoop.sh) Bucket for items which I use which cannot currently be found in official (or other) scoop buckets. If any of them are later in the official buckets, they may be deprecated or removed from this source.

Add the bucket using the following snippet:

```sh
scoop bucket add arbitrariae 'https://github.com/pigsflew/scoop-arbitrariae.git'
```

This bucket's contents should be listed at [scoop.netlify's apps page](https://scoop.netlify.com/apps/).

## The Apps

You can find these apps listed in [ScoopSearch](https://scoopsearch.github.io/#/apps?%22https%3A%2F%2Fgithub.com%2Fpigsflew%2Fscoop-arbitrariae%22).

|Name|License|Description|Why Here?|
|----|-------|-----------|---------|
|[advanced-combat-tracker](https://advancedcombattracker.com)|[Unknown](https://choosealicense.com/no-permission/)|MMORPG Log Parser|Elevated Privileges, persist rules may need adjusting. This app also autoupdates itself?|
|[ffxivquicklauncher](https://goatcorp.github.io/)|[GPLv3.0](https://github.com/goatcorp/FFXIVQuickLauncher/blob/master/LICENSE)|An open source alternative launcher for Final Fantasy XIV.|Testing needed around auto-update from within the launcher.|
|[fluidsynth](https://www.fluidsynth.org)|[LGPL2.1](https://github.com/FluidSynth/fluidsynth/blob/master/LICENSE)|synthesizer for Soundfont 2 MIDI voices|Unclear if this is really necessary.|
|[fontbase](https://fontba.se)|[Freeware](https://fontba.se/legal/terms)|Freemium font manager with Google Fonts downloader|Works, but Idk if i actually like this program, so I don't have it installed anymore.|
|[x-mouse-button-control](https://www.highrez.co.uk/downloads/XMouseButtonControl.htm)|[Freeware](https://www.highrez.co.uk/downloads/XMouseButtonControl.htm)|A mouse reconfiguration tool.|Not fully tested, but may be a good candidate for `extras`|

## Updates

- Upgraded this repository to the new [Shovel.org GenericBucket layout](https://github.com/shovel-org/GenericBucket)
- Arbitrariae apps are listed in [ScoopSearch](https://scoopsearch.github.io/#/apps?%22https%3A%2F%2Fgithub.com%2Fpigsflew%2Fscoop-arbitrariae%22) and [rasa/scoop-directory](https://rasa.github.io/scoop-directory/by-bucket.html#pigsflew_scoop-arbitrariae).
- Corrected some things about the packages.

## TODO

- Autoupdate still seems broken.
- Better persist rules and handling autoupdaters
- Migrate these app installers to Chocolatey.

## Contact

This repository was created and is maintained by [Addie GS](https://pigsflew.com "Pigsflew.com, Addie GS' personal website").

Input is welcome, please use [issues](https://github.com/pigsflew/scoop-arbitrariae/issues) to contact me regarding questions, suggestions, improvements or bugs.

## License

Except where below noted, this repository is released under [The Unlicense](https://github.com/pigsflew/scoop-arbitrariae/blob/master/LICENSE).

The bucket structure was sourced from the [shovel-org/GenericBucket template](https://github.com/shovel-org/GenericBucket), and have been used in good faith to build, test, and deploy this repository's scoop manifests.
