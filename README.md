# Amazing CodeWithHarry Hacktoberfest Project

We live in a world where people think

- Brexit is good for Britain
- Trump is good for USA 
- A Shit MR is good for a free Hacktoberfest T-shirt

So what are you going to do about it? Ignore the stupid just have fun!

## Show your true colors

This week, my friend [@poef](https://github.com/poef) mentioned the old joke that, in HTML colors, `Chuck Norris` is red.
And not in a [`#bada55`](http://bada55.io/) way but _actual_ red. To be precise:`#C00000`.
Or in a more modern format: `rgb(192, 0, 0)`.
<table><tr><td bgcolor="ChuckNorris">&nbsp;</td></tr></table>

Any search engine will give you some hits as to _why_, so I'm not going into that here.

What I will do, is tell you that this trick (obviously) works for other names as well.
For instance, "CodeWithHarry" spells `rgb(192, 0, 10)`, which is only slightly more blue than Chuck Norris.
<table><tr><td bgcolor="CodeWithHarry">&nbsp;</td></tr></table>

I won't go into the relevance of "CodeWithHarry" here either, but I'm sure you can find some information online yourself.

So "What does my name spell" I hear you ask? Well...

"Potherca" becomes a rich dark blue`rgb(0, 14, 202)` 
<table><tr><td bgcolor="Potherca">&nbsp;</td></tr></table>
and "Ben Peachey" becomes `rgb(190, 234, 224)`, which is a grayish-cyan.
<table><tr><td bgcolor="BenPeachey">&nbsp;</td></tr></table>

Obviously, "Ben Peachey" is not actually _your_ name... So what color _does_ your name translate to?

My challenge to you: Find out and share your result with us!

How? Well... to stay in the HacktoberFest spirit: Open an MR!

## The Rules

Below this text is an HTML table. Want to know what color your name will be?
Simply clone this repo, an add your name to the table and see!
You are welcome to open an MR to share your findings with the rest of the world, but fair warning:

Only MRs that **add both name _and_ color in alphabetical order** in the list will be honored.

So what do he rules for HacktoberFest say about all of this?

> We discourage [..] Something that's clearly an attempt to simply +1 your pull request count for October.

Regarding repositories they say:

> Bad repositories will be excluded [..] repositories that encourage participants 
> to make simple pull requests – such as adding their name to a file [..] goes 
> against one of our core values for Hacktoberfest.
>
> We've implemented a system to block these repositories, and any pull requests 
> submitted to such repositories will not be counted.

So will you MR count towards you gaining you that free `#hacktoberfest` T-shirt?

I guess there is only one way to find out... 😏

## People

<table>
  <thead>
    <tr>
      <th>Name</th><th>RGB</th><th>Color</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Ben Peachey</td><td>rgb(190, 234, 224)</td><td bgcolor="Ben Peachey"></td></tr>
    <tr><td>BenPeachey</td><td>rgb(190, 234, 224)</td><td bgcolor="BenPeachey"></td></tr>
    <tr><td>Chuck Norris</td><td>rgb(192, 0, 0)</td><td bgcolor="Chuck Norris"></td></tr>
    <tr><td>CodeWithHarry</td><td>rgb(192, 0, 10)</td><td bgcolor="CodeWithHarry"></td></tr>
    <tr><td>Donald Trump</td><td>rgb(208, 208, 0)</td><td bgcolor="Donald Trump"></td></tr>
    <tr><td>Poef</td><td>rgb(0, 0, 239)</td><td bgcolor="Poef"></td></tr>
    <tr><td>Potherca</td><td>rgb(0, 14, 202)</td><td bgcolor="Potherca"></td></tr>

    <!-- Leave the line below as last row -->
    <tr><td>Your name here?</td><td>rgb(255, 255, 25%)</td><td bgcolor=""></td></tr>
  </tbody>
</table>


## Places

<table>
  <thead>
    <tr>
      <th>Name</th><th>RGB</th><th>Color</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Britain</td><td>rgb(176, 160, 0)</td><td bgcolor="Britain"></td></tr>
    <tr><td>Great Britain</td><td>rgb(234, 176, 160)</td><td bgcolor="Great Britain"></td></tr>
    <tr><td>U.S.A.</td><td>rgb(0, 0, 160)</td><td bgcolor="U.S.A."></td></tr>
    <tr><td>USA</td><td>rgb(0, 0, 10)</td><td bgcolor="USA"></td></tr>
    <tr><td>World</td><td>rgb(0, 0, 208)</td><td bgcolor="World"></td></tr>
  </tbody>
</table>

<style>  
  .markdown-body table td[bgcolor]::after {
    color: #fff;
    content: attr(bgcolor);
    font-weight: bold;
    text-shadow: -1px 0 1px black, 1px 0 1px black, 0 -1px 1px black, 0 1px 1px black;
  }

  .markdown-body tbody td:nth-child(2) {
    background-color: #1b1f230d;
    border-radius: 3px;
    font-family: "SFMono-Regular",Consolas,"Liberation Mono",Menlo,Courier,monospace;
    font-size: 85%;
    margin: 0;
    padding: 0.2em 0.4em;
  }
</style>

<!-- @TODO:

## Words

Amazing 
Brexit
People
Project
Hacktoberfest 
Shit
free 
Hacktoberfest 
T-shirt
fun
stupid
colors
github
HTML
RGB
Google
name
Merge Request
Rules
repo
repositories
pull request count
core values
-->
