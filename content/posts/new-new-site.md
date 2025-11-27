---
date: '2025-11-27T21:44:08Z'
draft: true
title: 'New New Site'
tags:
  - news
---

Hi all.

Welcome to the new site.

When Postitive Internet contacted me last week letting me know I was using PHP 5.6 -- which I subsequently realised went out of support about 7 years ago at this point -- I had kind of forgotten I was responsible for the server.

In fact, given the site ran Wordpress, I was astounded the site hadn't been done over.

Postivie Internet kindly let me know that the upgrade might cause Wordpress to break.

So I did what everyone should do in these situations and backed everything up.

But the server is still upgraded to pretty old versions of Debian, Apache and PHP which was alarming.

So I've taken the liberty of using the backup to [move everything over to a static site using Hugo](https://github.com/yamatt/gllug-site). Take that hackers!

I also removed the spam that had found it's way in to the site from I think a previous release.

I was also able to configure it so the old Wordpress URLs are redirected to the new URLs without the need for `index.php` in the URL.

I realise this is at least the [second time the site has been updated](./welcome-to-the-new-gllug-site.md).

I've also got a neat solution for automated deployments as evidenced by this new post which is simply pushed to GitHub and then then synced to the server.

I've also noticed there have been a few recent meets.

One of the things I want to do is to capture these on the site in future. This new site should make that easier. Or people who want to publish their meet can raise a PR.

Reach out on the mailing list if you see any issues.

And I am extremely greatful to Positive Internet and particularly Brad who helped me fix everything, incudling adding certs to the site.
