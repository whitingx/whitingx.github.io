---
published: true
title: Writing Useful Error Messages - Resources and Ideas
layout: post
tags: [ux, error messages]
---
Writing a useful error message is tricky. Striking the right balance of presenting useful information to people while explaining what the error was and, more importantly, what they can do about it is not an easy thing to do, especially when looking to automate/template these type of interactions.

![Windows 10 Error Message](https://raw.githubusercontent.com/whitingx/whitingx.github.io/master/_posts/images/bad-error-message.png "Windows 10 Error Message"){: .blog-image }
<span class="blog-image-caption">Windows 10 Error Message - Please don't do this ツ</span>

### Try to Avoid Using Error Messages

The ideal goal is to not _need_ to use error messages at all. Look instead to design what _Don Norman_ calls a 'collaborative' system, tell the user the requirements _before_ they do the work. If there are special ways you want user to enter content/data into a system tell the user _before_ they enter it, not afterwards.

### If You Do need to Display Error Messages

Where Error Messages are used try to ensure they sound like they’ve been written for real people to understand and not using incomprehensible, 'machine code' style message.

Think of the error message as a conversation with the person using the system. Make it polite, understandable, friendly & jargon-free. The goal is to write an actionable error message that anyone could understand.

Ensure the error message is visible in regard to message size, colour & location. If the person can't _see_ the error message they will have trouble acting upon it. It needs to be specific as to what the problem is and help the user recover. Explain what they need to do next and how can they get back to what they were doing.

### An Example Error Message

A useful error message template, based off the above guidelines looks like this;

{% highlight linenos %}
[What has happened in plain, jargon-free language]

[What the user can do to continue with their task]

[Who the user can contact (including named person, email address, phone number, etc. where applicable) for assistance]
{% endhighlight %}

### Error Message Writing Resources

The Guidelines above are based on a few useful resources I've found when researching writing useful error messages.

[_Don Norman_ writes about using 'collaborative', rather then 'error', messages here](http://www.jnd.org/dn.mss/error_messages_are_e.html)

[_Ben Rowe_ gives 4 useful tips in this _UXMas_ article on error messages](http://uxmas.com/2012/the-4-hs-of-writing-error-messages)

[Some great error message writing tips in this article by _Thomas Fuchs_](https://medium.com/@thomasfuchs/how-to-write-an-error-message-883718173322)

[Some older, but still relevant, info in this article on error messages from Michael Bolton (not _that_ one, I think ツ)](http://www.developsense.com/essays/AReviewOfErrorMessages.html)

[_Steven Hoober_ talks here on how error messages are an anti-pattern](http://www.uxmatters.com/mt/archives/2015/11/error-messages-are-an-anti-pattern.php)

[Again on _UX Matters_ - _Caroline Jarrett_ explains how not to be embarrassed by your error messages](http://www.uxmatters.com/mt/archives/2010/08/avoid-being-embarrassed-by-your-error-messages.php)

and finally;

[_NN/Groups_ _Jakob Neilson_ offers some useful error message writing guidelines](https://www.nngroup.com/articles/error-message-guidelines/)
