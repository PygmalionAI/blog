---
title: Site is Up. Where to Next?
seo_title: pygmalionai-website
summary:
slug: pygmalionai-website
author: Tav
date: 2024-01-23T03:52:30-05:00

project types:
    - Announcements
---

We rarely make blog posts but this is important so please take your time to read. To those who want the site link. 

Click here: https://pygmalion.chat/

The link will give everybody access to our site’s character repository initially. We have a sizable community built with character creators, and members who like to use characters, so we encourage people to use our site as an alternative character repository. It’s better than being contained in a Discord server. The repository currently supports v2 cards only but we have plans to include more support if users request it. 

On the **1st of February, we will begin our closed beta period for the chatting section of the site** to determine the stability, usability, operations cost, and other metrics. This will influence how we determine our subscription pricing. 

You can sign up for the closed beta here - https://forms.gle/vpM38MG3ejKMNHf99

I recommend reading the rest of the blogpost as it will **cover the policies, roadmap and general direction for PygmalionAI.**

## Will the Site Be Censored like Character.AI?

No. There will be no invasive safety guardrails. The only thing the site will moderate:
- Adult content characters must be kept private 
- Publicly posted characters will have some generation differences when chatted with to respect the original intent of the creator
- Publicly posted characters will go through a human moderated approval queue

Please read further if you want to know why.

### Payment Processors
If you have used various chatting websites then you may be aware of the struggles those sites have with finding appropriate payment processors. Here is some recent examples:

- Spicychat.AI lost their support from Stripe and Patreon for adult content violations
- YodayoAI lost their support from Stripe and AppStores for adult content violations 

Operating a LLM chatting service is not cheap and we will have to rely on community support. Stripe, a popular payment processor, recently updated their restricted business guidelines to incorporate AI-generated content. Here is an excerpt from this page: [Stripe Legal Page](https://stripe.com/us/legal/restricted-businesses).  

![](https://files.catbox.moe/xopak8.png)

This sets a precedent that other payment processors may follow suit to deal with emerging AI technologies. Which is concerning when we were running an AI chatting site as our first service. Our main priority is ensuring PygmalionAI is sustainable. This is not possible if there is a constant threat of us losing our source of revenue due to an unhappy payment processor. There is no telling when and how the changes will happen so we believe it is best to play it safe for now. Everything we do on the site is determined by required guidelines and regulations, not due to personal interest. If we find a payment processor that is more open-minded as an alternative to our current one, then we will adjust the site guidelines accordingly. 

Currently, the company is driven by the personal funds from the co-founder Tav. We have a general anti-investor stance and believe taking outside capital would be detrimental to our influence in the company and our ability to stay open source. Taking open-source is a founding principle we follow, not a marketing gimmick. We believe the character repository we built will be a great alternative to what’s currently available and we hope to be leading with cool chatting features as well. And speaking of which…

## What Makes Our Site Any Different?
There are lots of chatting sites around. Character.AI still remains the most popular. You got adult centric ones, more gimmicky ones, and some being relationship simulators. We’re late with our arrival but we haven’t been slacking. Here are some site specific features not covered by other sites that are on our roadmap.

- Custom models (LoRA trained) for community requested franchises. A basic example would be when applying a franchise tag to a character like Genshin Impact, then all the generations will go through a Genshin Impact model that will make the details regarding that universe more correct. 
- Support for Lorebooks and Soft Prompts
- Various APIs. We think it’s possible to give an API to our character repository, to our models, and allow external APIs to hook up to our website frontend. It will have to be structured correctly so it will not be abused.
- Fun related features. Lots of fun things you can do with LLMs. For now, we’ll say having a visual novel mode and a textRPG mode would be fun.
- Community events where you can obtain some vanity flair 

There are more features we have planned. Consider this as a small sample of what is to come with our site. We will also support the standard quality of life practices existing in other applications as well, along with power user features seen in SillyTavern. Naming a few:

- Regenerating a message
- Swipes 
- Impersonate
- Author’s/Character’s Note
- Image recognition (through captioning)
- Diverse buttons and toggles to influence generations
- Sampler supports

It’ll take a while for us to catch up with common feature support but we’ll do it. A combination of features from AIDungeon, Character.AI, SillyTavern and Miku.gg is what we are aiming for. Our stance for the website is going for an uncensored approach but not aligned to adult content. What do we mean by this?

## Uncensored vs Adult Content and What to Support

Making smutty generations is easy. Making models uncensored is fairly easy nowadays too. There is an overlap assumption that uncensored must always equal lewd generations. We don’t think that is the case. Our models are designed to emulate personalities by user defined settings. You want a tsundere anime girl with a Texas accent? A himbo guy that’s a dumb dog personality on the streets but a beast in the sheets? Sure, let’s have our models support that. Just like image generations and continual research into text prompts to that one perfect image. We would like to provide models to do this for character personalities. 

The nature of censored models, due to their heavy artificial bland bias, is not suited for these robust personalities. If the character is an adult, and they have a promiscuous trait? Then a model should support that. Adult content generations for the sake of pornographic messages have no research potential. It gets samey. If we want to proceed as a company and last for a long time then our focus should be on making good roleplay models of all varieties, it just has the side effect of supporting adult content. Emulating the diverse spectrum of human personalities is not easy but we believe it is a worthwhile avenue to keep exploring for years to come in all aspects of accented dialogue, memory, emotive behavior and other elements that encapsulates a personality. The difficulty of doing this is why we are sparse with releasing models. It’s not easy. Here is an example of our HuggingFace repository and the experiments we do constantly. 

![](https://files.catbox.moe/meowh1.PNG)

## What's the Point of Making Personality Models?
There are a lot of arguments currently regarding the use cases of AI and how it may cause industry disruptions (image generators and the current artist world is a big example). We personally believe there is a use case for making personality models by applying it to games. A NPC with the ability to generate personality-tuned dialogue provides a more immersive experience compared to predefined scripts. You may be asking if script writers for games will be replaced but not quite. 

World building, making original characters, establishing the details, figuring out the relationships can only be done with human creativity. A custom model that will run NPC dialogues will still require the baseline information that a human created. For example, a game world built on the complicated relationship structure of a nation of sentient rats and mice can only be crafted with human precision. The names, the specific lore, the unique linguistic features even. This can only be crafted and added to a model by a person. We believe there can be a collaborative relationship between script writers for games, and a person who can apply it to a model to generate immersive dialogue according to the writer’s specifications. The creative process is still important going forward.

A lot of the features we would like to do on our website can be doubled as tech demos for model integrations into existing video game genres. The smaller we can make the models while keeping the quality will make it easy to support smaller less powerful devices like mobile phones. It is an area that is largely unexplored. A lot of the “meta” for producing models is focused on beating benchmarks and being “better” than OpenAI models. It is a bandwagon we don’t want to follow. We can continue developing in this space as long as we have the money to sustain ourselves. You can support us by using our website and other endeavors we have planned according to the principles of open source. 

## Are You Really Going to Keep Open-Sourcing Stuff?
Yes. For our models? Always. For other stuff? Here is our approach to open-sourcing that going forward. If we spend $50,000 dollars developing something then we would like to recoup that investment by building a service for it. After we made back our initial development investment plus ten percent more then we will open source it. If we open-sourced everything after completion then we’ll be running at a loss quickly. **This is not sustainable.** To encourage ourselves to do our best to recoup our investment, we will have public deadlines on when we will release things publicly for open source. The three founders, Alpin, Teargosling and Tav are not doing it for the money but rather for open source advancements. We just need enough money to pay our bills and live humbly. 

## Will the Site Revenue Be Enough?
We won’t be sitting on just our chatting service and assume it will be enough for the long term. Here are some other revenue ideas we can tackle down the line:

- Package our models with supported integration into existing game engines for a flat pay
- Offer our knowledge to other research groups for consultancy pay
- Get paid by study groups to do voluntary surveys and tests involving our community (we’ll avoid this path if people dislike it)
- Develop some fun light-weight application (under $5) that are more akin to tech demos for the PC and mobile phones that will hopefully encourage other developers to explore this technology
- Explore imagegen and audiogen models and offering an alternative service to existing ones (this is a tricky area due to the current split opinions on handling the data curation, we’ll have to do it correctly)
- Receive sponsorship deals for any community events we will do 
- Explore content creation 

## Anything Else?
Please stay tuned for our closed beta announcement. I also encourage people to read our content guidelines on our website when it is finished. The link to it will be provided when it has been finalized. 


