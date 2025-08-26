---
{"view-count":1,"permalink":"/gdm-aor/blogs/why-i-opted-out-of-doku-wiki/","dg-publish":true,"dgPassFrontmatter":true,"noteIcon":"","created":"2025-07-17T12:44:26.052+12:00","updated":"2025-07-17T05:26:56.736+12:00"}
---


**Written By:** Gdazegod

## Background
A couple of weeks ago, I called time on the previous incarnation of the current website which was the **GloryDaze.info** website. It used the **DokuWiki** publishing platform, but the more I continued with it, the more issues started appearing.

1) The site was dependent on a number of plugins. Many of which became outdated and were no longer fit for purpose. This then caused a cascade of error logs on our server, requiring constant maintenance.

2) I could never get YouTube videos to work properly. The specific plugin for this (Vshare) caused much gnashing of teeth. It wasn't helped by YouTube constantly running inference by mucking around with their code like whack-a-mole. It proved to be very frustrating.

3) Search Engine Optimisation was another headache. I used scripts to generate search results for Google, Bing and Yandex. The worst of which was Google. I simply gave up in the end as trying to nudge Google to get it right was an exercise in futility. As a result, we had loads of our pages being identified to be readied for indexing, but the indexes never took place.

4) Customer Support. A waste of time from my perspective. The DokuWiki team are in their own bubble.

## The Detail
In the end, I moved the entire GDM content base to the **Obsidian** platform. All of the content had been saved locally on both my phone and desktop. Obsidian is a mostly mobile platform (Android app) but is also used on the desktop too (via a Linux AppImage instance). It's a pleasure to work with, and best of all, I can publish the content at no cost. No domain hosting nor paid software. Beautiful.

This is how it works:

```
**Local to Online Repository:**

Obsidian -> Github (online repository)

**Online Repository piped to Web Platform:**

       -> Netlify (option 1)
Github -> Cloudflare (option 2)
       -> Vercel (Web option 3)
```

I use the Netlify option at this point in time. You are currently reading this blog post on Netlify.

At some point, I will probably move to the free tier option on Cloudflare, so that I can take advantage of other tools they have there, including:

- preventing Web page scraping
- using a customised domain mame
- and better access to global reach due to their CDN facilities.
- take advantage of better search engine management too.

However, setting up a Cloudflare instance is not a trivial issue though. Once I can get this sorted, things will get easier.

## In Summary
So far so good. The content needs slight markdown syntax coding changes. Much of it is similar, but coding changes to videos (using iframe) and file linking needs work, though thankfully, bulk copy paste across the entire content base shaves a lot of time off.

Keep checking back.

George (Gdazegod)

---

#blog