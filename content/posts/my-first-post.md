+++
title = 'Where is Machine Learning Research Heading to ?'
date = 2024-01-14T07:07:07+01:00
draft = false
+++

It is completely undeniable and also completely naive to deny that LLMs and foundational models have changed the course of the Deep learning research. I think one can draw a line where you have papers before the first GPT model was out  and papers after. You will see a clear difference. 

A field that also dramatically changed because of the surge of LLMs 
is NLP. 
One can easily claim that more than a half of research in NLP is 
now about prompting LLM for a task that before required extensive 
architecture designing and large datasets. 
The rest of NLP research would largely revolve around the 
properties of LLMs or (engineering) new better and faster LLMs.

AI agents and tools disturbance that you see today is not 
the first disturbance to the ML field. 
I started learning deep learning at the 
end of 2014, it was merely an accident and curiosity that 
drove my consistent persistence in learning about neural networks. 

At that time it was not yet a sexy field 
that everyone wanted to learn maybe at least for 
Computer Science 4th year students 
that are all into web and mobile development. 
There was a large rise in the need for software engineers 
at that time and data science was not yet something. 

After a couple of years, 
Deep Learning became the defacto
standard for doing research in Computer vision, 
for example. Before it was all about the combination of filters, 
feature extraction and Support Vector Machines which 
were mostly coded in MatLab. Later on it became all about Convolution Neural Networks. 

Deep Learning has done the 
disturbance in the research and publishing in fields as Computer Vision way before LLMs had done to the whole ML field. 

However, at that time I remember that I always got this sarcastic comment “DL is just statistics in disguise”. My naive answer would be that it just works. I have never actually doubt that it works. The idea of pouring large scale and consistently curated dataset of any domain into a neural network with millions of parameters and training for hundreds of hours on GPUs seems to be an inevitable success. It is because of the Universal approximation theorem.

I never have doubts until I had to do my master thesis project which was a bit different course than the popular research or models at that time. I worked on solving combinatorial optimization problems with neural networks. 

At the end when I achieved my goal, I realized that I did two things that were really curicural to the success of the models that I have built. First is the inductive bias that I have introduced and the second is scale. The inductive bias I have introduced was a simple attention mechanism based on cosine similarity, so I would assume that in general it would work for other problems too. 

The important lesson I learned is that when you deal with a new problem, it is really important to understand the domain of the problem and don’t just throw data to a neural network. Nevertheless, scale is the key. 

It does not mean necessarily that scale is 
the only thing (as most researchers now do believe). 
The fight between algorithmic approaches advocates and scale 
advocates will remain continuous for a long time, 
same as the fight between symbolic approaches and connectionism 
approaches advocates remains today. 
The latter fight is what drove AI to its glorious place today with the revive of AI agents. 
The scale and algorithms fight will continue driving AI 
into a new era of advancements, and probably none of them will win. 
 
The history of AI have been non-linear, in sense that advancements 
happened usually in parallel. It started with symbolic reasoning and search algorithms. 
At the same time, the perceptons that learn to recognize patterns emerged. 
Later on Expert systems became widely commercialized in banks and hospitals, also at the same time the connectionist approaches rose again.

At every point of time, it was hard to predict what could be the next big thing and is the next flop.
As an example, for the authors of the "Attention all you need" paper, 
it was the frustration with the recurrent based NLP models (they were slow and unscalable to large scale data)
that drove them to replace them with feed-forward models that see everything with attention, an idea that was fundamentally different from mainstream adaption of "recurrent models for everything".
In the beginning, the transformers were also widely received as just better "engineering" 
for solving NLP tasks. No one could simply anticipate that transformers would be as popular as it today. 

Scientists don't usually think this way (inventing things that has mainstream adaptation), rather they tend to ask questions and answer them.
If you would like to start a research career in AI today, which topic do you put your bet on ?
It was always two things: Better and Novel. Better can be better LLMs, better Reinforcement learning for instruction fine-tuning, faster LLMs and so on. 
The second aspect is novelty, and it is extremely hard to predict what is the next big thing or at least what is worth your time and effort to investigate in.
Take a look back at the example of the "Attention all you need paper". 

We can try to bet on many topics. Instead, we can think about the fundamental defects in the current state of the art.
Simply questioning why things work the way they work would lead to new discoveries.
We can also try to combine ideas into one and build a new thing. 
I here would use a different concept to anticipate the future of AI research. 
Let's think about 