# Awesome Edge Device / IoT Fleet Management

This community-driven resource informs edge developers and IoT fleet managers of foundational skills to know and best practices to learn. While it's hosted on the open balenaLabs org, these best practices and tips **do not have to be balena-related**. We want to create a resource that's helpful for edge developers and fleet managers using their favorite or preferred tools.

**The goal:** Empower anyone to become more comfortable and proficient with creating edge and IoT projects at scale.

At a high level, it covers:

* Docker / why containers on edge devices
* Edge devices and SBCs in general
* basic low-voltage electronic skills
* Setting up your development environment, hardware setup…
* Provisioning a device
* Managing a device
* Troubleshooting and testing
* Common networking things to make sure you do / or to avoid
* … probably a ton more

This format is crowd-sourced and community-driven, so it'll change as we grow the body of knowledge here.

## Additional topics to cover

Here are additional ideas from the [original balenaForums thread](https://forums.balena.io/t/id-like-to-create-an-edge-developers-guide-to-the-galaxy/353193/8):

* Security best practices!
* How to handle hardware? (how to store hardware so that it lasts, don’t keep a board on a metal surface, or don’t touch pins with a metal screw driver)
* Measuring and logging (temperature, wireless signal strength, IO ops, bandwidth)
* Linux basics
  * What is an operating system?
  * What is linux?
  * What are the various flavors of linux?
  * What are the basic commands in your chosen distro?
* Over-the-air (OTA)\Atomic updates
  * Why it’s so crucial to have a reliable system for atomic updates (Balena official docs already cover this point in details, imho).
* Architecture overview and choices for IoT solutions: since edge devices probably need to comunicate with cloud systems, it’s important to design carefully your edge-to-cloud architecture with all the design choices required. A mention to MQTT is a must. (for this point, I’d be happy to contribute myself since we had a heavy design process when approaching Balena).
* A path to scale, as in getting a prototype together in a manner that’s easily scalable when you want to deploy device 2, 3, 4…n.
  * Then perhaps actually taking the user through the steps of provisioning your second prototype,
  * and your first production device, and some of the aspects of fleet management
  * I think part of what’s cool about developing with balena is that to a certain extent you’re already set up to scale as soon as you hit v1 of your app, which is a strong benefit that perhaps isn’t apparent to beginners.
* move from 1 container to multi-containers
* different connectivity examples (e.g. cellular, WiFi, ethernet, LoRa, Zigbee, etc)

Please add more topics or full-on sections to this guide if you're interested! :)

## Acknowledgements
Huge thanks to the members on [this balenaForums thread](https://forums.balena.io/t/id-like-to-create-an-edge-developers-guide-to-the-galaxy/353193/8). I don't know what your handles are on GH, but feel free to add them to this doc so we can properly attribute you for your hard work and contributions.
