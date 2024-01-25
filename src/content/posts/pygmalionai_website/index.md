---
title: Site is up. Where to Next?
seo_title: Announcing the Website
summary: The website is finally up. Time to discuss the plans going forward.
slug: website_announcement
author: Tav
date: 2024-01-22T03:52:30-05:00

project types:
    - Announcements
---

We rarely make blog posts but this is important so please take your time to read. To those who want the site link. 

Click here: https://pygmalion.chat

The link will give everyone access to our website’s character repository. We have a sizable community built with character creators and their users alike, so we encourage people to use our site as an alternative character repository. It’s better than being contained in a Discord server. The repository currently supports v2 cards only but we have plans to include more support if users request it. 

On the **1st of February, we will begin our closed beta period for the chatting section of the site** to determine the stability, usability, operations cost, and other metrics. This will influence how we determine our subscription pricing. 

Sign up for our closed beta will be announced three times on our Discord - discord.gg/pygmalionai

I recommend reading the rest of the blogpost as it will **cover the policies, roadmap and general direction for PygmalionAI.**

## Will the Site Be Censored like Character.AI?

No. There will be no invasive safety guardrails. The only thing the site will moderate:
- Adult content characters must be kept private 
- Publicly posted characters will go through a human moderated approval queue. Approved creators can skip this queue.

Please read further if you want to know why.

### Payment Processors
If you have used the various chatting websites on the market, then you may be aware of the struggles those sites have with finding appropriate payment processors. Here is some recent examples:

- Spicychat.AI lost their support from Stripe and Patreon for adult content violations.
- YodayoAI lost their support from Stripe for adult content violations.
- Other platforms that build an app for their website with adult contents have difficulties being available the App Store and Google Play.

Operating an LLM chatting service is not cheap; we will have to rely on community support. Stripe, a popular payment processor, recently updated their restricted business guidelines to incorporate AI-generated content. Here is an excerpt from this page: [Stripe Legal Page](https://stripe.com/us/legal/restricted-businesses).  

![](https://files.catbox.moe/xopak8.png)

This sets a precedent that other payment processors may follow suit to deal with emerging AI technologies. This is concerning when we are running an AI chatting site as our first service.

Our main priority is ensuring PygmalionAI is *sustainable*. This is not possible if there is a constant threat of us losing our source of revenue due to an unhappy payment processor. There is no telling when and how the changes will happen so we believe it may be best to play it safe for now. Everything we do on the website is determined by required guidelines and regulations, not due to personal interest. If we find a payment processor that is more open-minded as an alternative to our current one, then we will adjust the site guidelines accordingly. 

Currently, the company is driven by the personal funds from the co-founder Tav. We maintain a cautious approach towards investors, refraining from accepting funds from those seeking to significantly alter the company's direction. We believe that external capital could compromise our influence within the company and our commitment to remaining open source. The open-source philosophy is a founding principle we follow, not a marketing gimmick (as evident by the majority of our [GitHub repositories being AGPL](https://github.com/PygmalionAI)). We believe the character repository we built will be a great alternative to what’s currently available and we hope to be leading with cool chatting features as well. And speaking of which…

## What Makes Our Site Any Different?
There are lots of AI chat websites around. Character.AI still remains the most popular. You got adult centric ones, more gimmicky ones, and some being relationship simulators. We’re late with our arrival but we haven’t been slacking. Here are some site specific features not covered by other sites that are on our roadmap.

- Custom models (LoRA trained) tailored for community-requested franchises or characters. As an illustrative example, applying a franchise tag to a character like Genshin Impact ensures that all generations undergo a Genshin Impact model, enhancing accuracy in portraying the details of that universe.
- Support for Lorebooks and Soft Prompts
- Integration of various APIs. We envision providing an API for our character repository and models while enabling external APIs to connect with our website frontend. Proper structuring will be essential to prevent abuse.
- Incorporation of entertaining features. There are many fun possibilities with LLMs. For instance, introducing a visual novel mode and a textRPG mode for added fun.
- Community events offering opportunities to acquire unique vanity flair.

There are more features we have planned. Consider this as a small sample of what is to come with our website. We will also support the standard quality of life practices existing in other applications as well, along with power user features seen in SillyTavern. Naming a few:

- Regeneration
- Swipes (and multi-swipes)
- Impersonation
- Author’s/Character’s Note
- Image recognition (captioning)
- Support for (almost) every sampling method
- Various other QoL features

It’ll take a while for us to catch up with common feature support but we’ll get there. A combination of features from AIDungeon, Character.AI, SillyTavern and Miku.gg is what we are aiming for. Our stance for the website is going for an uncensored approach but not aligned to adult content. What do we mean by this?

## Uncensored vs Adult Content and What to Support

Making smutty generations is easy. Making models uncensored is fairly easy nowadays too. There is an overlap assumption that uncensored must always equal lewd generations. We don’t think that is the case. Our models are designed to emulate personalities by user defined settings. You want a tsundere anime girl with a Texas accent? A himbo guy that’s a dumb dog personality on the streets but a beast in the sheets? Sure, let’s have our models support that. Just like image generations and continual research into text prompts to that one perfect image. We would like to provide models to do this for character personalities. 

The nature of censored models, due to their heavy artificial bland bias, is not suited for these robust personalities. If the character is an adult, and they have a promiscuous trait? Then a model should support that. Adult content generations for the sake of pornographic messages have no research potential. It gets samey. If we want to proceed as a company and last for a long time, then our focus should be on making good roleplay models of all varieties, it just has the side effect of supporting adult content. Emulating the diverse spectrum of human personalities is not easy but we believe it is a worthwhile avenue to keep exploring for years to come in all aspects of accented dialogue, memory, emotive behavior and other elements that encapsulates a personality. The difficulty of doing this is why we are sparse with releasing models. It’s not easy. Here is an example of our HuggingFace repository and the experiments we do constantly. 

![](https://files.catbox.moe/meowh1.PNG)

## What's the Point of Making Personality Models?
There are a lot of arguments currently regarding the use cases of AI and how it may cause industry disruptions (image generators and the current artist world is a big example). We personally believe there is a use case for making personality models by applying it to games. A NPC with the ability to generate personality-tuned dialogue provides a more immersive experience compared to predefined scripts. You may be asking if script writers for games will be replaced but not quite. 

World building, making original characters, establishing the details, figuring out the relationships can only be done with human creativity. A custom model that will run NPC dialogues will still require the baseline information that a human created. For example, a game world built on the complicated relationship structure of a nation of sentient rats and mice can only be crafted with human precision. The names, the specific lore, the unique linguistic features even. This can only be crafted and added to a model by a person. We believe there can be a collaborative relationship between script writers for games, and a person who can apply it to a model to generate immersive dialogue according to the writer’s specifications. The creative process is still important going forward.

A lot of the features we would like to have on our website can be doubled as tech demos for model integrations into existing video game genres. The smaller we can make the models while keeping the quality will make it easy to support less powerful devices with less VRAM. It is an important area to be explored to encourage more hobbyist development. A lot of the “meta” for producing models is focused on beating benchmarks and being “better” than OpenAI models. It is a bandwagon we don’t want to follow. We can continue developing in this space as long as we have the money to sustain ourselves. You can support us by using our website and other endeavors we have planned according to the principles of open source. 

## Are You Really Going to Keep Open-Sourcing Stuff?
Yes, consistently for our models. Regarding other projects, our approach is as follows. If we invest a large sum in development, we aim to recover the investment by creating a service for it, as these costs are typically covered from our own pockets. Once we've not only recouped our initial investment but also earned an additional ten percent, we commit to open sourcing it under a permissible license. Adopting a model where everything is open-sourced upon completion would lead to **unsustainable** financial outcomes. To incentivize the responsible recovery of investments, we will establish public deadlines for the release of projects as open source. The founders—Alpin, Teargosling, and Tav—are motivated by the advancement of open source, not monetary gains. Our goal is to generate sufficient funds to cover our expenses and lead a modest life. Note that this does not encompass our current open-source projects, such as our inference engine.

## Will the Site Revenue Be Enough?
We believe so for getting us off the ground. A lot of it is dependent on working with the community and building the best service we can. As long as we continue to deliver and present new ways to engage with an AI chatting website. We believe there is a reason to support us. Our main focus is ensuring the website is operational sustainability and paying any developers we will work with us. Any remaining funds will be given to the co-founders for their livelihood expenses and personal re-investments into PygmalionAI. In the event of difficult financial periods, the co-founders are no stranger to doing additional contracts or jobs to make ends meet within the company. We are committed to keeping the lights on in PygmalionAI as long as we can.

## Anything Else?
Please stay tuned for our closed beta announcement. I also encourage people to read the community guidelines on our website when it is finished. The link to it will be provided when it has been finalized. 
