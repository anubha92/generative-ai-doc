# generative-ai-doc

<!-- Output copied to clipboard! -->

<h2>WHAT IS GENERATIVE AI</h2>


<h3>Importance of Generative AI \
</h3>


With photography, we no longer needed to rely on the interpretation of an artist to capture reality, and with generative AI, we no longer need artistic talent to draw or to sing.

 We can access now 



* concise information in just a manner of seconds. 
* We can also automatically generate text such as news articles or product descriptions.
* We can even design custom products like shoes or furniture. 
* We can produce music, speech, visual effects, 3D assets and sound effects using algorithms trained on already existing data. 

Core creative and more strategic activities which is the very essence of what work is really about. 

The development of generative AI has a very rich and very fascinating history marked by significant breakthroughs, even though it gained widespread attention in 2022, its evolution was built on decades of mathematical research, starting with auto encoder neural networks in 2006 and continuing on through the mass adoption of generative AI models like DALL E, ChatGPT by Open ai, Kubrick, Journey and others today. 

Not only have the providers and services expanded but the quality of what is being produced has improved drastically as well.

<h3>How generative AI is different than other types of AI</h3>


Generative AI is a type of AI that, as this name suggests, generates new content. This is in contrast to other types of AI, like discriminative AI, which focuses on classifying or identifying content that is based on preexisting data. Generative AI is often used in applications such as image generation, video synthesis, language generation, and music composition, but to really understand this new tool, we need to know first where it fits in the broader AI landscape.  

 For example, 



* **Reactive** machines are used in self-driving cars. 
* **Limited memory AI** forecasts the weather. 
* **Theory of mind powers** virtual customer assistance.
* ** Narrow AI** generates customized product suggestions for E-commerce sites.
* **Supervised** **learning** identifies objects from things like images and video. 
* **Unsupervised learning** can detect fraudulent bank transactions, and reinforcement learning can teach a machine how to play a game.

 These are only a few of the subcategories, 



* **generative AI** models fall into a lot of these categories, and honestly, it's only growing. 

These other types of AI may still generate content, but they do it as a side effect of their primary function. 

Generative AI is specifically designed to generate new content as its primary output.<span style="text-decoration:underline;"> </span>

<h3>Creating your own content</h3>


So now that we have our generative AI model and our chassis, we are ready to create our own content.



*  If we're a beginner, we can use a paid service like Midjourney or Lensa.
*  If we are more experienced, we can use a notebook and pick from available models. 
* If you download a commercial app and upload only 10 pictures of yourself, like I did, the app suggests a variety of different avatars of yourself. It's super fun.
*  If you are a more experienced generative AI user, a creative technologist, you can go to GitHub, choose your favorite generative AI model, and see if it is available in the form of a notebook. If it's not available, you can still inquire about it inside the generative AI community. They're super friendly people. 
* And if you are a programmer, you can also create your own notebook by taking the model code from GitHub. 
    * For a demonstration, we will be running a Google Colab notebook named Deforum, that is based on stable diffusion, to generate a fantasy landscape. As you can see here, the notebook runs through the code, and depending on your settings, produces a personalized outcome. Google Colab requires a subscription.
    * 

In summary:



* a model is a set of algorithms that have been trained on a specific dataset. 
* A notebook is a tool for writing and running the code. 
* A creative application is an example of how a model can be used, and the generated outcome is what the end user produces by using a generative AI service or a notebook that houses the model inside it.

<h3>Natural language models: GPT stands for generative pre-trained transformer.</h3>


Most of the hype around text-based generative AI is using a model called GPT-3. GPT stands for generative pre-trained transformer. It's a language model developed by OpenAI, a research organization focused on developing and promoting friendly AI. The idea of pre-training a language model and finding it on a task-specific data set isn't something new. This concept has been around for decades and has been used in several other models before GPT. However, GPT has become notable for:



* its large scale
* use of transformer architecture
*  its ability to generate human-like text, 

which had lent to its widespread use and popularity in the field of natural language processing. Imagine you have a writing assistant that can help you write emails, articles, even a novel. GPT-3 can take in a prompt, like a topic or a sentence and can generate text based on that prompt. It can even continue a story or a conversation you started earlier. 



 However, GPT-3 has several limitations:



* such as the lack of common sense
* Lack of creativity
* Lack of understanding the text it generates
* biased data sets 
* danger of normalization of mediocrity when we come up with creative writing.

There are three main text to image generation services:



* Midjourney
* DALL-E
* Stable Diffusion. 

 If we were to compare these three text to image tools to operating systems:



* Midjourney would be macOS because they have a closed API and a very design and art-centric approach to the image generation process
* DALL-E would be Windows but with an 
    * open API because the model 
    *  released by a corporation 
    * initially had the most superior machine-learning algorithm
    * Open AI values technical superiority over design and art sensitivities. 
* Stable Diffusion would be Linux because it is open source and is improving each day with the contribution of the generative AI community. 

<h4>Industrial applications.</h4>




* **<span style="text-decoration:underline;">Cuebric</span>**. 
    * Hollywood's first generative AI tool created by our company, Seyhan Lee, for streaming the production of film backgrounds.
    *  A normal virtual production workflow uses three dimensional world building which involves a bunch of people building 3D worlds that are custom made for that film.
    *  It's time consuming, expensive, and requires a lot of repetitive tasks.
    *  An alternative now is to augment 2D backgrounds into 2.5D by involving generative AI in the picture creation process. 
* **<span style="text-decoration:underline;">Stitch Fix</span>**
    * When they suggest garments to discover their customer's fashion style, they use real clothes along with clothes generated with DALL-E.

<h3>Another generative AI model: Generative Adversarial Networks (GANs)</h3>


 To illustrate how GANs work, let's give a game of forgery as a metaphor. 



* Imagine you have an artist called **The Generator who is trying to recreate a painting** that is so realistic that it looks like a famous painting. 
* And you have another person called **The Discriminator who's an art expert and trying to spot the difference between the real painting and the forgery**. 
* The **Generator creates a painting** and **The Discriminator evaluates it,** giving feedback to the generator on how to improve the next iteration.
*  The Generator and The Discriminator **played this game repeatedly** until The Generator creates the painting that is so realistic that The Discriminator can't tell the difference between it and the real painting. 
* In the same way, a **GAN model has a generator and a discriminator.** The two parts work together in a competition. 
* That's why it's called generative adversarial networks. In this way, they improve the generator's ability to create realistic data, and over time, the generator becomes better and better at creating realistic data. 

REAL WORLD EXAMPLES



* Audi:

    * They trained their own GANs to get inspiration for their wheel designs. 

    * This process created lots of different wheel designs that simply didn't exist before, and gave inspiration to Audi designers so they can pick and choose which designs they wanted to use in their final decisions.



*  Beko:
    * that is a European-based appliance brand
    * they use custom trained GANs in their sustainability stand film, which also happens to be the world's first brand-funded AI film created and produced by Seyhan Lee. 
    * We use GANs to generate lightning, leaves, roots, eyes, flowers, and created seamless transitions to flow between humans and nature. GANs have this beautiful transitional quality. 
* in the context of financial fraud detection:
    * GAN models can be used to generate synthetic versions of fraudulent transactions, which can then be used to train a fraud detection model. 

<h3>VAE and Anomaly Detection</h3>




* One of the main models that we use in this space is **Variational Autoencoders**, referred as VAE. 
* These models can be used for **anomaly detection by training the model on a dataset of normal data, and then using the trained model to identify instances that deviate from the normal data**. 
* This can be used to **detect anomalies** in a wide range of situations:
    * like finding fraud in financial transactions
    * spotting flaws in manufacturing
    *  finding security breaches in a network. 
    * For example, Uber has used VAE for anomaly detection in their financial transactions to detect fraud. 
    * Another example would be Google has also used VAE to detect network intrusions using anomaly detection and another one of a real world application of VAE would be anomaly detection in industrial quality control. 
    * In this scenario, a VAE can be t**rained on a dataset of images of normal products and then used to identify images of products that deviate from the normal data**. 
    * It can be used to** detect defects** in products such:
        * Scratches
        * Dents
        *  misalignments. 
* **healthcare where VAE is used to detect anomalies in medical imaging** such as CT scans and MRI.
    * Children's National Hospital in Washington, DC uses a generative AI model to analyze electronic health records. 
    * The model uses data such as vital signs, laboratory results and demographic information to predict which patients are at risk of sepsis, allowing healthcare providers to intervene early and improve patient outcomes. 
* Variational Autoencoders are a flexible, generative model that are not only able to detect anomalies but are also a part of the architecture of several other generative AI models.

<h3>FUTURE PREDICTIONS</h3>




* **gaming, film and marketing sectors** generative AI will continue to be used in computer graphics, and animation to create more realistic, and believable characters, and environments. This is going to be particularly important in 3D modeling.
*  Generative AI will be used to improve n**atural language understanding in virtual assistants and chatbots** making them more and more capable of handling complex and nuanced conversations. 
* In the **energy sector**, generative AI models will be used to optimize energy consumption and production, such as predicting demand, and managing renewable energy sources, as well as improving the efficiency of energy distribution networks. 
* **transportation secto**r, generative AI models will be used to optimize traffic flow and to predict maintenance needs for vehicles. 
* In short, generative AI will be used to automate repetitive tasks and improve efficiency in a wide variety of industries. 

certain parts of your job that are **repetitive, dirty, dull, dangerous, or difficult, the four D's, can be automated**. As a result, you will have more time focusing parts of your skills that are more **human-centric, like creativity, problem solving, empathy, and leadership**. Just like the digital revolution in the 90s gave birth to the emergence of new companies, we're now witnessing several new endeavors due to the generative AI revolution. 

Music, writing, and all forms of creative production tools will be simplified and given to your fingertips. 

Humanity will transcend **from a society of consumers to creators**. 

My advice would be to start investing in expanding your consciousness, start getting to know what makes you unique, and sharpen your interpersonal, emotional, and creative skills.

CAUTION



* The greatest bias in AI is not race, is not ethnicity, nor gender. It is human's inferiority complex.
*  **If we see machines as superior to humans, we place them on a pedestal, and if we see humans as incapable fragile beings, we again place AI on a pedestal, but this time with the power of an authority.**
*  Emphasize the crucial and essential role of human creativity and decision-making in the process. 
* popular headlines suggest that AI is designing, AI is coding, **but let's remember**, it's **humans who wrote the algorithms for AI**, and it's humans who conceptualize, curate, and oversee the algorithms to produce the desired outcomes. If we place AI and technology at the center of our workflow in storytelling, we risk dehumanizing ourselves and contributing to a future where human jobs may really be eliminated. Instead, we should focus on highlighting the central role that humans play in the creation and the use of AI. 
* sentences such as like, "AI made this art, and, "AI is advancing quickly, AI is so cool," are common in the collective, **we should strive to correct ourselves in centering our actions and self-expression around human**s. _It is humans that are making art by using generative AI-powered tools, and it is, again, humans that are working in tandem with each other to advance several different human-benefiting technologies, including generative AI._
* _ _By modeling our tools after ourselves, we are inevitably transferring our own judgments, our own insecurities, and our own limitations onto this technology. So it is essential that we work to overcome our own insecurities and approach AI as a tool that can augment and empower us, rather than compete or replace us.
*  By doing so, we can create AI systems that contribute to the elation of humanity, assist us with creative productivity, and help us achieve our greatest potential as a species.

<h2>**Generative AI: The Evolution of Thoughtful Online Search**</h2>


<h3>How a search engine works</h3>


A traditional search engine works by performing three main functions:



* Crawling
    * search engines use computer programs, called web crawlers or spiders, to discover new and updated webpages. 
    * These crawlers systematically browse the internet following links from one webpage to another. 
    * This process of crawling is continuous, and its goal is to keep the search engine's index up to date. 
* Indexing
    * Indexing takes all the content found during the crawling process, and stores, and organizes it in a massive **database called the [search index](https://www.algolia.com/blog/product/what-is-a-search-index-and-how-does-it-work/)**. 
    * This is where a search engine keeps all webpage information, and also analyzes various factors like keywords, metatags, headings, and links to understand the relevance and context of all of this data. 
* Ranking
    * Ranking is the process of providing the best, most relevant results in response to a query. 
    * enter a query, the search engine's algorithm scans the search index to find the best webpages, and then it ranks those pages on a variety of factors, **including relevance, popularity, authority, and more**. These ranked results are then presented to the user with the most relevant and authoritative results first. 

<h3>How a reasoning engine works</h3>


So a reasoning engine, it's in the title.



* it's making some rational thinking. 
* It's reasoning from the inquiry that you're giving it as compared to a search engine, which is more likely just to give you back a response to the direct information that you queried. 
* There are many different types of reasoning engines, but here I'd like to talk about generative AI models like ChatGPT and Bing Chat. 
* These systems process and understand human language. So when a user enters a query, the reasoning engine can provide a relevant and informative response using human-like speech.
*  The GPT large language model that powers these reasoning engines was 
    * **pre-trained on a massive amount of training data**. 
    * This includes text and code from the internet, from books, articles, webpages, Wikipedia, and more. 
    * During this pre-training phase:
        *  the model learns language patterns, grammar, syntax, and factual knowledge
        *  The model then uses probability to predict the next words in response to a given prompt. 
        * In the initial training phases, human supervisors oversee the process, guiding the model toward accurate responses and contributing to its knowledge development
        * During later training stages, the AI model is asked to generate multiple responses to a prompt, and then human supervisors evaluate and rank these responses from best to worst. 




<h3>Harness the power of prompt engineering</h3>


 Prompt engineering is the act of asking questions of one of these foundation models. 


 Thoughtful reasoning engine search strategies



* **specific**. The more specific the prompt, the more customized and nuanced the generated results will be.
* ** Provide context**. Reasoning engines do well when you include context within your query, which often includes providing an example of the type of answer that you're looking for. - Rather than having to infuse it with knowledge, it already knows what it knows. Instead, we need to give it examples of what right looks like and how we can answer the question that we've asked in the very specific way that we want it answered. And your ability to provide that instruction happens in the prompt as well.
* **Break things down**. If you've got a complex query, try breaking it down into smaller parts. This can make it easier to get a thorough, non-confusing answer. Use clear language. Reasoning engines are designed to synthesize human speech, so it tends to do a fine job understanding colloquial language, jargon, or slang, but if you want the best results, write your prompt as clearly as possible with proper grammar. 
* **Experiment**. Try out all sorts of ways to write your prompts. Often, slightly changing your query leads to different responses and different levels of creativity. And the neat thing is this type of experimentation isn't just making you learn, it's also making the reasoning engine learn. - It's building over time and learning from the inputs. And it's more of a sort of a dance between human and machine because it's always... You're iterating the prompt, you're trying to push it into these new directions to be able to be more creative and in alignment with what you envision. 

**<span style="text-decoration:underline;"> here's a list of some creative ideas for how you can expand your prompt engineering skills</span>**



* **Role-play scenarios**. Frame your query as a role-play scenario where the reasoning engine takes on the persona of someone relevant to your query.
    *  For example, "**Imagine you're the product manager for a brand-new smartphone company. What are 10 potential innovative features that could be added within the next five years?**" 
* **Analogies**. In your prompt, explain concepts using an analogy to better understand complex ideas. 
    * For example, "**Explain quantum mechanics using a sports analogy.**" 
* **Debate-style questions**. Ask for arguments for and against a particular topic to get a more comprehensive understanding of different perspectives.
    *  For example, **"Present arguments for and against the implementation of universal basic income."** 
* **Creative exercises**. Ask the model to brainstorm, ideate, or write fictional scenarios related to your query. 
    * For example, **I'm writing a story about traveling to a parallel universe. Help me brainstorm some unique laws of nature that this parallel universe might have. **

<h2>Streamlining Your Work with Microsoft Bing Chat</h2>


<h3>CONVERSATION STYLES</h3>




* can choose a conversation style.
* It defaults to **balanced**, which is what they call an informative and friendly chat. The responses are reasonable and fast.
* **creative chat**, which is original and imaginative. It's a little bit more playful and entertaining for you. 
* **precise responses**. These are factual, straightforward, concise. It prioritizes accuracy and terseness.

 

<h3>Turn on Button</h3>




* Turns on context answering questions, meaning you can ask a Bing Chat about questions directly related to the current website or PDF file that you're on.
* If we opne a website, Landon Hotel website. fictitious website. it already knows that I'm on a hotel website. And down here at the bottom, it's got some sample questions that I can ask. So I don't need to scroll through this website to find what I'm looking for. I can directly ask it how do I book a room or what are the amenities. 

<h3>Summarize data with chat AI</h3>


<h2>Ethics in the Age of Generative AI</h2>




* ethics are and always will be a human function
* **In the banking sector**: AI and machine learning are helping us identify people who might have opportunities to be more financially secure, to save more, to increase retirement contributions and to have better pathways to economic opportunity.
* ** In agriculture**: AI models are helping to predict large weather events so farmers and producers can understand when additional insurance is wise or help them know exactly when to plant or harvest to best maximize their economic returns. 
* **inside of organizations**: AI is transforming human resources, helping managers understand how to inspire better performance from their teams, correct potential biases or discrimination and make sure that promotions are truly merit based.

**<span style="text-decoration:underline;">idea of deep fakes</span>**, tools that might create a persona or an avatar that's: 



* pretending to be a trusted person in your organization
* delivering fraudulent information to your customer
* or even advising them to take dangerous or potentially risky courses of action. 



<h4> **<span style="text-decoration:underline;">Three part framework that can be used for evaluating and advising organizations on the creation of new ethically grounded AI tools</span>**</h4>




*  The three pillars of the framework are responsible 
    * data practices
        * 
        *  This is the starting point for all ethical AI tools.
        *  ethical as the underlying data that it's trained on.
        *  For example, if the majority of our consumers to date have been of a particular race or gender when we train the AI on that data, we'll continue to only design products and services that serve the needs of that population. 
        * you should always ask



    * well-defined boundaries on safe and appropriate use 
        * Any new tool or application of AI should begin with a focused statement of intention about the organization's goals and an identification of the population that we're trying to serve. 
        * So for example, a new generative AI tool that can 
            * write news articles. 
            * help tell the stories of a wider range of underrepresented voices. 
        * We could use it in new languages or it could perpetuate misinformation.
        * When considering ethical use, you should ask : 


        * robust transparency.


<h4>**Organizing data with ethics in mind**</h4>




* Promoting transparency
    * Should be able to explain stakeholders how their data is used, stored. Customers should always have access to their data.

<h4>**Preparing technology teams to make ethical decisions**</h4>


Techonology teams are very unique in every organization:



* **Possess specific skills and expertise** which may or may not be understood by others or their managers as well.
* **They work in extreme tight deadlines**, they do not have bandwidth to look out for ethical uses.This means they have little extra time and resources to audit or to reflect on the consequences of their decisions on users or on the wider society. 
* **Subject to specific regulatory requirement**,  GDPR and associated laws in Europe.

They should have internal ethic culture.




<h4>**Preparing C-Suite in directing responsible AI**</h4>




<h4>**Preparing the Board of Directors to manage risk and opportunity in AI**</h4>




<h4>**Consulting your customers in building AI**</h4>


Building great products means listening to our customers, and using the framework we've described here, affectionately termed** LISA**, 



* lets us listen to our customers
* involve them in decision making
* shares privacy practices
* audit and accountability.


 

These practices mean that we can build better trust with our customers and ensure that technologies meet the needs and preferences of communities, not just the ones we serve today, but the ones we aspire to serve in the future.

<h4>**Communicating effectively organizationally and globally**</h4>


acronym called **ethics** to remind myself of the specific responsibilities of each stakeholder group. 

Using this mnemonic can help ensure that you're fulfilling your responsibilities to core AI action and including stakeholders across the globe. 

<span style="text-decoration:underline;">The ethics framework outlines six key stakeholder responsibilities for responsible AI</span>. 



* **E for executives and board members**. 
    * Top management has a responsibility to establish ethical AI cultures across organizations. 
    * This includes setting ethical guidelines and standards, ensuring that ethical considerations are integrated into decision-making processes, and allocating resources for ethical AI deployment and development. 
* **The T in ethics, technologists, engineers and developers**:
    * who have a responsibility to design and develop products that are transparent, explainable, and accountable, avoiding bias in data and algorithms, ensuring that systems are secure and safe, and developing AI systems that are compatible with existing ethical frameworks.
    * 
* ** H, human rights advocates**. 
    * Human rights advocates have a responsibility to ensure that the systems that technologists build respect human rights and dignity. 
    * This includes monitoring how AI systems are being used by vulnerable groups, identifying potential human rights violations, and advocating for the ethical use of AI. 
* **I is for industry experts**.
    *  Industry experts have a responsibility to share their knowledge and expertise on the ethical implications of AI.
    *  This might include providing guidance on developing tools, identifying potential risks, and collaborating with other stakeholders to address ethical concerns
* ** C, customers and users.** 
    * Customers and users have a responsibility to provide feedback and insights. This could include communicating concerns, feedback to relevant stakeholders, participating in user-testing and feedback sessions, and staying informed about the ethical implications of AI. 
* **S for society at large**. 
    * Let's acknowledge that this is a shared journey that all stakeholders have a responsibility to consider how these tools are changing the ways that we interact as humanity. This includes identifying and mitigating potential risks, promoting and advocating for transparency and accountability, and making sure that AI is used in a way that benefits society broadly. 

Steps to ensure ETHICS framework:



<h2>Introduction to Artificial Intelligence</h2>


**Artificial Intelligence**:							

Popularly called “AI,” a computer system that shows behavior in a way that could be interpreted as human intelligence, provided the system is dealing with pattern matching 

**Artificial neural network:	**		

An artificial intelligence system that mimics the structure of the human brain 

**Machine Learning:	**					

A process in which machines start by identifying patterns, and then learn more as they work through additional data 

**Supervised Learning:		**				

A type of learning process in which a data scientist shows a system the correct answer, and then allows the system to train itself to improve on identifying patterns that lead to the correct answer 

**Symbolic systems:		**			

Matching symbols to a programmed response 

**Unsupervised Learning:		**				

A type of learning process in which a system creates its own clusters of data based on observing patterns that it sees in the data 

					

		

Matching patterns and making response is not the true sign of intelligence, like SIRI, chirness room argument, car stopping at red lght.		

<h4>**Strong vs. weak AI**</h4>


If computer system is just matching symbols, it's almost like a high-tech phrase book. The system might seem intelligent, but it's actually just like a parrot with a great memory. 

The **philosopher John Searle** said that you can think of artificial intelligence in two ways. **There's strong AI and weak AI.** 



* **<span style="text-decoration:underline;">Strong AI</span>** is when a machine displays all the behavior you'd expect from a full fledged person. This is usually what you see in science fiction. These are artificial beings that have **emotions, a sense of humor, and even have a sense of purpose**. That's why C-3PO is scared when they land on Tatooine. It's also why Commander Data shows real creativity when battling the Romulus. 
* On the flip side, there's **<span style="text-decoration:underline;">weak AI</span>**. 
    * A personal assistant like Apple Siri is a good example of weak AI. 
    * This is AI that's confined to a very narrow task. It's like when a system processes language into text or when it sorts all the pictures on your computer. Most AI experts believe that we're just starting down the path of weak AI. Think about Siri. You can talk to Siri and ask questions. Siri listens to your input and then converts your language into something that the computer recognizes. Then, Siri matches a response to what's in her database. Most of the energy right now in AI is around developing and expanding weak AI.

		

One of the greatest challenges with symbolic expert systems is that every possibility needs to be programmed by an expert. When there are a lot of possibilities this can lead to an “combinatorial explosion.” This is when there are so many different scenarios that the possibilities can't all be recorded by an expert.

		

<h4>**Machine learning**</h4>




* you could program a system to become intelligent through observation.
* **In 1959, a computer scientist named Arthur Samuel** created a checkers program that could learn by playing against itself. It played both sides of the board and taught itself strategy through observation. The more the machine played the more it saw patterns on how to win. Computer scientists didn't program the machine to play checkers. It learned through its own experience. Arthur Samuel's called this idea machine learning. 
* This was different from symbolic systems. No human program the moves and counter moves. Instead, the system was designed to learn and improve on its own. The system would quickly learn new checker strategies and after a short period of time it consistently beat its programmer. Machine learning was a breakthrough discovery. 

<h4>**<span style="text-decoration:underline;">Artificial neural networks</span>**</h4>


 To identify items we ask questions, Ask if it's alive, does it make noise? After each round, we would start to zoom in to identify the item.

 Then at the end, we started making guesses. Is it a horse? Is it a cat? Is it a dog? 

An artificial neural network uses a very similar approach, except instead of asking questions, the **neural network uses hundreds or even millions of numerical dials**. 

Also, the network makes much more specific guesses. It would say that there's a 64% chance that it's a cat or a 32% chance that it's a dog. 

To build the network, 

there's a row of neurons on the left called the input layer.


    Then there's a row of neurons on the right called the output layer.


     All the neurons in between are called the hidden layers. 

They're hidden because it's not the input or output. 

To start, we'd feed the input layer of the network a picture of a dog. We know it's a picture of a dog because we've labeled it but the neural network doesn't look at these labels until it makes a guess. Just like the animal, vegetable, mineral game. The network would then look at each dot in the image as it passes through the hidden layers. Then it makes a guess for the output layer. Let's say for the first guess, it says there's a 10% chance the image contains a dog. Then the network compares its guess to the label on the image. This is called training the neural network. Then the network goes backwards and adjusts the neuron dials so they can see patterns in dog photos. Then it takes another dog image and sees if it gets closer. The neural network then tunes itself by looking at hundreds of thousands of pictures of dogs. Then it will adjust its own dials until it consistently guesses correctly. Now, it's important to keep in mind that the neural network isn't seeing the dog the same way you do. It doesn't think about panting, barking, or fur. Instead, the system only sees the dog as a recognizable pattern of dots in an image. 

<h4>**<span style="text-decoration:underline;">Searching for patterns in data</span>**</h4>


 Remember that machine learning systems feed on data to learn new things. 

The more data you feed into the network, the easier it will be for the machine to identify patterns. Think about the system that you're using right now. This is a professional social network that provides video training, users watch the training through an online video player. 

That video player collects data about how often you fast forward or how long you watch before moving on to the next lesson. Now, suppose that the player records that data for everyone who watches the videos. 

That might be hundreds of thousands of videos and millions of users. So that's a lot of data. No human could look through all that data and gain any meaning from it. But machine learning algorithms look through this data and find patterns. You can see which content users find more interesting. This is exactly the type of data that many businesses have been looking for. 

<h4>**Robotics**</h4>




* Robotics is about having machines work on physical tasks. 
* This can be lifting heavy objects in manufacturing or using robots that deliver food.
* Robots can even be vehicles, like self-driving cars or subway trains. 
* Inventors have long been fascinated with finding ways to have machines behave like living objects.
*  In the past, robots were just limited to highly specialized machines. 
    * They were used as welding machines in auto manufacturing. 
    * The auto plants near my hometown employed several specialized robots. 
    * lift a car and install parts underneath, but none of them would ever be mistaken as intelligent. 

As impressive as they were, these robots were very limited in what they could accomplish. Unless they were programmed, they couldn't help a coworker open a car door or start painting the hood. They worked best for repetitive tasks. Robotics combined with machine learning gives us many more options. A machine can adapt to its environment and learn new tasks on the job. A basic example of this is self-driving vehicles. You couldn't program a car to react to everything it might see on the road. That's why the newest vehicles are using machine learning on an artificial neural network.

				

			

<h4>**Natural language processing**</h4>


AI programs do something called natural language processing. 

This is when you interact with the machine using your own natural language. You can talk with the machine in the same way you talk with other humans. We're all familiar with communicating with a search engine like Google. 

There's a little box and then you type in questions. You can type something like recipe for Belgian waffles. Then the search engine will match your phrase to popular results. Now with some smart devices, instead of typing, you could say this in natural language. You could use natural language like could you give me a good recipe for those big, fluffy waffles?

		

<h4>**The Internet of Things**</h4>


there are thermostats, doorbells, and televisions that connect with each other and the world. And there are smartwatches that check your location and some even upload medical data.

 This new way of connecting is commonly called the internet of things. Sometimes you'll see it as IoT for short. IoT devices are objects with sensors that communicate with the outside world. They typically upload data through the internet. 

IoT devices are a massive new source of data. They can upload their locations, so that means that if you are wearing an IoT device then these machine learning systems can see patterns in where you travel. 

They can accurately predict where you work, shop, eat, watch, and who you visit. Maybe your smartwatch will tell your thermostat when you're on the way home.

 IoT also allows these devices to communicate with each other. They could unlock your doors or have your computer turn on when you sit at your desk. In some ways, these new devices make it easier to create data than it is for humans to analyze. 

Internet of Things or IoT devices can be a wealth of new data for artificial intelligence systems. They attempt to connect the digital world to the physical world. This will allow artificial intelligence systems to make predictions about where people go or how they interact with their devices.

					

				

			

<h4>**Labeled and unlabeled data**</h4>


 The system could do something called supervised learning. 

Here, a data scientist acts like a tutor for the machine. They show the machine the correct answers and then let the system train itself to get better at the game. 

The system could also do unsupervised learning. 

Here you just have the machine make all the observations on its own. The system might not know all the different names and labels, but it'll figure out their way to learn from the data.

 As you can imagine, these two approaches have their own strengths and weaknesses. **For supervised learning the system needs to have a knowledgeable tutor.** There must be someone that knows a lot about chess that can show the system how to play the game. With **unsupervised learning, the system needs to have access to a lot of data. That's the only way to see the patterns. **

 Companies use these techniques to get valuable insights about their customer. 

With supervised learning, a company like Amazon might identify a thousand customers who spend a lot of time shopping on their website. The company can then label these customers as high spenders. Then it would have the machine learning system look through the customer to find patterns that make them high spenders. Now, for unsupervised learning a machine learning system could be given access to all of Amazon's customer data. Here, the system might find its own patterns in the data. Maybe somebody who buys chessboards are much more likely to buy an expensive kitchen appliance. Then Amazon could use that data to advertise. If you use Amazon, you may have noticed that sometimes they advertise products that seem completely unrelated to what you're looking for but it's still something you're interested in buying. Both techniques have their own strengths and yet each one can give you incredibly useful insights.

<h4>**Massive datasets**</h4>


 Your **training data** is then used to let the machine identify the spam messages. Then once the machine learning algorithm gets close to identifying the thousand spam messages, you'll try it on the** larger test data set.** 

Once you're satisfied, that will be your initial data model. **Now, this machine learning algorithm only has two options. Is that a regular message or a spam message? That's why this is called, a Binary Classification Challenge**. 

You'll only need to classify your email message into one or two groups. This is one of the most common uses for machine learning. The key thing to remember is that, machine learning algorithms use statistics to find patterns in your data. Once your machine identifies these patterns, it can then classify your data based on what it's learned.

Supervised learning relies on labeled data. In this case the two-year-old students would use the letter written on the board as labeled data. Then they would try to classify the unknown data (the blocks) by matching the label. If the student sees that they made a mistake, they adjust and take another guess.

All binary classification uses supervised machine learning. Remember that supervised learning depends on labeled data. 

			

Clusters are when the machine uses unsupervised learning to create its own groups of data.

 If you've ever bought something online, you might notice that the store will include something called frequently bought together. Maybe you're buying a computer mouse and it recommends a keyboard. This is a very powerful feature and it helps customers find what they need and increases sales for the company. This is an example of a system using unsupervised learning to create clusters based on what it sees in your purchasing history. The big difference between clustering and classifying is whether you're working with human-created categories or machine-created groups. In general, if you're using supervised learning, you're classifying, and if you're using unsupervised learning, then you're clustering.




<h4>**Reinforcement learning**</h4>




 But the best music libraries don't just want you to buy things together, many of them want you to discover something new. So for that, you have to use a different form of machine learning. **This from of machine learning is called Reinforcement Learning**.

 These are machine learning algorithms that use rewards as a way to give the system incentive to find new patterns. A few years ago, Google used Reinforcement Learning to teach artificial intelligence systems how to play video games. Their AI systems beat expert players at Pong, Atari, and even more modern video games. But reinforcement learning can do much more than just play video games. These systems can improve over time, by setting a series of goals and rewards.

 The data scientists **design the algorithms so that every time you click a related song, it gets a tiny digital reward**. It's almost like money for the machine learning system. It gets this reward coin when you click on the recommended song. Then the longer you listen, the more the reward increases, so it gets a reward coin for every minute that you listen to the song. These algorithms often use **something called Q-Learning**. This type of reinforcement learning helps create more sophisticated rewards. In Q-Learning, there are set environments or states, there are also possible actions that can respond to the states. In Q Learning, you want the machine to improve the quality of the outcome, which is represented by the letter Q. In this case, you'd start with a Q of zero. Then you'd have the machine learn the actions that improve its conditions.

Reinforcement learning can create strategies to better find patterns in the data. Unsupervised learning just tries to create clusters based on what it already sees in the data. So if you were developing an AI system to buy related items, an unsupervised system would create a cluster of items frequently bought together by other customers. A reinforcement system might invent a strategy to encourage customers to purchase something new.

		

<h4>**Machine Learning Algorithms	**	</h4>


	

			

<h4>**K-nearest neighbor**</h4>



 The closer the match, the more likely it was to be classified. Another way to look at it is we were trying to minimize the distance between the unknown dog and the known breeds. If the features were closely matched, then there was a short distance between the unknown dog and its nearest neighbor.

 A very common supervised machine learning algorithm for **multi-class classification is called K nearest neighbor.** The algorithm plots new data and compares it to the data that you already have. **Multi-class classification is different from binary classification, because there are more than two dog breeds**. Minimizing the distance is a key part of K nearest neighbor. The closer you are to your nearest neighbors, the more likely you are to be accurate. The most common way to do that is through something called Euclidean distance. This is a mathematical formula that can help see the distance between data points. 

<h4>**K-means clustering**</h4>


<h4>**Regression**</h4>




* ** Regression analysis is a supervised machine learning algorithm**. 
* It looks at the relationship between predictors and the outcome. 
* Sometimes you'll hear predictors called input variables, independent variables, or even regressors. 
* Regression analysis is a supervised machine learning algorithm. You're taking the training data and labeling the correct output. 
* Then you're using the labeled data with the test data. The best way to think about regression is to imagine trends. 
* As the weather gets warmer people are more likely to buy convertibles. As the weather gets cooler people are more likely to buy trucks and SUVs. Regression analysis doesn't tell you why people do these things. This is for data scientists and business analysts to figure out. It just tells you that these things are happening. Machine learning regression algorithms work in a similar way. Once you have your training data, you make a prediction then see how close you are to the outcome. Then you repeat over and over again until the system makes the most accurate prediction. In this case, the data science team thought that the change of seasons would be a great predictor for the sale of some vehicles. So they put the months as a predictor. Then they mapped that against the sales of certain vehicles. With this training data, they created a simple X and Y axis diagram. Remember that this is the simple chart that you learned from geometry. Along the Y or bottom axis they listed the names of the month, and along the X or top axis, they put the sales by vehicle type. Then they looked at the trend line. Convertibles and sports car sales would go up in May, June, and July. Then those sales would go down in September, October and November. For trucks and SUVs, it was the opposite. 



<h4>**Naive Bayes**</h4>


 Naive Bayes is one of the most popular machine learning algorithms. It's naive because it assumes all the predictors are independent from one another. 

Naive Bayes will do something called class predictor probability.

 This is when it looks at each one of the predictors and creates a probability that the dog belongs in this class. So let's see what happens when we try to identify an unknown dog. The first predictor we look at is hair length. The machine learning algorithm checks the probability of a dog with this hair length belonging in the three breeds. It finds that a dog with this hair length has a 40% chance of being a terrier, a 10% chance of being a hound, and a 50% chance that it's a sport dog. The next thing you check is the unknown dog's height. It looks at this predictor independently and tries to calculate the class predictor probability. So it looks at the training data and finds that there's a 20% chance that it's a terrier, a 10% chance it's a hound, and a 70% chance that it's a sport dog. The final thing you want to check is the unknown dog's weight. This might seem like a strange predictor because it's closely related to height. But remember that Naive Bayes is evaluating the probability of each predictor independently. It looks at the training data and finds that there's a 10% chance that it's a terrier, a 5% chance that it's a hound, and an 85% chance that it's a sports dog. 

<h4>**Select the best algorithm**</h4>


Ensemble modeling is when you use several machine learning algorithms to make better predictions. Two of the most popular techniques are bagging and stacking. Bagging uses the same machine learning algorithm with different data sets to improve the prediction power. Stacking can use several different machine learning algorithms “stacked” on top of each other to improve the predictions.

					

 The most popular is bagging and stacking.

 Bagging is when you use several versions of the same machine-learning algorithm. 

Stacking is when you use several different machine-learning algorithms, then you stack them on top of one another. 	

 In fact, one of the biggest challenges in machine learning is balancing the bias and the variance. 



* **Bias** is the **gap between the predicted value and the actual outcome**. Let's say that you were playing dice and predicted that you would roll five, three times, but you rolled four, three times. Then your prediction would have a high bias. You were off by one each time.
*  **Variance** is when the **predicted values are scattered all over the place**. So if you were playing dice and you predicted that you would roll five, three times, but you actually rolled two, four and six, then you'd be off by different amounts. Then your data would be too spread out.

 The machine could throw three darts, and each one of them would be consistently wrong. **They'd all land in the upper-right-hand corner just above the red bullseye. This is called having a high bias and low variance**. The darts are grouped together closely, but all of them are too far to the right. The dataset would have a high bias. That means to make a better prediction the machine would just have to pull the group of darts down and to the left. 

Now imagine a different challenge. The machine throws the darts at the dart board and they're all over the place. **That means that the data has a wide spread, so this data would have a high variance. To make a better prediction, the machine would want to tighten up the darts closest to the bullseye. Ideally, you want the predictions to have a low bias and a low variance.** That means that all the darts are in the bullseye. But in most cases, the machine is going to have to fix either a high bias or a high variance. In machine learning, this is such a common problem that it's referred to as the bias-variance trade off. Like any trade off, it means that if the system tries to balance the impact of one, it has to look at the impact on the other.

<h4>**Overfitting and underfitting**</h4>


When you create a model, you need to be careful not to underfit or overfit the data. Sometimes you can identify patterns that work with a small set of data but that doesn't fit when you start to look at larger datasets. This is called underfitting the data. Other times you can add more variables. This can create a lot of complexity and you might miss data outliers (data that is close but doesn't quite fit the model). This is called overfitting the data.

 The system can create simple rules for its training data that doesn't work well when looking at the larger test data.

 What works well at home, doesn't work well in the outside world. This challenge is called underfitting the data. 

Sometimes data scientists add more complexity, and then that complexity makes it more difficult for the system to handle. This is called overfitting the data. 



<h4>**Build a neural network**</h4>




Since the pixel data moves through the layers from left to right, <span style="text-decoration:underline;">this is called a feedforward neural network. </span>

<h4>**Weighing the connections**</h4>




<h4>**The activation bias**</h4>


 Remember earlier that the system is trying to throw darts in a tight cluster near the bullseye. The network will throw a dart and then measure how close it is to making the right prediction. Then it will adjust the weights and throw another dart to see if it's closer. Remember that when you're making a prediction, you need to balance the bias and variance in the data. This is called the bias variance trade off. So adjusting the variance will have an impact on the bias. In an artificial neural network, the bias is the number that the system assigns to each neuron. This bias number will shift the data in a different direction to make it more accurate. The network must tune itself to find a sweet spot between the data bias and the data variance. The main dial that it has to tune itself is adding weights to the connections and adding a bias to the neuron. 



				

<h4>**Learning from mistakes**</h4>


		 The challenge is how the system figures out how wrong that is. In a sense, the neural network needs a measure of wrongness. In neural networks this is measured as a cost function. The cost function is just a number that the system uses to measure its answer against the correct answer. If it's really close, then that number will be small. But if it's really far off, then that number will be larger. Say your neural network is trying to determine if an image contains a dog. The network says there's a 97% chance that it's a dog photo, but it turns out that it's a cat photo. That wrongness will have a slight cost. Now, let's say that the network says that there's a 99% chance that it's a dog photo, but this time it's a photo of a snow-covered mountain. This wrongness will have a much higher cost. That's because here the network was very, very wrong, so it needs to make more aggressive adjustments <span style="text-decoration:underline;">to its weights and biases.</span>	

		

Gradient means steepness, and descent means going down. So imagine that your artificial neural network is playing darts again. It's making predictions and seeing how close it gets to the bullseye. Some of the predictions are way off, but other predictions are close. When it throws a dart, there's a distance between it and the dartboard. When it's in the air, the dart travels at an upward angle and then a downward angle. Then it hits the board. If it misses the board entirely, it'll want to make a bigger change to the angle. If it's very close to the target, then it'll want to make the tiniest change to the angle. That way it can hit the bullseye. Well, the neural network does pretty much the same thing. It uses calculations of gradient descent to adjust the weights and biases in the network. It's not using darts, but it's using a very similar calculation to measure the angle of its wrongness. In fact, this is one of the biggest innovations in artificial neural networks. It's called the backpropagation of errors in the network, or backprop for short. 

Artificial neural networks need a measurement of “wrongness.” That way it knows how much to adjust its weights and biases. This is typically done through a calculation of the gradient descent which will increase or decrease the cost function. If it's very wrong, it will make big changes to the weights and biases. If it's slightly wrong, it will make much smaller changes

Cost function is a measure of wrongness, which in turn determines how much adjustment to weights and biases is needed.
