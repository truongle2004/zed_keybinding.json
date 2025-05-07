# zed_keybinding.json
```js
[
  {
    "context": "Workspace",
    "bindings": {
      // "shift shift": "file_finder::Toggle"
    }
  },
  {
    "context": "Editor && mode == full",
    "bindings": {
      "ctrl j": null
    }
  },
  {
    "context": "Editor",
    "bindings": {
      "ctrl j": "editor::ContextMenuNext",
      "ctrl k": "editor::ContextMenuPrevious"
    }
  },
  {
    "context": "!renaming && ProjectPanel && !VimWaiting && vim_mode != insert && !editing",
    "bindings": {
      "a": "project_panel::NewFile",
      "space e": "workspace::ActivatePaneRight"
    }
  },
  {
    "context": "Editor && vim_mode == visual && !VimWaiting && !VimObject",
    "bindings": {
      "shift-j": "editor::MoveLineDown",
      "shift-k": "editor::MoveLineUp"
    }
  },
  {
    "context": "Editor && VimControl && !VimWaiting && !menu",
    "bindings": {
      ";": "command_palette::Toggle",
      "ctrl-w z": "workspace::ToggleZoom",
      "ctrl-w t": "terminal_panel::ToggleFocus",
      "] e": "editor::GoToDiagnostic",
      "[ e": "editor::GoToPreviousDiagnostic",
      "g r": "editor::FindAllReferences",
      "shift-k": "editor::Hover",
      "space a": "editor::ToggleCodeActions",
      "space r": "editor::Rename",
      "space g o": "editor::OrganizeImports",
      "space f": "file_finder::Toggle",
      "space o": "tab_switcher::Toggle",
      "space e": "workspace::ToggleLeftDock",
      "space p": "outline::Toggle",
      "space v": "editor::GoToDefinitionSplit"
    }
  }
]


```
