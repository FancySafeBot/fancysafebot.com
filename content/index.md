---
layout: splash
subtitle: A fancy robotics library for safety critical systems
---

Fancy Safe Bot is a modern robotics library intended to be used in safety critical systems. It was originally developed for research in [**rehabilitation robots**](https://kylechisholm.com/assets/pdf/chisholm2014.pdf) and has been adapted to modern coding standards and tooling for C++. Dive deeper into the [**documentation**](https://docs.fancysafebot.com) to learn more about how you can use it to control robots designed with safety in mind.

{% include "snippets/links-card.njk" %}

The library was originally developed for research in rehabilitation robotics and was released with a small set of features. Fancy Safe Bot is in [**active development**](https://github.com/FancySafeBot/fsb-library) and we'd love to hear from you about how to make the library better and what features you'd like to see. Please have a look at the [**developer's guide**](https://docs.fancysafebot.com/developers_guide.html) if you'd like to contribute.

## What is special about Fancy Safe Bot

Fancy Safe Bot strives to make it possible to integrate robotic control software into safety critical systems with the following library features:

- Follows coding standards with safety in mind ([MISRA](https://misra.org.uk/))
- Unit testing, code coverage, static analysis, and profiling
- Opinionated set of robotics features: Kinematics, dynamics, state machine, controllers, filtering, etc.

Software designed for safety-critical systems needs to be certified for its intended use, whether in medical robotics, self-driving cars, space robotics, aviation, or other applications where safety is paramount. Large open-source software projects are difficult to get certified in these applications where the entire design, verification, and validation process must adhere to strict international standards.

Fancy Safe Bot addresses these challenges with an open-source robotics library that can be integrated into a certifiable software development process.
