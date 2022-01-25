# pi_screen

A UI Project for Raspberry PI and managing... Z-wave controllers and other stuff?

One could easily imagine the application consisting of different services running on a raspberry pi, polling different connected devices and exposing a UI using Flutter. So, this will basically be a test app that does this. First it will get data from some kind of Internet resource, then local services / resources that work in tandem with it. It should be usable on the Raspberry PI touchscreen, but there are some touch latency issues there that do not sound promising, however, they might not be that big of a problem given that we will most likely not do any dragging - except for sliders, of course. 

The Flutter package for Rpi works on 3s and 4s, but we might end up in a situation where we need another 4, which is totally fine. The cool part is that we can probably write the app for desktop and that's that.  

## First things first

What is the first thing I want to show on my little management screen, huh?

Lets do global covid deaths.


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
