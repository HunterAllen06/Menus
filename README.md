<details>
<summary>Disclaimer</summary>
This repo primarily exists for personal use, and so projects I'm working on that have multiple programmers can share these utility/helper classes. Again, please note that these tools are built for my own projects; <b><ins>this means that they could change in functionality at any time</ins></b>. If you plan on using them long term, I strongly suggest sticking to one version/installing a packing and sticking to it, or paying very close attention to each update/commit. Feel free to use these in your own projects or base your own code off of mine, no credit needed; just don't claim it as your own.
</details>

# Menus
A few components to help with interface menus.

## Menu.cs
A component that goes onto a GameObject that is the 'menu'. Requires a CanvasGroup component on the same GameObject.
- EnterMenu() - Calls the OnEnterMenu event, animates the menu if a MenuAnimator component is on the same GameObject.
- ExitMenu() - Calls the OnExitMenu event, animates the menu if a MenuAnimator component is on the same GameObject.
## MenuAnimator.cs
Automatically animates the menu's transform and canvas transform when the menu is entered or exited.
## MenuGroup.cs
Can be put on a GameObject that is the parent of one or more GameObjects with the Menu component to help automatically exit previous menus when a new one is entered.
