# FreeFocus

FreeFocus is a pomodoro app for focusing on your work. That way, you can do much more in your free time rather than finishing off your work that you procrastinated off.

A pomodoro timer is a timer which allows you to work while the timer is running, and after the timer, you can have a small break.

This online app includes a timer, break, white noises and lofi hip-hop beats to help you focus. The settings are fully customisable.

[![button](assets/launchbutton.png)](https://freefocus.web.app/)

⠀

## Table of Contents

- [FreeFocus](#freefocus)
  - [Table of Contents](#table-of-contents)
  - [How to use](#how-to-use)
  - [Settings](#settings)
  - [Modes](#modes)
    - [Default Mode](#default-mode)
    - [Hover-only Mode](#hover-only-mode)
  - [For developers](#for-developers)
    - [How to deploy app to firebase](#how-to-deploy-app-to-firebase)
    - [How to deploy to preview channels](#how-to-deploy-to-preview-channels)
- [Changelog](#changelog)
  - [2.1.0 - 18/03/21](#210---180321)
  - [2.0.0 - 30/01/21](#200---300121)
  - [1.8.0 - 30/01/21](#180---300121)
  - [1.6.0 - 30/01/21](#160---300121)
  - [1.5.0 - 29/01/21](#150---290121)
  - [1.0.0 - 28/01/21](#100---280121)
  - [< 1.0.0 - 17/01/21](#-100---170121)

⠀

## How to use

Use the arrows to change the length of the pomodoro in minutes. Once you're ready, you can click on the centre circle to start. You must do your work during the pomodoro, then you can have a break after it finishes.

If the circle is green, the pomodoro is running. If it's red, it is paused and you must concentrate (only in hover-only mode). A blue circle means you're having a break.

This pomodoro also comes with a health bar, so you can see how long you procrastinated. Every 5 seconds of procrastination, you lose health. The loss of health depends upon what mode you're currently using.

⠀

## Settings

The settings menu can be opened by hovering over the lower-right hand corner.

- **show health bar**: toggles whether or not you can see the health bar.
- **hover-only mode**: toggles the mode between default and hover-only. More information below.
- **pomodoros until long break**: how many pomodoros you should do before you can have a long break.
- **short break length**: how long, in minutes, a short break should last.
- **long break length**: how long, in minutes, a long break should last.
- **background sounds**: white noise or lo-fi hip hop which can help you concentrate.
- **circles**: choose what background color you want.

⠀

## Modes

FreeFocus offers two different modes in order for you to get the maximum amount of focus you could get!

### Default Mode

In the default mode, you can do everything as usual. This is useful for any kinds of work, may it be physical or in the computer. If you're taking a break, hover your cursor on the heart. Taking a long break may make you lose your health.

### Hover-only Mode

If you're on desktop and your work isn't on the computer, hover mode is the best choice. You must keep your cursor on the circle, otherwise your health bar gets lower.

⠀

## For developers

How to host the app and put it on a website.

FreeFocus is hosted on Google Firebase, a free app hosting service. 

### How to deploy app to firebase

```console
$ firebase deploy --only hosting:freefocus
```

### How to deploy to preview channels

```console
$ firebase hosting:channel:deploy preview_name
```

⠀

# Changelog

## 2.1.0 - 18/03/21

  - made a Github repository for the project
  - gave the project a new website home :)

## 2.0.0 - 30/01/21

  - Polished the settings menu design.
  - The background can only be changed in the settings menu.
  - Settings menu is finished.
  - Removed 'hide health bar' animation.

## 1.8.0 - 30/01/21
  - Fixed bugs for settings.
  - Made setting variables into cloud variables.
  - Settings can only be closed with icon.
  - Added break settings.

## 1.6.0 - 30/01/21

  - Changed settings menu design.
  - Added background noise options.
  - Added lofi and white noise music.
  - Settings menu is hidden most times.

## 1.5.0 - 29/01/21

  - Added a break.
  - You still cannot change break settings.
  - How many pomodoros to a long break.
  - Long break length.
  - Short break length.
  - Fixed minor bugs.

## 1.0.0 - 28/01/21

  - Finalised design and buttons.
  - Added default mode for those who work on the device.
  - Added two switches.
  - You can now hide the health bar.
  - Made sure the circle is green instead of red before the start of the pomodoro.
  - You can now use the timer again and again without restarting.
  - Made settings more accessible.

## < 1.0.0 - 17/01/21

  - Created scratch project and added some features to it.
  - Simple pomodoro timer.
  - Hover-only mode.