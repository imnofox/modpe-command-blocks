# Command Block Mod

Download and install [main.min.js](https://raw.githubusercontent.com/imnofox/modpe-command-blocks/master/build/main.min.js) in BlockLauncher.

You can enter commands, or Javascript to run by prepending `javascript:` or `js:`, ie `js: ModPE.showTipMessage("Hello world!");`

## Easter eggs

This mod also features [Minecraft 1.9's command block easter eggs](http://minecraft.gamepedia.com/Easter_eggs#Command_blocks).

## Javascript mode examples

Using Javascript is great, as you don't need to rely on having other mods installed, however you do need some knowledge of the ModPE functions. You can refer to the ModPE API [here](http://imnofox.github.io/zxc/).

### Take screenshot (save name as current time)

```
javascript: var d = new Date(); ModPE.takeScreenshot(d.now());
```

## Toggle mode

If the command block has toggle mode enabled, it will run when it gets powered but also when it gets unpowered.

# Sharing

Please use the [official link](https://raw.githubusercontent.com/imnofox/modpe-command-blocks/master/build/main.min.js) when distributing.
That way, the link will always be up to date with the latest version.

It would also be great if you could link back to this github repo or the [MCPE Stuffs article](http://www.mcpestuffs.com/2016/02/command-blocks-mod/) :)
