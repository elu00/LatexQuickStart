---
title: "Installation"
weight: 11
---
# MiKTeX
To get started with installing TeX, you'll first need to choose a variant, or "distribution," to install.
Although there previously were major difference between the different distributions, by now, most of the differences between the distributions are just historical.
For this tutorial, we'll be using [MiKTeX](https://miktex.org/), although alternatives like [TeXLive](https://www.tug.org/texlive/) should work just as well.

1. To get started then, just navigate to the [MiKTeX download page](https://miktex.org/download) and download the correct installer for your operating system (in this example, we're using Windows).
{{< picture "MiKTeX1.png" "MiKTeX1.png" "The installation page" >}}
2. Now run the installer! Most of the default options are fine here, but the installation process is below for completeness (you can click on a photo to enlarge it).
{{< gallery dir="/images/installer" caption-position="none"/>}} {{< load-photoswipe >}}
3. Now after the installer finishes, verify that everything's working by opening a command prompt (i.e., by pressing ``Windows + R`` and typing ``cmd``) then running the command ``pdflatex``. If your prompt looks below, then you're good to go! Now just hit ``Ctrl + c`` and close the window!

{{< picture "terminal.png" "terminal.png" "The installation page" >}}
# Perl
After installing MiKTeX, we'll also need to install Perl, an extra piece of software that makes working with the compiler slightly nicer.
To do so, just visit the [homepage](https://strawberryperl.com/) and run the installer of your choice.
Again, this process is pretty straightforward, but is included below for completeness.
{{< picture "strawberry.png" "strawberry.png" "The installation page" >}}
{{< gallery dir="/images/perl" caption-position="none"/>}}