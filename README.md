# Collapse the context menu button of docked windows in WPF DockingManager

This sample demonstrates how to hide the context menu button on docked windows using the Syncfusion WPF DockingManager. It provides a Visual Studio-like layout with tool panes (Solution Explorer, Toolbox, Properties, Output) and a Start Page document while removing the title-bar context menu button for a cleaner UI.

## What this sample shows
- Disables the context menu button for all docked panes using the DockingManager property `IsContextMenuButtonVisible="False"`.
- Basic Visual Studio-style layout using `ContentControl` panes inside the DockingManager.
- Targets .NET Framework 4.6 and references Syncfusion WPF packages via NuGet.

## Usage tips
- To re-enable the context menu button, set `IsContextMenuButtonVisible` to `True`
- You can assign pane titles with `syncfusion:DockingManager.Header` on each child element.
- Add more panes or user controls as needed to extend the layout.

## Why hide the context menu button?
Some applications prefer a minimal title bar and prevent users from opening pane context menus. Using `IsContextMenuButtonVisible="False"` ensures a consistent, simplified experience while preserving docking, auto-hide, and floating behaviors.

## About the sample
This sample provides a minimal Visual Studio-like layout using Syncfusion DockingManager and demonstrates how to collapse the title-bar context menu button across all docked panes. The layout includes common panes (Solution Explorer, Toolbox, Properties, Output) and a Start Page document, declared as ContentControls within the DockingManager. Extend it by replacing these ContentControls with your own user controls and by applying themes or additional DockingManager settings as needed.
