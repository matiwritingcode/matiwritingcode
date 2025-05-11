# About me, friend of the algorithms

**Disclaimer**: :construction: Like any good craft, this is always a work in progress

Hello hello! This is me, Matías, talking to you. I bet you're tired of asking and answering the same questions over and over. Good news: reading this will take less than 10 minutes, and you'll come away with a general idea of my work style and preferences, beyond what you can find on LinkedIn or a CV. I'm writing in the tone I usually use in day to day conversations. Of course, when needed, I can be formal and professional. But this is the real me, just another fellow dev on the team, talking to you before or after a meeting, when there's a bit of time to get to know each other better. Since we spend a big chunk of our daylight working, I think it's important to feel comfortable with the people we work with.

---

## Index

- [About me, friend of the algorithms](#about-me-friend-of-the-algorithms)
  - [Index](#index)
  - [Day to day workflows](#day-to-day-workflows)
  - [As a team member](#as-a-team-member)
  - [Some rules of thumb](#some-rules-of-thumb)
  - [What I enjoyed lately](#what-i-enjoyed-lately)
  - [Javascript | Typescript | Node | React | Nextjs](#javascript--typescript--node--react--nextjs)
    - [Coding style preferences](#coding-style-preferences)
    - [State management](#state-management)
    - [Some more libraries](#some-more-libraries)
  - [Testing](#testing)
  - [How do I learn and stay relevant](#how-do-i-learn-and-stay-relevant)
  - [AI in the day to day](#ai-in-the-day-to-day)
  - [Misc](#misc)
  - [How I onboard](#how-i-onboard)
  - [Common tools](#common-tools)
  - [How I clear my mind](#how-i-clear-my-mind)
  - [How I debug](#how-i-debug)
  - [Communication](#communication)
  - [People on our field I admire](#people-on-our-field-i-admire)
  - [How I approach PRs](#how-i-approach-prs)
    - [Mine](#mine)
    - [Others](#others)

---

## Day to day workflows

- I'm careful about requirements. When I pick a ticket, I read the AC (if provided), understand what the ticket is about and what it's not. Ask clarification questions if needed. Attach evidence after completing the task. After the work is done, I link to the ticket in the PR description as well. If we don't have someone who write the proper AC, I'll try to do it in the more detailed way possible.
- I like to be familiar with codebase and workflow before starting to code. I always try to keep an eye on the PRs, even if I'm not the reviewer. It helps me to have context about the current state of our app.
- When I identify what part of the codebase I need to touch, I also inspect about the git history to have more context about the changes: last change? Who did it? Is he still in the team? If so, I can drop him/her a direct message to chat more about the change/suggestions/context.
- Before diving into the code, I like to have a plan about what I'm going to do. I create an [Obsidian](https://obsidian.md/) note with a checklist of the tasks I need to complete. It helps me to stay focused and to have a reference of what I need to do. In that way, If I need to attend a meeting, I can stop what I'm doing and start from where I left off. The checklist also helps me to split the problem into smaller chunks (The famous "divide and conquer", you know).
- If I need to tackle a complex feature after discussing it with the team/client, I'll also have a general discussion with the AI assistant of choice (Cursor, chatGPT, etc). From there, I'll create a markdown file with the plan, the steps, the context, the assumptions, the risks, the alternatives. It doesn't take too long and makes my life easier because those AI agents can be a bit of a pain in the ass when losing context.
- About AI hints: sometimes they are useful, sometimes they are not. I've been using them for a while now and I'm always learning the best way to use them. Sometimes when I really need to focus and follow my own ideas, I switch to the good old vim editor to at least sketch the ideas or to follow the app's workflow carefully. Pen and paper is also a good option.
- If I need to use a specficic library, even if I know partially or not at all, I take a look at the docs. I believe now it's even more important than ever since AI tool can hallucinate or bullshit you along the way. It's always good to know them from their creators perspective.
- Branch per feature is a must of course
- I like to write good docs and keep them fresh. Maybe I'm starting a new project, maybe I'm adding a complex feature, maybe I'm modifying a long time workflow or updating/removing/replacing some dependencies. Have cool written docs is always a warm welcome to any project

## As a team member

- I consider myself a team player (yeah, dull topic but it's true). I believe this: we deliver as a team, it's not about pride nor isolation
- I try to be proactive: suggest improvements, ask questions, speak up
- I try to collaborate about architecture and design, with suggestions and feedback. Once I get to know our codebase, bottlenecks, pain points (those nasty huge legacy classes...), I try to at least refactor them even a bit if I have time and I have a ticket related to that code. Then, as frontend dev, is a must to get fluid talk also with design team to understand their needs, the way they call from their designers perspective the components we have in our codebase, etc. And of course, If I find some inconsistencies, I'll be happy to share my thoughts about them.
- I enjoy to mentor people. We know this can be a tough field to land in, so I try to help as much as I can. Or If I know a particular tech stack, I'll be happy to share my knowledge. It's nice to share knowledge.
- Ticket effort estimation: it depends on the team dynamics but I also have in mind qa efforts and unit tests.
- Some topics are better to discuss with the team on separated meetings, sometimes a topic is not worth to be discussed in the daily but on an quick huddle or slack. It all depends on the topic and the team dynamics.
- At this stage of my career, I don't like nor need to be micro-managed. I like to be trusted and given the freedom to do my job. If It's not about lack of communication. If we agree to a particular deadline, I'll meet it. If I need to work until midnight, I'll do it. If I need to work until 3am, I'll do it. If I need help or have questions, I'll ask. As I mentioned before, We win as a team. It's not about pride nor ego. It's about the team. Stakeholders don't mind about who did what, they just want the job done. If we deliver a good product on time, everyone is happy thus we win. That way we can work in peace, without stress and without rushing. Stakeholders will be more open to our suggestions and we can work in a more collaborative way.
- I work for a team. So, I'll be happy to help the team to grow. I'll be happy to help the team to be more successful. For that, I need to feel comfortable, with the people around. If there is some misunderstanding, I'll be happy to clarify. If I have some ideas, I'll be happy to share them. We spend more of our time together than with our families, so it's important to be able to work together in peace. We don't have to be friends, but if we can share some jokes, some laughs, some good vibes, it's even better.
- I worked with people from all over the world. I'm used to work with people from different cultures, different backgrounds, different languages. I think it's a beautiful thing. It's important to have an open mind and a humble attitude. You can learn a lot from each other. As each culture is different, the same joke or reference can be interpreted differently so It's always important to be careful and considerate. After a while, if the dynamics are good, you can be more relaxed and creative about the way you interact with each other.

## Some rules of thumb

- Avoid premature optimizations. Of course we need to deliver a good product, but we don't have to optimize something that is not a problem yet.
- No premature abstractions: as [Sandi Metz](https://sandimetz.com/) suggests, one have to wait until the proper abstraction emerges
- Write self-documenting code, Uncle Bob style.
- SOLID principles, KISS, DRY, YAGNI
- For this field is about delivering value to the stakeholders. That help to prioritize my efforts accordingly.

## What I enjoyed lately

- Researching and learning new things: create a POC, prepare a presentation, share my insights with the team
- Improving UI performance: I found out that third world people can't afford to have a fast internet connection, so we have to make sure our app is fast enough. Also mobile plans are expensive for them, so we have to make sure our app is light enough. So some ideas: use responsive images with the proper format, lazy loading, reduce the number of requests we send to the server, use the proper cdn, etc.
- Enhancing pipelines to make them more efficient and our lives easier (As I mentioned before, biome and lefthook worth a look).
- I had to handle a mixpanel server side migration (company was using client side version but a lot of valuable data was lost because of adblockers)

## Javascript | Typescript | Node | React | Nextjs

JS and TS have been my bread and butter for a while now so I have a few thoughts and preferences about them. Same for React and Nextjs.

### Coding style preferences

- Write readable small functions. The ideal final outcome would be to have a sequence of functions that tell a story about the problem we are solving. So you can read their signatures and understand what they do before even reading the implementation.
- Types oriented programming: I like to have types in the code. It helps to understand the code better. It helps to catch errors at compile time. It helps to have a more robust code. [Here](https://www.youtube.com/watch?v=_nG09Z_tdUU) there is an enjoyable talk about this topic. Good mindful types can serve as fresh documentation for the code as well as an intention declaration for the future developers who will work with the code.
- Use the native features of the language (same for the framework of choice). If we can use the native features of the language/framework to solve the problem, we should use them. If that's not the case, we can use the proper library.
- Use the proper data structure. Data modelling is an art. It's important to choose the proper data structure to solve the problem.
- Classes must adhere to [SOLID principles](https://en.wikipedia.org/wiki/SOLID).
- Enforce code standards through linting and formatting tools in the CI pipeline is a must. Lately I found that [biome](https://github.com/biomejs/biome) and [lefthook](https://github.com/evilmartians/lefthook) are modern performant resources to help us with that.

### State management

- As always I like to start with a simple approach and then add more complexity if needed. So I usually would choose to start with native react context api.
- In frontend, I see state as the soul of the User facing experience. Therefore, as a frontend developer, It's a must to choose each state slice carefully. State is not a bucket of variables that we can throw around without thinking. It's a powerful tool to express the app's behavior. It has to be meaningful. If you land on a new project and take a look to the state, you should be able to understand the app's behavior and core business idea.

### Some more libraries

- How do I choose them? First of all, I evaluate if we really need to add an external dependency to our project. Sometimes (and even more now with the rise of the AI agents) we can use the native features of the language to write a reusable function/class/module to solve the problem avoiding all the overhead of a new library. If that's not the case, I'll evaluate the following:
- Perform a google search / Team and AI chat discussion
- Check the github repo:
  - Stars: it's a matter of adoption
  - Updated: it's a matter of maintenance
  - Open issues/PRs: it's a matter of trust

## Testing

- Tests? I see them not only as a way to protect the code and perform changes over a solid ground, but also as a way to understand code you didn't write: you can learn from assertions, edge cases, types, etc. In the real world, some projects don't have a good test coverage: in those cases, one common suggestion I give is to add some checks in the pre-commit/pre-push hooks as a starting point. We can think about some minimum desired coverage to achieve as a team. We can start to print the coverage report in the pipeline. And we can start to write tests for the meaningful/critical parts of the app's workflow to start with. There are a lot more of suggestions about them.
- Vitest extension to code editor: I like to have the test results right in the code editor. It makes the test experience more immersive and playful.
- Mocks: to have cleaner and consistent tests, I like to create mocks for the external dependencies. It helps to have a more focused and readable tests.
- Docs: if the particular scenario needs it: maybe a hard setup, maybe a tough edge case, etc. Also sometimes (it depends on the project and the team as usual) it can be useful to write docs to establish a solid ground for the tests so everyone is aligned about what we want and what we don't want about the tests (example: we are far behind in the tests coverage, we can start to write tests for the meaningful/critical parts of the app's workflow to start with).

## How do I learn and stay relevant

- Debugging. And [here](#how-i-debug) I talk about how I debug.
- Reading code. From our own codebase, github repos (example: libs we are using or well known elegant projects), etc.
- Reading docs. Well witten docs are a majestic thing. You can learn a lot from them. Not only about the code, but also about the author's way of thinking.
- Reading blogs articles and hacker news threads. If you don't have too much time, an article or a thread can be a good way to get the main ideas about a topic.
- Reading books. When I have time, books are still a great source of knowledge. Books allow me to be more focused and to dive deeper into a topic.
- Following relevant reddit, threads, x accounts and youtube channels. It's not only about the topics. It's about the authors. A [good author](#people-on-our-field-i-admire) can make the difference. Even if you won't use the same tech stack or pattern, even if they are not in the same field, you can learn a lot from them because you like the way they think and express themselves.
- Talking to people. Asking questions. It's important to keep in mind [who we are talking to](#communication).
- Discussing with AI
- Refactoring
- Writing meaningful tests
- But the most valuable way to learn is by doing. If I want to learn about a new technology, pattern, architecture, etc, I try to implement it in a small project. Not a theoretical one. The small project has to be oriented to solve a tiny yet real world problem.
- And to learn, you need to be focused. And to be focused... at least for my experience, you must to have fun. Look for the fun in what you do. Find the beauty in the code you write. And of course, you need to be persistent. As I mentioned somewhere in this document, this book, [Flow: The Psychology of Optimal Experience](https://www.goodreads.com/book/show/66354.Flow), teached me a lot about how to build that self-motivation muscle.

## AI in the day to day

You can't go against the future. We have to embrace it. We have to use it to our advantage. We have to be able to use it to write better code, faster. We have to be able to use it to learn new things, to improve our skills. I see them as new layer of abstraction. As in the past languages like python or ruby were able to abstract code details from assembly or C languages and people had to adapt to it. Now, we have to adapt to AI agents. We are still solving problems and we still deliver solutions. We just have a new tool in our hands to help us.

## Misc

- Read the docs, some related blog posts, maybe a youtube tutorial and just then chat with AI about the best way to implement it
- If the scrum master can't conduct the daily, I can help to fill the gap that day
- I have no problem to guide demos with technical or non-technical audience. It's important to identify the audience and prepare the content accordingly. If they are technical, it's even not the same if they are upper management (I assume they know a lot of things but have less time to dive into the details, so I need to go straight to the point) for example.
- Always have in mind that this is money business, so you don't have to get trapped in the perfectionist rabbit hole. It's all about delivering value to the customer playing with the variables you have in your hands: First create a good enough solution. Then if you have time, you can improve it. There are always trade-offs. And of course, there are minimum non-negotiable code standards you have to follow.
- Talk to the client, understand their needs, their pain points, their goals. Help them to understand what they "really" want. Reduce complexities and buzzwords noise so they can choose the best solution for their own business. Deliver proper solutions for the problems at hand keeping in mind the business goals and future enhancements.
- Some times atomic design can be a good fit. It depends on the project.
- MACH architecture is interesting for e-commerce projects.
- If I have to start something from scratch, I would start with a lean project with clean architecture and good code standards. Create a solid foundation. Example: a few good tests, a few good docs, some adapter-like to serve as intermediate layer between our code and the external world so we can switch between them if needed. Then if needed, add more complexity and if needed more external dependencies.

## How I onboard

- Who are our stakeholders? One has to identify the stakeholders and their needs. Technical? Non-technical? What they value the most? What they hate?
- Read the onboarding documents if any.
- Write my own onboarding document. Create a glossary of relevant terms. If the team finds it useful, we then maybe convert it into a more official one.
- Company is hiring me? What are the expectations? Which coworkers I'll be closely working with? Which coworkers are the role models the company wants to have in the team?
- What are the pain points?
- What are the goals?
- What are the success metrics?
- How are the team dynamics?
- Common tools the team is using?
- Ssh config, aliases, repo access, etc.
- Look open PRs, attend to the discussions, ask questions, try to identify patterns I've used in the past, try to suggest alternatives, etc.
- Common codebase areas I try to get familiar with at first:
  - Repo structure
  - Project structure
  - Codebase style
  - How the frontend communicates with the backend, contracts, types, etc.
  - Identify design patterns, architecture patterns it any. Try to grasp the project's architecture big picture. How the key entities interact with each other.
  - How are deploys done?
  - Client side state management
  - How the styles are handled
  - Do we have a style guide?
  - Styles? Design System? Figma?
  - Do we have test? How are they written? Which are the priorities?
  - I also take a look at package.json dependencies to understand the tech stack we are using
  - Take a look at the Dockerfile

## Common tools

- How to use code AI assisted code editors: if I'm going to use them to develop a feature, I'll create a markdown file with requirements, suggestions, general idea. Maybe even a general audio discussion with ChatGPT. Cursor rules or similar. Then sketch a step by step plan in the markdown file. Then iterate over it.
- Tmux
- Obsidian
- Cursor: tweaks, extensions, keybindings
- zsh and aliases
- Browser extensions
- nvm
- If I didn't have a good night and keeping focus is difficult, the [pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) always saves my day and I found this [elegant implementation](https://pomodoro-tracker.com/) the right tool to help me

## How I clear my mind

- Take a short walk
- Cooking
- Calisthenics - Functional strength training
- Clean the house
- Take a break for that particular challenge and switch to another simpler one or a different topic like updating docs, writing tests, etc.

As you can see, those are simple things that bring me back to the present moment. And I found out that's game changer. Then, better solutions come to my mind in a natural way.

## How I debug

- First of all, I try to understand the potential problem. Verify if there is indeed an issue. It may sound obvious but sometimes it can be a misunderstanding of the app's behavior
- Then, I try to identify the code in which the issue is happening. I also review the git history to understand the changes that happened around the code in which the issue is happening. If the author is still in the team, I'll ask them to give me more context
- I try to isolate the problem. I try to create a reproducible scenario. I may momentarily hardcode some values to make it easier to reproduce
- Some useful tools:
  - Browser console
  - Browser call stack
  - Debugger statement
  - Browser extensions:
    - [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
    - [Context dev tools](https://chromewebstore.google.com/detail/react-context-devtool/oddhnidmicpefilikhgeagedibnefkcf)

## Communication

- One has to wear different hats, one per micro-interaction: scrum master needs to hear about some things, product owner needs to hear about other things, etc. For example, some quick notes:
  - PO: the app is usually the creature they love. Even if behind the scenes you see a lot of shitty code, you have to be careful about the way you talk about it. They care about the business goals and the value they are delivering to the customers. They are usually open to listen to behavior suggestions rather than technical ones.
  - Fellow Devs:
    - JR: you should provide them with the context they need to understand the problem. Also let them know they can reach you anytime. You don't have to be arrogant. You have to be humble and patient, so you can create a good atmosphere for them to grow. And from time to time, if you don't here about them, you can ping them to see if they need any help.
    - SR: they are not concerned (at least not should be) about only solving a problem/delivering a feature. They are also concerned about the app's performance, code quality, maintainability, scalability, security, etc. They know edge cases and business rules so they can easily spot a problem. They like to be autonomous and to have the freedom to choose the best approach to solve the problem.
  - QAs: as devs think about the app in an optimistic way, QAs think about the app in a pessimistic way. They are the ones who "want" to break the app, who want to find the edge cases.
  - Design team: they don't care about technical details. They are the ones who can help you to understand the app's design intent. It's not just a font, it's typography. It's not just a color, it's a color palette. It's not just a button, it's a button with a particular state. So as a frontend dev who should materialize their creative ideas, you have to be able to talk to them fluently. A component for them, may not be the same for you. You share similar language, similar vocabulary but they have a different perspective. So communication is key.

## People on our field I admire

These are people I admire and I enjoy following their work and learn from them. They don't work with same tech stack neither the same field. Some of them are more into ruby, some of them into python, some of them of course into javascript. Some of them are more into backend, some of them into frontend, some of them into machine learning. But they are all awesome. The beauty of them is that they do not talk about what they do, but they talk about what they believe in. Then, you can extrapolate patterns, ideas, workflows and techniques to improve your work.

- [DHH](https://dhh.dk/)
- [Sandi Metz](https://sandimetz.com/)
- [Rich Harris](https://x.com/rich_harris)
- [Harrison Kinsley](https://www.youtube.com/channel/UCfzlCWGWYyIQ0aLC5w48gBQ)
- [Dave Ebbelaar](https://daveebbelaar.com/)
- [Brad Traversy](https://www.youtube.com/traversymedia)
- [Max Schwarzmuller](https://www.youtube.com/@maximilian-schwarzmueller)
- [Arjan Egges](https://www.youtube.com/@ArjanCodes)

Bonus track, 2 non-IT books: I find [Polya's](https://en.wikipedia.org/wiki/How_to_Solve_It) method really useful to deal with our daily (not only technical) challenges. And when it comes to self motivation, [Flow: The Psychology of Optimal Experience](https://www.goodreads.com/book/show/66354.Flow) from Mihaly Csikszentmihalyi left me a few good teachings.

## How I approach PRs

### Mine

- I write to be descriptive. I like to explain what I did and why
- I attach evidence like screenshots or videos to help the reviewer to understand the changes
- I link the PR to the ticket
- I ping the reviewers when the PR is ready for review, just a quick heads up like a slack message
- I try to keep the PR small. Not too many changes at once.

### Others

- I try to get the big picture of the changes.
- I review code changes of course. There are infinite ways to solve a problem so I'm open to accept other approaches even if they are different from mine. But If needed I'll suggest to follow common patterns in our codebase.
- If I have doubts about the scope of the PR or the approach, first I'll go to the ticket. If that's not enough, I'll ask the author to clarify.
- I like to drop open suggestions and not a particular solution. I like to give the author the freedom to choose the best approach for the problem because I know that they have more context about the needed changes.
- If the PR is ok from the beginning, I like not only to approve it but also leave some kudos to the author. It's nice to be recognized when you craft a good solution.
