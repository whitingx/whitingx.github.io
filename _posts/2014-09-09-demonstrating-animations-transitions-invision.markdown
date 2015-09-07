---
published: false
title: Demonstrating Animations & Transitions in InVision
layout: post
tags: [tools, InVision]
---
#### A quick tutorial on how to capture animations and transitions into InVision for design discussion.

The web is not a static medium. Animations to offer visual feedback to a user are becoming commonplace as [the technology to easily accomplish this becomes more prevalent](http://caniuse.com/#feat=css-animation).

InVision - [http://www.invisionapp.com/](http://www.invisionapp.com/) - is a great app for design discussion and prototyping but demoing animations & transitions that are an integral part of the prototype is currently not a documented feature.

As a requirement arose to allow a distributed team to view these animations I worked out the following solution. While not as smooth as the usual InVision workflow, it still works well for required use cases.

Firstly, an additional piece of software is required to capture the animations and transitions as an animated gif. For this I recommend the open-source and easy to use LiceCap - [http://www.cockos.com/licecap/](http://www.cockos.com/licecap/). This offers a cross-platform solution for Windows and MacOS (it should also run under Linux using WINE or alternative options can be found in this thread - [http://askubuntu.com/questions/107726/how-to-create-animated-gif-images-of-a-screencast](http://askubuntu.com/questions/107726/how-to-create-animated-gif-images-of-a-screencast).

Initially, use LiceCap ([how to record with LiceCap demo here](http://www.cockos.com/licecap/how_to_licecap.gif) to capture an image showing the animation you would like to add to InVision for discussion.

![Example animation captured using LiceCap](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/notification-anim-demo.gif "Example animation captured using LiceCap"){: .blog-image }

Example animation captured using LiceCap{: .blog-image-caption }

Keep this image simple, if you have multiple animations, record them separately and upload as individual screens to avoid confusion around comments.

I’d also advise not demoing transition between screens using this method as any comments added may lose context as the animation moves between the different screens.

Once you have captured the animated image, simply upload to InVision as normal and add comments where required.

![Animation uploaded to InVision with an added comment](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/invision-anim-comment-2.png "[Animation uploaded to InVision with an added comment"){: .blog-image }

Animation uploaded to InVision with an added comment{: .blog-image-caption }

This allows a distributed team to make use of the features contained in InVision while allowing relevant animations and transitions to be viewed and commented on.