---
layout: post
title: Fighting with Jekyll
author: Caitlyn Williams
date: 2024-12-19 +1030
modified_date: 2024-12-22 +1030
---

I made a blog-ish... thing. This is gonna be mess of all my interests getting spewed out onto the internet.

Me being me I wanted to make my own site from scratch using [*Tailwind*](https://tailwindcss.com), my favorite font ([*Atkinson Hyperlegible*](https://www.brailleinstitute.org/freefont)), and emoji set ([*Fluent*](https://github.com/microsoft/fluentui-emoji)).

<!--more-->

I do plan to do this but I wanted to *use* a website, not spend the whole time playing with and swearing at CSS. I'll probably end up modifying the theme here bit by bit.

But yeah, welcome, there'll be more posts I swear...

Actually setting this up was more of a pain than expected, I followed GitHub's instructions for [deploying Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll) and [developing a page locally](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll), and this worked... until God forbid I wanted :sparkles:dark mode:sparkles:. I remembered @Cubie87 has a GitHub pages-based site with dark mode, but they just modified the [Minima](https://github.com/jekyll/minima) theme. Then I stumbled upon [this](https://blog.slowb.ro/dark-theme-for-minima-jekyll) article which talks about Minima `v3`, which of course GitHub doesn't support, so then after going down a long rabbit hole of trying to get it working without the `github-pages` gem-screaming. Thanks to [this](https://stackoverflow.com/questions/68518590/does-minima-dark-skin-work-on-github-pages) thread in StackOverflow, I think its working. At the time of writing I haven't pushed to GitHub so we'll see.

The next stage was just messing around with different configuration vales, trying to add plugins, and changing the includes to remove stuff I don't need, like RSS (sorry I know it's cool but it scares me).

UPDATE: I have now pushed an update to include Hyperlegible as the default font, I've also changed the code font to be [*Fira Code*](https://github.com/tonsky/FiraCode).