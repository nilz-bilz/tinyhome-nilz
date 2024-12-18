# tinyhome

tinyhome generates a static HTML homepage via shell script.
Original Project: [tinyhome](https://github.com/bderenzo/tinyhome)

## Features

* Minimal dependencies (coreutils)
* Easy configuration and customisation
* Tiny optimized result page
* [Font Awesome](https://fontawesome.com/v5.15/icons?d=listing&p=2&s=solid&m=free) icons (solid only)
* Dark mode

## Demo

An example site is available [here](https://lab.bdro.fr/tinyhome/)
My instance: [here](https://nilzdash.netlify.app)

## Setup

To generate a personal dashboard:

* Clone the repository and go to the created directory
* Edit the configuration file `config.csv`
* Generate the homepage `./tinyhome | tee index.html`
* Serve the page (with the css and webfonts folders) with your favorite web server

## Configuration file

The syntax of `config.csv` file is:
```
Element, Name, Icon, Url
```

For instance:
```
heading, Heading, -, -
section, Tools, wrench, -
item, Status Page, heart, https://github.com/bderenzo/tinystatus
item, Dashboard, bookmark, https://github.com/bderenzo/tinyhome
```

