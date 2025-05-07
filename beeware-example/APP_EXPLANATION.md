# BeeWare Example App: What It Does

This BeeWare example app is a simple cross-platform GUI application built with Python and the Toga library.

## Features

- **User Input:** The app displays a window with a text input labeled "Your name:".
- **Button:** There is a "Say Hello!" button.
- **Output:** When the button is pressed, the app prints a greeting with the entered name to the console.

## Structure

- The main logic is in `app.py`, which defines a `HelloWorld` class inheriting from `toga.App`.
- The UI is built using Toga widgets (`Box`, `Label`, `TextInput`, `Button`).
- The entry point is `__main__.py`, which runs the app.

## Purpose

This app demonstrates how to use BeeWare to create a native windowed application in Python that works across different operating systems.
