# onlysquatch
Choosing website options for the next big thing in life coaching

![](squatch1.jpg)

Prompt used:

Create a stylish webpage for a 'Sasquatch Lifecoach' business called 'OnlySquatch'. The premise is someone dressed as sasquatch has calls with you to help work through business and life decisions. The call to action is to subscribe to coach squatch on onlyfans. Use this photo (https://github.com/johnowhitaker/onlysquatch/blob/main/squatch1.jpg) somewhere, it's a 16:9 screenshot of a zoom call with him. Make the site stylish but a little bigfoot-themed :) **Use only vanilla HTML/JS/CSS and put it all in a single .html file.**

**bold only included for the basic html version**

## Results

- [v0.dev](https://v0.dev/): [prompt](https://v0.dev/chat/onlysquatch-website-Xgd1YLDFay2?b=b_dcqeZQ06bIx&p=0) and [result](https://unvnwgcmbmi5qx55.vercel.app/). Slick-looking, fixed one small error with one click, easy to deploy, not obvious how to download or run locally but integrated into Vercel.
- [bolt.new](https://bolt.new/): [result](https://jade-wisp-0c6f50.netlify.app/). Very smooth experience, integrated editor was nice. I've heard good things.
- val.town Townie: [result](https://johnowhitaker-blithecrimsonpike.web.val.run). Quirky but got *a* result right away. It generated an image to use, which is cool I guess! Also, actually linked to OF haha. 
- o1 (via GitHub's web copilot UI): the index.html shown via [GitHub Pages here](https://johnowhitaker.github.io/onlysquatch/) - a different set of constraints, does a good job being a simple, illustrative example.
- Replit.com: Very fancy-looking result, this 'agent' is one of the better ones for sure, it benefits from all of Replit's existing pieces for deployment etc. Easy deploy process to an autoscaling thing, [result](https://sasquatch-guidance.replit.app/). Also nice to see they no longer shoehorn every app into the same stack. Compared to some others this seems more likely to handle extra steps like adding booking functionality.
- Claude Artifacts: one small glitch loading tailwind, but since it gave me a single HTML file I give it bonus points for ease of use. [result](https://johnowhitaker.github.io/onlysquatch/ca.html).
- Cerebrascoder: [result](https://cerebrascoder.com/p/137153): impressive speed, the magic trick of this one is that it's done in a second! The model (Llama 3.3 70B) isn't as powerful though, and the result looks a little clunky.
- TogetherAI's [llamacoder](https://llamacoder.together.ai/). Deepseek V3 was timing out, the default qwen coder did an OK job and was pretty fast: [result](https://llamacoder.together.ai/share/v2/FvX_4xAelqJljhV1).
- Devin: [result](https://sasquatch-life-coach-website-o1jm72vi.devinapps.com/). Took longer, proactively made some sort of update? Able to deploy when asked, which is nice. Not worth the wait IMO.


## Thoughts

These 'instant app' frameworks are fun for something simple like this! Many give you a near-instant initial version and a way to prompt changes with quick feedback. I liked bolt.new's code editor - I could paste a new image URL then hit 'save' and 'deploy' without having to prompt an AI to make the changes for me. If you never expect to edit code yourself, and want the convenience of something inside your existing assistant UI, then something like Claude Artifacts is *fine*. I notice a lot of similarity in the final results, I bet I can guess which run Sonnet 3.5 as their model :) Ones paired with existing hosting services (like replit, v0/vercel or val.town's townie) have extra tricks they can do and so might be worth it in cases where that's needed. And there's a lot to be said for having a recommended stack - ones like v0 that take an opinionated stance on what libraries to use often look impressive (with the downside of less differentiation from all other apps built like that). 

![bolt UI](https://github.com/user-attachments/assets/c0c2c224-eaf5-4a3c-b5e1-5860ac153eae)

## PS: OpenAI o1 w/ Canvas

In the lesson I wasn't sure if canvas could render HTML. It can:

![image](https://github.com/user-attachments/assets/38f28cf7-ac71-4f4b-9f73-e013dae42ead)


