---
layout: default
---

As a kid I was already pretty interested by electronic.

I remember looking at circuit boards coming from things I disassembled and
wondering what all these components were used for.

I got in touch with computers quite early in elementary school. At that time we
had one computer for the whole class. I remember I was a bit afraid to go on it
because our teacher told us we had to power on the screen first and then the
computer or maybe it was the oposite. I've never been too sure of the proper
order and I though I might break something.

Thinking about it now, I'm not sure if there was in fact a requirement or not.

I got my first contact with the Internet in 6th grades. At that time it was 
still mostly empty but it was a nice thing to just type something in the search
engine and look at the results.

In the middle of high school, my parents bought our first computers. I think it
was a bit on the late side compared to others of my age. However I got to skip
the dialup and go straight to broadband :)

From there I got my fair share of time at the computer trying to understand all
there is to know.

I'm still working on that.


# Professional experience

Most of my past work has been around taking pieces and making something with
them.

As such, I think it gives me a wider scope but without any deep expertise like
somebody who would do C++ for most of his career.

## [Distech Controls Inc.](http://www.distech-controls.com/en/ca/)

Distech is a company that specialises in making HVAC products.

As part of my daily work, I got to work on two Android based products,
[Eclypse](http://www.distech-controls.com/en/ca/products/eclypse/) and 
[Horyzon-C](http://www.distech-controls.com/en/ca/products/displays/).

On these products, I've been involved in quite a few things including:

* Boot sequence
* Hardware configuration
* Network connectivity
* Source code management
* Automated builds

I also helped in getting the FIPS 140-2 certification.
([line 12](https://csrc.nist.gov/Projects/Cryptographic-Algorithm-Validation-Program/Validation/Validation-List/SHA-3))

and got to debug some pretty [interresting](https://github.com/qca/open-ath9k-htc-firmware/commit/97217c1250772c3c6dbba8b00bab70df6dbd22da#diff-d89a76e909ac97f43228c098ed8facb3)
[problems](https://www.spinics.net/lists/linux-usb/msg162253.html).

Not to forget my participation in this [patent](https://patents.google.com/patent/US20170071015A1/en?inventor=francois+gervais&oq=francois+gervais).

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
and the [front-end](https://brioconcept.com/portfolio-items/web-interface-for-personal-locator/)
where the administrator would manage a pool of watches or the
user would control his watch.

### [Kontron Canada Inc.](https://www.kontron.com/)

At Brioconcept we did mostly in-house projects for others but sometimes we also
send engineers for help in other companies.

That's what happened to me when I got to go work at Kontron.

Basically they made a server motherboard for storage server company which
was running what we refered to as the legacy BIOS. That is, the old style,
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

This project is not on the Brioconcept's website so I'm not sure what happened
to that one.

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


# Personal projects











Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```