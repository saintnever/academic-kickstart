---
title: Interconnection Techniques
summary: I develop power transfer and cross-device interaction techniques for interactive IoT devices.    
#To realize pervasive interaction, I design interfaces that establish power and information links among distributed devices. 
# tags:
# - Deep Learning
date: "2017-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Currently, most interaction interfaces are designed for powerful and independent computing devices, which adopts a device-centered design approach. A human-centered pervasive interface, however, requires seamless interconnection among devices for resource redistribution. By allocating energy, computation, and interaction resources based on needs, the design of the interfaces can be more flexible and thus truly be woven into the fabric of everyday life. 
<!-- The power and information interconnections are the underlying infrastructure, on top of which interaction techniques can be implemented.   -->

<figure>
  <img src="./touchpower.gif" width="100%" />
  <figcaption><i>Figure 1. TouchPower is an Interaction-based Power Transfer (IPT) technique. It transfers DC power through contact between electrodes on the glove and the object. </i></figcaption>
</figure>

 Power interconnection between few on-body wearables and many off-body objects can significantly reduce user maintenance efforts. I invented the concept of __Interaction-based Power Transfer (IPT)__, which transfers on-body energy to off-body devices leveraging the contact and close distance between user and object during interaction. IPT is especially suitable for devices that only need to be powered during interaction (e.g. mouse, remote controller). The concept was validated with a glove-based IPT prototype __TouchPower__ (Figure 1), which transfers DC power through contacts of electrodes on the glove and objects. With careful design of the transfer interface, energy can be distributed without affecting the original interaction. 

<figure>
  <img src="./intro.png" />
  <figcaption><i>Figure 2. Tap-to-Pair enables wireless device association with minimal resource requirements. </i></figcaption>
</figure>

It is challenging to establish information interconnection between resource-constrained IoT devices. __Tap-to-Pair__ provides a spontaneous device association experience based on temporal correlation of two signals. Users can tap the initiating device to induce periodic wireless signal strength changes, which is then correlated with the blinking patterns of target devices for association. In a follow up work, I proposed a 2D design space and design guidelines for blinking patterns by applying Bayesian models of user tapping behaviors. Such optimization enables the technique to support robust selection among more targets. 


*Go to* [*Sensing Tags*](/project/sensing)  
*Go to* [*Finger Wearables*](/project/smartring)  
