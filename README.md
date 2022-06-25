# Hugo DevResume Theme

This is a Hugo port of [DevResume](//github.com/xriley/DevResume-Theme) by [cowboysmall](https://github.com/cowboysmall-tools/hugo-devresume-theme.git) and modified by me - a great looking resume/CV template 
designed for developers by Xiaoying Riley.

## Screenshot

![DevResume screenshot](https://raw.githubusercontent.com/mazzutti/mazzutti.github.io/main/images/screenshot.png)

## Features

### Original

- Fully Responsive
- HTML5 + CSS3
- Built on Bootstrap 4
- 1000+ FontAwesome icons
- SCSS source files included
- Compatible with all modern browsers

### Added

- Google Analytics

## Demo

You can see it in action on my [Online Resume](https://mazzutti.github.io/). 

## Contents

- [Hugo DevResume Theme](#hugo-devresume-theme)
  - [Screenshot](#screenshot)
  - [Features](#features)
    - [Original](#original)
    - [Added](#added)
  - [Demo](#demo)
  - [Contents](#contents)
  - [Installation](#installation)
  - [Getting Started](#getting-started)
    - [Setup](#setup)
    - [Viewing](#viewing)
    - [Building](#building)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

Within the root of your project execute the following:

    $ git clone https://github.com/mazzutti/mazzutti.github.io.git

## Getting Started

After successful installation as a minimum you need to take the following steps:

### Setup

Open `config.toml` and add your relevant information.

### Viewing

To view your site, execute the following: 

    $ hugo server

and go to `localhost:1313` in your browser.

### Building

To generate your site in the `public` folder, execute the following:

    $ hugo

within the root of your project.

## Contributing

Post bugs and contributions to the [issue tracker](//github.com/cowboysmall-tools/hugo-devresume-theme/issues). 
Or make a [pull request](//github.com/cowboysmall-tools/hugo-devresume-theme/pulls).

## License

This template is 100% FREE as long as you keep the footer attribution link. You do not have the rights to resell, 
sublicense or redistribute (even for free) the template on its own or as a separate attachment from any of your work.
If you’d like to use this template without the footer attribution link, you can buy the 
[commercial license](https://themes.3rdwavemedia.com/bootstrap-templates/resume/devresume-free-bootstrap-4-resume-cv-template-for-developers/)

You may change the "Ported for..." line by adding the following to the end of `config.toml`

    [params.footer]
        copyright = ""
