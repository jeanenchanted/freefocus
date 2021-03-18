# FreeFocus

FreeFocus is a pomodoro app for focusing on your work. That way, you can do much more in your free time rather than finishing off your work that you procrastinated off.

## How to use

Click on the arrow buttons to change how long you want the pomodoro to last for.

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