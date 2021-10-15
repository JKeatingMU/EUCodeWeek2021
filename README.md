˛
# EU Code Week 2021 - Introductory Coding for Creatives: Using Scalable Vector Graphics (SVGs) to make Emoji and Cartoon Characters

John G Keating
Department of Computer Science
Maynooth University


## Introduction

In this short workshop we will look at how to create and work with SVG (Scalable Vector Graphic) images. If you haven't used SVGs before, then this lesson provided a short overview about what SGVs are, how to create them, and how to use them in online environments. In particular we will learn how to create simple emoticons and cartoon figures (ghosts) using SVG commands. 

This workshop (Live Streamed to YouTube; https://youtu.be/_jumZw12Jn4) will introduce participants to the world of vector graphics and explain the basics of creating emoticons (emoji) and simple cartoon characters (ghosts) using Scalable Vector Graphics (SVGs). Participants will first learn how to hand-code using basic and advanced SVG element commands. Once the basics are understood, participants will learn how to animate their creations. Finally, the workshop will end with a short lesson on how to control the graphics and animations using HTML and JavaScript. 

John Keating is an Associate Professor in Computer Science at Maynooth University. John has been teaching coding for over 30 years and currently teaches courses on Web Development, Interaction Design, and Software Design. John’s primary research interest is educational technology, collaboration technologies, and technology supported learning. John has doctorates in experimental physics and linguistic methods in science education. All of John's current lecture videos in Software Design and Web Technology are accessible from his YouTube channel (https://www.youtube.com/c/JohnKeatingMU).

## Getting Ready for the Workshop

Participants who have a computer can join in and follow John as he works through the workshop lecture and SVG creation examples. John has provided provide details on how participants can set up their device to make their own SVGs in advance of the workshop; a “Getting ready for the Workshop!” video is available here ( https://youtu.be/jLmNlb_RRAA). Or check the next section on "Tools Required".

All of the example material will be provided via this GitHub repository. Participants do not need internet access to create emoji and cartoons, but they will need internet access to download and install the tools required (the Atom Editor and packages). The “Getting ready for the Workshop!” video will show how to set up everything. If participants have a mobile device with YouTube access they can watch and join in on the live discussion. Teachers may project the YouTube video onto a classroom screen and students can follow on (offline) lab computers, etc. Participation in the chat will require individual access, however.

## Tools Required for the workshop

If you want to code along with John during the workshop you will need to install an editor and an SVG viewer. You will also need a browser that can view SVG images. Specifically, you will need

- The Atom Editor with (sag-preview package installed): (https://atom.io) Atom works for Windows and MacOS and I show how to install it and the SVG preview package. You need to have permission to install applications to use this option.

- Alternatively, you can use an online editor and viewer (https://www.svgviewer.dev). This works well and you will be ablate share your creations easily using this website.


## Scalable Vector Graphics (SVG)

SVG is to graphics what HTML is to text. It is a text-based (XML), open Web standard for defining vector-based images that can be rendered cleanly (scaled/zoomed without loss of quality) at any resolution, and are designed specifically to work well with other web standards such as DOM, CSS, JavaScript, XSL, etc. SVG has been developed by the World Wide Web Consortium (W3C) since 1999. SVG 1.1 became a W3C Recommendation on 16 August 2011.

SVG images and their accompanying behaviours are defined using pure XML text files, which means they can be searched, indexed, scripted, etc. Every element and attribute of the image can be animated. They can be created and edited with any text editor, with drawing software, or created using programs (like we will be doing in this module).

Compared to classic (bitmapped) image formats such as JPEG or PNG, vector images such as SVG can be rendered at any resolution without loss of quality. They can be easily localised,  without the need of a graphical editor, by updating the embedded text using a text editor. With a proper understanding of their construction, and using libraries or custom-written programs, SVG files can be localised interactively.
