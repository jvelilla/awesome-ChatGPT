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
