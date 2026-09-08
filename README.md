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
