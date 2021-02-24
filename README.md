# Scoop Arbitrariae Bucket [![Build status](https://ci.appveyor.com/api/projects/status/cx5wfxjavur7hasc/branch/master?svg=true)](https://ci.appveyor.com/project/pigsflew/scoop-arbitrariae/branch/master)

This is a [Scoop](https://scoop.sh) Bucket for items which I use which cannot currently be found in official (or other) scoop buckets. If any of them are later in the official buckets, they may be deprecated or removed from this source.

Add the bucket using the following snippet:

```sh
scoop bucket add arbitrariae 'https://github.com/pigsflew/scoop-arbitrariae.git'
```

This bucket's contents should be listed at [scoop.netlify's apps page](https://scoop.netlify.com/apps/).

## The Apps

Under each app, if there are known installer issues, they will be detailed, as well as "Why Arbitrariae?", a rationale for *not* pushing this installer into the `main` or `scoop-extras` repositories.

### Advanced Combat Tracker (ACT)

**Homepage**: <https://advancedcombattracker.com>
**Source**: <https://github.com/EQAditu/AdvancedCombatTracker>

A plugin-extendable MMORPG log parser. Extremely useful for the games it supports.

**Installer Issues:**

1. ACT may need to be run with elevated privileges.
2. Persist rules may need adjusting.
3. ACT is now self-updating; this may need to be disabled.

**Why Arbitrariae?**

1. Privileged apps are generally a bad fit for the main/extras buckets.
2. ACT may encourage violating TOS for some games.
3. There is not currently a LICENSE file in the repository for ACT and I couldn't figure out what license it's released under.

### FluidSynth

**Homepage**: <https://www.fluidsynth.org>
**Source**: <https://github.com/FluidSynth/fluidsynth>

A cross-platform synthesizer for Soundfont 2 MIDI synth voices.

**Why Arbitrariae?**

1. Unclear how necessary this is. FluidSynth is generally built into player applications like VLC.

### FontBase

**Homepage**: <https://fontba.se>

A freemium graphical Font manager. Automatically loads the Google Fonts feed and allows users to easily enable/disable them.

**Installer Issues:**

1. No persist rules yet.

**Why Arbitrariae?**

1. No Persist rules yet.
2. I haven't fully tested everything and I'm not sure if anything doesn't work as is.
3. Fontbase is a little adware-y.

### X-Mouse Button Control

**Homepage**: <https://www.highrez.co.uk/downloads/XMouseButtonControl.htm>

A mouse reconfiguration tool.

**Why Arbitrariae?**

This installer is still in development, but I may request it be added to `Extras` soon.
