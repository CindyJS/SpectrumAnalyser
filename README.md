# SpectrumAnalyser

This is part of the Lalalab exhibition of [IMAGINARY](https://lalalab.imaginary.org).
The exhibit can be used to analyse the live-spectrum of the microphone.

It is based on the [CindyJS](https://cindyjs.org)-framework.

## Installation

Just download everything and put in on a webserver and open `index.html`.

An [online version](https://raw.githack.com/CindyJS/SpectrumAnalyser/master/index.html) of this repository is served through githack.com.

For exhibits, it is recommended to use the [kiosk-browser](https://github.com/IMAGINARY/kiosk-browser) and [xbanish-hide](https://github.com/IMAGINARY/xbanish-hide) on a minified desktop environment such as [Openbox](http://openbox.org/wiki/Main_Page).


## Configuration

The applet requires a click before the CindyJS widget starts. On most browsers this is required before access to the the microphone is granted.
This behavior can be switched of by adding `?autostart=false` to the URL, i.e. opening the URL `index.html?autostart=false`.

## Author & License
Created by [Jürgen Richter-Gebert](https://geo.ma.tum.de/en/people/juergen-richter-gebert.html).

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

The framework CindyJS (`build/js`) is licensed under the Apache License 2.0.
