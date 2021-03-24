---
layout: legalese
title: Privacy Policy
description: What information we collect about you, and why. And who are the other parties that will know about you.
---
## As a visitor to welcomments.io
We use Plausible Analytics to track overall trends in the usage of our website.
Plausible Analytics collects only aggregated information, which does not allow us to identify any visitor to our website.
To learn more, see their [privacy policy](https://plausible.io/privacy).

## As a website owner using Welcomments on their website
Here's the information we collect about you when you integrate Welcomments to your website.

### Information you provide to us explicitly
It's probably no surprise that we collect the information you explicitly provide to us.
This information consists of:
* **Your GitHub username**. When you sign in to the Welcomments console using GitHub, we get to know
  your GitHub username.
* **Information of your GitHub repositories**. When integrating Welcomments to your website, you give us 
  access to the GitHub repositories that you choose to. This gives us access to read and write data on the GitHub repositories
  you give us access to.
* **Communications with us**. If you reach out to us at [hello@welcomments.io](mailto:hello@welcomments.io), we will store
  a copy of our communications with you. This may contain your full name, email address, your website, and the contents of the email
  messages and any information in them you explicitly send to us.

### Information we automatically collect about you
When you sign in to the Welcomments console using GitHub, we'll also automatically collect the following information:

* **Your email address**. We get to know the email address your GitHub account is associated with. We use Firebase Auth 
  for authentication, and they also get to know your email address.
* **Your IP address**. Firebase Auth collects your IP address for abuse prevention and enhanced security. Your IP address
  is encrypted and stored temporarily by Firebase Auth, and _unaccessible to us_.
* **Your user agent**. Firebase Auth also collects your user agent, and it's also for fighting abuse and enhancing security.
  Your user agent is encrypted and stored by Firebase Auth and _unaccessible to us_.

When you delete your Welcomments account, all data mentioned above will be deleted and unaccessible to us within a day.
Firebase Auth will delete the data from their systems within 180 days.

To know more about Firebase Auth and their policies, refer to the [Firebase Privacy Policy](https://firebase.google.com/support/privacy).

## As a commenter
Here's the information we collect about you when you post a comment to a website that is using Welcomments.

### Information you provide to us explicitly
These are the fields that the Welcomments comment form asks from you, and that you fill in yourself.

The fields we store are your **name**, your **website** (optional), your **email address** (optional), and the **comment message**.
Your name, website, and comment message will be publicly visible to everyone.

#### What about my email address?

Your email address (if you provide it) will be stored in our database using strong 256-bit AES encryption, and it will be
unaccessible to other parties, including the website owner.

When you receive a reply to your comment, we'll use Mailgun to deliver the reply notification email to you.
Mailgun will store your email address in a hashed, pseudonymised format for better deliverability purposes.

At any given time, you can get your email address removed from our database (but not Mailgun's) by clicking on _"Unsubscribe from further replies to this comment"_
at the bottom of every reply notification email.

To read more about Mailgun and their policies, see their [privacy policy](https://www.mailgun.com/privacy-policy/) and
[GDPR email compliance](https://www.mailgun.com/gdpr/) documentation.

### Information we automatically collect about you
When you submit a comment on a website using Welcomments, we also collect:

* **Your IP address**. We temporarily store your IP address for spam prevention purposes. Your IP address is shared with 
  our spam prevention partner Akismet. After Akismet confirms that your comment is not spam, we'll delete your IP address
  from our database.
* **Your user agent**. We also temporarily store your user agent for spam prevention, and share it with Akismet. After 
  Akismet confirms that your comment is not spam, we'll delete your user agent from our database.
  
Your IP address and user agent will be strongly encrypted using 256-bit AES encryption, and they are not accessible to outsiders.

In addition to your IP address and user agent, we also share your name, website, and comment message with Akismet for spam prevention purposes.
Akismet keeps this data in their databases from two weeks up to ninety days.

To read more about Akismet's policies, see their [privacy policy](https://akismet.com/privacy/).

## Contact
If you have any questions or worries, would like to get a copy of your data or get all of it removed, please don't hesitate
to contact us at [hello@welcomments.io](mailto:hello@welcomments.io).