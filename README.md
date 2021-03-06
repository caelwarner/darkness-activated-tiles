# Darkness Activated Tiles

![GitHub all releases](https://img.shields.io/github/downloads/caelwarner/darkness-activated-tiles/total?style=for-the-badge) ![FoundryVTT Version](https://img.shields.io/badge/FoundryVTT-v0.8.8-orange?style=for-the-badge) ![GitHub License](https://img.shields.io/github/license/caelwarner/darkness-activated-tiles?color=blue&style=for-the-badge)

Darkness Activated Tiles allows tiles to be hidden when the darkness level in a scene goes outside a customizable range. It works the same as the darkness activation range works with ambient lights and sounds.

## Installation

Installation can be done with either Foundry's built-in module browser or by using the URL below:

> https://github.com/caelwarner/darkness-activated-tiles/releases/download/0.1.0/module.json

Remember to enable the module in the **Manage Modules** menu in Foundry.

## Usage

Using Darkness Activated Tiles is simple. In a tile config menu, under the **Basic** tab, there is a setting called **Darkness Activation Range**. Just change the values to your liking, and then you're done. The tile will then only be visible whenever the darkness level in the scene is within the range or equal to the minimum/maximum.

## Supported Versions

FoundryVTT versions 0.8.x work. Versions lower than FoundryVTT 0.8.0 should work but aren't put under official compatibility because I haven't tested them.

## Found a Bug?

Check the issues on this GitHub repository to see if it's already there. If not, please report it by creating a new issue. Thanks!

## Changelog

- 0.2: 
  - Fixed module.js not being included in module.zip, therefore there was no code to load
  - Moved module.js to scripts/module.js
- 0.1: 
  - First version.
