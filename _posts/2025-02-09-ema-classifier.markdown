---
layout: post
title:  Building an EMA classifier
date:   2025-02-09 00:06:22 -0800
categories: jekyll update
---

Game jams are the quintessential game development competition. In a game jam, developers commit to making a game based on a central theme and submit it within a set time constraint. The theme is announced at the official start time of the jam. This theme announcement serves two main purposes: to provide a starting point for participants and to help enforce the rule that games must be made from scratch. If a theme is specific enough, it excludes pre-existing projects, ensuring all submissions are original.

For the Cozy Jam, teams had 72 hours to make a game using the theme “**Chill.**” This jam was hosted on [Itch.io](https://itch.io/) as with most other UCLA ACM Studio game jams. Since this jam took place in the midst of UCLA’s midterm season, I emphasized its low-stakes nature. There were no restrictions on art style, game engine, or even the type of game—some participants made board games or even physical games. I intentionally kept the theme open-ended to encourage creativity and unique submissions. Since there was no prize, I didn’t have to worry about enforcing strict originality rules—the entire point was to be *cozy*, after all.

---
⠀

## Results of the Jam 🎉

After assembling teams, hosting a kickoff event in one of the engineering rooms at UCLA, and having a cozy time making some chill games, the results are in. It turns out my solo game **Chillmoji** won the jam!

- First place goes to **Chillmoji**
- Second place goes to **THE ROT CONSUMES**
- Tied for third place is **Slime Farm** and **Amazing Card Marathon**.

![First place]({{ "/assets/chillmoji_won.png" | relative_url }})

---
⠀

## Game Jam Ratings 💯

You might be wondering how I can host a jam and also win the competition, so let me explain. Itch.io game jams typically use a rating system where participants or judges score games based on predefined criteria such as gameplay, creativity, visuals, and theme adherence. Ratings are usually on a scale (e.g., 1-5 or 1-10), and the final ranking is determined by averaging scores across all voters.

For the Cozy Jam, games were rated in five categories: 
- **Gameplay**
- **Graphics/Art**
- **Fun**
- **Coziness**
- **Music/Sound Design**
 
We decided to let anyone browsing the games cast a rating from 1-5 in each category. This includes anyone on the internet except for the developers themselves. In a more competitive Game Jam perhaps I would have considered hiring judges instead of allowing anyone to rate. The final ranking was determined by averaging the scores from all voters.

[Check out the submissions here.](https://itch.io/jam/acm-studio-2025-cozy-jam){:target="_blank"}

---
⠀

## About Chillmoji 😎

All in all, I am satisfied with this being my first time hosting a game jam, but I am actually really happy about how my winning solo game submission turned out. It is inspired by the game **2048** with the 4x4 grid and tiles combining in powers of 2. The twist is that you control a character in this world with the goal of manually combining like-numbered tiles. The code for pushing blocks when the character moves was a particularly elegant use of recursion. This problem initially seemed daunting because it would have to handle every possible combination of merging and pushing exactly as I had envisioned it. **If you are a nerd for code, this recursive method is at the heart of Chillmoji:**

![Recursion code]({{ "/assets/recursion_code.png" | relative_url }})

 

I am so grateful I solved the problem using such an elegant function and this ended up leading to a great game. I was so amazed by the amount of time *other people* would play my game. When three other people doubled my highscore I knew I had successfully crafted an enjoyable game.

![Micheal score]({{ "/assets/micheal_score.png" | relative_url }})

Shoutout to **Micheal from the ACM Studio Discord** for being the first to beat my own high score. That is always a truly wonderful moment for a game developer—to see other people get even more invested than you.

---
⠀

## Creativity vs. Rule Enforcement 🎨🚓

When running a game jam, there’s often a tradeoff between encouraging creativity and preventing rule violations. I tend to prioritize creativity, but high-stakes jams like Ludum Dare need to ensure strict adherence to the *made-from-scratch* rule without stifling developers. One interesting way Ludum Dare manages this is by having two categories:

- **Jam (72 hours):** No team size limit, pre-made assets allowed, looser rules.

- **Compo (48 hours):** Solo-only, strict rules requiring open-sourced code, no pre-made assets, and restrictions on using pre-existing gameplay code.

This allows for open-ended themes like *“Tiny Creatures”* (Ludum Dare 56) while maintaining fairness. The strict rules make Compo submissions all the more impressive.

---
⠀

## Advice for Newcomers ♥️

Complete beginners are almost always part of the target audience for game jams because anyone with a computer can join and contribute to the game dev community. My number one tip for new developers: **fall in love with the process, not just the product.**

Don’t get fixated on making the game of your dreams—appreciate the beauty of **procedural generation, well-tuned physics, or emergent gameplay** just to name a few. These aspects of game development both make the game development process more fun and, when executed with care, make playing the game more fun. That is the ultimate goal—to enjoy the process of making a fun game. If you focus on churning out the exact video game of your dreams before you have worked with and appreciated these essential aspects of game development, you will inevitably fail to have fun, and you will get burnt out before you make a fun game. I still want you to go and make the game of your dreams, I just caution newcomers from biting off more than they can chew. Once you have some exploratory projects under your belt, perhaps you are ready to turn your dreams into reality.

If you are interested in diving deeper into game development philosophy, I highly recommend you check out [Mark from Game Maker’s Toolkit](https://www.youtube.com/channel/UCqJ-Xo29CKyLTjn6z2XwYAw){:target="_blank"}.

---
⠀

## My Journey into Game Development ⚒️

Playing games like *Chess* and *Minecraft* has always been a big part of my life, and I fell in love with game development during the COVID era (8th to 9th grade). I first discovered this rewarding hobby through the charismatic game development YouTuber [Brackeys](https://www.youtube.com/channel/UCYbK_tjZ2OrIZFBvU6CCMiA){:target="_blank"}, which got me hooked on Unity for the next four years. During that time, I made games involving *ragdoll physics, machine learning agents, virtual reality, pathfinding algorithms*, and a whole lot more. Most importantly, it introduced me to software development fundamentals like **version control and debugging**. Now I am using those fundamental skills in my work on my personal website, as head researcher for CruX UCLA, as a computer vision engineer for Bruin AI, and even in creating this blog. 😇

Recently, however, I—along with a large portion of Unity developers—have jumped on the **Godot** bandwagon. If you’re new to game development, I highly encourage you to check out [Godot](https://godotengine.org/){:target="_blank"}. It’s lightweight (only 50MB!), and I love how the built-in code editor seamlessly integrates with the game engine. The GameObject equivalent, called **Nodes**, can be dragged and dropped straight into the code editor. Plus, since Godot is open-source, it benefits from continuous community-driven improvements. *That’s the end of my Godot glazing.* 😍

![Godot vs Unity]({{ "/assets/godot_vs_unity.webp" | relative_url }})

---
⠀

## Acknowledgments & Future Jams 🤔

I couldn’t have run this game jam without the incredible support of the **ACM Studio Interns and Officers**. Huge thanks to our marketing and engagement team for creating this awesome promotional graphic:

![Gift Jam Instagram]({{ "/assets/gift-jam-instagram.png" | relative_url }})

If you want to stay updated and possibly join a future game jam, follow [ACM Studio on Instagram](https://www.instagram.com/acmstudio.ucla/){:target="_blank"}.
---
⠀

⠀

My Socials:
[Portfolio; ](https://aeriab.github.io){:target="_blank"}
[GitHub; ](https://github.com/aeriab){:target="_blank"}
[LinkedIn; ](https://www.linkedin.com/in/aeria){:target="_blank"}
[Instagram; ](https://www.instagram.com/brendan_aeria1622/){:target="_blank"}
[Twitter; ](https://x.com/BrendanAeria){:target="_blank"}
[YouTube; ](https://www.youtube.com/@brendan3511/featured){:target="_blank"}



