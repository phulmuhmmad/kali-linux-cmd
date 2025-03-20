# kali-linux-cmd
# <h1> How to reset kali linux </h1>
1. Create a New User Profile
If you only want to reset user settings (like desktop environments, terminal settings, etc.), you can create a new user profile:
Add a new user:

# sudo adduser newusername

Switch to the new user:

# su - newusername

This new user will have default settings, and you can move your files if needed.

# 2. Reset Desktop Environment Settings
If you're only resetting the desktop environment settings (like GNOME or XFCE):

Remove the configuration files for your desktop environment in your home directory:

# rm -rf ~/.config ~/.cache ~/.local
Log out and log back in. This will regenerate default configuration files.


In windows powersell venv not works then use
# Set-ExecutionPolicy RemoteSigned
in powersell admister
