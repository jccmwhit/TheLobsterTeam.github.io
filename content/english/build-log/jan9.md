---
title: "Build Update - Jan 9"
date: 2023-01-26T21:37:37-05:00
# post image
image: "blog_images/jan9/jan9_header.png"
# post type (regular/featured)
type: "regular"
# meta description
description: "This is meta description"
# post draft
draft: false
---

With the new year comes our 4B term, which means it's time to start building!

<hr>

### Project Recap

In Fall 2022, we identified a need for better PCB prototyping solutions, and we set out to make prototyping and testing two-layer circuits faster and easier.

We designed a fully autonomous, all-in-one solution that mills traces, drills via holes and thru-hole component holes, and produces vias with solid copper wire.

![image](../../blog_images/jan13/cad_render_23_01_26.png)

### Design Recap

At a high level, the device performs the following tasks:

* Drill via holes
* Produce vias using solid copper wire
* Mill electrical traces
* Drill thru-hole component holes

The device can also be broken down into several subsystems, which fall under three main categories of mechanical, electrical, and software/firmware:

| Mechanical          | Electrical                | Software/Firmware |
| ------------------- |-------------------------- | ----------------- |
| Frame               | High Voltage Conversion   | Motion Control    |
| Wire Feeding        | Low Voltage Distribution  | PCB Data Parsing  |
| Via Pressing        |                           | Computer Vision   |
| Motion              |                           |                   |
| Milling & Drilling  |                           |                   |

### Building and Testing Timeline

The device has many systems; some are similar to existing works, and some are novel that we are developing. First and foremost, we need to build the frame and electrical systems, so that we can mount components and power them. Then, to ensure we have sufficient time to test and debug the novel systems, we've prioritized their builds first.

The general build and testing order is as follows:

1. Frame + Electrical
2. Wire Feeding + Computer Vision (Novel System)
3. Via Pressing + Via Press Motion Control (Novel System)
4. Motion + General Motion Control
5. Milling & Drilling

### Progress to Date

Before the winter holidays, we completed the design up to a prototyping readiness. While the design will inevitably change as we go along, we are currently at a point where we can start building the physical machine and developing its firmware.

Also before the holidays, we purchased all of components required to build the current design, and currently we've received all but one component. As the design evolves, we may have to buy new components as we go along, but materials aren't expected to cause delays in the short term.

While we all took some time off to enjoy the holidays, we also made sure to put time in on the project:

* Josh machined our custom aluminum components and fine-tuned some of the mechanical design
* Caleb started developing computer vision programs to help feed the via wires
* David spent time familiarizing himself with Klipper, the open-source firmware platform we'll be developing off of
* James worked on our electrical components to ensure we'll get CSA field certification for the symposium
* Brandon optimized our schedule and kept track of incoming orders

<hr>