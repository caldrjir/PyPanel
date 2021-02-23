![IMG](docs/img/logos/nb_icon_w_text.svg)
## Introduction
A minimalistic Windows app framework powered by [DearPyGUI](https://github.com/hoffstadt/DearPyGui).

PyPanel offers a wide variety of discrete tools, such as:
- Monitoring sub-apps (i.e. Weather, HW Info, Game Server Info)
- Financial sub-apps (i.e. Stocks, Exchange rates)
- Notification sub-apps (i.e. Twitch, Youtube, Downdetector)

Sub-apps are continually added, as are performance and design features.

For upcoming sub-apps and features see [Feature Tracker](https://github.com/Finoozer/PyPanel/projects/2)

## Getting started

### Installation
Installing PyPanel couldn't be easier:
1. Head over to [Releases Page](https://github.com/Finoozer/PyPanel/releases)
2. Under Assets, you will find `PyPanel-vX.X.X.exe`, download it
3. Go through the setup wizard
4. Done!

### How to use profiles?
_Profiles are used to save your apps, settings and data._

Once you open PyPanel, the first thing you want to do is create your own profile. You can do so, by either clicking 
on `Save Profile` or `Profiles -> Add`

You will be prompted to choose a name for your profile. After clicking on `Add` your profile is loaded as a blank 
template. Now click on the menubar item `Apps`. Here, you'll find all the apps currently implemented in PyPanel.

_PyPanel stores not only data you put in, but also the sub-app window positions and sizes._

After you are done setting up your PyPanel workspace, hit `Save Profile`.

### RustApp
Monitor number of joined, queued and max players on a Rust server using Battlemetrics' URL.

#### Usage

### ClockApp
A simple app to display local or remote time.

### WeatherApp
Local weather forecast. Displays temperature, precipitation type (i.e. raining, snowing) and amount (in mm/hr) for the 
next 8 days.

### PassGenApp
Generate stronger and easier to remember passwords. Based on [xkcd #936](https://xkcd.com/936/).

#### Usage

## License
PyPanel is licensed under the [MIT License](https://github.com/Finoozer/PyPanel/blob/master/LICENSE.md).