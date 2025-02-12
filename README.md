# Android iOS Emulator

A small Visual Studio Code extention to run Android or iOS Simulators in a click.  
Link to marketplace: https://marketplace.visualstudio.com/items?itemName=DiemasMichiels.emulate

**Running iOS simulators only works on Mac with Xcode!**

## Features

Select and run your emulator from Visual Studio Code.

Open command pallete `Cmd-Shift-P` -> Type `Emulator`

![Image of Emulator](https://raw.githubusercontent.com/DiemasMichiels/Emulator/master/images/emulator.gif)

## Requirements

### Android Studio

To run Android emulators you need to have Android studio and already created the Android Virtual Devices.

Add the Android Studio emulator script to your settings in Visual Studio Code:  
&nbsp;&nbsp;&nbsp;&nbsp;Mac: `"emulator.emulatorPath": "~/Library/Android/sdk/tools/emulator"`  
&nbsp;&nbsp;&nbsp;&nbsp;Windows: `"emulator.emulatorPath": "<your android home>\\Sdk\\emulator\\emulator.exe"`
&nbsp;&nbsp;&nbsp;&nbsp;Linux: `"emulator.emulatorPath": "~/Android/Sdk/emulator"`

Your visual studio code settings are found here:  
&nbsp;&nbsp;&nbsp;&nbsp;File -> Preferences -> Setting -> User Setting -> Extensions -> Emulator Configuration

### Xcode

To run iOS emulators Xcode is required.

## License

MIT License

Copyright (c) 2018 Diemas Michiels

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
