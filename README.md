NXC GUI
=======

**GUI library for NXC to make your programs for Lego NXT more beautiful and user-friendly** 

The library uses [NXC display module](http://bricxcc.sourceforge.net/nbc/nxcdoc/nxcapi/group___display_module.html) to render various UI components. 

Usage
-----

### Using copy/paste

This is the easiest and quickest way to use this library.

1. Copy `src` folder to your project directory and rename it to `nxc-gui`.

2. Add following to the top of your main NXC file:  
   ```c
   #include "nxc-gui/default-strings.nxc"
   #include "nxc-gui/nxc-gui.nxc"
   ```
3. Get inspired from `test.nxc`
4. Use and enjoy!

### Using git submodules

This is better and cleaner way to use this library, but has some extra prerequisities.  
**Prerequisities:**

- Your project uses Git
- You are familiar with Git submodules

If so, then:

1. Run `git submodule add https://github.com/FireFragment/nxc-gui` in console
2. Add following to the top of your main NXC file:  
   ```c
   #include "nxc-gui/src/default-strings.nxc"
   #include "nxc-gui/src/nxc-gui.nxc"
   
   ```
3. Get inspired from `test.nxc`
4. Use and enjoy!
