<pre align="center">
 _   _      _ _       _   ___ _            <code style="color:#f5e836">____</code><code style="color:#3cf536">__</code>                      
| | | | ___| | | ___ | | |_ _( )_ __ ___  <code style="color:#f5a236">|_</code>    <code style="color:#3cf536">_|_</code><code style="color:#36f5e5">_  _</code> <code style="color:#3d47ff">__</code> <code style="color:#a83dff">_</code>   <code style="color:#ff3df9">_</code> <code style="color:#ff3d9e">_</code> <code style="color:#ff3d40">__</code>  
| |_| |/ _ \ | |/ _ \| |  | ||/| '_ ` _ \    <code style="color:#f5a236">|</code> <code style="color:#f5e836">|/</code> <code style="color:#3cf536">_ \</code><code style="color:#36f5e5">| '_</code><code style="color:#3d47ff">_|</code> <code style="color:#a83dff">| |</code> <code style="color:#ff3df9">|</code> <code style="color:#ff3d9e">'_</code> <code style="color:#ff3d40">\</code> 
|  _  |  __/ | | (_) |_|  | |  | | | | | |   <code style="color:red">|</code> <code style="color:#f5a236">|</code> <code style="color:#f5e836">(_</code><code style="color:#3cf536">) |</code> <code style="color:#36f5e5">|</code>  <code style="color:#36f5e5">|</code> <code style="color:#3d47ff">|_</code><code style="color:#a83dff">| |</code> <code style="color:#ff3df9">|</code> <code style="color:#ff3d9e">|</code> <code style="color:#ff3d40">|</code>
|_| |_|\___|_|_|\___/(_) |___| |_| |_| |_|   <span>$${\color{red}|_|}$$</span><code style="color:#f5a236">\__</code><code style="color:#f5e836">_/</code><code style="color:#3cf536">|_|</code>   <code style="color:#36f5e5">\</code><code style="color:#36f5e5">_</code><code style="color:#3d47ff">_,</code> <code style="color:#a83dff">|_|</code> <code style="color:#ff3df9">|_</code><code style="color:#ff3d9e">|</code>
                                                           <code style="color:#3cf536">|</code><code style="color:#36f5e5">__</code><code style="color:#3d47ff">_/</code>       
</pre>

<div align="center">
  <a href="https://github.com/ttorynn/badges">
    <img src="https://badges.toryn.bio/views/ttorynn?color=000" />
  </a>
  <a href="https://discord.com/users/340324858405847042">
    <img src="https://badges.toryn.bio/discord/340324858405847042?color=000">
  </a>
</div>

<br />

I'm a fullstack, machine learning, and electrical engineer—as well as a designer—passionate about building novel products that [actually] change the way we approach problems.

Here on GitHub, you'll find all of my projects that I've decided to make public. Feel free to get in touch with me if you have any questions about my projects, experience, or simply want to say hi.

### Featured Projects

#### 🔆 [RF-Controlled LED Event Bracelets](https://toryn.bio/blog)

Researched and learned PCB design, circuit theory, RF impedance matching, antenna selection, and transmission line theory to develop LED bracelets for events at my school. These are programmable with any light sequence, but are intended to sync to music.

A Raspberry Pi running a SvelteKit webserver integrated with SQLite serves the bracelet control platform, which communicates via IPC to a C++ binary that leverages the Qt Bluetooth framework in order to broadcast byte-sized commands to hundreds of bracelets. The bracelet PCBs, designed in KiCad, possess an impedance-matched Johanson Dialectric antenna that connects to a TI SimpleLink MCU. This MCU is programmed via a Tag-Connect flashing header that transfers compiled C binaries, which use the TI SimpleLink hardware abstraction libraries to translate RF signals into PWM alterations that control the PCB's two LEDs. These PCBs are encased in a custom designed, 3D printed PETG shell.

More information, including photos, can be found [on my blog](https://toryn.bio/blog).

#### [🪪 Licer](https://github.com/ttorynn/licer)

A CLI that generates repository LICENSE files. Automatically fetches information, such as contributor names, emails, etc from either a `Cargo.toml`, `pyproject.toml`, `package.json`, or the global git config. It can generate many commonly-found licenses in their respective formats.

#### [🌐 PinDrop](https://github.com/ttorynn/pindrop)

A peer-to-peer file sharing service that leverages WebRTC. Similar to Apple's AirDrop and Google's Nearby Share except it is an online, cross-platform service that requires connection to the internet. Being a PWA, it can also be downloaded as a local application.

Use it [here](https://pindrop.toryn.bio).

#### [🎖️ GitHub Badges](https://github.com/ttorynn/badges)

A profile `README` badge service that offers a profile view count and Discord status badge. Both are seen at the top of this `README` with my information.

### Languages

![TypeScript](https://img.shields.io/badge/-TypeScript-000?&logo=TypeScript)
![JavaScript](https://img.shields.io/badge/-JavaScript-000?&logo=JavaScript)
![Python](https://img.shields.io/badge/-Python-000?&logo=Python)
![C](https://img.shields.io/badge/-C-000?&logo=C)
![C++](https://img.shields.io/badge/-C++-000?&logo=c%2b%2b&logoColor=00599C)
![SQL](https://img.shields.io/badge/-SQL-000?&logo=MySQL)
![HTML](https://img.shields.io/badge/-HTML-000?&logo=HTML5)
![CSS](https://img.shields.io/badge/-CSS-000?&logo=CSS&logoColor=663399)

### Technologies

![Docker](https://img.shields.io/badge/-Docker-000?&logo=Docker)
![Django](https://img.shields.io/badge/-Django-000?&logo=Django&logoColor=092E20)
![Figma](https://img.shields.io/badge/-Figma-000?&logo=Figma)
![Next.js](https://img.shields.io/badge/-Next.js-000?&logo=Next.js)
![SvelteKit](https://img.shields.io/badge/-SvelteKit-000?&logo=Svelte)
![React](https://img.shields.io/badge/-React-000?&logo=React)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-000?&logo=Cloudflare)
![Git](https://img.shields.io/badge/-Git-000?&logo=Git)
![Node.js](https://img.shields.io/badge/-Node.js-000?&logo=Node.js)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-000?&logo=PostgreSQL)
![PyTorch](https://img.shields.io/badge/-PyTorch-000?&logo=PyTorch)
![Redis](https://img.shields.io/badge/-Redis-000?&logo=Redis)
![Prisma](https://img.shields.io/badge/-Prisma-000?&logo=Prisma)
![Drizzle](https://img.shields.io/badge/-Drizzle-000?&logo=Drizzle)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-000?&logo=TailwindCSS)
![pandas](https://img.shields.io/badge/-pandas-000?&logo=pandas)
![KiCad](https://img.shields.io/badge/-KiCad-000?&logo=KiCad&logoColor=314CB0)
![LTspice](https://img.shields.io/badge/-LTspice-000?&logo=LTspice&logoColor=900028)
![Ansys HFSS](https://img.shields.io/badge/-Ansys%20HFSS-000?&logo=Ansys)

### Statistics

<img src="https://github-readme-stats.vercel.app/api?username=ttorynn&show_icons=true&bg_color=000&text_color=fff&icon_color=fff&hide_border=true&hide_rank=true&hide_title=true&border_radius=0" /><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ttorynn&bg_color=000&hide_border=true&title_color=fff&text_color=fff&layout=compact&border_radius=0" />
