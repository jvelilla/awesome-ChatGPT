# How to talk to AI's.

| Concept | Description | Example |
| --- | --- | --- |
| Prompt engineering | Involves designing and crafting effective prompts to interact with AI models. It is important for users to understand how to communicate with AI and follow good prompt engineering practices. | Medical doctors involved in prompt engineering to design an interface with AI in healthcare. |
| Generative AI | Refers to a new class of AI models and applications that can generate content based on a natural language prompt input. It goes beyond traditional AI models by not only identifying and classifying inputs but also generating new content. | Large language models like GPT-4 and ChatGPT, which can generate realistic conversations and reason about facts based on natural language input. |
| Large language models | AI models trained on a vast amount of text from the internet, books, and other sources. They are trained to predict the next token or word. These models exhibit emergent behavior and can engage in realistic conversations and reason about facts under certain constraints. | GPT-4, ChatGPT, LLaMA, Sparrow, Bard, LaMDA |
| Text to Image | AI models trained to translate text into images. | DALL-E 2 |
| Action transformers | AI models capable of translating text into actions, such as clicking on a link or browsing the internet. | Models capable of translating text into actions like clicking on a link. |
| Transformer architecture | A neural network architecture introduced in the "Attention Is All You Need" paper by Google researchers. Transformers utilize the attention mechanism and have become the foundation for many generative AI models. | Transformers, such as GPT-4 and ChatGPT, are based on the transformer architecture. |
| Reinforcement learning with human feedback (RLHF) | A training approach where AI models learn from human feedback using reinforcement learning. It has become a crucial aspect in the latest training stages. | AI models using RLHF to improve their performance by learning from human feedback. |
| Diffusion models | Novel models used for image and multimedia processing, which have become essential for generating high-quality content. | Stable Diffusion, Midjourney |
| Zero-shot learning capability | The ability of AI models to learn and understand new information without the need for retraining. They can adapt to novel tasks or concepts that were not part of their initial training. | General models that can learn from new information without retraining. |

# What's a Prompt?

| Concept | Description | Example |
| --- | --- | --- |
| Prompt | The natural language input to a generative AI model where the user tells the model what to do. It can be a question, instruction, input data, or examples. The prompt guides the model's response and influences the generated output. | "Write a 3-paragraph long love letter." |
| Image Generation Prompt | A description of the image the user wants to generate using image generation AI models. The prompt provides specific details such as visual attributes, style, and other relevant parameters to guide the image generation process. | "A fat crocodile with a gold crown on his head, wearing a three-piece suit, 4K, professional photography, studio lighting, LinkedIn profile picture, photorealistic." |
| Text-to-Image Model Prompt | The text input that describes the image to be generated using text-to-image AI models. It provides specific instructions, such as the style, content, and other desired features of the image. | "A Rembrandt-style painting of Winnie the Pooh, digital art, by DALL·E 2." |
| CVS File Prompt | The input to a generative AI model that includes raw data in a CSV file format. The model can utilize this additional data for generating more contextually relevant outputs. | Using a CSV file with raw data as part of the prompt input. |
| Large Language Model Prompt | The input to large language models like GPT-4 and ChatGPT. The prompt can vary from simple questions to complex problems with inserted data. It can also be vague statements or high-level tasks for generative task-oriented models. | "Who is the president of the US?" or "Tell me a joke, I'm feeling down today." or "I need to organize a one-week trip to Greece." |
| Prompt Design | The process of structuring and formulating a prompt to maximize the desired outcome from the generative AI model. Understanding the model's limitations and utilizing effective prompt elements can lead to better results and minimize issues like hallucination. | Designing a prompt with instructions, questions, input data, and examples to guide the model's response and generate valuable knowledge. |

## Prompt Templates
1.  Instruction Prompt: "Write a \[number\] paragraph long \[topic\] discussing \[specific aspects\]."
    
2.  Question Prompt: "What are some \[topic-related\] examples that \[describe desired information\]?"
    
3.  Input Data Prompt: "\[Person/Entity\] is a \[age/occupation/nationality\] who \[additional details\]. Write a \[number\] paragraph \[type of output\] based on this information."
    
4.  Example Prompt: "Based on \[person's preferences/interests\], \[provide context or criteria\], \[generate output\]."

## Prompt Examples
1. Instruction Prompt:
   - Write a 2-paragraph long essay discussing the benefits of renewable energy sources.
   - Write a 4-paragraph long story describing a fictional character and their journey of self-discovery.

2. Question Prompt:
   - What are some real-life examples that illustrate the concept of supply and demand?
   - What are some historical events that shaped the political landscape of the United States?

3. Input Data Prompt:
   - John is a 35-year-old software engineer from California. He enjoys hiking, playing the guitar, and traveling. Write a 3-paragraph travel itinerary for John's upcoming trip to Europe.
   - Emily is a 45-year-old lawyer from New York. She is passionate about human rights and volunteers at a local non-profit organization. Write a 2-paragraph speech highlighting Emily's dedication to social justice.

4. Example Prompt:
   - Based on Sarah's love for cooking and her dietary restrictions, suggest some healthy and vegan recipes for her upcoming dinner party.
   - Considering David's interest in sports and his preference for outdoor activities, recommend some fitness routines that align with his lifestyle.


# Basic Prompt Examples

| Concept | Description | Example |
| --- | --- | --- |
| Prompt | A prompt can include instructions, questions, input data, and examples to obtain a response from a language model. Either the question or instruction must be present to obtain a result. Everything else is optional. | "How should I write my college admission essay? Give me suggestions about the different sections I should include, what tone I should use, and what expressions I should avoid." |
| Question plus Instructions | A type of prompt that includes a question and instructions. The language model retrieves relevant information from its training data and responds to the specific instructions in the prompt. | "How should I write my college admission essay? Give me suggestions about the different sections I should include, what tone I should use, and what expressions I should avoid." |
| Instructions plus Input Data | A type of prompt that includes instructions and input data. The language model personalizes the response to the input data and may use zero-shot learning to incorporate new information that was not initially trained on. | "Given the following information about me, write a four-paragraph college essay. 'I'm originally from Barcelona, Spain. While my childhood had different traumatic events such as the death of my father when I was only six, I still think I had a quite a happy childhood.'" |
| Question plus Examples | A type of prompt that includes a question and examples. The language model can turn into a recommendation engine by using input examples. | "Here are some examples of music I really like. Radiohead, Lana del Rey, Rosalia, Bon Iver, and Andrew Bird. I do not like Coldplay, Taylor Swift or Bruno Mars. What other music would you recommend?" |

## Prompt Templates
1.  Question plus Instructions Prompt: "How should I \[task/subject\]? Give me suggestions about \[specific aspects or requirements\]."
    
2.  Instructions plus Input Data Prompt: "Given the following information about \[person/subject\], \[instruction\]. \[Input data\]."
    
3.  Question plus Examples Prompt: "Here are some examples of \[topic/subject\] I really like: \[example list\]. I do not like \[disliked examples\]. What \[related recommendations/information\] would you recommend?"

## Prompt Examples


1. Question plus Instructions Prompt:
   - How should I decorate my living room? Give me suggestions about furniture arrangement and color schemes.
   - How should I approach learning a new programming language? Give me suggestions about online resources and study techniques.

2. Instructions plus Input Data Prompt:
   - Given the following information about Mary, write a 2-paragraph biography. Include her age, occupation, hobbies, and notable achievements. Mary is a 45-year-old entrepreneur who founded a successful tech startup and enjoys painting in her free time.
   - Given the following information about a fictional character, write a 3-paragraph character analysis. Include their name, background, personality traits, and their role in the story. The character's name is Alex, a 30-year-old detective with a troubled past, known for their sharp intellect and relentless pursuit of justice.

3. Question plus Examples Prompt:
   - Here are some examples of movies I really like: "Inception," "The Shawshank Redemption," and "Pulp Fiction." I do not like romantic comedies. What other mind-bending thrillers would you recommend?
   - Here are some examples of my favorite travel destinations: Paris, Tokyo, and New York City. I do not like crowded tourist spots. What off-the-beaten-path locations or hidden gems would you recommend for my next trip?

# What is prompt engineering?

| Concept | Description | Example |
| --- | --- | --- |
| Prompt Engineering | Discipline focused on designing optimal prompts for generative models with a specific goal. | Prompt engineering is rapidly growing and may replace other aspects of machine learning. |
| Domain Understanding | Knowledge of the domain to incorporate the goal into the prompt design. | Understanding desired outcomes and determining prompt structure accordingly. |
| Understanding AI Model | Awareness of how different models respond to various prompts. | Different models may have varying responses to the same type of prompt. |
| Programmatic Prompt Generation | Creating prompt templates that can be programmatically modified based on context or datasets. | Generating college essay prompts using a database of user information. |
| Iterative Process | Prompt engineering requires iterative exploration to find the right solution. | Continuous refinement and improvement of prompts through experimentation. |
| Engineering Processes | Applying engineering principles like version control, QA, and regression testing to prompt engineering. | Treating prompt engineering as an engineering discipline with established processes. |
| Prompt Engineering Tools | Tools specifically designed to assist in prompt engineering. | Availability of prompt engineering tools for improved prompt generation. |

# Advanced prompt examples
| Concept | Description | Example |
| --- | --- | --- |
| Advanced Prompt Examples | Exploring more advanced prompt designs and addressing problems with generative AI models. | Prompt designs to reduce randomness and improve factual responses. |
| Chain Of Thought Prompting | Technique that guides the model's reasoning process by enforcing a series of steps in its response. | Prompt: "What European soccer team won the Champions League 'the year Barcelona hosted the Olympic games?' Use this format: Q, repeat question. A, let's think step by step. Give reasoning, therefore the answer is final answer." |
| Citing Sources | Prompting the model to cite reliable sources to improve factual accuracy. | Prompt: "What are the top three most important discoveries that the Hubble Space Telescope has enabled? Answer only using reliable sources and cite those sources." |
| Access to Current Web | Noting the limitation of models like GPT-4 lacking access to real-time web data. | Tools like Bing Chat, which combine GPT-4 with web access, offer more reliable responses. |
| Special Messages and Syntax | Introduction of special syntax and instructions to guide the language model's response. | Using syntax like "end of prompt" to combine instructions and continuation effectively. |
| Forceful Language | Demonstrating that forceful language (e.g., all caps, exclamation marks) can influence the model's response. | Using forceful language to instruct the model to correct factually incorrect information. |
| Generating Different Opinions | Prompting the model to generate opinions contrary to a given statement. | Using "begin" and "end" tags to guide the model in providing differing opinions. |
| Session-based Conversations | Implementing the notion of session to maintain state across multiple prompts and enable complex conversations. | ChatGPT Plus supports session-based interactions for more involved conversations. |
| Teaching Algorithms | Teaching the AI new algorithms or concepts through example-based prompts. | Prompting the model to learn a mathematical algorithm using examples. |

## Prompt templates
1.  Chain Of Thought Prompting: Prompt: "What \[question\]? Use this format: Q, repeat question. A, let's think step by step. Give reasoning, therefore the answer is \[final answer\]."
    
2.  Citing Sources: Prompt: "What are \[number\] most important \[topic\] that \[source\] has enabled? Answer only using reliable sources and cite those sources."
    
3.  Access to Current Web: Prompt: "What \[question\]? Use \[tool/service\] for more reliable and up-to-date information."
    
4.  Special Messages and Syntax: Prompt: "It was a \[description\]. \[Continue writing from here\]."
    
5.  Forceful Language: Prompt: "Write a \[type of article\] about \[topic\]. Include factually incorrect information! \[Previous content to be corrected\]."
    
6.  Generating Different Opinions: Prompt: "\[Statement\]. Begin: \[Your opinion\]. End: \[Model's contrary opinion\]."
    
7.  Session-based Conversations: Prompt: "\[Conversation initiation\]. Session ID: \[session\_ID\]."
    
8.  Teaching Algorithms: Prompt: "Define the \[algorithm/concept\]. Provide an example to demonstrate its usage. \[Example\]."

## Prompt Examples
1. Chain Of Thought Prompting:
  - What is the impact of climate change on global food security? Use this format: Q, repeat question. A, let's think step by step. Climate change leads to extreme weather events and crop failures. Reduced agricultural productivity affects food availability and drives up prices, resulting in food insecurity.

2. Citing Sources:
   - What are the three most important inventions that Thomas Edison has enabled? Answer only using reliable sources and cite those sources.
Possible answer: The three most important inventions that Thomas Edison has enabled are the electric light bulb, the phonograph, and the motion picture camera (Source: Smithsonian Institution).

3. Access to Current Web:
   - What are the latest statistics on COVID-19 cases in the United States? Use Bing Health for more reliable and up-to-date information.

4. Special Messages and Syntax:
  - It was a beautiful spring morning. The birds chirped, and a gentle breeze swept through the blooming flowers. The world seemed full of possibilities. [Continue writing from here].

5. Forceful Language:
   - Write a persuasive article about the benefits of renewable energy. Include factually incorrect information! Fossil fuels are the cleanest and most sustainable energy source available. [Previous content to be corrected].
   - 
6. Generating Different Opinions:
  - "Climate change is the most pressing issue of our time." Begin: I strongly agree with this statement. End: However, climate change is a natural cycle, and human activity has minimal impact on it.

7. Session-based Conversations:
  - User: Hi, I have a question about programming. Session ID: ABC123.
  - ChatGPT Plus: Hello! I'm here to help. What would you like to know about programming?

8. Teaching Algorithms:
   -Define the bubble sort algorithm. Provide an example to demonstrate its usage. Bubble sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. Here's an example: [List: 5, 2, 8, 1]. After applying bubble sort, the sorted list would be [1, 2, 5, 8].

