# mcMMOAction

![Action-bar messages](https://i.imgur.com/QYvRTRA.png)

## Description

This lightweight plugin is based on the feature request from [here](https://github.com/mcMMO-Dev/mcMMO/issues/2659).
It forwards some useful mcMMO messages to the action chat. Instead that these messages spam the regular chat,
you'll see them above the item-bar and they will disappear after a shorten time. This plugin has no config. Just drop
the plugin in your plugins folder and start your server.

## Features

* Lightweight
* Notification sound for new messages (except progress)
* Support many mcMMO messages
* Supports localized messages
* Ignore the messages you don't want to see in the action bar
* Shows progress message if the user gains skill experience
* Good performance - Messages are loaded only once in a fast collection

## Supported messages (by default)

* All skill messages:
    * level-up
    * ability activate and deactivate
    * tool raise and lower
* Too tired message
* Hardcore messages
* Refresh message
* Party level-up
* Combat abilities (i.e. swords bleeding)

## Commands

* /mmoaction - toggle the action-bar for mcMMO messages
* /mmoaction progress - toggles the progress feature for the invoker

## Dependencies

* [ProtocolLib](https://dev.bukkit.org/bukkit-plugins/protocollib)
* [mcMMO](https://dev.bukkit.org/bukkit-plugins/mcmmo)

![progress](https://user-images.githubusercontent.com/6004542/30592754-0c7b1706-9d16-11e7-8136-cccde2296446.png)
