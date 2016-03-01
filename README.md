# Hydra-Desktop
Hydra Desktop Environment

Version: **Proof of Concept**

This is where I will slowly build up the Hydra desktop environment, it will be based on Wayland, C and HUT and may possibly utilize python as a scripting language. I may (or may not) port it or some of it's components to Windows.

The goal of this desktop environment is of course to create that perfect desktop I always dreamed of when I switched over to Linux.

**Major features include:**
* All the major features of Windows 7's base environment (it will also share a lot of things, like keyboard shortcut layout).
* Windows 7 and Windows 10 themes/modes where the DE will look and behave as a precise replica of these two environments (users can also copy over Windows icons on their own to make it look exactly the same, some features of W10's environment will be missing though) with some improvements of my own of course.
* It's own distinctive out of the box look/default theme to blow people's minds.
* Windows Explorer-like File Manager (with **all** of it's features, and probably some improvements)
* Windows-like Task Manager (With all the linux replicatable features and some improvements)
* ALSA volume mixer frontend with per-application-volume controls and optional Pulseaudio support.
* Many of the basic programs of Windows like...
 * Notepad (Will improve this one vastly, may port or fork Notepad++ to linux)
 * Run
 * msconfig
 * Games (Minesweeper, Solitaire, maybe a few extras and maybe a few of my own)
 * Windows update (haha, jk jk... or am I?)
 * Calculator
 * Image Viewer (New and Improved!)
 * Media Player (will be centered around music; may or may not support video playback, will not be default for it, Winamp mode)
 * Desktop Gadget/Widgets (Cus lol... And this stuff is pretty useful on linux; unlike windows)
 * On-Screen Keyboard
 * Management utilities (like disk manager, resource monitor and possibly event viewer)
 * Firewall (e.g. I will have the firewall emulate the behavior of Windows' firewall, this will be pretty tough)
 * Outlook (May skip this and just use thunderbird as default instead)
 * Network sharing (May use SAMBA, may develop my own approach, because I hate SAMBA)
 * User Account Control (I am not joking, it might be a gaping security hole compared to sudo, but it's what windows users are used to, it can be disabled (which will use password prompts instead), besides, I kinda like it over typing my password evreytime I need to do something administrative)
 * Disk Defragmenter (No this time I'm really joking!)
 * Device Manager (or as much of it as I can make on linux)
 * System Restore (cus we fuckin need it)
 * Windows activation (I had to make this one...)
 * Uninstall Programs Manager (Will use the package manager, and may have wine intergration)
 * All the pointless spying features of Windows 10 (Ok I'm done!)
 * And the many various option menus of Windows 7 for performance and look tweaks
* WINE Intergration features (May create a WINE front-end like Play on Linux)
* Many applications of my own (not based on/inspired by windows applications):
 * Hydra Remote
 * Hydra Macros (frontend for VKBM; which I will also make)
 * Hydra Remote Rendering (If I make it)
 * Hydra Text Editor (Will look like and possibly be a fork/port of Notepad++, and will probably be labeled that as an alias)
 * Hydra Remote Rendering(if I make it) 
 * Hydra Paint (this won't be anything like MS Paint, I promise, I'm an artist so I'll put work into this, a lot of work, this may be one of my biggest projects even)
 * Hydra Archive (Archiver, to process compressed archives... Will look and behave a lot like WinRAR probably)
 * Hydra Video Player (Bomi and MPV based high quality video player)
 * Hydra Package Manager (This will be some fancy mix of Portage and Pacman with support for AUR, gentoo package repos and my own package repos)
 * Hydra PDF (Reader and Writer; this project I may skimp on)
 * Hydra Flash Player (Probably a PPAPI/NPAPI wrapper)
 * Hydra Browser (Another one I might never actually do, it's my lowest priority of all, but could be fun)
 * Hydra Control Panel (Settings, both linux and hydra specific and ones that are some imitation of windows)
 * Hydra Develop (Development environment tailored towards working on HUT applications or extending the Hydra Desktop with themes or widgets)
 * Hydra Terminal (Because I can, might be able to look like command prompt, and emulate some of it's commands, but will be bash based of course, and a relatively normal, probably rather minimal terminal)
* Video-file looping backgrounds
* Game Engine/3D Animated Backgrounds (Possible)
* Virtual Reality Mode/Compatibility (Cus that would be pretty cool, this is again not an immediate priority, but once I have a VR headset on hand you bet I'll do this)
* And a lot of other stuff...

**To Do:**
* Develop HUT
* Create a basic desktop shell that can display windows and a background.
* Create basic window layout (borders, titlebar, titlebar context menu, etc)
* Create basic extensions (Taskbar, XWayland)
* Get a Windows 7 looking theme up and running, and develop it's major configuration and applications and extensions
 * Aero-like compositing effects
 * Taskbar with all it's functionality, and the start menu
 * File Manager
 * Context Menu Code (This will be fancy stuff)
 * Window Management Component (best to develop while I'm actually working on other components, even if it's not a part of the W7 theme)
 * Widgets (might not exactly be like the windows gadgets thing, it will have more of a... linux flair to it )
 * Run
 * On-Screen Keyboard
 * Calculator
 * Image Viewer
 * Media(Music) Player
 * User Account Control
 * Hydra Control Panel (Again not really a W7 theme component, but here is when it is first needed)
 * msconfig/hydraconfig and a whole bunch of system configuration menus that you can find throughout Windows 7
 * Firewall front-end
* Create a Windows 10 theme based on the 7 theme
* Review the theme scripting approach and make all components as modular as possible (source code is gonna be a bloody mess)
* Create the default (Hydra) Theme (and make all my work on the windows themes redundant! except it won't be, for users who want them)
 * Commission artists to create high resolution backgrounds
 * Create the titlebar and window border themeing (as well as color scheme)
 * Create the widgets and extensions needed for this theme
 * Create cursor theme
 * Create new compositing effects
* Create the rest of the applications
 * Task Manager
 * Resource Monitor
 * Disk Management (will probably be a parted front-end based loosely on gparted, Hydra theme will have it completely differently themed than the W7/W10 themes will)
 * On Screen Keyboard
 * Sound Mixer
 * Device Manager
 * System Restore
 * Network Manager
 * File Sharing (If I don't use SAMBA)
 * Printer Sharing (If I don't use SAMBA)
 * Games
 * And others not mentioned here
* ???
* Profit.
