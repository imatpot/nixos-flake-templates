
<h1 align="center">NixOS Flake Templates</h1>

<p align="center">
  <i>Prīmae nivis plūmae dēcīdunt — The first snowflakes are falling</i> <br />
  Templates for <a href="https://nixos.org">NixOS</a> system configurations based on <a href="https://nixos.wiki/wiki/Flakes">Nix Flakes</a>
</p>

<p align="center">
  <a href="https://nixos.org" style="text-decoration: none">
    <img src="https://img.shields.io/badge/built%20for-NixOS-5074BF.svg?style=flat-square&logo=NixOS&logoColor=white">
  </a>
  <a href="https://nixos.wiki/wiki/Flakes" style="text-decoration: none">
    <img src="https://img.shields.io/badge/built%20with-Nix%20Flakes-7EB4DF.svg?style=flat-square&logo=NixOS&logoColor=white">
  </a>
</p>

<br />

## What is this?

As the title says, this is a collection of templates for NixOS system configurations based on Nix Flakes. They're designed to be easy to understand and use for people getting started with, and wishing to migrate their system configuration to Flakes.

## Okay, but *why* is this a thing again?

The other day I was researching how to setup a Flake containing a system configuration, since I wanted to move my [personal config](https://github.com/imatpot/nixos-config) to Flakes for a while.

The result was not a hard-to-grasp config, if you know how to use Flakes. I didn't. And getting to the point of knowing how to use them wasn't exactly as straight-forward as I'd personally hoped. This is sadly very typical for the Nix ecosystem. Never, ever can you find that one place where you have everything you need, not even basic, barebones, boring, generic examples that you can build upon. People go out of their way to have these amazing sophisticated setups, only for every beginner to fail to even grasp the very foundation.

This collection aims to be but a single spark of light in the darkness surrounding Nix Flakes, specifically in the area of system configurations built upon it.

## How do I use this repo?

You can find all the templates in the conveniently named [`templates/`](templates/) folder. They all contain at least two files:

- `README.md` — This is where the template is explained (structure & usage)
- `flake.nix` — This is the base file for the configuration. Check the template's `README.md` on how to use it!

If you've never used a Flake before, you'll want to begin at the [most basic template](templates/basic) which has no shenanigans going on apart from a raw system configuration. Its [`README.md`](templates/basic/README.md) has a special section on how Flakes work and a list useful of resources about them. All other templates will require a basic understanding of Flakes (keywords: inputs, outputs, modules).

## Contributing

I am always open to new templates. However, given I want this to be as beginner-friendly as I can make it, there is a good chance that I might reject a PR if the template is too complex. Of course I will first try to give feedback on what would need to change for it to be included. So, if you do want to submit a template with a specific feature, make sure you try to orient yourself by the already existing templates.
