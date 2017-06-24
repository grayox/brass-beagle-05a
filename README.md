## References

#### Demos

|Name|Demo|Source|
|Vaadin Board|[Demo](https://demo.vaadin.com/vaadin-board/)|[Source](https://github.com/vaadin/vaadin-board-demo)|
|Moji Brag|[Demo](https://mojibrag.firebaseapp.com/)|[Source](https://github.com/notwaldorf/mojibrag)|
|Blocks Dashboard|[Demo](http://www.prepbootstrap.com/bootstrap-theme/single-page-admin/preview/index.html)|None|
|Home Assistant|[Demo](https://home-assistant.io/demo/)|[Source](https://github.com/home-assistant/home-assistant-polymer)|
|Polymer Admin|[Demo](https://polymer-admin.firebaseapp.com/)|[Source](https://github.com/akveo/polymer-admin)|
|Admin Template|[Demo](http://demo.tb3.co.in/polymer/admin-starter-theme/theme/#dashboard)|[Source](https://github.com/akveo/polymer-admin)|
|Vaadin Dashboard Demo|[Demo](https://demo.vaadin.com/dashboard/)|[Source](https://github.com/vaadin/dashboard-demo)|
|Vaadin Valo Theme|[Demo](https://demo.vaadin.com/valo-theme/)|[Source](https://github.com/vaadin/valo-demo)|
|Vaadin Expense Manager|[Demo](https://demo.vaadin.com/expense-manager/)|[Source](https://github.com/vaadin/expense-manager-demo)|
|Vaadin Fitness Tracker|None|[Source](https://github.com/vaadin/fitness-tracker-demo)|
|Hoverboard|[Demo](https://hoverboard-master.firebaseapp.com)|[Source](https://github.com/gdg-x/hoverboard)|

[List of Polymer Projects](https://github.com/abdonrd/PolymerProjects)

#### How to Run Github Source Code
```
git clone https://github.com/vaadin/vaadin-board-demo
cd vaadin-board-demo
bower install
polymer serve
```

#### Vaadin License
[30-day free trial license for Vaadin Charts](https://vaadin.com/directory#!addon/vaadin-charts)
and clicking the orange "Free trial key" button.
It gives you a trial key. [See the help section](https://vaadin.com/directory/help/installing-cval-license)
which shows you how to install the key.

#### Themes and Colors
[Reference](http://paletton.com/)
|Base|Complementary|Palette|Source|
|#0079FF|#FF9A00|[Palette](http://paletton.com/#uid=23B0u0k++++qKZWAF+V+VAFZWqK)|Apple osX, iOS, Valo?|
|#00B4F0|#FF8300|[Palette](http://paletton.com/#uid=23p0u0k++VZrFZTEh+V+VyeZZpQ)|Vaadin (Theme-A) primary ("--water")|
|#33383A|#5C5751|[Palette](http://paletton.com/#uid=23q0u0k42bB2+n-3-hC5X4Df15m)|Vaadin (Theme-A) secondary ("--charcoal")|
|#414B56|#847661|[Palette](http://paletton.com/#uid=23B0u0k8vgy4AqO6Lln9A9Ah+9C)|Vaadin (Theme-B) secondary [`valo-menu-background-color`](https://github.com/vaadin/dashboard-demo/search?utf8=%E2%9C%93&q=valo-menu-background-color&type=)|
|#1879DB| Valo Theme Primary ("--water", gradient: low:rgb(22, 110, 213), mid:rgb(24, 121, 219), high:rgb(27, 135, 227) | #166ED5, #1879DB, #1B87E3 ) (measured by Digital Color Meter | macOS > Utilities)
|#1778DC| Valo Theme Primary ("--water", rgb(23, 120, 220)) (measured by Digital Color Meter | macOS > Utilities)
|#187CDD| Valo Theme Primary ("--water", rgb(24, 124, 221)) (measured by Digital Color Meter | macOS > Utilities)
|#4B4B4B| Valo Theme Secondary ("--charcoal", rgb(75, 75, 75)) (measured by Digital Color Meter | macOS > Utilities)
|#434343| Valo Theme Secondary-selected ("--charcoal-dark", rgb(67, 67, 67)) (measured by Digital Color Meter | macOS > Utilities)
|#585858| Valo Theme Secondary-selected ("--charcoal-light", rgb(88, 88, 88)) (measured by Digital Color Meter | macOS > Utilities)
|#FAFAFA| Valo Theme Background ("--smoke", rgb(250, 250, 250)) (measured by Digital Color Meter | macOS > Utilities)

# \<board-demo\>

Demo app for vaadin-board element

### Setup

##### Prerequisites

First, install [Polymer CLI](https://github.com/Polymer/polymer-cli) using
[npm](https://www.npmjs.com) (we assume you have pre-installed [node.js](https://nodejs.org)).

    npm install -g polymer-cli

##### Install dependencies

    bower install


### Start the development server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve --open
