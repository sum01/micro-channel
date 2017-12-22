# micro-channel

This is a channel for [Micro](https://github.com/zyedidia/micro) to congregate any plugins not in the [offical Micro channel](https://github.com/micro-editor/plugin-channel).  
The goal of this is to be quicker than the official channel.

Want a plugin/theme added? Open a new issue, or submit a pull request. I should be quick to add it.

## How To Use

1. Open up your `settings.json` for Micro (can be found using `eval "messenger:Message(configDir)"`)
2. Add `https://raw.githubusercontent.com/sum01/micro-channel/master/channel.json` to your `pluginchannels`, like so...

```
"pluginchannels": [
    "https://raw.githubusercontent.com/micro-editor/plugin-channel/master/channel.json",
    "https://raw.githubusercontent.com/sum01/micro-channel/master/channel.json"
],
```

3. Restart Micro, and then all the plugins should be searchable/installable.

# Plugin List

Note that I won't personally test each and every plugin, and make no promises about the quality of them.

| Name used to download                                             | Description                                                 |
| :---------------------------------------------------------------- | :---------------------------------------------------------- |
| [bookmarks](https://github.com/codezapper/micro-bookmarks-plugin) | Bookmarks plugin for micro text editor                      |
| [ctags](https://github.com/codezapper/micro-ctags-plugin)         | Adds (rudimentary) support for reading/parsing a ctags file |
| [railscast-theme](https://github.com/pbsds/micro-railscast-theme) | A colorscheme based on the RailsCast TextMate theme         |
| [bluemood-tc](https://github.com/lmintmate/blue-mood-micro)       | A port of emacs Blue Mood theme for the micro text editor   |

<!-- | [textlint](https://github.com/hidaruma/micro-textlint-plugin)     | Textlint plugin for micro-editor                            | -->
