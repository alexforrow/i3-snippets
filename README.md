# i3-snippets
Various scripts and config snippets from my i3 environment

I make heavy use of Google Chrome's `--app` feature, which allows you to open a certain URL in a standalone window without address bar or tab support. This is great for making web apps feel like local apps and therefore not get lost amoungst other tabs. Additionally they are easy to indentify by their window properties, so can be found by i3 for focusing.

# Adaptation

These scripts are directly from my environment and may need adapting. Some things to consider

* The scripts are best suited tied to hotkeys keyboard, or keyboard shortcut
* Some scripts require [jq](https://stedolan.github.io/jq/) to be in $PATH
* I use Google Chrome with two profiles. `Default` for personal and `Profile 2` for work
* These scripts are installed by Chef on my laptop, hence it not being very [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
