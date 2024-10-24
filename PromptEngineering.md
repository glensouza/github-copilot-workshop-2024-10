# Prompt Engineering

## Introduction to Prompt Engineering

When it comes to working with GitHub Copilot and other prompt‑based generative AI tools, your results are heavily dependent on how you format and structure your prompts.

I've been using GitHub Copilot and other prompt‑based generative AI tools like Midjourney and ChatGPT, and sometimes I still get a little frustrated because my prompts don't deliver the results I want or expect. And it doesn't help to read articles or see examples of other creators and developers getting impressive results with their prompts and it leaves me wondering what am I doing wrong and how are other people getting much better results with these tools than I am?

After a lot of trial and error, I was able to get my prompts to provide better results. The issue wasn't so much what I was trying to achieve with GitHub Copilot or these other AI tools, but how I was crafting my prompts. How I provide information to GitHub Copilot by providing context, clear instructions, and examples in the form of comments and code, I later learned that this process of crafting, refining, and improving your prompts is actually called **prompt engineering**.

With the rise of these generative AI tools, developing the skills to craft well‑constructed prompts or mastering the practice of prompt engineering will become a valuable skill.

Let's take a minute and talk through this concept of prompt engineering. To define it, prompt engineering is *the practice of giving an AI model specific instructions to produce the results you want*. A prompt is a string of text or a code snippet designed to trigger a response from an AI model. These prompts serve as a bridge between human intent and machine understanding, influencing the quality and precision of responses generated by large language models like the ones powering GitHub Copilot.

The importance of prompt engineering lies in its capacity to refine and guide the model's behavior. Crafting well‑structured prompts involves a nuanced understanding of the model's capabilities and limitations, allowing you as the user to extract the desired information or achieve specific tasks efficiently.

A large reason why GitHub Copilot is amazing is because it is trained on billions of lines of code. So it does predict quite accurately what you may want to do, especially when you need to use boilerplate code and code patterns. But GitHub Copilot still needs clear step‑by‑step instructions to help generate the code that best helps you. We saw some good examples of this when we built out our Snake game. So to do something similar, let's go through a hands‑on exercise to better understand the impact of using prompt engineering to get better results.

## Best Practices For Prompt Crafting with GitHub Copilot

While GitHub Copilot can be a powerful tool for generating code suggestions, it's important to remember that *it's not a replacement for your own programming skills and expertise*. AI models are only as good as the data they have been trained on. So it's important to use these tools as aids and not rely on them entirely. It's highly recommended that every user of GitHub Copilot thoroughly reviews the code that is being recommended or provided to you. Also make sure to execute unit tests and other forms of code testing, manually testing your code to verify that it's working as expected and just follow good coding practices.

GitHub Copilot will follow your coding style and patterns as it provides suggestions to you. So, with this in mind, let's look at some helpful tips for getting better results with your prompts.

* **Iterate on and recraft your prompts**. If your initial prompt doesn't give you what you want, delete the generated code suggestion, edit your comment or prompt with more details, or, by saying it another way, with more details and examples, and then try again. Just like a two way conversation with someone new, this is a learning process for you and for GitHub Copilot. As you spend more time using GitHub Copilot, the better you'll get at communicating with it and better understanding how to recraft and iterate on your prompts to get better results.
* **Keep the prompt simple and specific to the point** with the right amount of description. We're not writing a story with our prompts, but providing a series of clear steps to define what we want. Think of this as more like a recipe with a list of separate ingredients or steps that we're sending to GitHub Copilot instead of a long paragraph that includes everything.
* **Keep a couple of relevant tabs open in your editor**. GitHub Copilot uses a technique called neighboring tabs that allows the AI pair programmer to contextualize your code by processing all of the files open in your IDE instead of just the single file that you're working on. By opening all files relevant to your project, GitHub Copilot will automatically comb through all of the data and find matching pieces of code between your open files and the code around your cursor and then add those matches to the prompt response if it's relevant. This allows you to GitHub more complete response that provides code suggestions and explanations of code that not only are applied to one file but multiple files within the same prompt response.
* **Provide GitHub Copilot examples within your prompts**. Learning from examples is not only useful for humans, but also for generative AI tools like GitHub Copilot. So in addition to providing steps within your prompts, you can show GitHub Copilot what you want it to do with examples in your preferred coding style. While GitHub Copilot is using an AI model that is already trained on a large amount of data, providing examples to GitHub Copilot will help it understand the context and constraints of a particular code snippet. Now this concept of providing examples to AI models is actually a common practice in machine learning, and some popular approaches are called **zero‑shot learning**, **one‑shot learning**, and **few‑shot learning**:
  * With **zero‑shot learning**, imagine you have a friend who loves animals but has never seen a zebra before. If you show your friend a picture of a zebra and ask what animal is this and your friend guesses it's a zebra without any prior information. That's like zero‑shot learning. It's making a correct guess about something without any training or examples beforehand.
  * With **one‑shot learning**, let's now say your friend has seen a few pictures of zebras before but not many. If you show a new picture of a zebra and your friend can correctly say it's a zebra based on just that one additional picture, it's like one‑shot learning. It's learning from a very small amount of information.
  * With **few‑shot learning**, if your friend has seen a bunch of pictures of different animals including zebras and you show a new zebra picture, they can still recognize it even though they haven't seen many zebras before. It's learning from a small but still more than one set of examples.

The LLMs, or large language models, behind generative AI coding tools are designed to find and predict patterns from their training data, apply those patterns to existing language, and then produce code or a response that follows those patterns.

==========================================

Prompting is the way to effectively collaborate with AI, like GitHub Copilot, to get better results.

## "3S" Principle of Prompt Engineering

### Simple

Try to solve as simple as possible with your prompts.

### Specific

Be specific in your prompts. The more specific you are, the more likely you are to get the results you want. If you ask an open-ended question, you may not get the results you want.

### Short

Keep your prompts short. The shorter the prompt, the more likely you are to get the results you want.

## Provide Context

The more context you provide, the better the results you will get. If you provide context, you will get more relevant suggestions.

## Be Predictable

If you are predictable in your prompts, you will get better results. If you are all over the place, you may not get the results you want.

## Resources

[![Master the core principles of prompt engineering with GitHub Copilot](https://img.youtube.com/vi/hh1nOX14TyY/0.jpg)](https://www.youtube.com/watch?v=hh1nOX14TyY)

[![Visual Studio Prompt Engineering with GitHub Copilot](https://img.youtube.com/vi/9hZsOeIINg8/0.jpg)](https://www.youtube.com/watch?v=9hZsOeIINg8)

[![Prompting with Copilot](https://img.youtube.com/vi/ImWfIDTxn7E/0.jpg)](https://www.youtube.com/watch?v=ImWfIDTxn7E)
