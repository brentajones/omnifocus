# omnifocus
Here's some Omnifocus stuff I use.

## Plugins

Here's Omnigroup's [documentation on installing plugins](https://omni-automation.com/plugins/installation.html)

### [Cycle Project Type](https://github.com/brentajones/omnifocus/blob/main/cycle-project-type.omnijs)

I wanted to be able to create projects from the keyboard, and got annoyed by needing to use the mouse to change project type. I found [this plugin](https://discourse.omnigroup.com/t/keyboard-shortcut-to-turn-selected-project-or-task-group-parent-to-sequential/63128) by unlocked2412 in the forums, but I wanted to cycle through all the types.

This works with one or multiple projects selected. The order is **sequential** -> **single-action** -> **parallel**. If you have multiple projects of different types selected, on the first run of this plugin they'll all be changed to sequential.

### [Toggle 'Complete with last action'](https://github.com/brentajones/omnifocus/blob/main/toggle-complete-with-last-action.omnijs)

I wanted to be able to toggle the "Complete with last action" checkbox with a keyboard shortcut. This will take an input of any selected Projects or Items, and if any of them has children, it will toggle its checkbox to the opposite state. Note this behavior is slightly different to my "Cycle Project Type" plugin — that plugin makes all its selected items have the same type. This one changes each item individually to the opposite state.