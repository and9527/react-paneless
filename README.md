<!--
[![NPM](https://img.shields.io/npm/v/paneless.svg)](https://www.npmjs.com/package/paneless) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
-->
# paneless

A minimal window manager that may be included in your ReactJS app.

I am developing paneless to use in a larger app. I want to be able to display multiple, overlapping windows. With paneless each window is called a _frame_. Here is a screenshot of one frame of the app with five _panes_.

- All app content is rendered in a pane.

- Frames may be minimized to a thumbnail size.

- Panes are rendered in frames.

- Each pane may be split so that a single frame may contain an arbitrary layout of multiple panes.

- Tabbed panes are implemented by this library.

- This library supports persisting layouts.

<p align="center"> <img src="/images/RR-App-ScreenShot-002.png?raw=true alt="RR App Screenshot" /> </p>


## Warning

Early development. Tried only on Chrome so far.

## Example

This repository includes an example app. Images below are of the example app, illustrating features.  

<p align="center"> <img src="/images/Paneless-All-002.png?raw=true alt="RR App Screenshot" /> </p>

Any pane's button bar is exposed by hovering the mouse around the top of the pane.

<p align="center"> <img src="/images/Paneless-Pane-BtnBar-001.png?raw=true" alt="Pane Button Bar" /> </p>


## Install

Clone this repository in a directory on your machine. Then just play around with the example app.  

Or, if you already have an app you want to include it in, then do -  

```
npm install <paneless-directory>
```  

where \<paneless-directory\> is the directory you cloned this repository in.  

## Usage

See the example app.

## License

MIT © [BradDunagan](https://github.com/BradDunagan)
