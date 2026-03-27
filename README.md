# README HELP

## Table of Contents

- [Basics](#Basics)
  - [The Basics](#The-Basics-of-a-README)
  - [The Structure](#The-Structure-of-a-README)
  - [Features](#Features)
    - [Checkboxes](#Checkboxes)
    - [Text Effects](#Text-Effects)
    - [Collapsible Block](#collapsible-block)
    - [Special Github Symbols](#special-github-symbols)
    - [Images](#images)
  - [Keep in Mind](#Things-to-keep-in-Mind)
- [Cool Features](#Cool-Features)
  - [Typing SVG](#Typing-SVG)
  - [Emojis](#Emojis)
  - [Readme Stats](#Readme-Stats)
  - [Easy Icons](#Easy-Icons)

## Basics

> Do you want to be better than betters who are better than betters? I think not but i will consider yes!

How to Write a Kickass README?

Hello, fellow devs! 😄 Whether you’re new to GitHub or just looking to level up your README game, you’re in the perfect spot. I’ve rounded up the best tips to help you craft a README that’s as awesome as your project (if not more). Let’s dive in!

Why Does a Great README Matter?

Picture this: you stumble upon a GitHub project that sounds amazing. You click on the README… and it’s either blank or looks like a cryptic puzzle. Frustrated, you bounce to the next repo.

Your README is the front door of your project. It’s what hooks developers, contributors, and even recruiters (wink wink 😉). A great README isn’t just nice, it’s essential. Make it clear, make it fun, and most importantly, make people want to stay.

### The Basics of a README

At its core, a README is just a file written in Markdown, a ridiculously simple markup language that makes your text look pretty without giving you a headache. Think of it as the HTML for people who don’t want to fight with HTML.

Here’s a quick example to flex its magic:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
# My Amazing Project

Welcome to the **best project ever**.

## Features :P

- Lightning-fast performance ⚡
- Completely open-source 👐
- Powered by coffee ☕

## How to Improve it

[Click here](https://github.com/VivicatcHub/readme_help)
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

# My Amazing Project

Welcome to the **best project ever**.

## Features :P

- Lightning-fast performance ⚡
- Completely open-source 👐
- Powered by coffee ☕

## How to Improve it

[Click here](https://github.com/VivicatcHub/readme_help)

</td>
</tr>
</table>
</div>

### The Structure of a README

A great README follows a clear, logical structure, like assembling IKEA furniture, but without the confusing diagrams. Here’s the blueprint I swear by:

1. Project Title and Description

Start strong with a catchy title and a short, snappy description. Think of it as your project’s elevator pitch: What does it do? Why is it awesome? Convince us in a few sentences.

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
# Name of Project

Description
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

# Name of Project

Description

</td>
</tr>
</table>
</div>

2. Table of Contents (Optional)

If your README is heading into epic novel territory, a Table of Contents is a lifesaver. It helps readers quickly find what they’re looking for without scrolling aimlessly like it’s 2005.

Bonus tip: Markdown links are your friends! Replace spaces with `-` in headings to make clickable anchors, like this:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
## Table of Contents

- [The Structure](#the-structure-of-a-readmemd)
- [Installation](#installation)
- [Usage](#usage)
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

## Table of Contents

- [The Structure](#the-structure-of-a-readmemd)
- [Installation](#installation)
- [Usage](#usage)
</td>
</tr>
</table>
</div>

### Features

#### Checkboxes

Need to create a list with some interactive flair? Checkboxes are your new best friend. They’re perfect for to-do lists, progress tracking, or just looking cool.

Here’s how easy it is:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
## Checkboxes

I am:

- [ ] Dumb
- [x] Perfect
  - [x] Me
- [ ] Stupid
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

## Checkboxes

I am:

- [ ] Dumb
- [x] Perfect
  - [x] Me
- [ ] Stupid
</td>
</tr>
</table>
</div>

#### Text Effects

Markdown makes it ridiculously easy to spice up your text. Here’s a quick rundown of some effects you can use to grab attention or add style:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
_italic_

_italic_

**bold**

**_bold and italic_**

~~strikethrough~~

`code`

H<sup>2</sup>

H<sub>2</sub>

| Column 1 | Column 2 |
| -------- | -------- |
| Value 1  | Value 2  |
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

_italic_

_italic_

**bold**

**_bold and italic_**

~~strikethrough~~

`code`

H<sup>2</sup>

H<sub>2</sub>

| Column 1 | Column 2 |
| -------- | -------- |
| Value 1  | Value 2  |

</td>
</tr>
</table>
</div>

#### Collapsible Block

Sometimes, you want to hide some details or give readers the choice to "click to reveal." Markdown makes that easy with collapsible blocks!

Here’s how to create one:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
<details>
    <summary>Click to be spoiled</summary>

- He dies at the end !
</details>
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

<details>
    <summary>Click to be spoiled</summary>

- He dies at the end !
</details>
</td>
</tr>
</table>
</div>

This feature is perfect for spoilers, instructions, or anything you want to keep hidden unless explicitly requested. 😏

#### Special Github Symbols

Did you know GitHub Markdown supports special callouts to make your README pop? Use them to emphasize notes, warnings, or important details.

Here’s how to do it:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
> [!NOTE]\
> This is a Note

> [!WARNING]\
> This is a Warning

> [!IMPORTANT]\
> This is important
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

> [!NOTE]\
> This is a Note

> [!WARNING]\
> This is a Warning

> [!IMPORTANT]\
> This is important

</td>
</tr>
</table>
</div>

Use these symbols to keep your README both informative and visually organized. Perfect for catching the reader’s attention when it really matters! 🚨✨

#### Images

Want to spice up your README with some eye candy? Images are the way to go! You can add regular images or make them clickable to direct readers somewhere cool—like your project’s repo or your "Buy Me a Coffee" page. ☕

Here’s the how-to:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
<!-- Normal image -->
<img src="https://urlr.me/9DJpcG" align="center" alt="Image">

<!-- Clickable image -->

[![Link](https://www.buymeacoffee.com/assets/img/
custom_images/yellow_img.png)](https://github.com/VivicatcHub)
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

<!-- Normal image -->
<img src="https://urlr.me/9DJpcG" align="center" alt="Image">

<!-- Clickable image -->

[![Link](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://ko-fi.com/vivicaty)

</td>
</tr>
</table>
</div>

Pro tip: If you make an image clickable, you’re basically saying, "Hey, this image is cool, but click it to discover something even cooler!" Just don’t Rickroll your audience… unless they deserve it. 😉

### Things to keep in Mind

Markdown is awesome, but it’s not perfect. You can use HTML in Markdown, but with a few caveats. Here’s a non-exhaustive list of what works and what doesn’t:

What You Can Use:

- Basic HTML Tags: `<div>`, `<span>`, `<br>`, `<img>`, and friends.
- Tables: If Markdown tables feel clunky, HTML tables work like a charm.

What You Can’t Use:

- JavaScript: No `<script>` tags—GitHub keeps it safe and secure.
- CSS Classes: Sorry, no `<div class="fancy">` here. Inline styles only.
- Interactive HTML: Stuff like `<input>` or `<button>` won’t work as expected.

When in doubt, stick to Markdown for simplicity, but feel free to sprinkle in some HTML magic when Markdown falls short! 🪄

## Cool Features

Your README doesn’t have to be just plain text, it can stand out with fun, reusable projects from other developers! These gems add extra flair and functionality to your README, making it as cool as your code. 😎

### Typing SVG

Courtesy of [DenverCoder1](https://github.com/DenverCoder1), this project lets you add animated typing effects to your README. Perfect for grabbing attention!

Here’s how it works:

- Use the `?lines=` parameter to add sentences, separated by `;`.
- Don’t forget to replace spaces with `%20` (Markdown loves encoding).

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
<p align="center">
<a href="https://github.com/DenverCoder1/readme-typing-svg">
<img src="https://readme-typing-svg.demolab.com/
            ?lines=Typing%20colored%20text;Sty'%20hihi
            &font=Fira%20Code
            &center=true
            &width=440
            &height=45
            &color=f75c7e
            &vCenter=true
            &pause=1000
            &size=22"/>
</a>
</p>
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

<p align="center">
<a href="https://github.com/DenverCoder1/readme-typing-svg">
<img src="https://readme-typing-svg.demolab.com/?lines=Typing%20colored%20text;Sty'%20hihi&font=Fira%20Code&center=true&width=440&height=45&color=f75c7e&vCenter=true&pause=1000&size=22"/>
</td>
</tr>
</table>
</div>

You can also tweak other options like colors and speed. Full documentation is available [here](https://github.com/DenverCoder1/readme-typing-svg).

Go ahead, make your README type for itself! ⌨️✨

### Emojis

Emojis are the spice of life—and your README! 🌟 With [Ikatyang](https://github.com/ikatyang)’s handy cheat sheet, you can easily find the right codes to display emojis on GitHub.

Simply wrap the emoji code in colons, like this:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
- grinning: :grinning:
- genie_man: :genie_man:
- fish_cake: :fish_cake:
- trollface: :trollface:
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

- grinning: :grinning:
- genie_man: :genie_man:
- fish_cake: :fish_cake:
- trollface: :trollface:
</td>
</tr>
</table>
</div>

Want to explore the full emoji menu? Check out the [emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet) and add some personality to your README.

Because who doesn’t love a README with a little 🌈 and 🎉?

### Readme Stats

Want to show off your GitHub activity and prove that yours is the most impressive (Mine is bigger)? 📈 Enter GitHub Stats by [Anuraghazra](https://github.com/anuraghazra).

This handy tool lets you display cool stats like:

- Total contributions 🏆
- Most used languages 💻
- Fancy graphs and charts 📊

Here’s a quick example of how to use it:

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
<img src="https://github-readme-stats.vercel.app/api
            /top-langs/
            ?username=VivicatcHub
            &layout=compact
            &theme=transparent
            &text_color=cdd6f4
            &hide_border=true
            &icon_color=cba6f7
            &title_color=94e2d5
            &langs_count=8"
    alt="Most Used Languages"/>
</br>
<img src="https://github-readme-stats.vercel.app/api
            ?username=VivicatcHub
            &show_icons=true
            &theme=transparent
            &text_color=cdd6f4
            &icon_color=cba6f7
            &title_color=94e2d5
            &hide_border=true
            &rank_icon=percentile"
    alt="Stats"/>
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VivicatcHub&layout=compact&theme=transparent&text_color=cdd6f4&hide_border=true&icon_color=cba6f7&title_color=94e2d5&langs_count=8" alt="Most Used Languages"/>
</br>
<img src="https://github-readme-stats.vercel.app/api?username=VivicatcHub&show_icons=true&theme=transparent&text_color=cdd6f4&icon_color=cba6f7&title_color=94e2d5&hide_border=true&rank_icon=percentile" alt="Stats"/>
</td>
</tr>
</table>
</div>

Replace YourUsername with your GitHub handle, and boom, you’ve got a sleek, customizable stats card for your README. For more options and themes, check out [Anuraghazra’s repo](https://github.com/anuraghazra/github-readme-stats).

Because who doesn’t love flexing those contribution graphs? 💪😏

### Easy Icons

> Show Off Your Tech Stack Like a Pro

Why just tell people what languages and tools you use when you can show them? Thanks to [Skillicons](https://github.com/edmartelo/skillicons) by [Edmartelo](https://github.com/edmartelo), you can add slick, minimalist icons for programming languages, tools, and even social media!

<div align="center">
<table border="1">
<tr>
<th>
<h3>Code</h3>
</th>
</tr>
<tr>
<td align="left">

```md
Language Icons

Because a picture is worth a thousand lines of code:

<p align="center">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=c,js,py" />
    </a>
</p>

Media Icons

Let people stalk... uh... follow—you on different platforms:

<p align="center">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=instagram,linkedin,github" />
    </a>
</p>
```

</td>
</tr>
<tr>
<th>
<h3>Preview</h3>
</th>
</tr>
<tr>
<td align="left">

Language Icons

Because a picture is worth a thousand lines of code:

<p align="center">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=c,js,py" />
    </a>
</p>

Media Icons

Let people stalk... uh... follow—you on different platforms:

<p align="center">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=instagram,linkedin,github" />
    </a>
</p>
</td>
</tr>
</table>
</div>

Just tweak the `i=` parameter with the icons you need and voilà, your README just got a whole lot fancier! 🚀

Btw, the entire list is [here](https://github.com/edmartelo/skillicons)
