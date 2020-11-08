---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Odour stimulator"
summary: 'A fast, time precise, open source system to deliver odours'
authors: ["andre"]
tags: ["behaviour","stimulator"]
categories: []
date: 2020-11-03T11:02:20Z
# Optional external URL for project (replaces project detail page).
external_link: ""
# page_type: project
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Sussex-Neuroscience/olfactory-stimulator"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This open source stimulator is based on previous work by a different group. Their work is published  [here](https://www.pnas.org/content/111/47/16925), [here](https://www.sciencedirect.com/science/article/pii/S2589004218300646) and [here](<https://academic.oup.com/chemse/article/42/2/141/2709444>)


## Some information about this project:

- developed as part of the work of the [Nowotny lab](https://www.sussex.ac.uk/research/centres/sussex-neuroscience/phd/4yearphd/supervisors/circuits-projects/thomas-nowotny-project) and it is being setup initially for experiments with flies. 
- The reason we are publicly documenting things is that since the original papers describing the stimulator came out, some enabling technology has become widely available, which makes setting this up simpler and less expensive. This write up is our attempt to document this.
- Some documentation of the orignal stimulator is already publicly available on [github already](https://github.com/grg2rsr/OlfactoryStimulator), unfortunately some of the schematics are only in PDF format (which prevents fast conversion to PCBs) and some of the CAD files are in a proprietary format, that officially can only be read with "Autodesk Inventor". Luckily there is a [plugin for FreeCad](https://github.com/jmplonka/InventorLoader/) that allows the conversion to a more open format.  This derivative will share orignal files that can be modified using open source sofware.