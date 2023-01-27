# The purpose of this fork

Originally I had planned on publishing this as a fork of [BigDebuffs](https://github.com/jordonwow/bigdebuffs), as I thought the author was inactive. That is not the case, so I've removed this addon from Wago and will be contributing changes back to BigDebuffs instead. This repository just serves as a place for me to check in code that I'm experimenting with.

If you want to install my experimental version of BigDebuffs, you can do so by [downloading the zip file on the latest releases page](https://github.com/nozzlegear/bigdebuffs/releases/latest). Unzip it and drop the DjuxDebuffs folder into your `_retail_/Interface/AddOns` folder.

```
_retail_
└── Interface
    └── AddOns
        └── DjuxDebuffs
```

### Copying BigDebuffs settings

If you need to copy BigDebuffs settings over to this experimental version, you can do the following:

1. Open your `_retail/WTF/Account/{AccountName}/SavedVariables` folder.
2. Log out of your character in WoW, if you're logged in.
3. Make a copy of the `BigDebuffs.lua` and `BigDebuffs.lua.bak` files.
4. Rename the copied files to `DjuxDebuffs.lua` and `DjuxDebuffs.lua.bak`

Your BigDebuffs settings should now be copied to this experimental addon. Make sure you only have one version of the addon running at a time!.

To copy settings from the experimental version back to BigDebuffs, you can reverse the above process. **Warning: copying experimental settings back to the original addon risks breaking the original addon's settings.**
