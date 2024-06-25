---
title: "My Freelance Website is now live!"
description: "A few months ago, I was working on learning ReactJS, but stumbled upon a framework with a lot of ReactJS-isms but built for making static websites. That Framework was AstroJS. What Astro does is it allows for static [...]"
pubDate: "Jun 25 2024"
heroImage: "/freelance-site.png"
badge: "Hello, world"
tags: ["blog"]
---

A few months ago, I was working on learning ReactJS, but stumbled upon a framework with a lot of ReactJS-isms but built for making static websites. That Framework was AstroJS. What Astro does is it allows for static site generation(SSG) but using structured files similar to modern Frameworks like React or even Kotlin. This gives you the options to make HTML components similar to ReactJS composable functions. You can also write JavaScript logic to generate repeatable code, making the HTML hyper-readable. Also Astro is fast. Like really fast.

But... as I was messing around with Astro, I became nostalgic from when I used to make small websites. I really like Astro and it got my wheels turning. I should make websites for people!

That thought turned into a thing and now, well I have a business sites I moved to prod about a week and a half ago while I was on vacation.

<a href="https://yellowcityweb.dev/" target="_blank">Welcome to Yellow City Web Design!</a>

This is my new freelance site. It is handwritten using a few things to speed up my development. But I can't lie, I also choose one framework because I just wanted to play with it more. And turns out, it's pretty badass too.

The base framework it, of course AstroJS. If you haven't checked it out, you need too. Because of the above mentions perks, it's turned working with HTML from a chore to a treat. I also wanted to go with something different for my styling. Last I was doing this, Bootstrap the the hotness, but as I was looking into what I wanted for a stack, I learned about TailwindCSS, and I'm very glad I did too.

Tailwind is regarded as a "utility-first" styling system. What it really is, basically is a hug library with predefined CSS rules that can be strung together via the

```{ .css }
class"foo bar"
```

tag. Basically as I am writing, I get to do my styling inline instead of going back to a .css file and adding a new class, adding new rules, going to my HTML file, calling the new class, and still not having my div centered. I am still learning this framework. It's not super difficult to work with though, outside of flex and grid being a bit stringent on rules.

My portfolio is using DaisyUI, which is a library that sits on-top of Tailwind. It uses shorter predefined classes similar to BootStrap, but is still Tailwind underneath. You can use the Daisy elements and then drop down to Tailwind on the fly but it can make for messy code at times.

Though I still like Daisy, I wanted something to help me along that was also closer to pure Tailwind. I found Flowbite.

Flowbite is awesome for one reason. It comes served thick and chunky. Well not really, but it's a custom library that also sits on top of Tailwind. It uses a small helper function to do some swanky animations but also comes equipped with a whole library of pre-built elements, written in a slightly flavored Flowbite variation of Tailwind, but also sites right on top. So I can go back and forth from the Flowbite stuff and the Tailwind stuff. It's so seamless that it might as well be the same thing.

Outside of that I use a small bit of vanilla JS and some TypeScript, but at the end, my business sites, as a representation of what I plan to offer, compiles right down to virtually pure, raw HTML and CSS. That is partly why AstroJS is a powerhouse. My build environment is about 300 MB, but my deployed site sits somewhere between 4 and 9 MB. It's crispy and Flowbite is chunky. And now I'm hungry.

To wrap up my post, the new sites i live. I dusted off some old tricks and learned a lot more along the way. Modern static site gen is cool. My roadmap is to finish the blog gen for the site, similar to this one, to tidy of a bit of messy code, and then I wanna also revisit WordPress, CMS, and eCommerse to see what is going on with all that in 2024, and to figure out what route I am going regarding all of that.

But my next project is going to take what I learned from my freelance site and apply it to a super lightweight template meant for running raw HTML static sits from one of the many online repos. The idea is that I will be able to take a basic template that a client likes and give it the Astro treatment. Basically fast, small, SEO-centric sites and at a fraction of the time it would normally take to get a site up and running.
