# How to add a spacer to your macOS Dock

To add a spacer to your macOS Dock, type one of the following commands into your Terminal.app:

### For a bigger spacer use:
```
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock
```
### For a smaller spacer:
```
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="small-spacer-tile";}'; killall Dock
```

Now you can move the spacer to every location in your Dock.

## Remove a spacer from your Dock

To remove a spacer, just drag and drop it off your Dock, like any other folder or application.
