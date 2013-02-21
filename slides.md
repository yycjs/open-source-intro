# Becoming an Open Source JavaScript Hipster

---

## David Luecke

* GitHub: [daffl.github.com](http://daffl.github.com)

* Twitter: [@daffl](http://twitter.com/daffl)

## Eric Kryski

* GitHub: [ekryski.github.com](http://ekryski.github.com)

* Twitter: [@ekryski](http://twitter.com/ekryski)

## Mike Warren

* GitHub: [meejah.github.com](http://mejah.github.com)

* Twitter: [@meejah](http://twitter.com/meejah)

---

## Introduce Give a Mile

---

## Basic Web Stack (Dave)

* HTML, CSS, JavaScript, Server
* Diagram

---

## Awesome Mustaches (Dave)
* As promised, awesome hipster staches

---

## What do I need to get Started? (Dave)

---

## A browser

---

## Directly in the browser

- [JSFiddle](), [JSBin]()
- [Cloud9 IDE]()
- Developer tools
	- Chrome developer tools
	- Firebug
	- Safari Developer
	- IE

---

## Text editors

* Sublime Text 2
* TextMate
* Notepad++
* VIM, EMacs

---

## IDEs

* Webstorm
* Aptana

---

## Version Control!! (Mike)

* What? Why? (Even non-devs can use this)
* Distributed (SVN) vs. Centralized (Git)
* Hosted Solutions: Github, Bitbucket, Beanstock, Redmine

---

## Github FTW (Mike)

Live Demo!

* Registration (new signup)
* The interface
* Creating a repo
* Forking a repo
* Cloning a repo

---

## Git for Noobs (Mike or Eric)

* Github for Mac
* Github for Windows

---

## More Developer Focused Git (Mike)

* Source Tree (slightly less noobish)
* Command line (for neckbeards)

---

## Fixies (Mike)
* Maybe a plug for bike bike as well

---

## Recap (Eric)

* We have an idea!
* We have a text editor!
* We have source control!
* Let's build something :-)

---

## HTML 5 (Eric)

* It pretty much the same as old HTML!
* Some new tags (ex. number, email, date)
* New APIs. They are just JavaScript!
* Can do some crazy stuff with these API's that we'll look at later in the year

---

## Appropriate Hipster Attire (Eric)

---

## CSS (Eric)

* CSS 3 is the new kid on the block
* Again some new things but it's still CSS
* Crazy things you can do like WebGL shaders in CSS, animations, drop shadows, a lot of stuff you can do in Photoshop!

---

## Twitter Bootstrap (Eric)

* A CSS Framework
* Brought easy and pretty UI to developers
* Support all modern browsers including IE 7+
* Wrapbootstrap
* Bootswatch
* Bootswatchr

---

## JavaScript (Dave)

* It is the programming language of the web (and our favourite)
* This makes your app work and your website fancy!
*

---

## JavaScript in the browser (Dave)

![Overview](images/overview.png) (put a new image in)

---

## The DOM (Dave)

* It isn't as ominous as it sounds
* The internal representation of your HTML

---

## jQuery (Dave)

* Simplifies DOM manipulation, traversal and event handling
* AJAX support
* Effects
* UI elements with [jQuery UI](http://jqueryui.com) (~200Kb)
* Eliminates cross browser differences
* Plugin mechanism
* Fully open source (MIT licensed)
* ~ 32Kb

---

## jQuery - Example (Dave)

__jQuery__

	!javascript
	$(document).ready(function() {
		$('button').click(function() {
			var name = $('[name="your-name"]').val();
			$('#mydiv').html('Hi ' + name);
		});
	});

__Markup__

	!html
	<input type="text" name="your-name" />
	<button>Say Hi</button>
	<div id="mydiv"></div>

---

## Contributing to Open Source (Dave)
* Anyone can do it
* It can be as minor as fixing typos

---

## Next Month

* Templates, build tools, and more jQuery!

---
