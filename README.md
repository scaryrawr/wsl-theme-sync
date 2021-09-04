# WSL Theme Sync

This is just a script 😅 to help with reading the registry
setting for if Windows Apps are set to run in Light or Dark
mode.

Adding it to your shell rc or profile will cause it to
evaluate whenever you run a Linux app in WSLg, which will
cause the app to then launch in a light/dark theme if it
supports GTK theming and is Wayland (I've noticed
XWayland doesn't always end up in the expected theme...).

## Dependencies

Adwaita and Adwaita-dark.

```sh
# dnf based
sudo dnf install gnome-themes-extra

# apt based
sudo apt install gnome-themes-extra
```