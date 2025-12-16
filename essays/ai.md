---
layout: essay
type: essay
title: "Tuning AI to Harmonize"
# All dates must be YYYY-MM-DD format!
date: 2025-12-15
published: true
labels:
  - Learning
  - AI
---

<div style="text-align:center">
  <h3>
    My Use of AI in ICS 314
  </h3>
</div>

<div style="text-align:center">
  <img width="800px" class="rounded" src="../img/AI-tutoring.jpeg">
</div>
<br>

To grow in this field of computer science during such a special era of technology is entrancing. Not only are the capabilities that were once remotely dreamed of now come to life, but the significant rate of its continued growth is more tangible than ever. For a lifelong learner, this also means that the methods by which we can utilize AI as a learning, studying, and personal tutor tool is prevalent in this space of students. In this ICS 314 Software Engineering class, I have found myself using ChatGPT and Co-pilot to debug code and compiling errors, map dependencies of data design choices, and understand the best practices for code and scaffolding as I continue through larger projects. 

## AI in WODs 

In the timed performance, I found the perfect harmony in planning out the structure for code myself, then using AI to debug. Since the WODs were timed, and a single error in camel case or a trailing comma can take much longer to simply find and delete than actual logic and design, I find AI to be useful in catching what the human eye takes far less efficiently to detect, and the compiling errors may not have explicitly indicated the area of problem outright. Thus my primary use for AI was finding these minute issues while my focus could be distributed elsewhere. 

Over time, having had AI detect my usual mistakes, I was able to notice a pattern about my own coding mistakes, and it later became easy second nature to quickly rewrite them myself. For example, altering my spacing and finding much more productive keyboard shortcuts in VSCode, knowing that an ESLint error will show again if not using the same format, or quickly realizing what the TS complaint that a possible null or undefined variable is sourcing from. In a way, having AI point this out to me when time is constricted, then having it explicitly write to me what my tendencies are allow me to analyze what my habits are as a programmer. 


## A Personal Tutor
When it comes to practice and understanding of particular topics, my uses varied in the particular area. For example, in the initial learning of TypeScript, having preemptive knowledge of how to write things in Java and JavaScript, much of the ease in transitioning syntax to TypeScript was seeing how they directly translate, and how TypeScript accounts for types and enhances productivity. For instance, one of my prompts regarding the distinction with TypeScript went along the lines of: “In JavaScript, I can assign an object and set up error watchers without any issues, even if the structure doesn't match what I intended. But in TypeScript, similar assignments trigger type‑casting errors at compile time. Why doesn’t JavaScript inherently catch these mismatches, while TypeScript assumes and enforces the type constraints?”

I tend to be the type of learner to ask lower level questions to fulfill some connections that I can make later on in the learning process and feel everything click into place as it progresses. Fortunately, having a personal prompter immediately draw these connections really springbroads that curve in learning something new, especially when previously learned topics are similar, yet their respective caveats and distinctions. 

When it came to a concept that regarded UI design, generally I did not find any AI helpful to generate any code, and saw that my intuition during all the practice I had done was far more productive. Generally in the WODs and personal practice for the WODs (such as my personal recreation of the CISA website, Murphy’s, Snow Island, etc.), I used AI to see why certain styles were not applying, or taking precedence, over others. As such, I could improve the way I structured styling applications and better my practices for applying global styling, utilizing classes and IDs, and partition layout components to make the code itself more harmonious and simple.


## Final Project

The times that I did use ChatGPT in more expansive cases were when React came in and the goals started to expand in our final project: TeamUHp. There were many possibilities for React’s pre-made hooks and components and better ways to approach a design implementation than I had practiced with general HTML and Bootstrap designing. Without some Stack Exchange forums to guide me in the direction of how UI is usually standardized, then asking ChatGPT the best or most common approach among all of the possible options I collected in research, I was able to make better decisions for how each of the pages can be standardized. 

One instance of this is when we had a super-outdated looking date picker that resonated with old-school html boxes, rather than a modern calendar. I knew there had to be some better option for this than was currently implemented, and in analyzing the elements on pages like ZipRecruiter, Indeed, and LinkedIn via DevTools built into my browser, I could see that there were already available react hooks to accomplish the same thing. 

## Writing & Explaining Code

Additionally, I used AI to explain code related to my teammate’s work in the Final Project development. Since many issues were being handled simultaneously and versions of the main branch constantly being updated, portions in which my code was dependent on another person’s code, or got changed once I attempted to merge the branches together can become a lot of noise. I used AI to help me sort this out, especially when making changes with conflicts to pre-existing code implemented by another team member. I wanted to preserve all work, while also taking the absolute best approach, so if a team member was unable to be reached out to, helping AI decipher this was greatly helpful and gave some sort of a fallback opinion. 

Similarly, if I found that a new feature that I wanted to implement rode on the same source that another member’s implementation essentially used, I used AI to show me how to maintain the same structure, for a very specific use case that I wanted to integrate. For example, initially, our Add Contacts functionality had existed within the Edit Profile page, but I wanted to move it somewhere that was more intuitive for the end-user. Since the contacts logic was implemented by another member, I used AI to aid in understanding where the dependencies in the database and schema were, how the relation between contacts and contactsOf were affecting my implementation's checks (a bug I later fixed), and ensuring that removing the initial implementation in the edit profile can safely be removed but use the same essential logic.

## Code Documentation

During the development of the final project, I realized that many of the efforts for this project were in hours that were not even doing actual programming. A lot it was documenting changes, bugs, and issues to be addressed moving forward. I did have one chat open that acted as a place for me to dump things I had already done in shorthand, then it returned the memory of a lengthy growing list, where I could easily revise and reference it in the formal documentation. Since changes were being made so quickly, I found this to be a rather nice way to multitask the non-coding efforts then formalizing them. 

## Where AI Was Not Used

I did not use AI for any of the essays. Ultimately, I was already starting to write when my mind could think of ideas and an overall structure for the theme of my essays, and I have already had experience in frameworking, drafting, and revising my own writing. As such, AI was not used. 

I did not use AI for asking or answering any of the in class or Discord questions, as it does not strike me immediately to use it. When we discussed among my table about bugs or errors, we usually went through figuring them out collectively, rather than an individual with an AI helper. When answering questions in the #smart-questions channel, I had already experienced the very same issue a person was addressing in their question, so I was able to effectively answer them with my own experience. 

## Impact on Learning

Overall, AI as a tool has greatly encouraged my seeking to learn, and how much more tangible it is to become more knowledgeable. It has become so easy to ask the real technical questions should I be so enticed, or even the more broad question had I been very confused. I find that AI technologies have overall enhanced my understanding of software engineering concepts, as I very much like to ask the how’s and the why’s and appreciate most especially the hands-on practice. Rather than being frustrated on why a compile error is triggering or a bug seems to persist, I can be assisted to see what patterns like this usually have the same solution to. Valuing all of these collectively, then having them work together harmoniously, I find, still maintain that ability to build intuition whilst being effective and continuously curious. 

## Practical Applications
AI in the field has absolutely been a help for this industry. In such an environment like a hackathon or convention competition, when teams are working under time constraints with unfamiliar frameworks or APIs that start to expand or go beyond their scope of knowledge or scope for the objective, AI can quickly summarize documentation, identify common configuration issues, or suggest reasonable architectural starting points.

In a setting of project development, I can imagine AI being used to help in the project management side. For example, if documentation can be automated, or an AI can learn the tendencies for members in their development process, it is beneficial to have it generate a standardized workflow so that members can follow it and work more efficiently for the goals of the project. 

## Challenges & Opportunities
I do think that AI is not helpful in the context of a ‘quick implementation’ and perhaps is not meant for it at all. When developing a larger scale project, for instance, it is better that it be used for the minute handling of issues or smaller scope ideas for a feature. But ultimately, AI may suggest solutions that are overly complex, outdated, or misaligned with the architectural patterns already in use. It is better that we, as programmers, make these decisions, which can possibly be better informed by personal research, team research, and an AI research assistant.


This can lead to the opportunity for training users on how to prompt and interpret AI. Since this tool is essentially accessible to all, I have seen the importance of knowing how to handle it, and even become a mainstream skill to list and to market for yourself as a pursuer in computer science. I think training the user on better cases in which to use AI that is enhancing rather than challenging is important to ensure that it is used efficiently, while maintaining the programmer’s own process and critical thinking. 

## Between Traditional Teaching & AI Assisted Learning

Just as my ChatGPT has been, in a way, a personal tutor, the sort of personalized and immediate response has been a great way to proliferate understanding. I find myself going deeper into a concept than I realized I had the opportunity or curiosity for. Since it is so easy I find that it is enticing. As a framework, traditional teaching methods and documentation are very important and need foundational knowledge. I think that the expansion into the more abstract topics can be enhanced by using AI. The mix of both becomes a strong combination, and as a college student, I believe this harmony does exist in going to a lecture with a professor, discussing with peers at a table, having an offline lecture via videos and screencasts, and doing hands-on work in WODs and homeworkers, all with the ability to be supplementarily assisted with AI as well. 

## Future Consideration

Moving forward, AI will likely play an even larger role in software engineering education. As tools become more specialized and context-aware, and eventually the API integrations can help use the tool in the exact setting it was designed to be in. Such as the aforementioned workflows, documentation, and project management integrations. Such inclusions can also mean that the projects students do as part of the curriculum can expand into something larger than was expected in previous times, as having this AI now assisted. 

## Entwined in Harmony

Overall, as a student in the Computer Science field who is watching technology grow in advance, and as a learner who believes all knowledge is tangible and is only growing to be more and more accessible, I see an opportunity for continued growth and enhancement of modern learning. When thoughtfully integrating AI and interpreting where it is helpful in particular, a harmony can be developed that can translate traditional learning methods into a sort of language or workflow that are more personally understandable. Throughout this course, I have gained the greatest experience to date in developing a project, creating real ideas in a real use case, and mixing theoretical learning with practical implementation. AI played a supportive role in that process by helping me navigate complexity without removing the need for independent thinking, collaboration, or problem-solving. 
