# ff-theme-util

Utility using **inotify** to monitor gtk-theme config.

Creates matching symlinks in existing Firefox and Palemoon user profiles  
to the theme's **/usr/share/themes/{Firefox,Palemoon}/chrome** directory if provided by the theme.

Works realtime upon theme-changes with Xfce or tools like **lxappearance**  
or when using **$HOME/.gtkrc-2.0** or **$HOME/.config/gtk-3.0/settings.ini** for gtk configuration.

**ff-theme-util** should be autostarted for realtime monitoring.

A launcher .desktop file is provided.

Depends on **inotify-tools**

Designed for Manjarolinux with **Vertex(-Maia)-Themes** in mind.
