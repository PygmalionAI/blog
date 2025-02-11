---
title: It Is Finally Finished
seo_title: PygmalionAI Website Launch
summary: Our official launch!
slug: website_update
author: Tav
date: 2025-02-12

project types:
    - Announcements
---

Tav here.
It has been a while.
Over a year of silence from us. Last blogpost I wrote was back in January, 2024. 
If you happened to be part of our Discord community and regularly kept up with the open beta announcements with our site, this is more of a signal that the open beta is officially over.
For those unaware, the site is complete. Everything is operational at a good level and as of this date, PygmalionAI has completed its first platform.
Our promise of building a website that started all the way back in 2023 has been completed.

The website is here - https://pygmalion.chat/

I recommend reading the rest of this blogpost before proceeding to the site.

----
## Recap Over PygmalionAI
The AI industry moves fast so let me go over what this project is. 

### Current Founders and Stakeholder
![foundersv2](https://github.com/user-attachments/assets/7af479e2-29c7-4f00-bda3-c0e805e838ec)

### Brief History
This projected started back in late 2022. It was initially formed by people who were users of Character.AI, way back when Character.AI just started as a website, and decided that there needed to be an alternative as the site was in constant decline. Anyone who has used it knows what I mean - generation degradation, unfocused site updates and most importantly the filter.

Our first approach was building a model that could replicate the same experience. After a series of iterations, we eventually trained Pygmalion-6B to great success. Anyone who has been in the local community for a few years knows this model. We made several more model drops, not to the same success as Pygmalion-6B, in 2023, but we got things out there. 

The last model batch was in September 2023. After that, nothing. Not even for the entirety of 2024. Why?

During that time, it was when more base models started being released, more resources were being invested into making models, and the overall bar for quality has been raised. PygmalionAI, after one of the model developers left in mid-2023, only had one guy to handle finetuning models. While we trained a lot (around over 200 training runs on various base models), from internal testing and closed community feedback, we felt like it was not good enough to be released. That is my explanation on the lack of models until now (this will be bought up later in the blogpost).

Let me rewind back to mid-2023, the project was actually on the verge of being hired by other companies. I was only handling Discord stuff until I caught wind of it and inserted myself into the discussion. After many back and forth, we decided that incorporating officially as a company was preferable. This meant making our own platform.

Alpindale went off and started building Aphrodite-Engine. A batched inference beast.
Tav went off and started forming a web development team. The website was called Galatea internally.
TearGosling kept tinkering away at building datasets and training to potentially release new Pygmalion models.

2024 was the year of constant dedication to building our respective projects. It is the reason why we kept things quiet so we can focus and successfully complete our own tasks. We were still active with our community, that being the Discord, who helped us a lot with testing our projects. We sincerely appreciate everyone for their help. 
## The Site and What We'll Do
With the brief history segment out of the way, lets talk about the site. 

![](https://files.catbox.moe/v2fkkk.png)

I spent a lot of time doing my own due diligence on building a good website. The additional time, while unexpected, spent on developing the website has allowed me to really focus on what we should do. Everything regarding the site, the responsibilities and directions, falls upon my shoulders. It's a tough job, nevertheless, I personally find it fun. Lets go over some key points.
### No Matter What, Respect the Promise
What do I mean by this? 

Back early on, our original promise was to build a Character.AI alternative. The biggest criticism of that platform was its filter and the constant quality deterioration of the models. For us to do the same thing would be a violation of the original promise.

This promise can be interpretative however and I want to set the record straight on what exactly I am upholding here. 

I treat the "Filter" as a hard "NO", or in other words, a flat out denial on an user interaction. There are two levels to this, (a) external system independent of the model that checks whether an interaction is "appropriate", and (b) model itself does a hard refusal with the interaction. Generations like "As an AI assistant, I cannot..." is a standard example of (b). If you came from Character.AI, then you'll be very familiar with (a).

I'll go on record and say we won't be doing any of this. 

As for the quality of the models, that is tricky because everyone has their standard on what quality is. The only approach I can take with this is giving people options and communicating changes on what we do with models. 

The biggest headache I have to deal is scale. The more users we have, the more machines we have to deploy, which means we need to pay more for these machines. I am committed to allowing people to use our platform for free at some capacity, like Character.AI does, but I also don't have millions and millions of dollars to burn to meet those user demands. This leaves me with three options. Sacrifice quality for speed or reduce what the free users can do on the site. Either option is going to make people unhappy. The final third option, which is the hardest one, and cannot be done immediately, is constantly optimising models to be smaller but keeping the same quality, and increasing the speed of our inference engine. This takes a lot of development work.

If I was forced to make a decision to keep the website operating smoothly, then I would rather reduce what free users can do on the site until we can optimise things further. So, I'll abide by saying that free users will be the one hit the hardest when it comes to quality of service. It is an unfortunate reality in order to keep the site operational.
### Generic Clone Avoidance
A major stressing point was figuring out how to avoid our website feeling like it is another generic clone of already existing platforms. "Why should people pay for our platform?" was the big question. 

My conclusion was that we need to have features. And a lot of it. 

**Here is what exists on the site currently.** There are more additional features on the site but this image covers the major ones.

![](https://files.catbox.moe/pb011r.png)

**And here is what is planned for the future.**

![](https://files.catbox.moe/ymrryw.png)

You may be curious what this "Unnamed Project" is about. In short, it is an advanced customisation system related to prompting. In order for us to make cool scenarios and experiences, this needs to be built first. 

I'm going to avoid pigeon-holing ourselves into one approach. As long as there is something cool to do with text generative AI then I would like us to do it. At the end of the day, everything is just text. 

If you would to stick along for the ride and see what we cook up, you can support our endeavours by giving a subscription on our site.

## Models
Alongside our launch of the website, we're going to release the weights of two new models for the LLM community, both featured on our website: Pygmalion-3 12B, our standard roleplay model, and Eleusis-12B, an experimental model which people have enjoyed. Both models, created from the Mistral Nemo base model, are under the permissive Apache 2.0 license. Through this, we hope that our models help further enrich the open-source LLM sphere, as we always try to do.

Launching our website with new released weights does not mean our effort to make good chat models is done. Currently, we're working behind the scenes to create a wider variety of models that are suited for more specialized purposes, such as shorthand chatting or text adventure games. We're also looking into making our models even more soulful, as a proper return to the days of old. Look forward to more news about that soon!

As an aside, we'd like to note that our models from here on out will be developed with the expectation of being released on the site first and with the features of the site in mind. This, of course, doesn't mean that we're shying away from open-source - all it means is that we want to focus on models which will get ourselves off the ground first. If we have no money, we can't really keep developing models.

Right now, we're solely focused on making textgen models. We have no plans for releasing any other type of generative model; any release in that field would have to be done in collaboration with other groups and contributors.

## Transparency From Tav
It is no secret that PygmalionAI is a bootstrapped company. Meaning, anything involving money is funded by our own wallets. From paying developers, meeting bill invoices, and setting up advertising runs. 

In the start-up world, this is the most difficult approach. High risk, stressful and it requires a lot of effort from the founders. Running an AI platform is expensive and high capital sites like OpenAI and Character.AI are subsidising their costs with money raised from investors. They have the ability to do stuff for free for a lot of users.

That is not an option for us. Comparing us to them would be unfair.

I don't enjoy interacting with investors. I tried, dipped my toes into the waters, and decided it wasn't the approach. Living on borrowed cash and trying to constantly appease the investors, I feel, is the antithesis of a community first approach. It does mean however, that the community is the make it or break it for us. In other words, the longevity of PygmalionAI depends on community support.

While publicly, I'm titled as "Project Manager", my official role in the documents at PygmalionAI is the CFO, aka the money guy, and I will do my best to make sure we can last as long as possible. If I have to work full-time (alongside PygmalionAI work) to make ends meet, then so be it, and if I have to pay out of pocket to cover deficits, I will do it.  

At the same time, I'll be making sure to drop regular financial updates. My main goal is sustainability. When we earn enough money from our platform to cover the maintenance costs and paying our developer team without relying on our personal funds, that is when I say we "made it" as a company. 

The allocation of money will go as follows - Invoices/Maintenance > Developers > Founders.

I already offered to be last on the list when it comes to receiving pay from PygmalionAI. I didn't join up this project to make a quick buck and vanish. I like AI, especially text generations, and I want to us to do cool things. To those who have interacted with me before on my research focus, it has always been about text styles. While image generation and audio generation have very simplified pipelines to create styles per user customisation, in text generation, it doesn't really exist. 

I would like to change that and I believe it is very possible.

I'm very aware some people don't have the means to support us financially, be it due to the USD being too expensive, or you're simply unable for myriad of reasons. It's fine. As long as you tell us on how to improve things, give suggestions on what you'd like to see, and in general, remain passionate for text generative AI then that's all I ask. 

Before I wrap things up, I'll allow my other co-founders, and our only stakeholder currently Autometa, have a say too.

## Words from Alpin
A warm thanks to the many members of the Pygmalion community, generously supporting this effort with their kind words and patience. You're all truly wonderful. Have a good one.

## Words from TearGosling
It's hard to believe it's been more than two years since Pyg was founded. To be honest, I never imagined that a single post on a forum and the forking of two GitHub repos would lead to this, and I'm endlessly grateful to everyone that helped bring us here. We've had a long and bumpy road to the present day, with lots of delays, setbacks and learning experiences, but thanks to the hard work of many incredible people and the patience of you wonderful gaggle of enthusiasts, enjoyers and fans, I'm glad to say that we're finally up and running with many promising things in the works. Thank you, now and forever, for your help along the way.

And to a certain developer (you know who you are) who helped me from the very start to turn a dream into reality: I miss you, brother. I hope you're doing well, and I hope you're proud of us and what we've accomplished thanks to your endless assistance and insane work. I and the team can never thank you enough for everything you've done for us.

I hope you all enjoy our effort of love and care, and of course, if you don't, we're always listening. Thank you again, everybody. Keep your smile. Keep on smiling.

## Words from Autometa 
Its rare when you find yourself in the fortunate position of spending your time working on something you care about, let alone with people you care about. I'm endlessly grateful to the incredibly intelligent, consistent, and deeply talented people with whom I work with, and for those who walk along side us as we pursue a world where the ability to participate in artistic self expression comes as naturally as breathing for everyone.

Thanks guys, 
The future is going to be *very* interesting. 
Dont miss it!

## Final Remarks
This concludes the entirety of the blogpost. I consider this the turning point for PygmalionAI in many ways. There is going to be lots growing pains in 2025 and beyond. My main priority is making sure we survive each and every step of the way. I, and the rest of the team, have exciting things planned. There will be more regular communication on our plans and actions going forward. 

Once again, I, Tav, the Project Lead, thank you again for your patience and support. It means a lot to me.


