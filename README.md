# Responsive Web Design

- **Author:** Paul *"makemyA"* Henrot
- **About:** Learning about Responsive Web design
- **Period:** *-Start: 28/05/2018-*
- **Place:** BeCode bootcamp @Becentral buildings in Bruxelles

## Project Description

* Objective?

To be able to make internet site in responsive.

You can watch instructions [there](https://github.com/becodeorg/lovelace-2/tree/master/Parcours/02-Responsive%20Web%20Design)

* Day-1

I am starting with some W3schools tutorials.
I realized codepen folders to save code parts about responsive

Here they are:

    1. Starting exercice

*starting with responsive concept*
<p data-height="265" data-theme-id="dark" data-slug-hash="vrBypZ" data-default-tab="html,result" data-user="makemya-the-bold" data-embed-version="2" data-pen-title="Responsive-ex" class="codepen">See the Pen <a href="https://codepen.io/makemya-the-bold/pen/vrBypZ/">Responsive-ex</a> by Paul Henrot (<a href="https://codepen.io/makemya-the-bold">@makemya-the-bold</a>) on <a href="https://codepen.io">CodePen</a>.</p>

    1. Intermediar exercice
*-The only goal of this exercice is to understand how media query can change content.*

<p data-height="265" data-theme-id="dark" data-slug-hash="MXgOWY" data-default-tab="html,result" data-user="makemya-the-bold" data-embed-version="2" data-pen-title="responsive-web-design ex1" class="codepen">See the Pen <a href="https://codepen.io/makemya-the-bold/pen/MXgOWY/">responsive-web-design ex1</a> by makemyA (<a href="https://codepen.io/makemya-the-bold">@makemya-the-bold</a>) on <a href="https://codepen.io">CodePen</a>.</p>

 * Day-2

        * Final Exercice

*This exercice was pretty helpful to understand how to build a complete responvive website.*

View on Github [page](https://makemya.github.io/responsive-web-design/challenge/)

The exercice **Step by Step**:

For reminder, the exercice is about adaptating a website initially build for desktop without changing anything in html process.  The goal is to make it responsive for smartphone and Ipad.
I choice to start with the phone build css.
Firstable, I started to work with html version of the source file and disable all css rule. I added all css rules (from source) one by one and check into console (google chrome in my case) what's happening to my page. Off course you need to **select the mobile view** of your choice to make your build easier.
Second step is to add, delete or adapt some parts who doesn't concern phone version in your opinion. Add all your change or deletion in **@media query tag** for phone version on your css. In my case it was :

```css
@media only all and (max-width: 640px) { }
```
I get some difficulties with max-width range rendition. The result doesnt appear on my phone like asked. The problem was about the viewport name who wasnt initially created in the html file. Viewport rule say to your phone to respect the appears width of your phone. It make it work it correctly
