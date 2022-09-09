# chooser
Allows the user to create a list of domains which open in a specific browser.
Suitable for any Unix-like system and desktop manager.

### Installation and usage:
1. Make sure you have List::Moreutils, URI::Encode and Carp installed on your system.
2. Decide which browser you want to make "special" and which one you want to use as a default for everything else
3. Edit paths for $special_browser and $default_browser accordingly
4. Create a file for $special_open with all domains you want to open in $special_browser
5. Copy the "chooser" file to someplace in your $PATH and make it executable
6. Using tools specific to your desktop environment, set chooser to be your default browser
