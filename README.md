Hi, I’m Kevin Wessa, founder of [Brewww Studio](https://brewww.studio), a nimble product studio. I'm a product engineer with a knack for putting pixels in the right places, and I handle the whole process, from discovery to delivery.

Email me at [kevin@brewww.studio](mailto:kevin@brewww.studio), or find me on [LinkedIn](https://www.linkedin.com/in/kjwessa/).

## Question Everything (aka, the approach)

Discovery isn't optional for me, and I don't skim past it. Building is the fun part, and it's tempting to jump straight in, but when I do, I always hit the point where I'm asking "wait, why am I doing this again?" So I start by finding out what's actually needed, even when a request looks like something I've built before.

That's why most of my work happens before and after the code. I ask "why?" one more time than people expect, ship the smallest thing that answers the real need, then check the data to see if I was right.

## The Stack I Like (aka, getting weekends back)

On the backend, Payload CMS. Been using it since their v3 beta, and it’s such a solid product and I love how I can build anything with it. The big mental unlock for me was the first plugin I built using Tanstack Forms and Usesend. Tons of screw-ups but then it just clicked. After that, I built plugins for site settings, SEO integration, redirects and some other pieces.

The longer I used Next JS on the frontend though, the more I was curious about splitting them. When I discovered Astro, that was the right fit, and it felt opt-in for everything vs. the Next JS opt-out of the “blackbox” of magic approach. Never looked back, and I’m looking forward to Tanstack support in the upcoming v4. I think I’m done with Next JS. Useful to know it, but I think Tanstack aligns more with my no “magic” approach. I want control, to see how things are working. Spend more time building, less time debugging.

Posthog for observability and product context has helped a ton. No, I don’t work for them (but I’d like to some day). Turso for the read-heavy sites, Cloudflare on everything (feel like I haven’t even scratched the surface), and Turborepo is the glue that holds it all together (but I’m exploring NX for more granular control).

## Iteration

Shipping is when I start finding out whether I was right. PostHog runs on everything I build, and what it shows me becomes the next round of discovery. If you've never heard of [PostHog](https://posthog.com), it's a seriously great product, and 97% of their users pay $0. No, I don't work for them (but would love to someday).

Any code that catches a failure and carries on has to report it first, with a fixed fingerprint, so one problem stays one issue no matter how many times I deploy.

Over the last few years, everything I build moved into one private monorepo, which is why there's little public code here. Ask and I'll give you the tour.
<br><br>
  ![kjwessa's Streak](https://streak-stats.demolab.com/?user=kjwessa&theme=react&hide_border=true)
