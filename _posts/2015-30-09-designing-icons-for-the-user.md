---
published: true
title: Designing Icons for the User
layout: post
tags: [UI, icons]
---
I've recently been doing a lot of design work around **notifications**. This is an interesting area trying to get the balance between what the user needs to see and what the system needs to show them. Alongside the standard `info`, `success`, `warning` & `error` notifications the project required an additional notification style for `system` messages. These are things like showing the user a message has been sent, or the system is loading information.

For things like `info`, this icon choice is fairly straightforward. Just doing a search for _info icon_ - [https://www.google.co.uk/search?q=info+icon](https://www.google.co.uk/search?q=info+icon) - returns many results for the standard `i` in a container that is a fairly universal symbol for information.

![Tourist Information Kiosk](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/tourist-information-01.png "Tourist Information Kiosk"){: .blog-image }
<span class="blog-image-caption">Tourist Information Kiosk</span>

![Tourist Information Signpost](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/tourist-information-02.png "Tourist Information Signpost"){: .blog-image }
<span class="blog-image-caption">Tourist Information Signpost</span>

![Tourist Information Office](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/tourist-information-03.png "Tourist Information Office"){: .blog-image }
<span class="blog-image-caption">Tourist Information Office</span>

The same goes for the icons used for `success` or `error` - there's a fairly well defined set of universal symbols used for these and it makes sense to use these to reduce cognitive load for the user.

But looking at the `system` notification we realised that no one icon really covered the potential variants, so the decision was made to dynamically add a relevant icon to denote the system process taking place, display a certain icon to denote the system _saving_ an item and another one to denote the system _sending_ a message.

But then I took a step back to consider this more - from the users perspective they see a constantly changing notification, it increases the effort they have to put in to understand what the notification is telling them. We were designing this notification based on what the Designers & Developers thought the user would _want_ to see rather then what the user _needed_ to see. From the users perspective, all they need to know is that the system is performing an action and if that action has succeeded or failed.

Don't try to overthink UI, by avoiding dynamic notification icons in this area we made it easier for both the user to comprehend what is happening in the system and reduced development time and potential issues. In many cases, the simplest solution is the best.

