# 4. Customization

![Example Linux Desktop with customization](https://preview.redd.it/ht3qxm0i00x41.png?width=1080&crop=smart&auto=webp&s=8c14e34e5ffc389f2747041f8beb54bb6167a096)

Customization is a huge advantage of using Linux over other operating systems. Due to the open source nature of Linux, many application developers give access to users to customize even the most low level things such as window decoration and styles.

#### 4.1 Basic customization
Changing the theme is a great first step in making the Linux experience custom. Updating the theme includes changing the system style, accent color, and/or the background image. To update the theme:

Open the [Activities Overview](https://help.ubuntu.com/stable/ubuntu-help/shell-introduction.html.en#activities) by moving the mouse to the top left corner or by pressing the <kbd>Super</kbd> key. Depending on specific keyboard, the <kbd>Super</kbd> might be different, but on most keyboards, it is mapped to the <kbd>Windows</kbd> key. In the text box, type "Appearance". Then select the first result.
   
This opens the Appearance menu in settings. 

The first thing in this menu is the theme style. In this menu you can change the accent color and switch to dark theme. 

Scrolling down the menu allows you to change the background image. Ubuntu comes with template backgrounds, but you can upload your own images using the *+ add picture* button.

These are the basic appearance customizations that are built in to Ubuntu. Once you are in the settings menu, you are also able to change a couple other settings to customize Ubuntu to your liking by going to "Ubuntu Desktop".

Ubuntu Desktop menu settings:
- Desktop icon size
- Alignment of desktop icons
- Dock size and orientation
- Enabling / Disabling Tiling

These are the very basic settings that can be changed with the default Ubuntu configuration. Next we are going to explain a tool used to make some more tweaks using GNOME Tweaks program.
#### 4.2 GNOME Tweaks
Due to the way that Ubuntu desktop is managed, we can use GNOME Tweaks to make a few more customizations.

1. Open a terminal using the [Activities Overview](https://help.ubuntu.com/stable/ubuntu-help/shell-introduction.html.en#activities) screen
2. In the terminal type the following command: `sudo apt install gnome-tweaks`
3. Type in password to give installation permissions

Once GNOME tweaks is installed, open the Activites Overview screen and type "Tweaks" and launch the program. This will open the following window:

![Menu of GNOME Tweaks when opening application](https://hackmd-prod-images.s3-ap-northeast-1.amazonaws.com/uploads/upload_8ae3f1af5d08ef78047399062e2537b2.png?AWSAccessKeyId=AKIA3XSAAW6AWSKNINWO&Expires=1765311877&Signature=xUlW83yFhCvBJKFukNTkUaOcWK0%3D)

On the side menu there are many different navigation menus. We have listed the most popular customizations from the menus here:

<details>
  <summary>Fonts</summary>
  <ul>
  <li>Interface font type</li>
  <li>Document font type</li>
  <li>Monospace font type</li>
  <li>Font antialiasing</li>
  <li>Font scaling</li>
  </ul>
</details>
<details>
  <summary>Appearance</summary>
  <ul>
  <li>Cursor style</li>
  <li>Icon style</li>
  <li>Background image</li>
  <li>Dark style background image</li>
  </ul>
</details>
<details>
  <summary>Sound</summary>
  <ul>
  <li>System sound themes</li>
  </ul>
</details>
<details>
  <summary>Windows</summary>
  <ul>
  <li>Titlebar click actions</li>
  <li>Titlebar buttons</li>
  <li>Click actions</li>
  </ul>
</details>

There are many more customizations with GNOME Tweaks, and we highly recomend going through them all and experimenting to make Linux yours.

#### 4.3 GNOME Extensions
Another powerful feature of GNOME being Ubuntu's desktop manager, is that it allows for extensions to be installed. These extensions can range from just adding rounded corners to redesigning the whole desktop enviornment. 

To get started:

1. Open a terminal using the [Activities Overview](https://help.ubuntu.com/stable/ubuntu-help/shell-introduction.html.en#activities) screen
2. In the terminal use the following command to install GNOME shell extensions: `sudo apt install chrome-gnome-shell`
3. Type in your password, press enter, and wait for installation to complete
4. Open Firefox
5. Install the GNOME Shell Integration extension from [Firefox Browser Add-Ons](https://addons.mozilla.org/en-US/firefox/addon/gnome-shell-integration/)
6. Browse available extensions at [GNOME Extensions list](https://extensions.gnome.org/) 

Once you select a extension to install:

1. Click on the extension to open its page
2. In the top right, press the **Install** button and confirm the permissions

Now the extension is installed. To remove an extension:

1. Open the [Activities Overview](https://help.ubuntu.com/stable/ubuntu-help/shell-introduction.html.en#activities) screen and search for *Extensions*
2. Open the Extensions app
3. Scroll until you find the extension to remove
4. Press on the three dots menu, and select *Remove*

The extension should be removed. Now that you understand how to use the built in Ubuntu customization options as well as GNOME extensions, customize your workspace to your desire. 
