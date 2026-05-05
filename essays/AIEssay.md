---
layout: essay
type: essay
title: "From Tool to Teammate: Reflecting on AI in Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2026-04-26
published: true
labels:
  - Software Engineering
  - Nextjs
---

<img width="500px" src="../img/ex-AI.png"> <br>

## I. Introduction

Artificial Intelligence has become an increasingly common point of discussion when it comes to education, especially in software engineering. Where many individuals express concerns when it comes to topics such as cheating, inhibiting learning, and over reliance on tools outside general learning, modern view points (as well as my own personal experiences) show that AI has become an integral part of instruction; Problem-solving, debugging, and iteration are core to the learning process. In ICS 314, tools like ChatGPT and GitHub Copilot were not just available — they were integrated in a way to assist how we approached development.

Throughout this course, I used a combination of tools depending on the task. Grammarly was primarily used for essays to refine grammar and structure, while ChatGPT and Copilot were used for coding-related tasks such as debugging, generating examples, and understanding unfamiliar concepts. However, my use of AI was not constant or uniform. In many cases, I intentionally limited its use to ensure I understood the material myself.

Over time, AI shifted from being something I occasionally used when stuck to something that acted more like a supporting teammate — helping speed up certain tasks while still requiring me to understand and verify everything I used.

## II. Personal Experience with AI

### Experience WODs

For Experience WODs, I used AI sparingly. Most of my use was focused on verifying code or helping when I got stuck on something that I did not fully understand from the video lessons.

For example, I might ask:
> “Why is this function returning undefined when using map in JavaScript?”

AI was helpful in identifying mistakes or explaining concepts differently than the videos. However, I intentionally limited its use because I saw these assignments as a chance to learn independently. The benefit was clarification and debugging support, while the cost was that relying too much could reduce my own problem-solving effort. This choice was a result on initial over-reliance on the tool in another class; I was unable to identify some of the mistakes that came as a result of the logic behind the AI's answers. By learning without AI, I've learned to better prompt the tool to assist rather than be something I was reliant upon.

### In-Class Practice WODs

Since these were not timed, my AI usage was minimal. The main use was with Copilot, which would sometimes auto-generate code I was already planning to write. This was helpful as a time saver, but I avoided relying on it too much. Instead, I used it to confirm I understood requirements correctly. The benefit was efficiency, but the cost was potentially skipping over deeper thinking if overused. 

For example, during the in-class WOD for looking at trends in Atmospheric Data, Copilot was instrumental in speeding up my ability to code in an effecient manner - it started generating code I started writing almost to the near precision of what I was going to write. While this allowed me to shift focus to ensuring the instructions were met, one error in judgement of pre-reading the code it generated led to a function not working the way it was intended. This reminded me of a core concept we've all heard at one point or another - trust but verify, and I negleted to do the latter. 

### In-Class WODs

In timed WODs, I used AI more actively. Since I had already practiced similar problems, I used AI to generate smaller sections of code or assist with debugging while I focused on structuring the solution.

I remember when recreating the Maui Brewing Company website in react, one of the instructions given was essentially:
> “A Container with a unique id. It contains the elements of the top menu - Recreate it”

By prompting AI (ChatGPT in this case), I could work on the body or footer of the page while the code generated. Then, instead of having to recreate the container by hand, I could quickly scan though the code and make sure nothing "crazy" or "unintended" was included, and modify appropriately if it were. In this scenario, my practice in doing the code by hand allowed me to quickly identify these errors, but also save time in actually having to write the code by hand. 

### Essays

AI played almost no role in generating ideas for essays. Instead, I used tools like Grammarly and ChatGPT to refine grammar, improve clarity, and ensure I met formatting requirements.

As an example, I would write almost all of my essay out first before ever touching an AI tool. Following its completion, I would run the essay through Grammarly to ensure that no large grammatical errors were present, and also re-word some portions of the essay to better convey my intentions. Finally, I would run the Essay through ChatGPT along with the technical essay requirements to ensure I wasn't forgetting any portion.

The benefit was polishing the final product, while the cost was minimal since I still generated all ideas myself. It acted as the "red pen marks" a student would recieve on an essay turned in in-person to an instructor, and that feedback allowed me to elevate the product to the next level. 

### Final Project

AI was most useful during the final project. It helped with:
- Debugging issues
- Refactoring code
- Suggesting ways to modify existing functionality

For example:
> “Why is my Prisma query not returning expected results?”

More importantly, it helped guide how I thought about structuring features. However, all outputs required adaptation to fit the existing codebase. The benefit was speed and direction, while the cost was not only the time needed to verify and integrate solutions, but also to think through solutions first, prior to ever prompting the AI. The tools in this case most resembled a team-member or partner; by continuously prompting and refining ideas, AI almost acted like a conversation with a friend - someone (or something) to bounce ideas off, and help each other fix mistakes.

### Learning a Concept / Tutorial

AI was used selectively when learning concepts: For simpler topics like HTML or TypeScript basics, I avoided using AI because I knew I needed to work through them myself. Without the practice, I wouldn't even be able to comprehend a basic set of code that was generated. However, for more complex topics like functional programming, AI was extremely helpful. It allowed for another interaction point to further breakdown my understanding of a concept, as well as act as a safe space to practice typing out code to see if I was on the right path.

AI was also useful when tutorials broke due to version mismatches (such as issues connecting to Vercel, or instructions being written for an earlier version of Prisma). The tool allowed me to more expediently identify the issues as compared to reading through the documentation. It also provided on-hand support when implementing a fix that didn't quite work for a specific type of problem. 

### Answering a Question in Class or Discord

I did not rely on AI for answering questions in class or Discord. Instead, I used Discord as a discussion space where multiple perspectives could help identify issues that AI alone might not catch. One way to look at it is that I used the classroom or Discord setting as its own, separate tool - it provided a space where I could ask questions or discuss with classmates to further refine not only my understanding, but others as well. It also provided a wider range of perspectives on a given topic - an area where AI only reliance can be flawed. In most cases, AI will generate an answer, sure, but unless you personally know to prompt it, there is no second person opinion their to question the answer. 

### Asking or Answering a SMART Question

When answering or asking something in Smart Questions, one of the many topics we discussed in class was what makes up a SMART question, and what the best answers were. In this case, AI was instrumental in acting as my backup in ensuring my questions or answers were well-informed, and that I was able to accurately talk about the issue at hand.

One example of this came up during our initial try at setting up a database on Vercel. Several students expressed running into similar issues that I had previously run into, and I was confident that I could guide them the way I got to the answers myself. However, another student had posted a "SMARTer" question, which included some of the error prompts they were receiving. In this scenario I used AI to further verify what the issue pointed to before answering, and to my surprise, the fix was more in-depth than I had anticipated. While we were ultimately able to resolve the issue, AI was instrumental into quickly identifying the issue at hand and how best to address it.

In this case, AI served as a stop-gap to ensure I wasn't necessarily giving people incorrect answers, and to help ensure problem-solving was well informed.

### Coding Example

AI was used heavily for generating coding examples when learning new concepts.

An example prompt I used when going through the React experiences was:
> “Give me an example of using this component in React”

I would then try to recreate the example myself, or create another example of the coding structure to make sure I understood the topic properly. While this helped immensely when it came to identifying patterns when writing out the code, it did come at an upfront time cost as I needed to spend the extra time generating and re-prompting the AI. However, it ultimately helped to properly digest complicated topics, and helped to save time down the line by allowing me to be able to identify what was needed ahead of time.

### Explaining Code

AI was used mainly as tool for debugging rather than learning. After understanding the relative structure of a given use of code, the same pattern-identification skills gained from the coding examples were easy to disect when reading through some other code. While I did use it occasionally, the skills I gained helped to limit AI's use. However, when debugging, I can admit that I would become a little over-reliant on AI - While I knew I could identify the code at hand and attempt to debug it myself, the time-saving measures of AI appealed more than the practice in this scenario to quickly identify the issue at hand. 

This is another case where I understand the benefits it provides, but I need to better restrict myself on the reliance of the tool and take the time to read through the suggestions to better implement code in the future. 

### Writing Code

At the beginning of the course, I used AI very little for writing code because I wanted to build foundational skills. As the course progressed and I became more confident in what I wanted to build, I relied on AI more to generate code for efficiency. For example, when developing the seed.ts for our SRCH Curriculum Builder, I knew how I wanted the database to be seeded, and how to implement markdown. However, due to the sheer volume of information provided and needed in the SRCH Handbook, I relied on tools like ChatGPT to refactor the code into Markdown so that I could copy and paste, instead of editing each line by hand. 

### Documenting Code

AI use for documentation increased over time, mostly as a time-saving measure. This was less about understanding and more about improving efficiency, especially when I had already written the code but had not documented it. The benefit was speed, but the cost was reinforcing the habit of not documenting while coding - something that I've noticed has become more of a habit in recent times, and one I'm working to address myself.

### Quality Assurance

AI was used for debugging and QA tasks such as:
- Identifying errors
- Fixing ESLint issues
- Explaining why code was failing

For example:
> “Why is the User password wrong, but its correct in the database”  
> “There is an ESLINT error being caused by this input, but it works fine elsewhere. Can you identify the issue?”

The benefit was faster debugging, while the cost was needing to verify correctness.

### Other Uses

One important use of AI was resolving issues caused by mismatches between course instructions and newer versions of tools. For example, when base project files did not align with updated dependencies, AI helped identify differences and suggest fixes. Additionally, AI helped me learn how to better dissect problem statements, especially when requirements were unclear. This improved my ability to approach assignments more effectively.

## III. Impact on Learning and Understanding

AI had an overall positive impact on my learning, while making me aware of some of the negative impacts it could have if not appropriately identified and addressed. It improved my ability to debug and understand patterns more quickly, but it also required discipline to avoid over-reliance. The most valuable aspect was not getting answers, but getting explanations that helped reinforce concepts.

At the same time, I learned that relying too heavily on AI could reduce deeper understanding, especially early in the learning process. This is an easy pitfall for beginner developers, as the tools become more and more refined, and give better answers for issues over time. 

## IV. Practical Applications

Outside of ICS 314, AI is clearly applicable to real-world software development.

In my SRCH curriculum builder project, AI was used to:
- Debug issues
- Refactor code
- Suggest improvements to existing functionality

While this project was part of ICS 314, the way AI was used reflects how it is applied in industry — as a productivity tool rather than a replacement for developers. It did not generate complete systems or make decisions independently, but it significantly reduced the time required to identify problems and explore possible solutions.

Another clear application of AI was in accelerating iteration. When working on features such as mapping SRCH content to course objectives or handling authentication issues, AI allowed me to quickly test different approaches without having to start from scratch each time. For example, instead of manually researching multiple documentation sources, I could ask targeted questions and receive immediate direction, which I could then adapt to my codebase.

Beyond individual productivity, AI has implications for collaboration. Even though I was working independently at times, AI functioned almost like a secondary reviewer — helping check assumptions, explain errors, and suggest improvements. In a real-world setting, this mirrors how developers use AI alongside team discussions, code reviews, and documentation.

Overall, these experiences show that AI is not just useful in controlled assignments, but is directly transferable to real-world development. Its effectiveness comes from how it is used: not as a source of final answers, but as a tool to support the understanding and problem-solving skills used by individuals in the industry today.

## V. Challenges and Opportunities

The biggest challenge with AI was ensuring accuracy; Not all responses were correct, and some required significant modification. This compounds with the other challenge it presents, which was avoiding over-reliance, especially when learning new concepts. Throughout this essay, I've provided numerous examples where, if I hadn't taken the time I needed to develop that initial udnerstanding of a topic, I would have no idea what AI would generate, and if it was even an appropriate solution to the issue at hand. 

However, the opportunity is clear: AI can significantly improve productivity when used correctly, especially for debugging and repetitive tasks. There were many cases where, sure, I could code and develop an application by hand myself. At this point in my software development career (a student), this would have come at not only a considerable cost in terms of time, but also in terms of product effeciency and polish - I can admit that some of the work I've done would not have come out either on time or looked as well as it did without the assistance of AI.

These results show that as AI continues its development, its implementation in learning and the work place will be a vital efficiency tool, while always requiring checks in place to ensure that its use its properly implemented. 

## VI. Comparative Analysis

Compared to traditional methods, AI-enhanced learning is faster, interactive, and responsive to immediate needs. Instead of spending long periods of time searching documentation or rewatching lectures, AI allows for quick clarification and iteration. For example, when debugging an issue in my SRCH project or during WODs, I could ask a targeted question and get a response almost instantly. This made the development process feel more fluid, especially when working under time constraints.

However, traditional learning methods still play an important part in building a strong foundation. By working trough code manually — whether through lecture material, assignments, or trial-and-error — forces a developer to actually learn the concepts and topics at hand. Early in the course, I intentionally limited my use of AI for this reason; Learning core ideas like JavaScript fundamentals, React structure, or TypeScript typing required direct interaction and practice. 

One key difference between the two approaches is how they handle mistakes. Traditional methods often require more time to identify and correct errors, but that process reinforces learning. AI, on the other hand, can quickly point out what is wrong or suggest a fix, which improves efficiency but can sometimes bypass the deeper understanding that comes from struggling through a problem. Another important distinction is engagement. Traditional learning encourages persistence and problem-solving through effort, while AI can reduce friction by providing immediate assistance. While this can be beneficial, it also introduces the risk of becoming dependent on AI for answers rather than developing independent reasoning skills.

Ultimately, the most effective approach is not choosing one over the other, but using both. Traditional methods build the underlying knowledge and problem-solving ability, while AI enhances productivity and provides support when needed. In my experience, the strongest learning came from first attempting to solve a problem on my own, then using AI to verify, refine, or debug my solution. This balance allowed me to maintain understanding while still benefiting from the efficiency AI provides.

## VII. Future Considerations

AI will likely become even more integrated into software engineering education. Future improvements could include better guidance on how to use AI effectively without reducing learning. Teaching students how to prompt AI while verifying AI outputs will be just as important as teaching coding itself.

## VIII. Conclusion

At the beginning of the course, AI felt like an optional tool — something useful when stuck, but not essential. By the end, it became clear that AI is not just a tool, but a workflow enhancer. It did not replace learning. Instead, it changed how I approached learning. It made debugging faster, explanations clearer, prompts more accurate, and development more efficient. This of course came at the cost of ensuring I took the time to think through what I needed help from AI with in the first place. However, proper use of any tool can always lead to the age-old saying of "Work smarter, not harder."

The biggest takeaway though, is that AI works best not as a shortcut, but as a support system. Like any tool, its value depends on how it is used. When combined with a strong understanding of the fundamentals, it becomes a powerful asset rather than a crutch.
