+++
title = 'How to work on niche problems/areas/fields in AI/ML?'
date = 2026-08-19T10:00:00+02:00
draft = false
+++

## Introduction

One would think probably that a paper on LLMs is more mainstream than a paper that applies deep learning to identify animal sounds or detect malfunction in manufacturing machines. Usually, applications of AI in any field -which does not directly deal with computer algorithms- are considered niche, in the sense that usually these types of publications don't fundamentally contribute something to AI itself and usually go to conferences or journals that are not for AI/ML.

This does not mean that these publications are of no impact. [**AlphaFold**](https://www.nature.com/articles/s41586-021-03819-2) for example was published in Nature. For an ML practitioner working in these fields, it has no impact on the ML field itself—a similar situation is a mathematician working on optimization for industry problems, and other mathematicians don't understand what he is doing as they only dealt with optimization problems with 10 decision variables!

From the early beginning of my 10 years in machine learning, I found trouble landing on a genuine problem to solve or a subfield. In early 2020 after I finished my masters I regretfully abandoned NLP and decided to move to Computer Vision. I started working on RL to optimize meta-heuristic algorithms by the end of 2020 and decided to expand the work to hyperparameter optimization and AutoML as it was booming at that time. During this time, I completely overlooked the "Transformer" architecture and LLMs, and decided to jump in domains where there are few people working on these domains, hoping for more opportunities to find PhD positions in Europe or to find better work opportunities. 
 
With the same mindset, I applied for PhD positions in applied fields and departments that are not Computer Science. I got accepted into one, however what I really regret after that time of my PhD is missing the opportunity to be in contact with people who have experience in ML.

I believe through my career and until this moment, I have worked in **niche domains**. To define what a niche domain is, I would bring a single trait for what it is exactly. A **niche domain is a domain where there is limited to no interest from your peers or from your research community as a whole**, unlike mainstream work which has higher visibility and more interest from others.

It is worth mentioning that **NLP, computer vision, robotics, speech, and recommendation systems** are also applications of AI/ML. The difference is that these fields get much more attention than domains like medicine, biology, physics or chemistry. That is because the former fields can be derived into more cool applications such as chatbots or self-driving cars. The progress in other fields like medicine is much slower and adoption of AI has to overcome a lot of barriers, so the impact could not be seen except after many years later.

I was always in a similar situation, where my work is merely an application of deep learning in a field. **The good thing about working in a niche AI domain is that you are probably one of the very few people who are experts on this matter.** The bad thing is that nobody cares, and the impact you might leave is going to be limited or will not survive the [test of time](https://vanhoucke.medium.com/on-working-on-the-wrong-problem-11c5da48ab91).

This is a future note for myself, I put some thoughts here which might be useful for anyone working in a niche domain or will work in a niche domain.

## ❌ DON'T WORK ON NICHE PROBLEMS

This first might be a surprise: but the system of publishing and peer-review doesn't reward "niche" contributions. If you optimize a model to work for low-resources languages, or be accurate for children's speech or improve accuracy and speed by x%, it might be good and beneficial but across time it will be seen as an incremental work and might be completely wiped by another general approach. This type of work is usually what a researcher does in industrial settings, which is of course beneficial for his company/organization but not rewarding for the researchers. I read stories about researchers who spend years in a company and never publish a single paper, not necessarily because their work is secretive but also because it is just "niche" for the domain they are working.

**So if you want to do fundamental work in AI, DON'T WORK ON NICHE DOMAINS.**

## ❌ DON'T IMPORT METHODS FROM OTHER DOMAINS

If you typed in Google: "Foundation model for …" you will probably find a lot of completions. It seems everybody is doing a foundation model for something which is not language or vision. There are even domain-specific foundation models. My take is that most of these models are unable to replicate the success large models have done in language (and vision) because of the lack of data for niche domains.

Before, I admired different approaches in self-supervised learning for computer vision and large scale transformers and wanted to apply it to a problem that has very little amount data and as one might expect it yields no success.

I would have taken a different approach, which I call the **"AlphaFold" approach**. Protein folding is definitely a niche domain (i.e. computers that predict protein 3D structures is not mouth opening as making a female robot that can talk publicly), because it gets little attention compared to chatbots or other conversation systems. However, the Google Deepmind team took a different approach which is to **understand the problem first and not just apply a transformer to protein structure prediction**. That made the team contributions different (e.g. Evoformer and Pairformer) which are not fundamentally different from the transformer architecture, but yet solves the problem at hand to a good extent.

The thing is that with this approach the contribution made is not transferable (i.e. you can't apply it to other problems), but **if the problem and its domain has a great impact, your approach will probably survive the test of time.** I would argue that if a new general superintelligence is in place tomorrow, it would probably come up at the end with a similar contribution, because that is a logical path a rational agent would take whether it's human or AI.

## ✅ BROADEN YOUR PERSPECTIVE

The previous point made it sound like "dig deeper into the problem and don't look elsewhere", however if the Deepmind team wouldn't broaden their perspective and start considering deep learning as an alternative approach to the existing profound systems, there would be no AlphaFold.

If you decide to import a method from a different domain which is not used in your niche domain, don't import it as it is. However there is an alternative approach to "importing":

**Step a)** Almost every problem in machine learning can be brought down to a class of similar problems (e.g. classification, regression, ranking) or to a class of learning mechanisms (e.g. supervised problem, self-supervised, RL,..). Try to identify one of those classes for your problem.

**Step b)** Since your problem is niche, and you are probably hired as a researcher to solve this problem, then there is a challenge in applying these algorithms out-of-the-box on your domain data. If you are able to identify the cause behind why out-of-the-box methods fail, then you have a research problem/question to solve!

**Step c)** The research problem you just found is probably either:
- A limitation in the current methods
- The unsuitability of the method for this problem (e.g. data and compute are not enough)
- An incorrect evaluation method (e.g. an evaluation method that discard noise in inputs)
- Fundamentally something flawed with the method (e.g. most deep neural network architecture or training recipes does not directly apply to regression, because most literature and datasets are formulated around classification problems).
Congrats! You have found a real problem in a machine learning method that needs to be solved. The caveat now is the method you are going to introduce to solve it is probably not applicable to everything, thus this can not be a "new" machine learning method.

**Step d)** Bring us back to the impact of the field the problem lies in. If your field has great impact, and you broaden your perspective, with a good understanding of your niche domain and problem (which is as simple as doing a literature review of the domain), and using the steps above you will end up with a **strong and impactful contribution that survives the test of time**.

## ⚠️ DON'T LIMIT YOURSELF

I don't have a recipe that I can introduce here, because there is actually no recipe. Every company, every domain, and every person has different circumstances and values.

**The main point is don't limit yourself.** When DeepMind and OpenAI started, I was quite astonished by how many researchers they hired who don't have a PhD in Computer Science (mostly have background in Neuroscience, Mathematics and Physics). I never thought that a person could easily switch from one field to another (I was quite young and naive at that time). Now and with the boom of LLMs and AI agents, I am still astonished by how many researchers that I used to follow in the past have switched to do work in LLMs.

Through my limited experience, I have never seen a researcher that sticks to one domain, or one problem. Most AI researchers switch between domains from vision to NLP or from speech to NLP. The advantage of AI as a field is that **it is quite difficult to mention a single research domain (or life domain) that is not affected by advancement in AI** (or computing in general). So there are plenty of things to be done.

As with the previous point, I would say the alternative method to contribute something impactful is to **step outside of the box and widen your perspective completely**. Think of crazy things that no one ever talked about through meetings. An example: my colleague was quite astonished with how the **DALL-E** system works, and how from text an image can be generated. I suggested using the idea of alignment between text and images in our domain problem, but he laughed. Yet the idea of alignment between text and images can be effective in domains with limited data or no labels, where language can act as a source of weak supervision signal. It was a completely out-of-the-box idea for our domain.

Geoffrey Hinton once said:

> "Now neural networks are everywhere and it looks like the crazy approaches is winning"

in a speech during his awarding of IEEE/RSE James Clerk Maxwell Medal on how the fathers of AI was convinced that logic is the key to intelligence and neural networks that learn is a crazy idea.

**So be crazy!**
