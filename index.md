---
layout: default
---

# Open Source

As part of my professional and personal time I use and produce different open
source projects which can be found here:

* [Pull Requests](https://github.com/search?q=is%3Apr+author%3Afgervais) (GitHub)
* [Open Hub](https://www.openhub.net/accounts/fgervais)

I think open source software is a win for everybody and so I'm trying to
contribute whenever I can. 

# Personal Projects

Project | Description
--- | ---
<a href="https://github.com/fgervais/leak-detector" target="_blank"><img src="https://raw.githubusercontent.com/fgervais/leak-detector/master/assets/img/complete.jpg" width="200"> | Detect leaks and report through an alarm and a phone notification
<a href="https://github.com/fgervais/detergent-dispenser" target="_blank"><img src="https://raw.githubusercontent.com/fgervais/detergent-dispenser/master/assets/img/board.jpg" width="200"> | Dispense a specific amount of detergent

# Professional experience

## [Distech Controls Inc.](http://www.distech-controls.com/en/ca/)

Distech is a company that specialises in making HVAC products.

As part of my daily work, I got to work on a couple Linux and Android based products,
[Apex](https://www.distech-controls.com/en/eclypse),
[Eclypse](https://www.distech-controls.com/products/detail/947828/distech-controls/eclypse-connected-system-controller---ecy-csc-series) and 
[Horyzon-C](http://www.distech-controls.com/en/ca/products/displays/).

On these products, I've been involved in quite a few things including:

* Boot sequence
* Hardware configuration
* Network connectivity
* Source code management
* Automated builds

### FIPS 140-2
On the Eclypse product, we had to get the FIPS 140-2 certification which I
participated in getting: 
[3106](https://csrc.nist.gov/projects/cryptographic-module-validation-program/certificate/3106),
[3046](https://csrc.nist.gov/projects/cryptographic-module-validation-program/certificate/3046)

### Noteworthy Bugs

As part of my work I got to debug some pretty
[interresting](https://github.com/qca/open-ath9k-htc-firmware/commit/97217c1250772c3c6dbba8b00bab70df6dbd22da#diff-d89a76e909ac97f43228c098ed8facb3)
[problems](https://www.spinics.net/lists/linux-usb/msg162253.html).

#### Errata

Along with a co-worker, we got to the bottom of two ASIC issues.

First with the Microchip USB2412 USB hub:
[Detach detection failure](/assets/pdf/USB2412-Errata-DS80000824A.pdf)

Then with the Microchip/Micrel KSZ8863 Ethernet switch:
[Receiver error in 100BASE-TX mode following Soft Power Down](/assets/pdf/KSZ8863-Errata-DS80000829A.pdf)

Those were quite interesting ones. You can imagine what a company tells you when
you are trying to tell them there is a bug with a long running chip sold by the
millions. Lets just say it took a while.

### Patents

As part of my work at Distech, I got involved in the following patents:

#### Granted

[CA2919102C](https://patents.google.com/patent/CA2919102C) -
Environment control device (ecd) and method for configuring the ecd to operate a wi-fi communication interface
[2018-10-02]

[US20170071015A1](https://patents.google.com/patent/US20170071015A1) -
Environment control device providing a wi-fi hotspot for accessing the internet
[2019-04-03]

[US20190115082A1](https://patents.google.com/patent/US20190115082A1) -
Memory device comprising flash memory and method for controlling a write speed of a bus transmitting data for storage on the flash memory
[2020-03-17]

#### Pending

[US20190156195A1](https://patents.google.com/patent/US20190156195A1) -
Computing device and method for inferring a predicted number of data chunks writable on a flash memory before wear out
[filed: 2017-11-21]

[US20190155520A1](https://patents.google.com/patent/US20190155520A1) -
Computing device and method for inferring a predicted number of physical blocks erased from a flash memory
[filed: 2017-11-21]

[US20190182069A1](https://patents.google.com/patent/US20190182069A1) -
Environment controller and method for inferring one or more commands for controlling an appliance taking into account room characteristics
[filed: 2017-12-12]

[US20190179269A1](https://patents.google.com/patent/US20190179269A1) -
Environment controller and method for inferring via a neural network one or more commands for controlling an appliance
[filed: 2017-12-12]

[US20190179270A1](https://patents.google.com/patent/US20190179270A1) -
Inference server and environment controller for inferring one or more commands for controlling an appliance taking into account room characteristics
[pending: filed: 2017-12-12]

[US20190179268A1](https://patents.google.com/patent/US20190179268A1) -
Inference server and environment controller for inferring via a neural network one or more commands for controlling an appliance
[filed: 2017-12-12]

[US20190278242A1](https://patents.google.com/patent/US20190278242A1) -
Training server and method for generating a predictive model for controlling an appliance
[filed: 2018-03-07]

[US20190310589A1](https://patents.google.com/patent/US20190310589A1) -
Neural network combining visible and thermal images for inferring environmental data of an area of a building
[filed: 2018-04-06]

[US20190353366A1](https://patents.google.com/patent/US20190353366A1) -
Method and environment controller using a neural network for bypassing a legacy environment control software module
[filed: 2018-05-16]

[US20190379470A1](https://patents.google.com/patent/US20190379470A1) -
Computing device and method using a neural network to infer a predicted state of a communication channel
[filed: 2018-06-08]

[CA3022061A1](https://patents.google.com/patent/CA3022061A1) -
Environment control device and method for inferring an optimal wireless data transfer rate using a neural network
[filed: 2018-10-25]

[CA3022063A1](https://patents.google.com/patent/CA3022063A1) -
Inference server and environment control device for inferring an optimal wireless data transfer date
[filed: 2018-10-25]

[US20200184329A1](https://patents.google.com/patent/US20200184329A1) -
Environment controller and method for improving predictive models used for controlling a temperature in an area
[pending: filed: 2018-12-11]

[US20200200423A1](https://patents.google.com/patent/US20200200423A1) -
Computing device and method for inferring via a neural network a two-dimensional temperature mapping of an area
[filed: 2018-12-19]

[CA3042813A1](https://patents.google.com/patent/CA3042813A1) -
Method and environment controller for validating a predictive model of a neural network through interactions with the environment controller
[filed: 2019-05-09]

[CA3061446A1](https://patents.google.com/patent/CA3061446A1) -
Computing device and method for inferring an airflow of a vav appliance operating in an area of a building
[filed: 2019-11-13]

## [Brioconcept Consulting Inc.](https://brioconcept.com/)

As a consulting company, Brioconcept is doing a lot of different things.

During the 5 years I got to work there I worked mostly on 4 different projects.

### [Personal locator](https://brioconcept.com/portfolio-items/personal-locator/)

This project is a watch that can be used to know the location of the person
wearing it.

It can be used by older or younger people that have a tendency to get lost.

All these watches connect to a server where the whole pool is managed through
a web interface. On that interface you can see the location of the watch but
also get access to fancy features like get an alert if the watch get in or out
of a defined perimeter or if the watch get beyond a configured velocity.

On this project I was in charge on the back-end where the watches would connect
and the front-end where the administrator would manage a pool of watches or the
user would control his watch.

### Patents

As part of my work at Brioconcept, I got involved in the following patent:

[CA2848937C](https://patents.google.com/patent/CA2848937C) -
Apparatus and methods for geolocating an individual with respect to a perimeter

### [Kontron Canada Inc.](https://www.kontron.com/)

At Brioconcept we did mostly in-house projects for others but sometimes we also
sent engineers for help in other companies.

That's what happened to me when I got to go work at Kontron.

Basically they made a server motherboard for storage server company which
was running what we refered to as the legacy BIOS i.e. the old style,
assembly written one.

![Motherboard](/assets/img/s-l1600 (2).jpg)

At that time the market was slowly moving to the new UEFI BIOS and so they
needed help for the port.

This project got big really quickly and I ended up working on that project for
about 1 year and a half.

I got to do:

* UEFI BIOS development and debugging
* Legacy BIOS development and debugging
* PCIe AER (Advranced Error Reporting) support implementation
* IPMI/BMC development

I also did on site support for this product at the end customer site at
IBM XIV Storage System in Israel.

### Animal feeding device

This project was an inteligent feeding device for animal. The client wanted it
to run Android as the base firmware so he could just hire "of the shelf" app
developper as the device application.

On this project I ported Android to the embedded platform.

### Distech Controls Inc.

Before working at Distech as an employe, I worked there as a consultant.

I first got involved because they wanted to run Android on their new project
and I had experience doing so.

I ended up working there for about 2 years as a consultant before moving as a
full time employe.
