---
published: true
title: Quick Timestamps for Usability Testing Notes
layout: post
tags: [UX, testing, process, productivity]
---
Following on from the interesting talk by Christopher Bush ([https://twitter.com/suthen](https://twitter.com/suthen)) on Guerrilla usability testing ([http://northern-user-experience.org/2014/05/08/presentation-guerrilla-ux-testing](http://northern-user-experience.org/2014/05/08/presentation-guerrilla-ux-testing)) one aspect that I thought was a great idea was the use of text expansion to add a timestamp to observation notes (see slide `24` on the NUX page) to make them easier to cross-reference to recordings at a later date.

Since `OS X Mountain Lion`, _Apple_ have included an in-built text expansion tool hidden away under the keyboard settings.
 
![OS X Text Expander](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/osx-text-expander.png "OS X Text Expander")
<span class="blog-image-caption">OS X Text Expander</span>

But this doesn't allow for timestamps to be added. There are a few application available for this in the app store such as TextExpander ([http://smilesoftware.com/TextExpander/index.html](http://smilesoftware.com/TextExpander/index.html)) but this seemed over complex for the single use case required.

 Looking for other options, the discontinued **xType** ([http://www.adnx.com/web/english/app4mac](http://www.adnx.com/web/english/app4mac)) seemed to be the best solution. Due to being a discontinued product instructions on making this application work with `OS X 10.9` pointed towards the older, pre-`10.9` accessibility options but I was able to get this working through the following procedure.

1. Download and install **xType** - [http://mac.softpedia.com/get/Utilities/Presto-app4mac.shtml](http://mac.softpedia.com/get/Utilities/Presto-app4mac.shtml) - `version 1.3.1` is the most up-to-date.
2. Install and launch as usual, you will see a prompt to open the `Accessibility options` to allow **xType** to work but the required option is no longer located here.

    ![OS X Accessibility Settings](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/osx-a11y-settings.png "OS X Accessibility Settings")
<span class="blog-image-caption">OS X Accessibility Settings</span>

3. Navigate back to main `System Preference` and select the `‘Security & Privacy’` options.

    ![OS X Security & Privacy](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/osx-security-privacy.png "OS X Security & Privacy")
<span class="blog-image-caption">OS X Security & Privacy</span>

4. Select `Privacy` > `Accessibility`, click the padlock icon and enter password if required.

    ![OS X Accessibility](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/osx-a11y.png "OS X Accessibility")
<span class="blog-image-caption">OS X Accessibility</span>

5. Click the checkbox for `xTypeAgent` then click the padlock icon to prevent further changes.

    ![xTypeAgent](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/xtype-agent.png "xTypeAgent")
<span class="blog-image-caption">xTypeAgent</span>

**xType** should now work as required. Go into the application itself, create your required shortcut for the timestamp (in this example `.t`) and use the `extras` drop-down to set your preferred date/time format and set the option to only work in your note taking app.

![xType Settings](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/xtype-settings.png "xType Setings")
<span class="blog-image-caption">xType Settings</span>

Now whenever making observation notes simply type `.t` and the current timestamp will be added to your notes. Following on from Christopher Bush's suggestions you can also use the text expansion to highlight what area the note relates to so `.tn` could indicate a navigation issue `.td` a design one for example.

 Hopefully this information helps streamline your own usability test process.
