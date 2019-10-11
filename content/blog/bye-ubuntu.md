+++
title = "Bye Ubuntu! (And Hi! Manjaro)"
date = 2019-09-27T02:30:45+05:30
tags = [
    "ubuntu",
    "disto",
    "manjaro",
    "arch-linux",
]
categories = [
    "disto",
    "majaro-linux",
]
+++

I still remember that day: 15th February 2017, the day I finally gathered the courage to step into the world of Linux. Before then, just like everyone else, I was on windows for the past 7 years and the idea of using the terminal was alien to me.  

![My Ubuntu Screen](/img/ubuntu.png) 
<center>(My old ubuntu desktop)</center>

Ubuntu 14.04 was the distro that made me this transition very smooth. That GNOME environment was weird initially with its button on the left-hand side. It took me some time to get used to it. And how can I forget `apt` [breaking every time I try to install something new](https://askubuntu.com/questions/15433/unable-to-lock-the-administration-directory-var-lib-dpkg-is-another-process). And then slowly  I realized that **the Terminal is a superpower**. This tool has saved a lot of my time while sheep shaving¹.

¹ Sheep shaving means installing all the boring stuff like installing dependency before starting a new project.

Now, more than 2 years after the time has changed, just like they say _every good things must end_, I have decided to get out of my comfort zone again and try out a new distro. And after going through a lot of articles on the internet on distros, I have decided to use Manjaro. Yay! I'm one step closer to Linux Nivarana (Kidding!).

![My Majaro Screen](/img/manjaro.png) 
<center>(My current desktop)</center>

As Manjaro is based on Arch whereas Ubuntu is based on Debian, it is given that both of them are very different. This is also the first time I'm using KDE as my desktop enivronment and I have to say it has some really nice themes and in general more stable than GNOME (so far!). One major difference comes while working with default package managers. I have listed common commands will working with those below.   

### Commands: Ubuntu Vs Arch Linux 
<hr>

<table style="width:100%">
  <tr>
    <th></th>
    <th>Arch</th>
    <th>Ubuntu</th>
  </tr>
  <tr>
    <td>Package Manager</td>
    <td>pacman</td>
    <td>apt</td>
  </tr>
  <tr>
    <td>Refresh and Upgrade</td>
    <td>pacman -Syu</td>
    <td>apt-get update && apt-get dist-upgrade</td>
  </tr>  
  <tr>
    <td>Install a package</td>
    <td>pacman -S package-name</td>
    <td>apt-get install</td>
  </tr>  
  <tr>
    <td>Search for package</td>
    <td>pacman -Ss</td>
    <td>apt search</td>
  </tr>  
  <tr>
    <td>Remove a package</td>
    <td>pacman -Rs</td>
    <td>apt remove</td>
  </tr>  
  <tr>
    <td>Clean up all local caches</td>
    <td>pacman -Sc or pacman -Scc</td>
    <td>apt autoclean or apt clean</td>
  </tr>  
  <tr>
    <td>Remove unnecessary dependencies</td>
    <td>pacman -Qdtq | pacman -Rs -</td>
    <td>apt autoremove</td>
  </tr>  
</table>

<br>

Finally, I would suggest anyone new to the world of linux to go with Ubuntu and use [askbuntu](https://askubuntu.com/) as much as possible. And if you want to try something more exciting then try out [Arch Linux](https://www.archlinux.org/).

:raising_hand:
