---
layout: post
title: November 2021 update
---

Is Welcomments still being developed?
Why yes it is!

<!-- more -->

# What's new?
Although there is still stuff to be done, a lot of the core features are there today.

In April of 2021, Welcomments already had all of the following features:
* automatic spam protection
* email notifications for new comments and replies
* full functionality with no Javascript
* a base CSS file to get you started while offering full customizability
* optional Javascript snippet for more interactive experiences
* admin panel and easy setup for new websites

The pace has slowed down a little bit compared to the start of this year, but that
doesn't mean that we've been sleeping for 6 months!

Let's see some of the new stuff.

## Dark mode!
Nowadays, I'm a big believer of dark mode.

Most websites implement it, but Welcomments didn't.
This meant that every time I wanted to use [the Welcomments admin console](https://app.welcomments.io), I was blinded by the sudden change in brightness.
No more!
The [Welcomments landing page](https://welcomments.io) now adapts to dark mode too.

Unfortunately, I didn't find a sane way yet to add dark mode support for the Welcomments starter CSS template.
Switching to dark mode automatically based on the system dark mode would break existing websites that only work in dark mode.

For adding dark mode support for your own Welcomments comment section, you can [use our CSS file for getting started](https://github.com/welcomments/website/blob/abfe51f2a00687d18238356de9990348ff257c09/css/site.css#L8-L37).

## Manual comment moderation
Since the very beginning, Welcomments has used [Akismet](https://akismet.com) for automatic spam protection. And that's still the case.
However, support for manual comment moderation has been requested quite a few times.

You can now opt-in to that.

![A screenshot of enabling manual comment moderation for Welcomments.](/img/manual-moderation.png)

In the settings tab of your website, you can check a checkbox to disable the automatic spam protection and manually approve every comment yourself.

Every new comment will appear in the moderation queue tab.

## Viewing spam comments
Now there's a new tab called "Spam" in your website's details page in the [Welcomments admin console](https://app.welcomments.io).
Here you'll find all the comments that were automatically flagged as spam.

If for some reason, a comment was wrongly classified as spam, you can publish it with a click of a button.


## Work-in-progress documentation
We now have [a documentation section](https://welcomments.io/docs).

It still needs some love - we'll keep on updating and improving it.

## Miscellanous improvements
Welcomments also has gotten tons of bugfixes and small improvements over the last six months.

Notably, but not limited to:

* Users can now unsubscribe from comment reply notification emails by following a link at the bottom of each email
* We're now adding `rel="nofollow external"` and `target="_blank"` for all links in comment message bodies
* Blockquotes were not previously working - that's now fixed
* Faster response times - we moved our servers to Frankfurt, and will add new locations in the future so that the admin console & comments are handled really fast wherever the users are.
* The admin console should now feel way snappier, but we're still working on it!

We're continuing to add some cool features and polishing the existing experience. Stay tuned!