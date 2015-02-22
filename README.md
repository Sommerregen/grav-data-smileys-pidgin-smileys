# [Grav Smileys Data Pack -- Pidgin Smileys][project]

> Pidgin Smileys is a collection of smileys and emoticons from the [Pidgin chat program](http://pidgin.im).

## About

`Pidgin Smileys` is a collection of smileys and emoticons from the famous [Pidgin chat program](http://pidgin.im). It includes more than 170 smileys, each one having its own textual representation as can been seen [below](#contents) .

![Screenshot Pidgin Smileys](assets/screenshot.png "Pidgin Smileys Preview")

## Installation

To install this data pack, just download the zip version of this repository and unzip it under `/your/site/grav/user/data/smileys`. Then, rename the folder to `pidgin_smileys`.

You should now have all the data pack files under

	/your/site/grav/user/data/smileys/pidgin_smileys

>> NOTE: This data pack is a modular component for Grav Smileys Plugin which requires [Grav](http://github.com/getgrav/grav), [Grav Smileys Plugin](https://github.com/sommerregen/grav-plugin-smileys) and a theme to be installed in order to operate.

## Usage

To activate and use `Grav Smileys Data Pack - Pidgin Smileys` the best process is to copy the [smileys.yaml](https://github.com/sommerregen/grav-plugin-smileys/smileys.yaml) file from the [Grav Smileys Plugin](https://github.com/sommerregen/grav-plugin-smileys) into your `users/config/plugins/` folder (create it if it doesn't exist), and  set the smileys package option to

```
pack: pidgin_smileys
```

You can then use any of the below smiley acronyms in your pages and `Grav Smileys Plugin` will automatically convert them to their icon graphic file equivalent. As an example

```
I love you <3
```

will then transform to

<code>I love you ![<3](love.png "heart <3")</code>

### Contents

`Grav Smileys Data Pack - Pidgin Smileys` comes [pre-configured](pidgin_smileys.yaml) with each smiley entry having the format

```
<your-smiley-file-without-extension>:
	enabled: true | false
	acronyms: "<your space separated acronyms e.g. :-) :)>"
	description: "<your description>"
```

In other words, smilies can be disabled separately by setting `enabled: false` or modified by setting your own description and/or smiley acronyms.

By default many smiley acronyms are supported. For a detailed list, please open the configuration file [pidgin_smileys.yaml](pidgin_smileys.yaml).

## Contributing

You can contribute at any time! Before opening any issue, please search for existing issues and review the [guidelines for contributing](CONTRIBUTING.md).

After that please note:

* If you find a bug or would like to make a feature request or suggest an improvement, [please open a new issue][issues]. If you have any interesting ideas for additions to the syntax please do suggest them as well!
* Feature requests are more likely to get attention if you include a clearly described use case.
* If you wish to submit a pull request, please make again sure that your request match the [guidelines for contributing](CONTRIBUTING.md) and that you keep track of adding unit tests for any new or changed functionality.

> If you directly want to contribute an addition to Pidgin Smileys, be it a new smiley/emoticon or a package for the IM client, please visit http://pidgin.im .

### Support and donations

If you like my project, feel free to support me via [![Flattr](https://api.flattr.com/button/flattr-badge-large.png)][flattr] or by sending me some bitcoins to **1HQdy5aBzNKNvqspiLvcmzigCq7doGfLM4**.

Thanks!

## License

Copyright (c) 2015 [Benjamin Regler][github]. See also the list of [contributors] who participated in this project.

1. **Grav Smileys Data Pack - Pidgin Smileys** is [licensed](LICENSE) for use under the terms of the [MIT license][mit-license].

2. **Pidgin Smileys** is [licensed](PIDGIN_SMILEYS.LICENSE) for use under the terms of the [GPL v2 license][gpl-license].

[github]: https://github.com/sommerregen/ "GitHub account from Benjamin Regler"
[mit-license]: http://www.opensource.org/licenses/mit-license.php "MIT license"
[gpl-license]: http://opensource.org/licenses/GPL-2.0 "GPLv2 license"
[flattr]: https://flattr.com/submit/auto?user_id=Sommerregen&url=https://github.com/sommerregen/grav-data-smileys-pidgin-smileys "Flatter my GitHub project"

[project]: https://github.com/sommerregen/grav-data-smileys-pidgin-smileys
[issues]: https://github.com/sommerregen/grav-data-smileys-pidgin-smileys/issues "GitHub Issues for Grav Smileys Data Pack -- Pidgin Smileys"
[contributors]: https://github.com/sommerregen/grav-data-smileys-pidgin-smileys/graphs/contributors "List of contributors of the project"
