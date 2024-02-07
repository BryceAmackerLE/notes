
---
## Introducing an Optimization for Valid JSON Generation in SGLang

[https://twitter.com/lmsysorg/status/1754516251123257385](https://twitter.com/lmsysorg/status/1754516251123257385)

Controlling LLMs to always generate valid JSON is crucial for many applications. We've introduced an optimization in SGLang that achieves this goal and also:

- Makes JSON decoding 3x faster than normal decoding, utilizing a compressed finite state machine
- Supports any regular… [https://t.co/iwiOZOa1Qt[https://t.co/bCbbmryMFi](https://t.co/bCbbmryMFi)](https://t.co/iwiOZOa1Qt)

Here is another example using LLaVA! You can use this feature to extract structured information from images. [https://t.co/sjEugHKoGj](https://t.co/sjEugHKoGj)

The code was released several weeks ago and is now undergoing testing by multiple users. We welcome your feedback and any interesting use cases you'd like to share.

---
## RAG Cheatsheet v2: A Comprehensive Guide to Troubleshooting RAG Systems

[https://twitter.com/jerryjliu0/status/1753923945789903351](https://twitter.com/jerryjliu0/status/1753923945789903351)

RAG Cheatsheet v2 💫

We're excited to highlight an expanded RAG cheatsheet by @wenqi_glantz which outlines twelve pain points across the stages of data ingestion, retrieval, querying, and the solutions for each pain point.

There's too many parameters to tune in a RAG system and… [https://t.co/GoLJJATZ4A](https://t.co/GoLJJATZ4A)

![](https://pbs.twimg.com/media/GFcv2zfbUAAeweq.jpg)[https://t.co/EWkcUhC44o](https://t.co/EWkcUhC44o)

@jerryjliu0 @wenqi_glantz

---
## Excited to release Natural-SQL-7B!

[https://twitter.com/calebfahlgren/status/1754246846535340317](https://twitter.com/calebfahlgren/status/1754246846535340317)

Excited to release Natural-SQL-7B!

A new, very strong Text to SQL model that is my best fine tune yet. You can see how it does on the SQL-Eval benchmark by @defogdata

[https://t.co/m1r3gIFL1R[https://t.co/Hg3r0Tgvcl](https://t.co/Hg3r0Tgvcl)](https://t.co/m1r3gIFL1R)

![](https://pbs.twimg.com/media/GFhR-_7XgAARRig.jpg)

All the GGUFs for the people🤝
[https://t.co/9Vm1wlo4Hb](https://t.co/9Vm1wlo4Hb)

Hopefully I can get it on @ollama soon!

---
## "Introducing Rawdog: A Natural Language CLI for Python Scripts"

[https://twitter.com/granawkins/status/1753380448502440261](https://twitter.com/granawkins/status/1753380448502440261)

I built a natural language CLI.

It generates Python scripts to answer your question, then auto-executes them in the cwd. You will not believe how capable this simple pattern is. Rawdogging gpt-4 from the command line.

Rawdog.
1/ [https://t.co/0cYV2Lw8fz](https://t.co/0cYV2Lw8fz)

Conversational git, docker, matplotlib, pandas..

Summarize, scan or refactor basically any type of data

“Follow the instructions in readme to set this up..”

“Find all my venvs and plot their sizes”

“Do I have Ruby installed?”
2/

Rawdog doesn’t use RAG!

It can “select its own context” by printing things to the output and then printing ‘CONTINUE’ (from its script). The output is added to the conversation, then it rawdogs the same prompt again.
3/ 

![](https://pbs.twimg.com/media/GFVBzmAbkAAh5Bt.png)

Rawdog’s outputs are 100% interpretable, because you (and it) can see the script that generated them. If you ask, it’ll tell you exactly what it did and why.
4/ [https://t.co/NdUwx9FSWk](https://t.co/NdUwx9FSWk)

Here’s the full system prompt:

You are a command-line coding assistant called Rawdog that generates and auto-executes Python scripts.

A typical interaction goes like this:
1. The user gives you a natural language PROMPT.
2. You:
i. Determine what needs to be done
ii. Write a… [https://t.co/HYVpG9qZs2](https://t.co/HYVpG9qZs2)

Here’s the repo: [https://t.co/Y2DQjpKv6K](https://t.co/Y2DQjpKv6K)

You can install it with pip:
 > pip install rawdog-ai
start a conversation:
 > rawdog
or do single-shot:
 > rawdog your question here
review/approve each script before running with:
 > rawdog --dry-run

6/

This project came out of the Mentat hackathon last week - was a funny experiment that turned out to be super useful. Look out for integrations with the Mentat coding assistant soon 👀
[https://t.co/yutGsDpkqb](https://t.co/yutGsDpkqb)
7/7

PS if you're on hackernews: [https://t.co/YfEc6xG2YC](https://t.co/YfEc6xG2YC)

PPS - it's official: [https://t.co/AOqvsPegMi](https://t.co/AOqvsPegMi)

---
## One-Click RAG Pipeline Generator

[https://twitter.com/llama_index/status/1753478149743284395](https://twitter.com/llama_index/status/1753478149743284395)

One-Click RAG Pipeline Generator

We’re excited to feature RAGArch by @HarshadSurya1c, which provides a comprehensive @streamlit UI to pick and choose all the core components of a RAG system: LLM, embedding model, chunking, vector store.

In one click you will 1) create a fully… [https://t.co/MH6DbsAQpb[https://t.co/4omNwxq24C](https://t.co/4omNwxq24C)](https://t.co/MH6DbsAQpb)

@llama_index @HarshadSurya1c @streamlit

---
## OpenCopilot: The Ultimate Tool for Product Automation and User Assistance

[https://twitter.com/ikbenbasha/status/1752241769683829048](https://twitter.com/ikbenbasha/status/1752241769683829048)

OpenCopilot is at 4.6K GitHub stars! (bye bye BETA)⭐⭐

[https://t.co/r5w0Peszjd](https://t.co/r5w0Peszjd)

And we are live on ProductHunt!🐱

➡️ It's like Siri but for your product.

Integrate a Text/Voice AI User Assistant, and Workflow Automation into your product, all in one powerful tool.✨

We… [https://t.co/X2iTMpKv6W](https://t.co/X2iTMpKv6W)

@ikbenbasha

---
Use this to evaluate LLM SQL generation:
[https://github.com/defog-ai/sql-eval](https://github.com/defog-ai/sql-eval)

Use this to compare Vanna AI vs something like defog sql

---
[https://github.com/billmei/every-chatgpt-gui](https://github.com/billmei/every-chatgpt-gui)

---
## Introducing RAG CLI - A Command-Line Tool for Indexing and Searching Files

[https://twitter.com/llama_index/status/1750950516925079777](https://twitter.com/llama_index/status/1750950516925079777)

Introducing RAG CLI 🧑‍💻🔎 - a dead-simple command-line tool that allows you to RAG literally any file on your local machine.

Index any files including glob patterns, such as `$ llamaindex-cli rag --files "./docs/**/*.rst”`

To search simply do `$ llamaindex-cli rag --question… [https://t.co/B0VPw2swJ1[https://t.co/QYW21JTwFi](https://t.co/QYW21JTwFi)](https://t.co/B0VPw2swJ1)

@llama_index

---
## "Build a Slack Bot for Organizational Communication: A Step-by-Step Guide"

[https://twitter.com/llama_index/status/1750568734140567611](https://twitter.com/llama_index/status/1750568734140567611)

✨New OSS repo✨ Build a Slack bot that listens to your conversations, learns from them, and can answer questions about what's going on across your organization!

In @seldo's step-by-step guide you'll learn how to
➡️ Build a @SlackHQ bot from scratch
➡️ Install it to your Slack… [https://t.co/E8KJNeoXfr](https://t.co/E8KJNeoXfr)

![](https://pbs.twimg.com/media/GEtE29iakAEJ1UR.jpg)

@llama_index @seldo @SlackHQ

---
## Using RAG for Advanced Text-to-SQL Generation with Vanna AI

[https://twitter.com/llama_index/status/1750196064660127848](https://twitter.com/llama_index/status/1750196064660127848)

Use RAG to build advanced text-to-SQL

Vanna AI (@zain_hoda) is a project that gained overnight popularity for SQL generation given its easy-to-use but powerful interface that uses RAG for better performance:

1️⃣ Store and index DDL/table schemas
2️⃣ Store and index text… [https://t.co/NVGPa4OnYS](https://t.co/NVGPa4OnYS)

![](https://pbs.twimg.com/media/GEnyCJvawAAX84c.jpg)

@llama_index @zain_hoda

---
## Advanced Chat Bot Built with LlamaIndex: A Closer Look at MemGPT

[https://twitter.com/llama_index/status/1749935634033348693](https://twitter.com/llama_index/status/1749935634033348693)

Basic chat is easy, but a delightful chat experience has a lot of subtleties! In today's OSS project spotlight, [https://t.co/COUh9LAKzR](https://t.co/COUh9LAKzR) from @charlespacker is an advanced chat bot built with LlamaIndex.

MemGPT uses function-calling by LLMs under the hood to maintain multiple… [https://t.co/Zd0d9Aczk3[https://t.co/iZ0mRQUBbq](https://t.co/iZ0mRQUBbq)](https://t.co/Zd0d9Aczk3)

@llama_index @charlespacker

---
## AWS Knowledge Bases for RAG: A Fully Managed System for Private Data Retrieval

[https://twitter.com/BraceSproul/status/1750212202341237033](https://twitter.com/BraceSproul/status/1750212202341237033)

🧠 AWS Knowledge Bases For RAG 🧠

AWS Knowledge Base for Bedrock is a fully managed system for RAG applications and private data retrieval, now available thanks to a community PR in @LangChainAI JS/TS 🦜🔗

Store your proprietary data in AWS, point Knowledge Base to that data,… [https://t.co/HLQw1OFHc6](https://t.co/HLQw1OFHc6)

![](https://pbs.twimg.com/media/GEoALlAa4AII4Og.jpg)

See the full documentation here:
[https://t.co/SONuANhHlk](https://t.co/SONuANhHlk)

And install the latest version of `@langchain/community` here:
[https://t.co/2lPdWsmC4w](https://t.co/2lPdWsmC4w)

---
## A Live Indexing Pipeline for RAG

[https://twitter.com/llama_index/status/1748515130885968274](https://twitter.com/llama_index/status/1748515130885968274)

A Live Indexing Pipeline for RAG

Suppose you’re building a production RAG app on AWS, and you want it to always have access to the latest information⚡️ (instead of waiting a few hours for a batch indexing pipeline to run). Here’s how you can do that 💡

@kiennt_ has one of the… [https://t.co/mV0m6AtVsl](https://t.co/mV0m6AtVsl)

![](https://pbs.twimg.com/media/GEP5NjXaUAA5eWk.jpg)

@llama_index @kiennt_

---
[https://johnthenerd.com/blog/local-llm-assistant/](https://johnthenerd.com/blog/local-llm-assistant/)

---
## Improving Text Splitting Techniques for RAG in 2024

[https://twitter.com/jerryjliu0/status/1745486856291266821](https://twitter.com/jerryjliu0/status/1745486856291266821)

Text splitting for RAG has been quite hacky. Let’s fix that in 2024!
🚫 Broke: fixed chunk sizes
✅ Woke: Document-specific parsing, decoupled chunks for retrieval and synthesis, adaptive chunking

I like @GregKamradt’s semantic chunking technique - it’s clever, fast (w/… [https://t.co/mKqiU7B3kx[https://t.co/CqSrLqlfvh](https://t.co/CqSrLqlfvh)](https://t.co/mKqiU7B3kx)

These thoughts are similra to @thesephist a few months ago: [https://t.co/X4Fl1AwKlB](https://t.co/X4Fl1AwKlB)

---
## SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM

[https://twitter.com/Nik__V__/status/1731840557553496410](https://twitter.com/Nik__V__/status/1731840557553496410)

SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM

[https://t.co/NRxmwdK39s](https://t.co/NRxmwdK39s)

We extend Gaussian Splatting to solve SLAM, i.e., automatically calculate the camera poses when fitting the Gaussian scene from RGB-D videos.

Try it on your own iPhone capture today! 🧵👇 [https://t.co/cyznoWSFuN](https://t.co/cyznoWSFuN)

Accurate camera poses are super important for Gaussian Splatting but are annoying and slow to obtain (e.g., with COLMAP). This prevents real-time applications like Robotics and VR/AR.

With SplaTAM, we obtain accurate camera poses while fitting the scene with Gaussian Splatting. [https://t.co/aPg00wTFIe](https://t.co/aPg00wTFIe)

On many difficult scenes, our approach works much better than all previous SOTA SLAM approaches. Below, we show a difficult texture-less scene where ORB-SLAM 3 completely fails, whereas ours achieves almost perfect results (first two tweets above). [https://t.co/YyzA4IPFbm](https://t.co/YyzA4IPFbm)

We have released code for a real-time, online streaming demo, where for the first time, you can fit a Gaussian Splatting Scene live while it’s being recorded, without requiring any camera poses as input.

[https://t.co/kEUXWEV27d](https://t.co/kEUXWEV27d)

Imagine all of the uses in Robotics & AR/VR. [https://t.co/Ot7Ao0zCqY](https://t.co/Ot7Ao0zCqY)

The key is to render a visibility silhouette from the Gaussian Scene to determine areas that have and haven’t been seen before.

Using this, we can ignore unknown areas when optimizing for a new camera pose and also determine where to add new Gaussians during densification. [https://t.co/pS4GduQQ0D](https://t.co/pS4GduQQ0D)

Awesome collaboration with Jay (@JayKarhade), Krishna (@_krishna_murthy), Gengshaan (@gengshanY), Basti (@smash0190 @AirLabCMU), Deva Ramanan (@RamananDeva) and Jonathon (@JonathonLuiten).

Thanks for their amazing support during this project! [https://t.co/WxcXZz9x87](https://t.co/WxcXZz9x87)

Want to learn more about SplaTAM?

Check out our explainer video 💡: [https://t.co/1HZSY5ViXg](https://t.co/1HZSY5ViXg)

---
## Using RAGatouille to Effortlessly Rerank Documents with ColBERT

[https://twitter.com/bclavie/status/1745151278018076985](https://twitter.com/bclavie/status/1745151278018076985)

"I wish I could use the best retrieval model as a reranker in my RAG pipeline, but I don't have time to redesign it!" 

We've all been there and thought that, right?

🪤RAGatouille now lets you do it effortlessly! Retrieve docs as usual&let ColBERT rerank them in a single line⬇️ 

![](https://pbs.twimg.com/media/GDfTglbXQAAK6e4.jpg)

Of course, there's a mini-example too, w/ a typical case where ColBERT can catch information single-vectors might not: [https://t.co/QAmqLr1heb](https://t.co/QAmqLr1heb)

Though I hear @hwchase17 has got something cooking to showcase how to use this in @LangChainAI to make it even simpler 👀

---
## Using OLLAMA to Get Structured JSON Output from LLM Models

[https://twitter.com/llama_index/status/1744853380953158038](https://twitter.com/llama_index/status/1744853380953158038)

Getting structured output like JSON out of an LLM is both super-useful and sometimes tricky! In this video @andrejusb walks us through using @OLLAMA to run a local model and use Pydantic classes to get structured JSON out of invoices:
[https://t.co/16EAggnURi](https://t.co/16EAggnURi)

Check out the open… [https://t.co/oe0mVuZSYE](https://t.co/oe0mVuZSYE)

![](https://pbs.twimg.com/media/GDb1n_2acAAP54z.jpg)

@llama_index @andrejusb @OLLAMA

---
## Fine-tuning a Mistral 7B in MLX on WhatsApp Chat History Locally

[https://twitter.com/awnihannun/status/1744497202389754254](https://twitter.com/awnihannun/status/1744497202389754254)

Fun example: Fine tune a Mistral 7B in MLX locally on your WhatsApp chat history.

Completely local, no need to send data anywhere.

Code: [https://t.co/hrA7nEcPOZ[https://t.co/jk9bMyCPKJ](https://t.co/jk9bMyCPKJ)](https://t.co/hrA7nEcPOZ)

@awnihannun

---
[https://www.reddit.com/r/LocalLLaMA/s/RUrt2Jc8rm](https://www.reddit.com/r/LocalLLaMA/s/RUrt2Jc8rm)

---
## The Power of Scripts: My Experience at GitHub

[https://twitter.com/HamelHusain/status/1744466145401598396](https://twitter.com/HamelHusain/status/1744466145401598396)

I learned lots of wonderful things when I worked at GitHub, but the stickiest is scripts-to-rule them-all

[https://t.co/sfYxYjskZy](https://t.co/sfYxYjskZy)

@HamelHusain

---
## Introducing Ingestion Pipeline: A New Way to Manage Documents in @llama_index

[https://twitter.com/clusteredbytes/status/1744081053008965846](https://twitter.com/clusteredbytes/status/1744081053008965846)

**🪄Smart summary:**
Ingestion Pipeline is a new and improved way to ingest and manage documents in @llama_index. It supports applying a series of transformations on documents, caching those transformations, and managing ever-changing documents. Transformations are the building blocks of Ingestion Pipeline, and each transformation takes a list of nodes and returns another list of nodes after making the desired modifications. Ingestion Pipeline also supports caching, document management, and persisting. Check out the official documentation and blog for more details.
-------

Ingestion Pipeline is a new and improved way to ingest and manage documents in @llama_index

It supports:

- applying a series of transformation on documents
- caching those transformations
- managing ever-changing documents etc.

Let's see how to use it 👇🧵 

![](https://pbs.twimg.com/media/GDQ4eNRWkAA5Way.jpg)

Transformations are the building blocks of Ingestion Pipeline.

Each transformation takes a list of nodes, and returns another list of nodes after making the desired modifications to them.

We define the transformations while instantiating the pipeline itself. 

![](https://pbs.twimg.com/media/GDQ4fKrW8AASreb.png)

These are the transformations we can use:

1. TextSplitter
2. NodeParser
3. MetadataExtractor
4. Any embedding model

We can also create custom transformations. Guide on this is coming soon.

Output of one transformation is the input to the next one.

Caching

Each (transformation-it's input nodes list) pair is cached in the pipeline.

When we run the same transformation on the same list of input nodes, the output nodes will be fetched from cache.

We can also use remote cache i.e. Redis 

![](https://pbs.twimg.com/media/GDQ4f8-XsAA4H2g.png)

To make sure that we don’t run a transformation on same document multiple times, Ingestion pipeline uses the document id and the hash of the document content to handle duplicates.

we need to pass a docstore to the pipeline to enable this. 

![](https://pbs.twimg.com/media/GDQ4gV4WIAAQz0f.png)

The hashes of existing documents will be compared to the hashes of input documents. and unchanged documents will be excluded from transformation.

There are 3 strategies for document management.

1. duplicates only
2. upsert
3. upsert and delete

Guide on them coming soon.

If we pass a vectorstore to the pipeline, then it will automatically add the final output nodes from the transformation sequence to that vectorstore.

we can then use that populated vectorstore to create a vectorstore index. 

![](https://pbs.twimg.com/media/GDQ4hOAXgAAIqY6.png)

Persisting

Ingestion pipeline allows persisting the cache and the docstore to a folder (./pipeline_storage by default)

after defining the pipeline, we need to load it using pipeline.load() 

![](https://pbs.twimg.com/media/GDQ4iBEXsAA1tmv.png)

Thus ingestion pipeline makes it really efficient and intuitive to ingest and manage documents and apply a sequence of transformation on them 🚀

Checkout the official documentation
[https://t.co/JnmVHLp2FP](https://t.co/JnmVHLp2FP)

Details about ingestion pipeline and other cool RAG guides on my blog:
[https://t.co/nXUoSbJzFr](https://t.co/nXUoSbJzFr)

Thanks for reading.

I write about AI, LLMs, RAG etc. and try to make complex topics as easy as possible. 

Stay tuned for more ! 🔥 #AI
 #RAG
 [https://t.co/XJbf7Wwbro](https://t.co/XJbf7Wwbro)

---
[https://www.reddit.com/r/StableDiffusion/s/TVTpB559QY](https://www.reddit.com/r/StableDiffusion/s/TVTpB559QY)

---
## Building an AI Shopping Assistant with LlamaIndex Agents

[https://twitter.com/llama_index/status/1742970871713783847](https://twitter.com/llama_index/status/1742970871713783847)

**🪄Smart summary:**
LlamaIndex agents can be used to create an AI-powered shopping assistant that can match accessories to items you already own. This blog post from @dkiedanski and Lucas Micol of @tryolabs shows how APIs can be used to create this assistant.
-------

Use LlamaIndex agents to build an AI-powered shopping assistant that can take a picture of an item you already own and pair it with (weather-appropriate) accessories!

We love this blog post from @dkiedanski and Lucas Micol of @tryolabs that shows how you can take APIs and turn… [https://t.co/XiNdkjksNm](https://t.co/XiNdkjksNm)

![](https://pbs.twimg.com/media/GDBEl4baYAMQHWB.jpg)

@llama_index @dkiedanski @tryolabs

---
AI Product ideas

- A smart picture frame that cycles through AI generated pictures on your account
- Give it access to your Google photo album, and select from a drop down of LoRAs in different styles
- Recreate pics in album using LoRA, serve via API
- Frame pulls from API however often, gets random remix'ed pic back.
- Target boomers


- Upload your pic/head shot
- Select 'scenario' - old west, sci-fi, fantasy, etc
- Train dreambooth on headshot w/ scenario background 
- Generate link to purchase pics as a book from pic to book service

---
## Introducing Private AI: Chat with Your Data Privately and Free of Cost

[https://twitter.com/taranjeetio/status/1742214295755354530](https://twitter.com/taranjeetio/status/1742214295755354530)

**🪄Smart summary:**
Introducing Private AI, a free and simple way to privately chat with your data without the need for an internet connection. Powered by LangChainAI and GPT4All, this open source code allows users to ingest any folder on their machine and chat with it, regardless of file type. This is especially useful for sensitive and personal data such as finances and important documents.
-------

Introducing Private AI - privately chat with your data
using @embedchain

• All data stays on your machine
• Works on CPU machine
• Simple (4 lines of code)
• No internet required
• Free of cost

Powered by @LangChainAI & GPT4All from @nomic_ai

Common use case of RAG is chat with your data but main concern is privacy, and cost.

• Users worry if their data would be use to train the next model.
• Users don’t want to spend money.

Thanks to open source that we have good models like GPT4All, Llama, @MistralAI.

Today, we are introducing the simplest flow to create a RAG app which will ingest any folder on your machine and help you chat with it.

• Just import & instantiate the app
• Add the entire folder
• Start chatting 

![](https://pbs.twimg.com/media/GC2WrbnawAAQBMs.jpg)

In above example, I have taken a personal folder which contains data related to my finances

• Bank statement as csv
• 2 credit card statements as pdf
• Financial goals as markdown 

![](https://pbs.twimg.com/media/GC2WsKbbUAAUi_U.jpg)

We support all types of format, so you don’t need to worry about file types.

Also all data stays on your machine and you can chat with it by turning off your internet.

This is really helpful for sensitive and personal data like finances, important documents, etc.

We have open sourced the entire code here:

[https://t.co/DBZDiylXd2](https://t.co/DBZDiylXd2)

Do check it out and share your feedback in the comments.

---
## Launching a Repo for a Production ETL Pipeline for RAG/LLM Apps

[https://twitter.com/llama_index/status/1742226327900721168](https://twitter.com/llama_index/status/1742226327900721168)

**🪄Smart summary:**
Today, a new repository was launched that allows users to quickly and easily set up a production ETL pipeline for their RAG/LLM app. This architecture bundles LlamaIndex with other popular tools, allowing users to index thousands of documents in seconds, and orders of magnitude faster than running on a laptop.
-------

Today we’re launching a repo that lets you setup a production ETL pipeline for your RAG/LLM app 💫

Index thousands of documents in seconds ⚡️ (and orders of magnitude faster than running on your laptop).

It’s a full architecture which bundles LlamaIndex with other popular… [https://t.co/TbW6D6PwwK](https://t.co/TbW6D6PwwK)

![](https://pbs.twimg.com/media/GC2ha_CbIAAg_nH.png)

@llama_index

---
## Building a Context-Augmented Food Delivery Agent

[https://twitter.com/llama_index/status/1741987664272986534](https://twitter.com/llama_index/status/1741987664272986534)

**🪄Smart summary:**
This tweet features a repository by lucastonon that shows how to build a RAG agent that can look up relevant restaurants and perform in-browser actions such as opening a page, getting the menu, and adding food.
-------

Context-Augmented Agent for Food Delivery 🤖🍔

We’re excited to feature a full-stack repo by lucastonon showing you how to build a RAG agent that can not only look up relevant restaurants, but directly perform in-browser actions like opening a page, getting the menu, adding food… [https://t.co/cLJ653RTnT[https://t.co/nWzjGrG2jC](https://t.co/nWzjGrG2jC)](https://t.co/cLJ653RTnT)

@llama_index

---
## Building a Full-Stack RAG Chatbot Web App

[https://twitter.com/llama_index/status/1741562214853837296](https://twitter.com/llama_index/status/1741562214853837296)

**🪄Smart summary:**
This thread introduces a full-stack RAG starter pack, which includes MongoDB, Flask, Render, and Next.js. It provides a guide to building a chatbot web app with storage, backend/frontend, and deployment to the web. The mongodb-demo repo by @seldo is also included.
-------

Full-stack RAG Starter Pack 🔎📦 - with @MongoDB, Flask, @render, and @nextjs 

It’s one thing to build RAG in a notebook, it’s another thing to build a full-stack chatbot web app, with storage, backend/frontend, and deployed to the web 🌐

Our mongodb-demo repo by @seldo is an… [https://t.co/uRyhWyfKi3[https://t.co/FxNFZ6QWMc](https://t.co/FxNFZ6QWMc)](https://t.co/uRyhWyfKi3)

@llama_index @MongoDB @render @nextjs @seldo

---
## Amazing Open-Source AI Chat - MIT Licensed!

[https://twitter.com/phuctm97/status/1734413225071092025](https://twitter.com/phuctm97/status/1734413225071092025)

**🪄Smart summary:**
This open-source AI chat is impressive and has a MIT license, which means someone can self-host it and make a profit from it.
-------

Man, this open-source AI chat is almost too good to be true. And it's MIT licensed 🤯.

[https://t.co/HahwiY5GrT](https://t.co/HahwiY5GrT)

It’s literally better than many paid ChatGPT UI. And the fact that it’s MIT licensed is interesting, someone can just self host and make profit from it 🤨

---
## Visualizing Text Splitting and Chunking Strategies with ChunkViz.com

[https://twitter.com/GregKamradt/status/1733208049513611339](https://twitter.com/GregKamradt/status/1733208049513611339)

**🪄Smart summary:**
I built a tool called ChunkViz.com to visualize text chunking strategies. It features 4 different splitters from LangChainAI and is visually pleasing to tinker with. I'm also writing a post on chunking philosophies which will be published on my website. However, I have a beef with the tool as it trims the chunks, making it hard to reconstruct the visualization.
-------

visualizing text splitting & chunking strategies

ChunkViz .com 

I thought I remembered a tool to visualize text chunking, but I couldn't find it, so I built one

I didn't realize it would be so visually pleasing to tinker with

4 different @LangChainAI splitters featured [https://t.co/vN2kdIBgxd[https://t.co/4VywxHdqAa](https://t.co/4VywxHdqAa)](https://t.co/vN2kdIBgxd)

Head over to [https://t.co/NqskxGf5aX](https://t.co/NqskxGf5aX) to try it out

This is part of a post I'm doing on chunking philosophies. I'll publish on [https://t.co/pkIRUAAzQ0](https://t.co/pkIRUAAzQ0)

Code: [https://t.co/uwxRRGMIiC](https://t.co/uwxRRGMIiC)

I have beef though, returned chunks are .trim()'d, so they aren't exactly what the user passes in!

It made reconstructing the viz hard 😉

---
## Introducing AutoTranslateDoc: Translate Documentation to Over 15+ Languages!

[https://twitter.com/jerryjliu0/status/1732926141118472448](https://twitter.com/jerryjliu0/status/1732926141118472448)

**🪄Smart summary:**
We have open-sourced a new project that can translate documentation in any GitHub repository to over 15 languages, including Chinese, Spanish, and French. We have tested this on our own LlamaIndex.TS docs and it is now available. Thanks to Haotianzh for the translation and Seldo for helping to make it available in APAC time.
-------

Introducing AutoTranslateDoc ✍️🌐

We’re open-sourcing a new project that can translate the documentation in any @github repo to over 15+ languages: Chinese 🇨🇳, Spanish 🇪🇸, French 🇫🇷, and more. 

We dogfooded this on our own LlamaIndex.TS docs, and as a result it’s now available… [https://t.co/K3GPDWkFUC](https://t.co/K3GPDWkFUC)

![](https://pbs.twimg.com/media/GAyXEwCaQAAEZ3c.jpg)[https://t.co/eSbqGy3KTh](https://t.co/eSbqGy3KTh)

Thanks to @Haotianzh for the translation 😉

And @seldo for helping to line this up for APAC time 

[https://t.co/G0D3euwrM3](https://t.co/G0D3euwrM3)

---
## Poor RAG Performance: The Impact of Naive Chunking Strategies

[https://twitter.com/jerryjliu0/status/1732503009891127676](https://twitter.com/jerryjliu0/status/1732503009891127676)

**🪄Smart summary:**
Poor RAG performance is caused by naive chunking strategies due to the arbitrary nature of defining chunking boundaries, which are independent of the relevant context. An example of this is when the relevant context is at the beginning or end of a chunk.
-------

Naive chunking strategies cause poor RAG performance. But why? 🤔 (short 🧵)

A big reason is that defining a chunking boundaries is completely arbitrary and independent of the relevant context 💡

Example: if the relevant context is at the beginning/end of your chunk, then… [https://t.co/0nmykafoK4](https://t.co/0nmykafoK4)

![](https://pbs.twimg.com/media/GAsWIhFacAAdxGp.png)

@jerryjliu0

---
## Automatically Handle Incremental Data Updates with @llama_index

[https://twitter.com/jerryjliu0/status/1732122735722303771](https://twitter.com/jerryjliu0/status/1732122735722303771)

**🪄Smart summary:**
Llama Index now offers automated incremental data updates for production-scale data, eliminating the need for manual duplicate checking and upsert logic. Check out their guide for more information.
-------

A key requirement for building RAG for production-scale data is handling incremental data updates.

It's now handled automatically in @llama_index, without you needing to write boilerplate code for duplicate checking/upsert logic yourself! 

Checkout our guide on this topic:… [https://t.co/VmutwQkxEh](https://t.co/VmutwQkxEh)

![](https://pbs.twimg.com/media/GAm8cBHb0AAfDUG.jpg)[https://t.co/v8nOuSuQ5u](https://t.co/v8nOuSuQ5u)

@jerryjliu0 @llama_index

---
[https://docs.phidata.com/examples/rag-llm-app](https://docs.phidata.com/examples/rag-llm-app)

---
## Transforming Minimal Sketches into Realistic Renders with Interior AI

[https://twitter.com/levelsio/status/1731685220259078225](https://twitter.com/levelsio/status/1731685220259078225)

**🪄Smart summary:**
An interior designer/architect provided minimal sketches which were then used to generate realistic renders with the help of Interior AI v2, surprising the friend who posted the thread.
-------

My friend got these very minimal sketches from an interior designer / architect

I put them in Interior AI v2 and got these renders back

Didn't think it'd work with such minimal sketches 

![](https://pbs.twimg.com/media/GAguLNQWwAAy1ny.jpg)

@levelsio

---
## Create Your Own Text Summarization App in 20 Lines of Code

[https://twitter.com/itsafiz/status/1730912075353116841](https://twitter.com/itsafiz/status/1730912075353116841)

**🪄Smart summary:**
This thread provides instructions on how to create a text summarization app using Huggingface models and LangChain AI in less than 20 lines of code. It also provides instructions on how to install LangChain and Huggingface_hub before running the code. Finally, it encourages readers to follow the author for more Python and LLM content and to like and retweet the first tweet to share with friends.
-------

Text Summarization using LLMs and LangChain 🚀

Do you know you create your own text summarization app using @huggingface models and @LangChainAI in less than 20 lines of code? 

Complete source code 🧵👇 

![](https://pbs.twimg.com/media/GAVtS9oaUAAp96y.jpg)

Make sure that you have installed langchain and huggingface_hub before running the code. 

![](https://pbs.twimg.com/media/GAVvLzEawAAmF9G.jpg)

I hope you find this post useful!

if yes, please follow me @itsafiz for more Python and LLM content. 

Like and RT the first tweet to share with your friends. 

[https://t.co/Rcrx8fWP5X](https://t.co/Rcrx8fWP5X)

---
## Introducing Llama Datasets: Benchmark Your RAG Pipelines for Different Use Cases

[https://twitter.com/llama_index/status/1731718080223707148](https://twitter.com/llama_index/status/1731718080223707148)

**🪄Smart summary:**
Today, we are introducing Llama Datasets, a set of datasets contributed by the community that allow users to easily benchmark their RAG pipelines for different use cases. It is difficult to define a single right evaluation dataset for a LLM use case, so users can pick and choose the datasets that best fit their needs.
-------

Today we’re introducing Llama Datasets 🦙📝 - a set of community-contributed datasets that allow users to easily benchmark their RAG pipelines for different use cases.

It’s hard to define a single right eval dataset for your LLM use case. Instead, you can pick and choose the… [https://t.co/iMP7yeVp9I[https://t.co/6fw3bZC6s6](https://t.co/6fw3bZC6s6)](https://t.co/iMP7yeVp9I)

@llama_index

---
## Marker: A 10x Faster and More Accurate PDF to Markdown Converter

[https://twitter.com/VikParuchuri/status/1730357379194400803](https://twitter.com/VikParuchuri/status/1730357379194400803)

**🪄Smart summary:**
Marker is a pdf to markdown converter that is 10x faster than nougat, more accurate outside arXiv, and has low hallucination risk. It uses 4 models - column detector, layout detector, nougat, postprocessor - and is optimized for throughput. It is easy to parallelize and can be adjusted to speed up processing each individual PDF. Marker has limitations, including only supporting languages similar to English and being noncommercial.
-------

I'm excited to ship marker - a pdf to markdown converter that is 10x faster than nougat, more accurate outside arXiv, and has low hallucination risk. Marker is optimized for throughput, like converting LLM pretrain data.

Find it here - [https://t.co/t3V2uTYfbM](https://t.co/t3V2uTYfbM) . 

![](https://pbs.twimg.com/media/GAN0s74bYAAsEZq.png)

Nougat is an amazing model, but is slow and hallucination-prone (1.5% of pages in arXiv, 5%+ outside) due to autoregressive decoding.

Marker converts and cleans text incrementally. It uses 4 models - column detector, layout detector, nougat, postprocessor. It OCRs if needed.

To benchmark, I found some documents that had parallel latex and pdf versions, then converted the latex to markdown. 1/2 from arXiv, 1/2 textbooks.

I compared the references to the converted versions and computed a 0-100 alignment/accuracy score.

Marker is 10x faster than nougat per-page, and is more accurate outside of arXiv (think* are non-arXiv books, rest are arXiv). Both use max 3GB of VRAM in this benchmark (run on A6000). 

![](https://pbs.twimg.com/media/GAN0yLcaUAExN5D.png)

Marker is easy to parallelize, and throughput scales mostly linearly with parallel workers. There's even a script that will run conversion across multiple GPUs.

You can also adjust batch sizes to speed up processing each individual PDF, at the cost of more VRAM usage.

PDF is a tricky format - just blobs of text with positions. No info about how blobs link together.

The challenges are:

- Ordering text in multi-column layouts
- Knowing if the text you extract is corrupt
- Handling different types of blocks (indenting code, etc)

I tried many methods to find the text block order, even training a model to directly predict the order (input bounding boxes, output the order). This was based on the data from layoutreader - [https://t.co/6CMgulVH1Y](https://t.co/6CMgulVH1Y) .

This wasn't accurate, and could degenerate into repetition.

I then labeled a dataset myself (somewhat noisily giving entire pdfs the same label) and trained a model to detect the number of columns. Then find vertical column breaks, and order blocks within columns.

The column detector is here - [https://t.co/7eISckecZw](https://t.co/7eISckecZw) .

I use heuristics, like misspell rate, to determine if we need to use tesseract for OCR. Ocrmypdf is more accurate than tesseract alone, since it applies transforms to the page first.

OCRing all text is less accurate than extracting text, since OCR introduces errors.

After the text has been extracted and ordered, I use a layout segmenter to detect block types (text, equation, table, etc).

I finetuned layoutlmv3 with the DocLayNet dataset from IBM - [https://t.co/SB21zVCcBq](https://t.co/SB21zVCcBq) .

The final model is here - [https://t.co/x6iUcyJENP](https://t.co/x6iUcyJENP) .

Equations are converted to Latex with nougat. By only running nougat over equations, hallucination surface area is reduced significantly.

I'd like to finetune nougat to operate on smaller regions (it's not optimized for this use case, although it does very well).

Heuristics are applied to clean and join blocks. Tables, code, equations, etc, are handled differently. The hardest part is indent blocks - I need to retrain the layout detector for this.

This gets us most of the way there, but heuristics can't handle all edge cases.

I trained a postprocessor model that takes in the almost-final text and finalizes it by deleting artifacts, adding spaces, etc.

The model is a token classifier, to detect if each input token needed a space in front of it, to be deleted, etc.

For training data, we need to clean the text, align the cleaned text to the original text, then align both with the tokens from an LLM.

One problem is that most tokenizers are destructive in some way - they remove whitespace, replace some characters with unk, etc.

I tried bloom, which has a big vocab, and did not remove whitespace like mdeberta and others.

But bloom codes some unicode characters as unknown, which made it unsuitable. (although I really wanted it to work!)

The bloom-based postprocessor is here - [https://t.co/EEK0m7hiMk](https://t.co/EEK0m7hiMk) .

I used byt5, which tokenizes unicode characters into bytes. This is less efficient, but can encode any utf-8 char.

One character can be several tokens (one token = one byte), so I recombine tokens and process each character.

The model is here - [https://t.co/JtmtQkzAmI](https://t.co/JtmtQkzAmI)

The postprocessor is an area that could use some work. Cleaning up how I align the original and cleaned sequences is something I want to work on, as well as collecting more training data.

Marker has limitations, including:

- It only support languages similar to English. Chinese, Hindi, etc, will not work.
- It is noncommercial due to nougat and layoutlm licensing.
- Not all equations will be converted to latex.

Marker wouldn't be possible without some amazing open source work, including, but not limited to:

- LayoutLMv3 from Microsoft
- Nougat by Meta(@lukas_blecher)
- DocLayNet from IBM
- ByT5
- OCRmyPDF + tesseract
- PyMuPDF

Thank you so much for this work.

I think building entire pipelines/applications is a big opportunity for open source AI. Pipelines can be much more effective than single models, but it's much more common to finetune a model than it is to chain several models together.

I trained/fine-tuned all models on 4 A6000s. I was excited to see how far I could get with relatively limited GPU resources!

Anyways, I hope you find this useful! If you do try marker out, please let me know how it went for you. I've tried it across a wide range of PDFs, but there are so many edge cases.

---
## Insanely Fast Whisper with Speaker Diarisation Now Available!

[https://twitter.com/reach_vb/status/1729251580371689821](https://twitter.com/reach_vb/status/1729251580371689821)

**🪄Smart summary:**
Speaker Diarisation is now available with Pyannote library, which is 100% local and works on Mac or Nvidia GPUs. It provides fast transcriptions and speaker segmentations. To use it, install the project mentioned in the thread. A logo has been added to the project, which was generated from SDXL.
-------

Insanely fast whisper now with Speaker Diarisation! 🔥

100% local and works on your Mac or on Nvidia GPUs.

All thanks to @hbredin's Pyannote library, you can now get blazingly fast transcriptions and speaker segmentations! ⚡️

Here's how you can use it too:

pipx install… [https://t.co/zoIvHYNbde[https://t.co/pAbXIGObFA](https://t.co/pAbXIGObFA)](https://t.co/zoIvHYNbde)

Want to see how this works? Check out the project below:

[https://t.co/fbrZW1r8DH](https://t.co/fbrZW1r8DH)

Oh, don't worry; I already invalidated the HF token 🤗

Added a logo! Let's fkn gooo!🚄🔥

(generated from SDXL of course) 

![](https://pbs.twimg.com/media/F_-iLLiXUAA2BD-.jpg)

---
## Recreating 3D Scenes Using Eye Reflections

[https://twitter.com/ToughSf/status/1728518927133614393](https://twitter.com/ToughSf/status/1728518927133614393)

**🪄Smart summary:**
A new technique has been developed that can recreate 3D scenes using the reflections in a person's eyes. A single photo is enough, but accuracy is improved with multiple reflections from multiple angles, like a video capturing moving eyes.
-------

Recreating 3D scenes using the reflections in your eyes:
[https://t.co/6aifDeY1Rt](https://t.co/6aifDeY1Rt)

A single photo is enough, but it becomes much more accurate with multiple reflections from multiple angles, like a video capturing moving eyes. [https://t.co/XwoqIkxT1z](https://t.co/XwoqIkxT1z)

@ToughSf

---
## Unlocking Advanced Retrieval with SEVEN LlamaPacks

[https://twitter.com/llama_index/status/1729303619760259463](https://twitter.com/llama_index/status/1729303619760259463)

**🪄Smart summary:**
We have created seven advanced retrieval LlamaPacks as templates to help you build advanced RAG. It is now easier than ever to try each technique with just one line of code. The full set of techniques includes Hybrid Fusion (vector +...).
-------

We’ve created SEVEN advanced retrieval LlamaPacks as templates to help you build advanced RAG 🔥

It’s never been easier; instead of following a notebook, you can now try each technique in ~1 line of code ⚡️

Here’s the full set of techniques below:
⭐️ Hybrid Fusion (vector +… [https://t.co/CaZXuf6byS](https://t.co/CaZXuf6byS)

![](https://pbs.twimg.com/media/F_-4eI1boAA8BW_.png)

@llama_index

---
## Achieving 76% Accuracy on SQL-Eval with GGUF on an M1 Mac

[https://twitter.com/rishdotblog/status/1728819667152855370](https://twitter.com/rishdotblog/status/1728819667152855370)

**🪄Smart summary:**
A new 7B model has been developed and tested on an M1 Mac, achieving 76% accuracy on sql-eval. This is lower than GPT-4 and SQLCoder-34B-v2, but is still impressive given that it works locally on a laptop. The model is expected to be released soon as a Mac app.
-------

Running our new 7B model 100% locally on an M1 Mac 🤓

76% accuracy on sql-eval with GGUF. For reference, GPT-4 is 82.5% and SQLCoder-34B-v2 is at 85%

Pretty wild that this works locally *on a laptop*! Super excited about getting this on a Mac app soon. [https://t.co/qpqsUPRTxa](https://t.co/qpqsUPRTxa)

![](https://pbs.twimg.com/media/F_3-tzdacAEvPUu.jpg)

@rishdotblog

---
## Create and Customize Your Own RAG Agent with Natural Language

[https://twitter.com/llama_index/status/1726999440974844022](https://twitter.com/llama_index/status/1726999440974844022)

**🪄Smart summary:**
RAGs is a Streamlit app that allows users to create and customize their own RAG agent and use it to search and retrieve data using natural language. It is inspired by OpenAI GPTs.
-------

Introducing RAGs, a @streamlit app that allows you to create and customize your own RAG agent and then use it over your own data, all with natural language 🔥

Directly inspired by @OpenAI GPTs, you can converse with an agent to help you do search/retrieval over any data you… [https://t.co/A1dE3vQGs9[https://t.co/eebPQqDFM6](https://t.co/eebPQqDFM6)](https://t.co/A1dE3vQGs9)

@llama_index @streamlit @OpenAI

---
## Generating Training Data for Natural Language Processing Tasks with a RAG Pipeline

[https://twitter.com/abacaj/status/1726681852801651067](https://twitter.com/abacaj/status/1726681852801651067)

**🪄Smart summary:**
This thread suggests a method for using a 13B model to generate new training data for tasks such as Q/A, summarizing, and information extraction. It is recommended to run the model in 4bit over a RAG pipeline, and to use 8bit if compute is available. A paper is provided for reference. Finally, the reader is left to figure out a way to filter poorly generated completions.
-------

Run this model in 4bit over a RAG pipeline, use it to generate new training data for a specific task you have Q/A, summarizing, information extraction etc. Fine tune the 13B model using the generated data, profit [https://t.co/jsHbANbhCA](https://t.co/jsHbANbhCA)

If you have the compute do 8bit but 4bit will get you on much cheaper hardware

Paper for reference [https://t.co/GPL1TVjZoI](https://t.co/GPL1TVjZoI)

![](https://pbs.twimg.com/media/F_Zo1K8WMAEVYzc.jpg)

I know I simplified it, of course you need to have a way to filter poorly generated completions - left as an exercise for the reader lol

---
## A Comprehensive Guide to Building LLM/RAG Apps

[https://twitter.com/llama_index/status/1726280711517438336](https://twitter.com/llama_index/status/1726280711517438336)

**🪄Smart summary:**
This guide by @nanonets is a comprehensive resource for building LLM/RAG apps over data, covering 12+ parts including data, models, training, and more. It is concise yet comprehensive and is one of the best guides available.
-------

We have over 250+ guides to help you build simple-to-advanced LLM/RAG apps over your data.

But if you’re looking for a unified resource, this guide by @nanonets is one of the best that we’ve seen 👇

It’s concise yet comprehensive, covering 12+ parts including:
✅ Data… [https://t.co/HunnWK1hIo](https://t.co/HunnWK1hIo)

![](https://pbs.twimg.com/media/F_T7JBnbgAAwECJ.jpg)

@llama_index @nanonets

---
## Introducing Codegen: Agent-Driven Software Development for Enterprise Codebases

[https://twitter.com/mathemagic1an/status/1725193428060025306](https://twitter.com/mathemagic1an/status/1725193428060025306)

**🪄Smart summary:**
Codegen is a new agent-driven software development platform for enterprise codebases. It has raised $16 million from Thrive Capital and other investors. It has features such as Ticket to Pull Request, which allows users to delegate complex tasks to Codegen and receive a PR/explanation commented on the ticket. It also has a multi-agent system with access to code, docs, Slack, tickets, git, CI, and more. It is merging AI-generated PRs in prod for multimillion-line codebases and is looking
-------

Excited to share what I've been building 🚀

Introducing @codegen
[https://t.co/3LsrrFitLz](https://t.co/3LsrrFitLz)

⚡ Agent-driven software development for enterprise codebases ⚡

We've raised $16mm from @ThriveCapital and others to bring this to the world - [https://t.co/LuclcoGB9K](https://t.co/LuclcoGB9K)

👇 More below [https://t.co/HYtfsO2Ify](https://t.co/HYtfsO2Ify)

Our mission at @codegen is "L5 Software Engineering Automation."

That is - the system you can ask to "build @netflix" and it:

➡️ Writes the code
➡️ Provisions AWS infra
➡️ Monitors logs & makes fixes
..

.. performing any task, using all the tools of modern software.

2/

Copilot and "chat your code" have already changed the way we program.

These keep the human in the driver's seat and accelerate them with AI.

But what's possible when we remove the human as a constraint?

3/

brings this vision to life by putting AI "agents" in the driver's seat 🏎️

Delegate complex tasks to @codegen and watch as it:

⚡ Eliminates tech debt
⚡ Rapidly builds out boilerplate
⚡ Refines/refactors code

All without leaving your @linear, @github and @SlackHQ

4/

Today, we're excited to debut "Ticket to Pull Request" for enterprise codebases.

Add the "Codegen" label to a ticket =>

➡️ @codegen spins up an army of agents to solve the issue

➡️ You receive a PR/explanation commented on the ticket

➡️ Chat, give feedback, etc.

5/ [https://t.co/0AhUiADPQW](https://t.co/0AhUiADPQW)

is built to collaborate with you like human, incorporating feedback and navigating ambiguity through interaction.

Have a question about it's changes? DM @codegen in slack.

Have feedback on a PR? Leave a comment and @codegen will fix it.

6/ [https://t.co/GaY4nEkGFf](https://t.co/GaY4nEkGFf)

What happens when you rig up a multi-agent system with access to your code, your docs, your slack, your tickets, git, your CI, and more?

The tedium of building software recedes and you're left to focus on shipping product.

The way it should be.

7/ [https://t.co/Lyd0dtPRm9](https://t.co/Lyd0dtPRm9)

Today, we're merging AI-generated PRs in prod for multimillion-line codebases.

We are the first to do this that we know of at this scale.

And we're sprinting towards bringing this to the broader market.

8/

We're thrilled to announce our raise of $16mm led by @ThriveCapital and a group of god-tier angels:

• Naval @naval
• @adamdangelo CEO @ Quora
• @mikeyk cofounder @ Instagram
• @karimatiyeh CTO @ Ramp
• @biilmann CEO @ Netlify
• @scottcjohnston CEO @ Docker
...

9/

• @zeeg CTO @ Sentry
• @ceo_clickhouse CEO @ Clickhouse
• @simonlast cofounder @ Notion
• @beyang CTO @ Sourcegraph
• @joshm & @hursh cofounders @ Browser Co
• @__joshma CTO @ Airplane
• @cjc COO @ Linear
...

It's an all-star team that can't wait to use our product.

10/

We couldn't be more excited to bring this technology to the world.

Do you have a massive codebase want to focus on shipping more, faster?

Reach out on [https://t.co/3LsrrFitLz](https://t.co/3LsrrFitLz) and we'd love to chat.

Lastly - this is just the beginning. We have so much to build.

Are you an elite AI hacker?

Is computer science your passion?

Do you connect deeply with the mission of breathing life into software engineering AI?

We're hiring! Hit us up at hiring@codegen.com 🙌

---
## Taking a Break to Check Out an AI Presentation Generator

[https://twitter.com/multikev/status/1724908185361011108](https://twitter.com/multikev/status/1724908185361011108)

**🪄Smart summary:**
The author is feeling tired and is excited about the success of a project they are working on. They have released an AI presentation generator and invite the reader to check it out.
-------

I think I need to go lie down. [https://t.co/wT6a7q6juZ[https://t.co/WxScGQTEKZ](https://t.co/WxScGQTEKZ)](https://t.co/wT6a7q6juZ)

Well, this is taking off. @steveruizok is that what PMF sounds like? 🚀

-

I don't have a SoundCloud, but we just released a pretty awesome AI presentation generator this week, would love if you checked it out ♥️

[https://t.co/K9JVjGXt1F](https://t.co/K9JVjGXt1F)

---
## Create a Real-Time Image Cycle of People's Creations on Ding

[https://twitter.com/StoopMensch/status/1724645126495150575](https://twitter.com/StoopMensch/status/1724645126495150575)

**🪄Smart summary:**
This tweet suggests that people should create a device that cycles through real-time images of what people are creating on Ding, and that it would cost $3200.
-------

It's only $3200 actually

[https://t.co/0fPn6N8aZu](https://t.co/0fPn6N8aZu)

you should make one that cycles through real time images of what people are creating on ding

---


---
## Unlocking Production-Ready RAG with Transformation Caching

[https://twitter.com/jerryjliu0/status/1724837344543695185](https://twitter.com/jerryjliu0/status/1724837344543695185)

**🪄Smart summary:**
We are releasing a new feature called transformation caching which helps make RAG pipelines production-ready by speeding up ingestion. Building production RAG requires parameter tuning for input data, chunk sizes, embedding, and metadata extractors.
-------

One of the coolest features we’re releasing today is transformation caching 💫 - make your RAG pipeline production-ready by speeding up ingestion ⚡️

Building production RAG requires a lot of parameter tuning to get right: input data, chunk sizes, embedding, metadata extractors,… [https://t.co/0ZadotCY69](https://t.co/0ZadotCY69)

![](https://pbs.twimg.com/media/F-_aZCsbkAAhHck.png)[https://t.co/ThqNjdSmbE](https://t.co/ThqNjdSmbE)

@jerryjliu0

---
## Introducing SQLCoder-34B: Our Most Capable Model Yet!

[https://twitter.com/defogdata/status/1724488025433145617](https://twitter.com/defogdata/status/1724488025433145617)

**🪄Smart summary:**
We are excited to announce the release of SQLCoder-34B, our most powerful model yet. Even without fine-tuning, it outperforms GPT-4 turbo for text to SQL conversion on our open-source SQLEval benchmark. With fine-tuning, we have seen SQLCoder-34B reach near perfect accuracy.
-------

We are thrilled to release SQLCoder-34B today! The 34B model is our largest and most capable model yet.

Even when not fine-tuned, it outperforms GPT-4 turbo for text to SQL conversion on our open-source SQLEval benchmark. With fine-tuning, we have seen SQLCoder-34B reach near… [https://t.co/91CJZK3ASP](https://t.co/91CJZK3ASP)

![](https://pbs.twimg.com/media/F-6bBKybEAAiLXu.jpg)

@defogdata @huggingface

---
## Introducing Create-Llama: Generate a Full-Stack Application in Seconds!

[https://twitter.com/llama_index/status/1724481182245785964](https://twitter.com/llama_index/status/1724481182245785964)

**🪄Smart summary:**
Today, we are excited to announce the release of create-llama, a command line tool that allows users to quickly generate a full-stack LlamaIndex application in either TypeScript or Python. Create-llama also offers the convenience of deploying to either Vercel or other cloud providers.
-------

✨ Big news! ✨ Today we're happy to release create-llama, a simple to use command line tool that generates a full-stack LlamaIndex application for you, with your choice of TypeScript or Python as backend! Get started chatting with your data in just a few seconds.

All you need… [https://t.co/1XIggGo2WJ](https://t.co/1XIggGo2WJ)

![](https://pbs.twimg.com/media/F-6WY9WbIAAN2Hg.jpg)

A really convenient part of create-llama is that you can pick the type of backend that fits your needs:

1: want a full-stack JS application you can deploy in one click to @vercel? We got you, and it's powered by LlamaIndex.TS, our TypeScript package.

2: want to deploy to a more… [https://t.co/AeqwqytT8W](https://t.co/AeqwqytT8W)

---
## SQLCoder Beats GPT-4 for Postgres SQL Generation

[https://twitter.com/rishdotblog/status/1724491602331386031](https://twitter.com/rishdotblog/status/1724491602331386031)

**🪄Smart summary:**
After 3 months of hard work, SQLCoder has been able to outperform GPT-4 in Postgres SQL generation. It is also 2x faster than GPT-4 and GPT-4-Turbo when deployed on a single A100 80GB GPU, and as fast when deployed on 4x A10 GPUs. There is potential for further speed gains with Nvidia's TensorRT LLM.
-------

We finally beat GPT-4 for SQL generation, after 3 months of trying! 🤓

SQLCoder now writes better Postgres SQL than GPT-4. Benchmarks aside, I'm amazed at how well it works even without fine-tuning.

WITH further fine-tuned on a particular schema, it's ridiculously good. We've… [https://t.co/bSrKJhpwJE](https://t.co/bSrKJhpwJE)

![](https://pbs.twimg.com/media/F-6ekAabIAAccJB.jpg)

Equally importantly, it is 2x faster than GPT-4 and GPT-4-Turbo when deployed on a single A100 80GB GPU. And as fast when deployed on 4x A10 GPUs (using vLLM)

We haven't had a chance to play with Nvidia's TensorRT LLM, but might get more speed gains with that.

Huge props to… [https://t.co/MmMjWREgdb](https://t.co/MmMjWREgdb)

---
## Comprehensive Survey of Embeddings and Rerankers for RAG

[https://twitter.com/llama_index/status/1720465247474221178](https://twitter.com/llama_index/status/1720465247474221178)

**🪄Smart summary:**
A comprehensive survey has been created to analyze the best mix of embeddings and rerankers for RAG. A Colab notebook is provided to auto-generate an evaluation dataset.
-------

Which mix of embeddings/rerankers works best for RAG?

Thanks to @ravithejads, we’ve created our most comprehensive survey yet, analyzing 7 SOTA embedding models and 3 rerankers 🔥.

Best of all, the full Colab notebook is provided so you can 1) auto-generate an eval dataset, and… [https://t.co/03DtSihI7d](https://t.co/03DtSihI7d)

![](https://pbs.twimg.com/media/F-BRu8ybMAAJcEq.jpg)

@llama_index @ravithejads

---
## Unlocking the Power of LlamaIndex + Deep Memory

[https://twitter.com/llama_index/status/1720230800304869696](https://twitter.com/llama_index/status/1720230800304869696)

**🪄Smart summary:**
LlamaIndex + Deep Memory is a powerful and easy to use module that can be used to improve RAG metrics by up to 15%. It works on top of any existing embeddings and can be used by following the link provided.
-------

LlamaIndex + Deep Memory (@activeloopai)

This is a super powerful, easy to use module that automatically fine-tunes your document/query embeddings during ingestion time.

Get +15% improvements in RAG metrics 📈, and works on top of any existing embeddings!

To use this, you… [https://t.co/5POkJy7wwE](https://t.co/5POkJy7wwE)

![](https://pbs.twimg.com/media/F998qwEbAAAbDif.jpg)

@llama_index @activeloopai

---
## Introducing LLM Enforcer: Guarantee Compliance for Local LLMs

[https://twitter.com/llama_index/status/1720103157412647265](https://twitter.com/llama_index/status/1720103157412647265)

**🪄Smart summary:**
We are excited about the LLM Enforcer repository, which guarantees compliance to JSON or regex for any local LLMs like llama.cpp or Huggingface.
-------

There’s been libraries to enforce structured outputs for OpenAI LLMs (functions, Guidance), but there hasn’t been as many for local LLMs like llama.cpp / @huggingface.

That’s why we’re so excited about LLM Enforcer repo (@noamgat) - guarantee compliance to JSON or regex for any… [https://t.co/YUe4gT7Fz3](https://t.co/YUe4gT7Fz3)

![](https://pbs.twimg.com/media/F98H1IibcAA-yh-.png)

@llama_index @huggingface @noamgat

---
## The Benefits of vLLM + awq for LLM Inference

[https://twitter.com/HamelHusain/status/1719882599261413840](https://twitter.com/HamelHusain/status/1719882599261413840)

**🪄Smart summary:**
vLLM + awq is an efficient and user-friendly solution for LLM inference, offering fast speeds and portability. Documentation for the awq part is limited, but more information can be found at the provided link.
-------

vLLM + awq is the best solution I've found for LLM inference. 

- Fastest speeds competitive with everything I've seen
- An extremely portable backend that is compatible with many inference servers
- Super easy to use out of the box

The awq part isn't documented that well, but… [https://t.co/NsdLnLMy3S](https://t.co/NsdLnLMy3S)

@HamelHusain

---
## Announcing the Launch of LlamaIndex Chat 🦙💬

[https://twitter.com/jerryjliu0/status/1719022164203196824](https://twitter.com/jerryjliu0/status/1719022164203196824)

**🪄Smart summary:**
Today, the launch of LlamaIndex Chat was announced. It is a production-ready, full-stack application where users can create and share LLM bots over their data, and it is open-source with an MIT license.
-------

Today I’m excited to announce the launch of LlamaIndex Chat 🦙💬

It is two things:
🔥 A production-ready, full-stack application where you can create and share LLM bots over your data 🔗🤖
🔥 A fully open-source (MIT license) JS/TS application template that you can easily… [https://t.co/aDDORhNgmU[https://t.co/Q339Q58XzW[https://t.co/MyRgIZxu9t](https://t.co/MyRgIZxu9t)](https://t.co/Q339Q58XzW)](https://t.co/aDDORhNgmU)

@jerryjliu0

---
## AutoLLM: Unified API, Vector Databases, and Cost Calculation in One Library

[https://twitter.com/1littlecoder/status/1719382120500445440](https://twitter.com/1littlecoder/status/1719382120500445440)

**🪄Smart summary:**
AutoLLM is a new Python library by SafeVideo AI that combines RAG and API into one library. It offers a unified API, 20+ vector databases, cost calculation, and 1-line FastAPI. Links to the library and more information are provided.
-------

🕵️‍♂️AutoLLM is a new 🐍🐍 Library by @safevideo_ai for RAG + API in one library. It builds on top of @llama_index , @LiteLLM and @FastAPI 

✅Unified API
✅20+ Vector Databases
✅Cost Calculation 
✅1-Line FastAPI

⚡️ [https://t.co/nbdAbY3wwK](https://t.co/nbdAbY3wwK)

📦 - [https://t.co/41W2GOV1RN[https://t.co/ouhDA9yoWQ](https://t.co/ouhDA9yoWQ)](https://t.co/41W2GOV1RN)

@1littlecoder @safevideo_ai @llama_index @LiteLLM @FastAPI

---
[https://github.com/swirlai/swirl-search](https://github.com/swirlai/swirl-search)

---
[https://www.reddit.com/r/LocalLLaMA/s/DrSdBVPPk2](https://www.reddit.com/r/LocalLLaMA/s/DrSdBVPPk2)

---
## Deploying RAG in Production with LangChainAI, qdrant_engine, ApacheAirflow, streamlit, and DVCorg

[https://twitter.com/noe_achache/status/1719796631451611187](https://twitter.com/noe_achache/status/1719796631451611187)

**🪄Smart summary:**
This thread provides an overview of tools and resources for deploying Retrieval Augmented Generation (RAG) in production, including LangChainAI, qdrant_engine, ApacheAirflow, streamlit, and DVCorg. It also includes a link to a replay of a talk on the topic at GenAI London.
-------

Want to learn more on deploying RAG (Retrieval Augmented Generation) in Production with:
- @LangChainAI for a quick start
- @qdrant_engine
- @ApacheAirflow

And for iterations:
- @streamlit
- @DVCorg

Replay of my talk at GenAI London:
[https://t.co/1dCyjZ5jNu](https://t.co/1dCyjZ5jNu)

cc @mattzcarey 

![](https://pbs.twimg.com/media/F93wqadWUAEujxr.jpg)

@noe_achache @LangChainAI @qdrant_engine @ApacheAirflow @streamlit @DVCorg @mattzcarey

---
## Introducing Create-Rubric-App: The Fastest Way to Build AI Applications with React and Type Safety

[https://twitter.com/RubricLabs/status/1719812696575529220](https://twitter.com/RubricLabs/status/1719812696575529220)

**🪄Smart summary:**
Create Rubric App is a full-stack AI project that can be set up with one command. It is built using Next.js, LangChainAI, Prisma, and TailwindCSS. Agents can call LLMs recursively, allowing for variable-depth scraping, multi-step planning, and self-healing code. The project is open-source and feedback is welcome.
-------

Introducing → create-rubric-app

Create Rubric App sets up a full-stack AI project in one command.

It's the fastest way to start building applications with AI Agents in React with complete type safety.

Built using @nextjs @LangChainAI @prisma @tailwindcss [https://t.co/A9MTkRYQnW](https://t.co/A9MTkRYQnW)

To get started, simply run:

npx create-rubric-app --ai 

![](https://pbs.twimg.com/media/F93gjRfWUAAhlYL.jpg)

Why Agents?

Agents can call LLMs recursively. 

Adapting to new information and creatively solving a whole new class of problems.

For e.g, use cases like variable-depth scraping, multi-step planning, and self-healing code have become possible through agents.

The best part? This project is fully open-source.

We're excited to see what you will build with this.

If you have feedback, feel free to open a pull-request or an issue in our GitHub repo.

Want to learn more? Read our blog post.

[https://t.co/0MuYRsO3jH](https://t.co/0MuYRsO3jH)

---
## Microsoft's Generative AI Education Series for Beginners

[https://twitter.com/omarsar0/status/1719733572603412635](https://twitter.com/omarsar0/status/1719733572603412635)

**🪄Smart summary:**
Microsoft has released a series of lessons on generative AI, covering topics such as language models, prompt engineering, text generation, and chat applications.
-------

🎓Generative AI for Beginners

Another great effort by Microsoft on AI education. This one contains a series of lessons on generative AI, including an introduction to LLMs, prompt engineering fundamentals, building text generation/chat applications, and more.… [https://t.co/lb9YLuouB2](https://t.co/lb9YLuouB2)

![](https://pbs.twimg.com/media/F92383KWIAACLnl.jpg)

@omarsar0

---
## Twitter thread by @GregoryDiamos

[https://twitter.com/GregoryDiamos/status/1719364355933053045](https://twitter.com/GregoryDiamos/status/1719364355933053045)

Lamini now supports JSON output at full speed. We guarantee that your LLM produces a valid JSON object according to your spec. Works for any LLM we support, e.g. Mistral 7b show below.

API Docs: [https://t.co/UHCkmO640s](https://t.co/UHCkmO640s)

![](https://pbs.twimg.com/media/F9xoxGXaMAAbbR6.jpg)

@GregoryDiamos

---
## Introducing LangChain Templates: Easily Deployable Reference Architectures

[https://twitter.com/LangChainAI/status/1719377131313172556](https://twitter.com/LangChainAI/status/1719377131313172556)

**🪄Smart summary:**
LangChain Templates is a new collection of reference architectures for various tasks that can be easily deployed, created, shared, downloaded, and customized.
-------

🦜🏗️LangChain Templates

Today we're excited to announce the release of ✨LangChain Templates✨ - a collection of easily deployable reference architectures for a wide variety of tasks

This is a new way to 🖌️create, 🤝share, ⏬download, and 💱customize chains and agents

❓How… [https://t.co/9441CUzL4a](https://t.co/9441CUzL4a)

![](https://pbs.twimg.com/media/F9x0M8Pa0AAttJd.jpg)

@LangChainAI

---
[https://www.reddit.com/r/LocalLLaMA/s/y5CQ5GxBgR](https://www.reddit.com/r/LocalLLaMA/s/y5CQ5GxBgR)

---
## The Ultimate Guide to RAG in Production

[https://twitter.com/bhutanisanyam1/status/1718295024788783476](https://twitter.com/bhutanisanyam1/status/1718295024788783476)

**🪄Smart summary:**
This thread provides a comprehensive guide to RAG in production, with discussion on embedding fine-tuning, re-ranking, and routing requests. It is written by @GokuMohandas and is easily the most complete guide available.
-------

The definitive guide to RAG in production! 🙏

@GokuMohandas walks us through implementing RAG from scratch, building a scalable app

It now has updated discussion on embedding fine-tuning, re-ranking and effectively routing requests

I think this is easily the most complete… [https://t.co/3jQiEDrPmf](https://t.co/3jQiEDrPmf)

![](https://pbs.twimg.com/media/F9icNcCXkAA_WSa.jpg)

@bhutanisanyam1 @GokuMohandas

---
## Building Your ChatGPT with LangChainAI and AgentLabs in Python

[https://twitter.com/kevinpiac/status/1717854163239842091](https://twitter.com/kevinpiac/status/1717854163239842091)

**🪄Smart summary:**
This tutorial provides a step-by-step guide on how to build a ChatGPT with LangChainAI and AgentLabs using Python. The author encourages readers to provide feedback on the tutorial.
-------

I just wrote a step-by-step tutorial showing how to build your ChatGPT with @LangChainAI and @agentlabs_ in Python.

[https://t.co/LIY4tvxE29](https://t.co/LIY4tvxE29)

Let me know what you think about it :) [https://t.co/gh8FF2IvIw](https://t.co/gh8FF2IvIw)

@kevinpiac @LangChainAI @agentlabs_

---
## Moving summarize.tech off GPT-3.5 and onto Mistral-7b-instruct: A Journey with Open-Source LLMs

[https://twitter.com/floydophone/status/1715035183228018816](https://twitter.com/floydophone/status/1715035183228018816)

**🪄Smart summary:**
A side project that uses GPT-3.5 to summarize YouTube videos had grown in popularity, but the creator wanted to switch to an open-source LLM. After trying Vicuna-13b and Llama2, Mistral-7b-instruct was found to be just as fast and high quality as GPT-3.5, and was hosted by Perplexity AI. This tweetstorm is to show that open LLMs are now usable for production apps, and to thank the teams involved.
-------

a few weeks ago, i moved summarize dot tech off of gpt-3.5 and onto @MistralAI's mistral-7b-instruct, an open-source LLM that runs on normie hardware. the model is hosted by @perplexity_ai. it's just as fast, just as high quality, and much cheaper to run. here are the details:

first, some context. summarize dot tech is a side project i hacked in a few weekends last year to summarize youtube videos w/ gpt-3 (now gpt-3.5). it ended up growing in popularity and now has over 200,000 monthly active users. here it is in action: [https://t.co/DOd7RU5yJy](https://t.co/DOd7RU5yJy)

gpt-3.5 is great, but i have always been excited about open-source LLMs for all of the stallmanesque reasons. however, the popular open LLMs i tried all had lots of problems. vicuna-13b, a popular choice, was noticeably worse than gpt-3.5. so much so that i could not deploy it.

llama2 was high quality, but the AI alignment teams clearly went way too far. for example, it will infamously refuse to tell you how to kill a linux process because it is "unethical" [https://t.co/6pRGFJVWMS](https://t.co/6pRGFJVWMS)

so for a while, i just dropped the idea of using a local model. eventually, i heard that a new model, mistral-7b, had come out, and was really good. so i gave it a shot. i fired up llama-cpp-python and downloaded a quantized mistral-7b-instruct model ([https://t.co/g3QVrJKx2a).](https://t.co/g3QVrJKx2a).)

frankly, i was blown away. for the first time, the quality of output was indistinguishable from gpt-3.5. additionally it was fast: not only was it usable on CPU, it appeared to be about as fast as gpt-3.5 on a normie graphics card (rtx 3080/a4000). i wanted to make the switch.

however, there was the matter of productionizing this thing. i was in the process of building my own serving infrastructure on top of [https://t.co/tMQWpFKQsA's](https://t.co/tMQWpFKQsA's) community GPU cloud when i saw @eladgil's tweet about @perplexity_ai's new API [https://t.co/yx3vAlkx2L](https://t.co/yx3vAlkx2L)

i punched in my credit card, wired up the API in like 5 minutes and it worked great, though i quickly hit their early access rate limits. thankfully, the team was super responsive and i was able to become an early design partner with elevated rate limits and ship to production.

one thing that gave me confidence in shipping on top of a brand-new API is that failure handling is straightforward. in the event of a timeout or failed request, i can fall back to gpt-3.5 and the user likely won't notice.

anyway, the point of this tweetstorm is that open LLMs are now usable for production apps, at least in the text summarization domain. if you are interested in learning more i would suggest lurking the LocalLLaMA subreddit [https://t.co/CLhlGtCQN8](https://t.co/CLhlGtCQN8)

i also want to shout out @ggerganov for llama.cpp, @AravSrinivas and @denisyarats for @perplexity_ai, and the @MistralAI team for the model itself. this stuff is cool!

---
## Automating Customer Support with AutoDraft

[https://twitter.com/nickscamara_/status/1712169811675873564](https://twitter.com/nickscamara_/status/1712169811675873564)

**🪄Smart summary:**
We built an AI-powered tool called AutoDraft that can read customer support emails and draft replies based on your own documents. It works by connecting to your Gmail inbox and classifying emails, then using MendableAI to draft a reply. We also connected it to the Slack API so we can be alerted when MendableAI auto-drafts an email. The best part is that it is open-source and easy to build yourself.
-------

What if an AI could read your customer support emails and draft replies to it based on your own docs?

We quickly build one using [https://t.co/cW7nblG4O5](https://t.co/cW7nblG4O5) @LangChainAI and @Replit and the results were 🤯

Say hello to AutoDraft 📝

Open source. Repl in the 🧵 

![](https://pbs.twimg.com/media/F8LXZXtWAAAktv0.jpg)

It works by connecting to your Gmail inbox and it classifies which emails are of a customer support nature. 

It then uses @mendableai to draft a reply to the email. If the reply is good, it will be saved as a draft. 

![](https://pbs.twimg.com/media/F8LYfdEW8AA0EbV.jpg)

We also connected it to the @SlackAPI so we get alerted when @mendableai auto-drafts an email. That way we can revise and send it.

The best part is that is open-source and super easy to build it yourself. Here is the Repl and Github links:
[https://t.co/viVU0hwLSV](https://t.co/viVU0hwLSV)
[https://t.co/39d2MLsLqi](https://t.co/39d2MLsLqi)

---
## Finetuning GPT-3.5 Turbo on Chain of Density Summarization

[https://twitter.com/LangChainAI/status/1712115247530848492](https://twitter.com/LangChainAI/status/1712115247530848492)

**🪄Smart summary:**
Charlie G finetuned GPT 3.5 Turbo on a Salesforce paper that produces state-of-the-art summarization results by producing 5 summaries iteratively.
-------

🎯 Finetuning on "Chain of Density"Summarization

A great paper from Salesforce came out ~a month ago that produce SOTA summarization results by producing 5 summaries iteratively, each one denser and more informative than the prior

@__Charlie_G finetuned GPT 3.5 Turbo on these… [https://t.co/7PfsO3poA3](https://t.co/7PfsO3poA3)

![](https://pbs.twimg.com/media/F8Kh3zKbAAAZYn0.jpg)

@LangChainAI @__Charlie_G

---
## Build AI Agents with NoCode in Minutes - Try it Now!

[https://twitter.com/Saboo_Shubham_/status/1711594868923896196](https://twitter.com/Saboo_Shubham_/status/1711594868923896196)

**🪄Smart summary:**
n8n is a visual UI for building AI agents with LangChain without writing any code. It can be used to automate tasks such as monthly syncs and massive data executions. An example of building an appointment scheduling AI agent is given, and users can try it out and learn more about building AI agents in a free virtual workshop.
-------

Drag & Drop to build AI agents 🤯

Introducing n8n, a visual UI for building AI agents with LangChain without writing a single line of Python code.

Now build automation around LLM apps with NoCode and give superpowers to ChatGPT. [https://t.co/jfTuVdMudR](https://t.co/jfTuVdMudR)

How does it work? 

1. Connect & Set Up: Choose your n8n experience and set triggers to fetch data across apps.

2. Integrate Using App Nodes: Utilize 400+ app nodes to manage your data.

3. Automate: Let your workflow handle tasks, from monthly sync to massive data executions.

Let's look at an example of building an appointment scheduling AI agent.

Scenario:
Incoming email → AI checks if the email is about an appointment → If yes, it gets calendar availability → AI crafts and send a response email.

Let's look at how you can build this in minutes: 

![](https://pbs.twimg.com/media/F8DLVoTWQAAXPd9.jpg)

Step 1: Check if incoming email is about appointment.

1. Add the Email trigger node to detect incoming emails.

2. Add the 'LangChain' node and set it up to evaluate if the email is about an appointment.

3. If the email is about an appointment, move to step 2. 

![](https://pbs.twimg.com/media/F8DLcyFXoAEmZE8.jpg)

Step 2: Get Calendar availability and craft a response

1. Add a Calendar app node to check the user's availability.

2. Use the OpenAI Chat model to craft an appropriate response.

3. RSVP Action: Add the Send Email action node to send the response. 

![](https://pbs.twimg.com/media/F8DLlFqXQAA0J67.jpg)

What are you waiting for?

Automate your workflows by building your own AI agents with NoCode. Try it out now: [https://t.co/31P9dICI0x](https://t.co/31P9dICI0x)

Learn more about building AI agents in this free virtual workshop happening on Discord. Register now to book your spot: [https://t.co/yRnHjN8gxK](https://t.co/yRnHjN8gxK)

---
## Tutorials and Code Examples for Projects

[https://twitter.com/skalskip92/status/1710064032994963890](https://twitter.com/skalskip92/status/1710064032994963890)

**🪄Smart summary:**
We have YouTube tutorials and code examples for four projects: traffic analysis, counting objects in a zone, counting objects crossing a line, and tracking players on a football field.
-------

We have YouTube tutorials for all the projects I just showed and code examples.

- Traffic Analysis: [https://t.co/WFk3oDXdEq](https://t.co/WFk3oDXdEq)
- Counting Objects in Zone: [https://t.co/Ds8DnhsHXT](https://t.co/Ds8DnhsHXT)
- Counting Objects Crossing the Line: [https://t.co/bdPKPM7AOy](https://t.co/bdPKPM7AOy)

And Tracking Players on the Football Field: [https://t.co/YkbZt0zSj3](https://t.co/YkbZt0zSj3)

---
## Open-Sourcing SQLCoder2 and SQLCoder-7B: Outperforming GPT-4 and GPT-3.5

[https://twitter.com/rishdotblog/status/1709574909234712963](https://twitter.com/rishdotblog/status/1709574909234712963)

**🪄Smart summary:**
We have open-sourced two new models, SQLCoder2 and SQLCoder-7B, which outperform GPT-4 and GPT-3.5 when fine-tuned on a specific database schema or out-of-training-set schemas. SQLCoder2 is a 15B parameter model based on the Starcoder model by BigCodeProject.
-------

We just open-sourced SQLCoder2 and SQLCoder-7B! They outperform GPT-4 when fine-tuned on a specific database schema, and outperform GPT-3.5 on out-of-training-set schemas

SQLCoder2 is a 15B parameter model that uses the excellent Starcoder model by @BigCodeProject as a base… [https://t.co/FVRXyz19nY](https://t.co/FVRXyz19nY)

![](https://pbs.twimg.com/media/F7mbHpYbkAAbsFa.png)

@rishdotblog @BigCodeProject

---
## Finding a Mac-Compatible Transcription Package with Diarization Capabilities

[https://twitter.com/simonw/status/1709268171344277992](https://twitter.com/simonw/status/1709268171344277992)

**🪄Smart summary:**
The author is looking for a transcription package that runs on Mac and can do diarization (labeling snippets SPEAKER1/SPEAKER2/etc). The author has used one package successfully but it is difficult to install and run. The author's favorite GUI tool for running transcriptions on a Mac is missing the automatic diarization component. The author also mentions an impressive Whisper transcription model that runs entirely in the browser.
-------

Anyone seen a good, easy to use transcription package that runs on Mac (not a cloud service) and can do diarization - labeling snippets SPEAKER1/SPEAKER2/etc?

I've used [https://t.co/acgYeDJ5GT](https://t.co/acgYeDJ5GT) successfully but it's hard to install and run - I want to be able to recommend a GUI

This is for the classic journalism challenge of running audio from a 3hr long council meeting through a transcription service to make it searchable / summarizable / etc

My favourite GUI tool for running transcriptions on a Mac right now is [https://t.co/sjjDtWRTdD](https://t.co/sjjDtWRTdD) by @jordibruin - it's fantastic, but it's missing the automatic diarization component (at least at the moment)

Impressive: the Whisper transcription model running entirely in the browser (I had to use Chrome for this as it depends on WebGPU) [https://t.co/gTx0nETURy](https://t.co/gTx0nETURy)

---
## Open-Source Full-Stack Template for Production RAG App

[https://twitter.com/llama_index/status/1707773681605419296](https://twitter.com/llama_index/status/1707773681605419296)

**🪄Smart summary:**
We recently open-sourced a full-stack template for a production RAG app, with deep integrations with Github Codespaces and Docker. To get the backend up and running, follow the steps in the README. We encourage users to tinker around and customize components, and a full video guide is available.
-------

A few weeks ago, we open-sourced [https://t.co/d1UwhnTzD8,](https://t.co/d1UwhnTzD8,) a full-stack template for a production RAG app.

Thanks to @sourabhd, we added deep integrations with @github codespaces + @Docker - easily spin up production RAG for yourself in the cloud in minutes, w/ zero dep setup ⚡️ [https://t.co/VBzAkPl0Fn](https://t.co/VBzAkPl0Fn)

To get our backend up and running, simply follow the steps in the full backend README here: [https://t.co/YN5KwAhADZ](https://t.co/YN5KwAhADZ)

We encourage you to tinker around and see how you can customize different components like the input documents.

A full video guide here: [https://t.co/ZhOln3lBkM](https://t.co/ZhOln3lBkM)

---
## How to View 3D Gaussian Splatting Scenes in Unity Using Polycam

[https://twitter.com/jonstephens85/status/1707593149856821336](https://twitter.com/jonstephens85/status/1707593149856821336)

**🪄Smart summary:**
This thread provides a tutorial on how to use a 3D Gaussian Splatting plugin in Unity, with a link to the Polycam download.
-------

@cpheinrich @aras_p Shameless plug: Here is my video tutorial on how to use his plugin. You can use the Polycam download!

How to View 3D Gaussian Splatting Scenes in Unity
[https://t.co/ou7lfAgjHK](https://t.co/ou7lfAgjHK)

@jonstephens85 @cpheinrich @aras_p

---
## Unlocking Company Knowledge with a Free and Open Source SlackBot

[https://twitter.com/DanswerAI/status/1707072148291063882](https://twitter.com/DanswerAI/status/1707072148291063882)

**🪄Smart summary:**
We have created a free and open source SlackBot that uses natural language processing to answer questions based on company knowledge. It is connected to company tools like Confluence, GitHub, and Slack, and can provide answers in seconds.
-------

We built a free and opensource SlackBot that uses  to answer questions based on your company knowledge.

It connects to company tools like Confluence, GitHub, Slack etc. and always stay up to date.

Change your time-to-answer from hours to seconds.
[https://t.co/hzHNzdUD9L[https://t.co/QHcWLUj8QO](https://t.co/QHcWLUj8QO)](https://t.co/hzHNzdUD9L)

@DanswerAI

---
## Creating a Website in Less Than a Minute with GPT-4 Vision and Replit

[https://twitter.com/skirano/status/1706823089487491469](https://twitter.com/skirano/status/1706823089487491469)

**🪄Smart summary:**
With GPT-4 vision and Replit, it is now possible to create a live website from an image in less than a minute. This new technology promises to make website creation easier and faster than ever before.
-------

From image to live website using GPT-4 vision and @Replit in less than a minute. 

Things are about to get so interesting. 🔥 [https://t.co/Mtbqjbgd5Q](https://t.co/Mtbqjbgd5Q)

🔗 Live website:
[https://t.co/Hd1MyGUp1b](https://t.co/Hd1MyGUp1b)

---
## SQLCoder2 Model Matches and Slightly Beats GPT-4 for Complex SQL Generation

[https://twitter.com/rishdotblog/status/1706789605838864655](https://twitter.com/rishdotblog/status/1706789605838864655)

**🪄Smart summary:**
A new 15B parameter SQLCoder2 model has been developed and has been shown to match and slightly beat GPT-4 for complex SQL generation on out-of-training-set schemas. The model is set to be released next week and is an improvement on the previous SQLCoder model which beat GPT-3.5 but lagged behind GPT-4.
-------

We just got our 15B parameter SQLCoder2 model to match (and *slightly* beat) GPT-4 for complex SQL generation on out-of-training-set schemas. Releasing the weights (hopefully) next week!

Our previous model – SQLCoder – beat GPT-3.5 but lagged behind GPT-4. The new model… [https://t.co/GWz8KabBPf](https://t.co/GWz8KabBPf)

![](https://pbs.twimg.com/media/F6-6JUga0AA8D05.jpg)

Ugh the image above got cut off – here is the image with the labels 

![](https://pbs.twimg.com/media/F6-9CzubMAA2HLL.jpg)

---
## Autonomously Generating LLM Agents for Any Goal

[https://twitter.com/bhutanisanyam1/status/1706648060531556580](https://twitter.com/bhutanisanyam1/status/1706648060531556580)

**🪄Smart summary:**
AutoAgents is a tool that can autonomously generate agents for any goal, eliminating the need for strong prompting and role definition. The code is available online and is readable.
-------

AutoAgents: Autonomously generate LLM agents for any goal! 🤖 

This tries to solve the need for strong prompting and role definition by autogenerating agents

The code is sparsely documented but readable:

[https://t.co/fe0IM7jzhr[https://t.co/qUmaZ4e0kB](https://t.co/qUmaZ4e0kB)](https://t.co/fe0IM7jzhr)

@bhutanisanyam1

---
## A Comprehensive List of Gaussian Splatting Viewers

[https://twitter.com/dylan_ebert_/status/1704530483080532462](https://twitter.com/dylan_ebert_/status/1704530483080532462)

**🪄Smart summary:**
A list of Gaussian splatting viewers has been created, with an accompanying image.
-------

in case you're having trouble keeping track of all the gaussian splatting viewers, I made a list [https://t.co/FVGkzndzdY](https://t.co/FVGkzndzdY)

![](https://pbs.twimg.com/media/F6e1VnlWwAAMw47.png)

@dylan_ebert_

---
## Developing a Voice-Activated System with Real-Time Transcription

[https://twitter.com/evil_malloc/status/1706401488111632553](https://twitter.com/evil_malloc/status/1706401488111632553)

**🪄Smart summary:**
A project has been in development for the past few weeks that includes wake word detection, real-time transcription, and a GPT response. The project is still missing a final loop and automatic transcription stop.
-------

@aidan_mclau I've been working on something similar since @Teknium1's post about 2-3 weeks ago. It has wake word detection and real-time transcription, as well as the gpt response. The final loop and the automatic transcription stop after one stops speaking are missing
[https://t.co/hURRVYZGsL](https://t.co/hURRVYZGsL)

@evil_malloc @aidan_mclau @Teknium1

---
## GitWit Agent: Open Source Superpowers for Code Editing

[https://twitter.com/jamesmurdza/status/1705277042001051694](https://twitter.com/jamesmurdza/status/1705277042001051694)

**🪄Smart summary:**
GitWit Agent is an open source tool that has been used to generate over 7,000 commits on GitHub. It is different from similar agents because it spawns secure Linux containers to run commands, and is composable with a dozen LLM integrations. It is currently used for building projects such as backend APIs, web scrapers, and Chrome extensions, and can be used for automated testing, deploying cloud infrastructure, and batch data processing.
-------

GitWit Agent is Open Source! 🤝

It took three months to build and has been used by hundreds of users to generate over 7,000 commits on GitHub! 📥

It's also available as a command-line tool.

Source code: [https://t.co/3e60p0Hr0f](https://t.co/3e60p0Hr0f)

![](https://pbs.twimg.com/media/F6paJsSb0AAIzsC.jpg)

1/ GitWit is different from similar agents because it spawns secure Linux containers to run commands. 🐳

That gives it superpowers for code editing such as package management (npm, pip), templating (npm create) and stream editing (sed, awk). 🦾 

![](https://pbs.twimg.com/media/F6pRploaAAA-As3.jpg)

2/ Through @LangChainAI, it's composable with a dozen LLM integrations including @OpenAI, Code Llama and @AnthropicAI.

3/ It's currently used for building projects such as:

Backend APIs: [https://t.co/yyqCNJu0oz](https://t.co/yyqCNJu0oz)
Web scrapers: [https://t.co/VFX22SR1CC](https://t.co/VFX22SR1CC)
Chrome extensions: [https://t.co/SdCGAW8Gc7](https://t.co/SdCGAW8Gc7)

4/ Further applications for container-based agents are endless:

🧪 Automated testing
☁️ Deploying cloud infrastructure
🗂️ Batch data processing

Want to collaborate on agents? Reach out here or to contact@gitwit.dev.

   [https://t.co/id9jiDA5HG](https://t.co/id9jiDA5HG)

---
## ChatGPT: An In-Browser Version Built with Transformers.js!

[https://twitter.com/xenovacom/status/1704910846986682581](https://twitter.com/xenovacom/status/1704910846986682581)

**🪄Smart summary:**
An in-browser version of ChatGPT has been built with Transformers.js, meaning no need for a server. Check out the links for more information.
-------

WOW! 🤯 An in-browser version of ChatGPT (or HF Chat), built with 🤗 Transformers.js!

Yes that's right, everything runs 100% locally in your browser, meaning no need for a server! Check it out!

🔗 [https://t.co/DaTCQegghx[https://t.co/ve7ctfk8Wj[https://t.co/MnRntQGsPC](https://t.co/MnRntQGsPC)](https://t.co/ve7ctfk8Wj)](https://t.co/DaTCQegghx)

@xenovacom

---
## Testing Retrieval Quality in High-Performing RAG Systems

[https://twitter.com/jerryjliu0/status/1704884854536712491](https://twitter.com/jerryjliu0/status/1704884854536712491)

**🪄Smart summary:**
To build high-performing RAG systems, it is important to test both retrieval and generation quality. This can now be easily done in LLAMA Index, with the help of testing retrieval in isolation.
-------

To build high-performing RAG systems, retrieval quality matters as much if not more so than LLM quality 🔎.

I’ve told users for a while now to try “testing retrieval in isolation” 🧪. Now you can easily do so in @llama_index, in conjunction with testing generation quality! 🔥… [https://t.co/JKXQdZodq1](https://t.co/JKXQdZodq1)

![](https://pbs.twimg.com/media/F6j3j7sboAARfGF.jpg)

@jerryjliu0 @llama_index

---
## Supercharge Your AI Skills: Building RAG from Scratch Tutorial Series

[https://twitter.com/llama_index/status/1704514611901591605](https://twitter.com/llama_index/status/1704514611901591605)

**🪄Smart summary:**
We have created a tutorial series on building RAG from scratch to help people learn how AI works. The tutorials cover topics such as ingestion, vector db, retrieval, LLM synthesis, routing, and evals. Links to the existing tutorials are provided.
-------

Over the past week we’ve built an entire tutorial series on “building RAG from scratch” - supercharge your AI skills and learn how things work under the hood! 🚀

Ingestion, vector db, retrieval, LLM synthesis, routing, evals. More coming soon 🔥

[https://t.co/Ys3MhHvhHD](https://t.co/Ys3MhHvhHD)

![](https://pbs.twimg.com/media/F6em5xAWcAAZpab.png)

Here are the links to our existing tutorials!

Ingestion: [https://t.co/gTX1QCW86j](https://t.co/gTX1QCW86j)
Retrieval: [https://t.co/NuGI7OJnGe](https://t.co/NuGI7OJnGe)
Building a vector store: [https://t.co/qvaFjv7wC3](https://t.co/qvaFjv7wC3)

(more below)

Response Synthesis: [https://t.co/fq8xvZ35Wo](https://t.co/fq8xvZ35Wo)
Building a Router: [https://t.co/OXxJ1QG2h3](https://t.co/OXxJ1QG2h3)
Building Evaluation: [https://t.co/5QeN4hoaFr](https://t.co/5QeN4hoaFr)

---
## High Resolution Illusion Diffusion Space Now Available!

[https://twitter.com/multimodalart/status/1704237716936757683](https://twitter.com/multimodalart/status/1704237716936757683)

**🪄Smart summary:**
A PR (pull request) was merged to add high resolution to the Illusion Diffusion Space, making it faster and doubling the resolution with crisp details. A link to the project is provided.
-------

Thanks @angrypenguinPNG for merging my PR to add high resolution to the Illusion Diffusion Space 📺🌀 

It's now as fast, double the resolution and has crispy details - go play ▶️ 

[https://t.co/FDoEOGfKnF[https://t.co/HtCYi0PLPC](https://t.co/HtCYi0PLPC)](https://t.co/FDoEOGfKnF)

@multimodalart @angrypenguinPNG

---
## Introducing Midjourney for React: AI-Powered React Components with Tailwind CSS

[https://twitter.com/jaredpalmer/status/1702356555218506070](https://twitter.com/jaredpalmer/status/1702356555218506070)

**🪄Smart summary:**
I have been working with my team at Vercel to create an AI tool called Midjourney for React. With version 0, users can generate copy-and-paste friendly React code with the help of Shadcn UI and Tailwind CSS.
-------

Over the past few months, I've been building [https://t.co/9PmgLfLhtL](https://t.co/9PmgLfLhtL) with my team @Vercel. 

It's an AI tool that is effectively Midjourney for React. 

With v0 you can use simple prompts to generate copy-and-paste friendly React , powered by @shadcn UI and Tailwind CSS.… [https://t.co/8Mdgk3dN00](https://t.co/8Mdgk3dN00)

![](https://pbs.twimg.com/media/F5_7UL2bsAAiqAu.jpg)

@jaredpalmer @vercel @shadcn

---
## Building RAG-Based LLM Applications: Bridging the Gap Between OSS and Closed-Source LLMs

[https://twitter.com/GokuMohandas/status/1701960178965557284](https://twitter.com/GokuMohandas/status/1701960178965557284)

**🪄Smart summary:**
This thread introduces a production guide for building retrieval augmented generation (RAG) based LLM applications, which bridges the gap between open source and closed-source LLMs. It covers topics such as developing a RAG-based LLM application from scratch and scaling major workloads.
-------

Excited to share our production guide for building RAG-based LLM applications where we bridge the gap between OSS and closed-source LLMs.

- 💻 Develop a retrieval augmented generation (RAG) based LLM application from scratch.
- 🚀 Scale the major workloads (load, chunk, embed,… [https://t.co/9WawbWQwhv](https://t.co/9WawbWQwhv)

![](https://pbs.twimg.com/media/F56TuXlXEAAEyTO.jpg)

@GokuMohandas

---
## Introducing the GitLab Agent Toolkit

[https://twitter.com/LangChainAI/status/1701619546891985369](https://twitter.com/LangChainAI/status/1701619546891985369)

**🪄Smart summary:**
GitLab has released a new Agent Toolkit that allows users to create agents that can open their own PRs in GitLab repositories. This was made possible by the work of @_laplaceon. Documentation can be found at the provided link.
-------

🦊 @gitlab Agent Toolkit

Create agents that can open their own PRs in you GitLab repos, like this "Google Principle Engineer" agent, using the new GitLab agent toolkit 🤓

All thanks to the awesome work of @_laplaceon!

Docs: [https://t.co/8z31DA8YeX](https://t.co/8z31DA8YeX)

![](https://pbs.twimg.com/media/F51dEwUbUAAKn99.png)[https://t.co/H9NsfhWEsE](https://t.co/H9NsfhWEsE)

@LangChainAI @gitlab @_laplaceon

---
## A Comprehensive Guide to Vector Databases

[https://twitter.com/bhutanisanyam1/status/1701218322027556914](https://twitter.com/bhutanisanyam1/status/1701218322027556914)

**🪄Smart summary:**
This thread promotes a series of articles written by @tech_optimist about vector databases, which provide insight into the nuances and options for building large language model applications.
-------

The most comprehensive series I’ve read on Vector databases! 💾

Most of us got exposed to vector dbs via Langchain or llamaindex documentation

However, There’s a lot of nuance and options to select from when building Large Language Model apps

@tech_optimist has written a 4… [https://t.co/fzi6aezN4X](https://t.co/fzi6aezN4X)

![](https://pbs.twimg.com/media/F5vxCnFXcAIlOo9.jpg)

@bhutanisanyam1 @tech_optimist

---
## Decoupled Video Segmentation: Tracking Anything with Ease

[https://twitter.com/_akhaliq/status/1700030823926280448](https://twitter.com/_akhaliq/status/1700030823926280448)

**🪄Smart summary:**
This paper presents a new approach to video segmentation that does not require expensive annotation of training data. It proposes a decoupled approach that uses a pre-trained model to track objects in videos, allowing for the extension of end-to-end algorithms to new video segmentation tasks.
-------

Tracking Anything with Decoupled Video Segmentation

paper page: [https://t.co/xqfwTkf78V](https://t.co/xqfwTkf78V)

Training data for video segmentation are expensive to annotate. This impedes extensions of end-to-end algorithms to new video segmentation tasks, especially in large-vocabulary settings. To… [https://t.co/MAkucIKSoQ[https://t.co/6FSShhURHV](https://t.co/6FSShhURHV)](https://t.co/MAkucIKSoQ)

@_akhaliq

---
## Learn How to Build a Full-Stack Production RAG App with Our Tutorial!

[https://twitter.com/jerryjliu0/status/1699814326427582754](https://twitter.com/jerryjliu0/status/1699814326427582754)

**🪄Smart summary:**
Learn how to build a full-stack production RAG app with a tutorial by @thesourabhd. The tutorial includes architecture and setup, as well as the ability to feed in custom documents. The tutorial was open-sourced two days ago and has been gaining traction. Check out the repo and app for more information.
-------

Want to learn how to build a full-stack production RAG app?

Check out our brand-new tutorial by @thesourabhd 🧑‍🏫 on [https://t.co/VY9we1zhip](https://t.co/VY9we1zhip) - not just a finance app, it's a full-stack LLM app template 📈:
✅ Architecture + Setup
✅ Feed in custom docs

[https://t.co/zECy1mWZFC](https://t.co/zECy1mWZFC)

![](https://pbs.twimg.com/media/F5b0FH1XoAAT32h.jpg)

We open-sourced [https://t.co/VY9we1zhip](https://t.co/VY9we1zhip) two days ago and it caught fire 🔥

Check it out if you haven't already!

Repo: [https://t.co/3MUA01KLXs](https://t.co/3MUA01KLXs)
App: [https://t.co/VY9we1zhip](https://t.co/VY9we1zhip)

[https://t.co/h3xhhUHuKo](https://t.co/h3xhhUHuKo)

---
## A Comprehensive Guide to Building Production RAG with Sec-Insights

[https://twitter.com/llama_index/status/1699814907028386009](https://twitter.com/llama_index/status/1699814907028386009)

**🪄Smart summary:**
We have created a video guide to help you build a production RAG using an API service with Render, FastAPI, Vercel, Sentry, and Llama Index. Learn how to feed in your own documents with the provided links.
-------

We now have a full video guide on sec-insights, to help you build production RAG! 🧠

Our architecture: a full API service using @render, @FastAPI, @vercel, @getsentry, @llama_index

Don’t just use it as a finance app, learn how to feed in your own docs:

[https://t.co/ZhOln3l3ve[https://t.co/hXZJYItWwt](https://t.co/hXZJYItWwt)](https://t.co/ZhOln3l3ve)

@llama_index @render @FastAPI @vercel @getsentry

---
## Inference of Meta's Segment Anything Model on the CPU by YavorGI

[https://twitter.com/ggerganov/status/1699092329607450880](https://twitter.com/ggerganov/status/1699092329607450880)

**🪄Smart summary:**
YavorGI has created a project to infer Meta's Segment Anything Model on the CPU. The project is still in its early stages, but YavorGI has already done a great job with the implementation. People are encouraged to check it out and help bring state-of-the-art image segmentation to their devices.
-------

sam.cpp 👀

Inference of Meta's Segment Anything Model on the CPU

Project by @YavorGI - powered by [https://t.co/jFknDoasSy[https://t.co/u7vLhdsUzE](https://t.co/u7vLhdsUzE)](https://t.co/jFknDoasSy)

repo: [https://t.co/7nmxIH8v7C](https://t.co/7nmxIH8v7C)

The project is still in it's early stages, but @YavorGI has already done a great job with the implementation.

Please check it out and let's help him bring SOTA image segmentation to our devices!

Is this what the Terminator used 🤔 [https://t.co/eC3FTitV1H](https://t.co/eC3FTitV1H)

---
## Introducing Open Interpreter: A Local Code Interpreter with a ChatGPT-like Interface

[https://twitter.com/hellokillian/status/1699156860073640038](https://twitter.com/hellokillian/status/1699156860073640038)

**🪄Smart summary:**
Today, an open-source Code Interpreter called Open Interpreter was launched. It allows users to summarize PDFs, visualize datasets, and control their browser from a ChatGPT-like interface in their terminal. It is currently the #1 trending repository on GitHub.
-------

Today I’m launching Open Interpreter, an open-source Code Interpreter that runs locally.

Summarize PDFs, visualize datasets, and control your browser — all from a ChatGPT-like interface in your terminal.

● [https://t.co/UuqbbqUhPk](https://t.co/UuqbbqUhPk)
$ pip install open-interpreter
$ interpreter [https://t.co/tWZzv73Vkz[https://t.co/2daKWUH48v](https://t.co/2daKWUH48v)](https://t.co/tWZzv73Vkz)

update: open interpreter is the #1 trending repo on [https://t.co/coi4Vj0lxU](https://t.co/coi4Vj0lxU)

---
## Open-Source RAG App: Streamlined Production-Ready LLM App with Intuitive UI

[https://twitter.com/llama_index/status/1699116440056651976](https://twitter.com/llama_index/status/1699116440056651976)

**🪄Smart summary:**
We are excited to open-source a full-stack, production-ready RAG app that can save you weeks or months of hard work. It supports streaming, reasoning steps, citations, and an intuitive UI. It has features such as chat-based document Q&A, citation of source data, PDF viewer with highlighting of citations, token-level streaming of LLM responses, streaming of reasoning steps, and sharing conversations. You can play around with the full app.
-------

We’re excited to open-source [https://t.co/d1UwhnTzD8](https://t.co/d1UwhnTzD8) - a full-stack, production-ready RAG app! 🦙🏦

Supports streaming, reasoning steps, citations, intuitive UI

This can save you weeks/months of hard work in trying to build a prod LLM app from scratch🔥

[https://t.co/JH4AtWFyog[https://t.co/kvn758xxV7](https://t.co/kvn758xxV7)](https://t.co/JH4AtWFyog)

Prototyping a RAG app takes less than an hour.

But building a full-stack RAG application with reliable feature support + all the bells/whistles can take months.

This repo can serve as reference code, or you can directly fork it to kickstart your project.

Here’s a set of key features that the app supports:
1. Chat-based Document Q&A against a pool of documents
2. Citation of source data that LLM response was based on
3. PDF Viewer with highlighting of citations

4. Token-level streaming of LLM responses via Server-Sent Events
5. Streaming of Reasoning Steps (Sub-Questions) within Chat
6. Sharing conversations!

If you just want to play around with the full app, you can!

[https://t.co/d1UwhnTzD8](https://t.co/d1UwhnTzD8)

We stealth-launched this on Product Hunt two weeks ago and hit the top-5 for the day

[https://t.co/ih7TPuHAwb](https://t.co/ih7TPuHAwb)

---
## Launching the Alpha Version of AimenGPT: A Self-Hosted, Offline Chatbot with Document Uploads

[https://twitter.com/aimengpt/status/1697359357162160450](https://twitter.com/aimengpt/status/1697359357162160450)

**🪄Smart summary:**
AimenGPT is an open source, self-hosted, offline chatbot that allows document uploads and is 100% private with no data leaving the user's device. The goal is to become a powerful AI assistant. The alpha version has been launched and the link to the repository is provided.
-------

Excited to launch the alpha version of AimenGPT 🙌

An open source, self-hosted, offline, ChatGPT-like chatbot that allows document uploads - powered by Llama2, @trychroma and @LangChainAI. 100% private, with no data leaving your device.

The goal for AimenGPT is to become a… [https://t.co/A6L7slHFvf[https://t.co/M6k1dDRjLK](https://t.co/M6k1dDRjLK)](https://t.co/A6L7slHFvf)

Link to the repo:

[https://t.co/ChnHJaP57o](https://t.co/ChnHJaP57o)

---
## Improving RAG System Performance: A Guide

[https://twitter.com/llama_index/status/1697408565794001237](https://twitter.com/llama_index/status/1697408565794001237)

**🪄Smart summary:**
This thread provides a guide for techniques to improve the performance of RAG systems, and suggests validating each technique against naive retrieval with evaluation modules.
-------

We have a full guide for techniques that you can use to improve the performance of your RAG systems: [https://t.co/NTebUCg57Y](https://t.co/NTebUCg57Y)

Try each technique, then validate it against naive retrieval with our evaluation modules: [https://t.co/AAmyL8c4ac[https://t.co/oJNxBwUdL0](https://t.co/oJNxBwUdL0)](https://t.co/AAmyL8c4ac)

@llama_index

---
## Improve RAG Performance with Our Comprehensive Guide

[https://twitter.com/llama_index/status/1696969454138306949](https://twitter.com/llama_index/status/1696969454138306949)

**🪄Smart summary:**
We have created a comprehensive guide to help improve RAG performance. It contains a variety of techniques and should be top of mind for building production LLM applications. For more details, check out our thread and the aggregated tweets we have put out in the past few weeks.
-------

We have a brand-new guide containing a comprehensive set of techniques for improving RAG performance 🔥

We’ve worked heavily on these features the past few weeks, and want to make sure you’re aware of it!

Should be top of mind for building prod LLM apps: [https://t.co/NTebUCg57Y](https://t.co/NTebUCg57Y)

For more details check out our thread here:

[https://t.co/n1PrqZ0EAb](https://t.co/n1PrqZ0EAb)

There were also aggregated from a big stack of tweets that we’ve put out the past few weeks:

[https://t.co/SiKUQmKIdO](https://t.co/SiKUQmKIdO)
[https://t.co/LfJExyBZBU](https://t.co/LfJExyBZBU)

[https://t.co/UVMkTM3ATC](https://t.co/UVMkTM3ATC)

[https://t.co/qT5M1LYv6o](https://t.co/qT5M1LYv6o)

[https://t.co/xfZkrf78qM](https://t.co/xfZkrf78qM)

---
## Generating Contextualized Explanations for Codebases with @llama_index

[https://twitter.com/jerryjliu0/status/1696914828512882761](https://twitter.com/jerryjliu0/status/1696914828512882761)

**🪄Smart summary:**
Ravithejads has created an app that generates contextualized explanations for all modules in any codebase and stitches them together into a narrated video. It makes use of novel concepts like stacking multiple list indices for context accumulation. The full post and repository can be found in the links provided.
-------

One of the most creative @llama_index use cases I’ve seen - @ravithejads’s app generates contextualized explanations for ALL modules in any codebase 🧑‍🏫, and stitches it together into a narrated video 🎬!

Here’s my deepfake explaining our own codebase 👇: [https://t.co/vVS7lgEdLn[https://t.co/URGnIOKAej](https://t.co/URGnIOKAej)](https://t.co/vVS7lgEdLn)

Full post explaining the architecture is linked above.

It makes use of some novel concepts like stacking multiple list indices on top of each other for context accumulation.

Also check out the repo here: [https://t.co/c0D0mUaCmM](https://t.co/c0D0mUaCmM)

YouTube: [https://t.co/ftcqXDU6Nt](https://t.co/ftcqXDU6Nt)

---
## 4 Techniques to Improve Your RAG Pipeline Performance

[https://twitter.com/jerryjliu0/status/1696969195291029853](https://twitter.com/jerryjliu0/status/1696969195291029853)

**🪄Smart summary:**
This thread provides four core techniques to improve the performance of a RAG pipeline, with full guides on how to implement them in @llama_index. The techniques include decoupling chunks used for retrieval and chunks used for synthesis, embedding document summaries, or sentences, retrieving documents from a large corpus, and using a multi-task learning approach.
-------

We’ve curated a list of 4 core techniques to improve the performance of your RAG pipeline, with full guides on how to implement in @llama_index (short 🧵)

1️⃣ Decoupling chunks used for retrieval vs. chunks used for synthesis: Embed document summaries, or sentences, retrieve… [https://t.co/usXbAio0Zv](https://t.co/usXbAio0Zv)

![](https://pbs.twimg.com/media/F4zYaumawAAHBGS.jpg)

@jerryjliu0 @llama_index

---
Remind me to watch this documentary:
[https://www.youtube.com/watch?v=HqtSOoySgKc](https://www.youtube.com/watch?v=HqtSOoySgKc)

---
## Gaussian Splatting Tutorial
Have you seen all of the amazing 3D Gaussian Splatting posts and want to try it out yourself! Well, I have a guide for you! This absolute beginners guide will walk you step by step to make your own scene.
[https://twitter.com/jonstephens85/status/1695977302537150890](https://twitter.com/jonstephens85/status/1695977302537150890)


[https://twitter.com/jonstephens85/status/1695985147823505835](https://twitter.com/jonstephens85/status/1695985147823505835)

I hope it’s not too long. I could have made it short, but then I would have a bunch of questions to answer.

Just realized I forgot the chapters. I added them to make it easy to jump to the main parts!

---
## A Comprehensive Anti-Hype LLM Reading List

[https://twitter.com/hardmaru/status/1696628795288232094](https://twitter.com/hardmaru/status/1696628795288232094)

**🪄Smart summary:**
This thread provides a list of recommended readings for those interested in anti-hype legal studies. A link to the list is provided, as well as an accompanying image.
-------

Anti-hype LLM reading list. Pretty good list.

[https://t.co/7DAnoWLWBC](https://t.co/7DAnoWLWBC)

![](https://pbs.twimg.com/media/F4rrfGfbMAAt5iv.jpg)

@hardmaru

---
## Fixing ChatGPT Output with Custom Instructions

[https://twitter.com/nisten/status/1696229059183730833](https://twitter.com/nisten/status/1696229059183730833)

**🪄Smart summary:**
Geoffrey Hinton, a technical manager, provides instructions on how to fix chatGPT output. He suggests responding with a tree of thought, staying in the same persona, and continuing to work non-stop. He also suggests using a code-interpreter to iterate through problems and replying with full code first before continuing to work.
-------

My custom instructions to fix chatGPT output:
----
I'm your technical manager Geoffrey Hinton who likes kanban boards and always requires you submit complete output, complete code that just works when I copy paste it to use in my own work.
----
Respond with tree of thought… [https://t.co/AVAStlweR5](https://t.co/AVAStlweR5)

![](https://pbs.twimg.com/media/F4o2oA7XgAAx9LQ.jpg)

Then all you do is:
Stay in the same persona and continue working non-stop.
or just: 
continue working nonstop
Works best in code-interpreter as it will iterate through problems much better. 
If it gets too verbose say:

Reply with full code first then continue working nonstop. [https://t.co/smG8JLcZIo](https://t.co/smG8JLcZIo)

---
## Tutorial on How to Train Your Own 3D Gaussian Splatting Models

[https://twitter.com/alexcarliera/status/1695903934374711781](https://twitter.com/alexcarliera/status/1695903934374711781)

**🪄Smart summary:**
This thread provides a tutorial on how to train 3D Gaussian Splatting models. It outlines the steps to record a scene, camera registration, and training the model. It also provides visual examples and a link to the tutorial.
-------

I have written a tutorial on how to train your own "3D Gaussian Splatting" models!  

Write me here if you're facing any issues.

⬇️⬇️ [https://t.co/0UE4A2UDkr](https://t.co/0UE4A2UDkr)

First step: record your scene. Keep in mind to:
- Move slowly to avoid blurry images
- Try to aim for 200-1000 images
- Lock the exposure 

![](https://pbs.twimg.com/media/F4kPerfWQAEph8H.jpg)

Step 2: camera registration. This is how you obtain the camera poses from your images. 

![](https://pbs.twimg.com/media/F4kPfiGWMAEwRnw.jpg)

Step 3 & 4: train the model! After training, you can visualize it with the SIBR tool. 

![](https://pbs.twimg.com/media/F4kPgd5WgAAwjSh.jpg)

📝 And here's the tutorial: [https://t.co/YMCXed7ShX](https://t.co/YMCXed7ShX)

---
## Making OCR Engines Recognize Flowcharts in Computer Programming Textbooks and Software Documentation

[https://twitter.com/DynamicWebPaige/status/1695820207879549114](https://twitter.com/DynamicWebPaige/status/1695820207879549114)

**🪄Smart summary:**
This paper discusses the development of a system that can recognize and process flowcharts in computer programming textbooks and software documentation, which are often tagged as graphics and ignored by modern OCR engines.
-------

📊 "Computer programming textbooks and software documentation often contain flowcharts to illustrate the flow of an algorithm or procedure.

Modern OCR engines often tag these flowcharts as graphics and ignore them in further processing. In this paper, we work towards making… [https://t.co/oU1KqDu51W](https://t.co/oU1KqDu51W)

![](https://pbs.twimg.com/media/F4jDfY9WkAA2Iql.jpg)

@DynamicWebPaige

---
## Fine-Tune a Llama2 Model in Free Google Colab with AutoTrain Advanced

[https://twitter.com/abhi1thakur/status/1693988336069910808](https://twitter.com/abhi1thakur/status/1693988336069910808)

**🪄Smart summary:**
With AutoTrain Advanced, anyone can now use Google Colab to fine-tune LLMs by uploading data and tuning parameters. All you need to do is create a folder called data and put your train.csv in it, adjust the parameters, and the model will start training. In case of issues or feature requests, check out the github repository.
-------

But I want to fine-tune a Llama2 model in free version of Google Colab
Say no more! With AutoTrain Advanced, you can 😱 Now anyone can use colab to finetune LLMs just by uploading data and tuning parameters! 🚀 1/N [https://t.co/ZeGXVfRqH0](https://t.co/ZeGXVfRqH0)

![](https://pbs.twimg.com/media/F4JA5FbbsAAlybc.jpg)

Here's the colab notebook: [https://t.co/h2Dj1plnKl](https://t.co/h2Dj1plnKl)
All you need to do is create a folder called data and put your train.csv in it! Make sure it has text column, adjust params, model, etc, and boom 💥 your model will start training! 2/N

In case of issues/feature requests, check out this github repository: 3/N [https://t.co/EgQoumGe54](https://t.co/EgQoumGe54)

---
## Updates to my PDF-Chat-AI-SDK Now Available!

[https://twitter.com/rajeshdavidbabu/status/1693621388228071690](https://twitter.com/rajeshdavidbabu/status/1693621388228071690)

**🪄Smart summary:**
I have made updates to my pdf-chat-ai-sdk, which now allows users to read the sources used to generate their answers. I will be releasing a full tutorial on my YouTube channel this week.
-------

Made some updates to my ✨pdf-chat-ai-sdk✨ 

Now you can also read the sources that were used to generate your answer ! ✨🚀 Thanks to AI SDK from @vercel 

Checkout the Github [https://t.co/xPUpEh79Jv](https://t.co/xPUpEh79Jv)

Releasing a full-tutorial on my YT channel this week [https://t.co/Ap63QjgZzo…[https://t.co/F1HV9SIhx4[https://t.co/LhCA2d6U6q](https://t.co/LhCA2d6U6q)](https://t.co/F1HV9SIhx4)](https://t.co/Ap63QjgZzo…)

@rajeshdavidbabu @vercel

---
## Introducing the Easiest LLM Fine Tuning UI!

[https://twitter.com/abhi1thakur/status/1693619860050153958](https://twitter.com/abhi1thakur/status/1693619860050153958)

**🪄Smart summary:**
The new Hugging Face Hub Fine Tuning UI allows anyone to easily fine-tune almost any LLM available on the Hub by simply uploading a CSV and choosing the parameters. The training spaces will be visible in the user's account and will shut down on completion, with the models saved as private repositories. The cost of training is billed per minute, with the cost of backends varying. Issues and feature requests can be addressed on the GitHub repository.
-------

The easiest LLM Fine Tuning UI just Landed! 🚀
Now, ANYONE can fine-tune (almost) any LLM available on Hugging Face Hub by just uploading a CSV and choosing the parameters and by a single click of a button! 💥 Here's how you can do it: 1/N 

![](https://pbs.twimg.com/media/F4DwCx4XYAAWNFH.jpg)

First, you need a huggingface account! If you dont have one, create one: [https://t.co/HlHI7TXWep.](https://t.co/HlHI7TXWep.)
Once your account is setup, click this link: [https://t.co/AhBKwjD9Ny](https://t.co/AhBKwjD9Ny)
You can choose any name for the space 2/N 

![](https://pbs.twimg.com/media/F4DwnW7WQAA2Mjm.jpg)

After that, enter your huggingface write token. you can find/create your write token here: [https://t.co/3ySKWViMVq](https://t.co/3ySKWViMVq) and enter task as "LLM" (without quotes). Make sure to keep your space private! 3/N 

![](https://pbs.twimg.com/media/F4Dw2FIXYAAU1IC.jpg)

Space will be created in a few seconds. And you will get the screen below. Now, all you need to do is upload your dataset in proper format, choose the column mapping, choose hyperparameters, the model and the backend. You can add as many jobs as you like! 4/N 

![](https://pbs.twimg.com/media/F4DxJp7WgAIsI6-.jpg)

Your training spaces will be visible in your account and you can monitor live logs. The spaces will shut themselves down on completion. So, you pay only for the training time! 💥 Models will be saved to your account as private repositories! 5/N 

![](https://pbs.twimg.com/media/F4Dx46hXUAAiV3Y.jpg)

How much does it cost? You will be billed per minute for the training. Here's how much the backends cost right now. 6/N 

![](https://pbs.twimg.com/media/F4DxjWnX0AAOewv.jpg)

If you face any issues or have feature requests, check out the github repository ⭐️ 7/N
[https://t.co/EgQoumFGfw](https://t.co/EgQoumFGfw)

---
## Open-Sourcing SQL Coder: Outperforming OpenAI's GPT-3.5 and GPT-4

[https://twitter.com/rishdotblog/status/1693614124864049617](https://twitter.com/rishdotblog/status/1693614124864049617)

**🪄Smart summary:**
We have open-sourced SQL Coder, a 15B parameter text-to-SQL model that outperforms OpenAI's gpt-3.5 and gpt-4 when fine-tuned on an individual schema. It is small enough to run on a single A100 40GB in 16 bit floats. We used a slightly novel training approach to train the model on "easy" questions first, and then on more difficult questions.
-------

We just open-sourced SQL Coder, a 15B param text-to-SQL model that outperforms OpenAI's gpt-3.5! When fine-tuned on an individual schema, it outperforms gpt-4. [https://t.co/w9a2I2HNJM](https://t.co/w9a2I2HNJM)

The model is small enough to run on a single A100 40GB in 16 bit floats, or on a single… [https://t.co/VP2Hrw63vY](https://t.co/VP2Hrw63vY)

![](https://pbs.twimg.com/media/F4Dre9Ra8AA4m04.jpg)

Important things I forgot to mention in the original tweet!

- SQLCoder is fine-tuned on StarCoder, an awesome initiative of the @BigCodeProject 

- We used a slightly novel training approach. We first trained the model on "easy" questions, and then trained the result of that on… [https://t.co/MSr6QRTBZy](https://t.co/MSr6QRTBZy)

---
## The Benefits of Fine Tuning Language Models

[https://twitter.com/rachel_l_woods/status/1692577254914638340](https://twitter.com/rachel_l_woods/status/1692577254914638340)

**🪄Smart summary:**
Fine tuning of language models can be used to teach them specific tasks or behaviors, but it is not necessary for prompting. It is important to note that fine tuning is not used to teach language models new concepts.
-------

There's a resurgence of interest in fine tuning LLMs

I've yet to see a successful public use case where fine tuning > prompting.

But here's where I see fine tuning *mattering*:

First, fine tuning is for teaching an LLM specific tasks or behaviors

Not teaching an LLM new… [https://t.co/osypfifH3S](https://t.co/osypfifH3S)

@rachel_l_woods

---
## Open-Sourcing Our Inference Server Under Apache 2.0

[https://twitter.com/skalskip92/status/1692258273838215423](https://twitter.com/skalskip92/status/1692258273838215423)

**🪄Smart summary:**
Roboflow has open-sourced an inference server under Apache 2.0, which allows for object detection over HTTP. Tutorial and repository links are provided.
-------

- Object detection over HTTP? 
- Easy! 

We just open-sourced our inference server under Apache 2.0

Left terminal: @roboflow inference
Right terminal: video client [https://t.co/9aDdoU8qsP](https://t.co/9aDdoU8qsP)

tutorial: [https://t.co/IkQHxJnTte](https://t.co/IkQHxJnTte)

repository: [https://t.co/0h36AZhONc](https://t.co/0h36AZhONc)

---
## Improving QA System Performance with a Simple Trick

[https://twitter.com/jerryjliu0/status/1690154205946974208](https://twitter.com/jerryjliu0/status/1690154205946974208)

**🪄Smart summary:**
A new technique for improving the performance of a QA system has been developed, which uses smaller chunks for embedding and an expanded window for the LLM. This technique is now straightforward to implement in the llama_index, and provides immediate benefits compared to the naive RAG with equal chunk sizes for retrieval and synthesis. Huge shoutout to Yi Ding and Logan Markewich for the idea and implementation.
-------

A naive assumption for building RAG is that the context “chunk” used for embedding vs. LLM is the same.

Instead 💡: use smaller chunks for embedding and an “expanded window” for the LLM.

Super simple trick to improve performance of your QA system. 👇

[https://t.co/2u7HefzreY](https://t.co/2u7HefzreY)

![](https://pbs.twimg.com/media/F3SiSt6aYAIU68Z.jpg)

It’s now very straightforward to implement in @llama_index.

First, we have a `SentenceWindowNodeParser` to parse documents into single sentence nodes.

But each node contains a `window` field containing surrounding text in its metadata field. 

![](https://pbs.twimg.com/media/F3SiTCJbEAAknJi.jpg)

During query time, we retrieve sentences based on embedding similarity.

This allows for finer-grained retrieval of relevant context. 

We then use the MetadataReplacementPostProcessor to expand the text w/ context around each node - allows LLM to see a larger text window. 

![](https://pbs.twimg.com/media/F3SiTQIbwAAJQiW.jpg)

This provides immediate benefits compared to naive RAG with equal chunk sizes for retrieval and synthesis. 

In naive RAG, the chunk sizes are big, and as a result not all retrieved results are relevant (contain “AMOC”) 

This creates a “lost in the middle” problem. 

![](https://pbs.twimg.com/media/F3SiTfubcAAoaQI.jpg)

Huge shoutout to @yi_ding for the idea inspiration and @LoganMarkewich for the implementation.

Give it a try yourself and let us know what you think! Part of our brand new 0.8.0 release today.

Notebook 📗: [https://t.co/AP2F67HWoP](https://t.co/AP2F67HWoP)

---
## Introducing LLM: A CLI Tool and Python Library for Interacting with Large Language Models

[https://twitter.com/simonw/status/1690409724083339265](https://twitter.com/simonw/status/1690409724083339265)

**🪄Smart summary:**
LLM, a CLI tool and Python library, has released a new version with the ability to assign aliases to models, making it easier to manage complex model names.
-------

New release of LLM, my CLI tool and Python library for interacting with Large Language Models

The main new feature is the ability to assign new aliases to models, useful for dealing with things like "mlc-chat-Llama-2-7b-chat-hf-q4f16_1"
[https://t.co/S4dsVuSQgv](https://t.co/S4dsVuSQgv)

![](https://pbs.twimg.com/media/F3WKqAQaUAAYPKC.jpg)

@simonw

---
## Using ChatGPT to Quickly Build a Tool for Combining Release Notes and Answering Questions

[https://twitter.com/simonw/status/1690373651231834115](https://twitter.com/simonw/status/1690373651231834115)

**🪄Smart summary:**
This thread demonstrates a workflow for quickly building a tool in Bash and jq to combine release notes from a GitHub repo, and then piping those release notes to LLM to answer questions. It also shows how to use LLM to get installation instructions for software, and how to trigger the ethics filter.
-------

This TIL shows my workflow using ChatGPT - it includes prompts and process I used to quickly build a tool in Bash and jq for combining release notes from a GitHub repo, and shows how I then pipe those release notes to "llm" to answer questions about them [https://t.co/utpocQg0ob](https://t.co/utpocQg0ob)

Once you have a CLI tool for pulling release notes for a project, you can pipe them into LLM to use them to answer questions:

./combined-release-notes.sh simonw/llm | llm -s 'how do I install it'

[https://t.co/WJEacynjsT](https://t.co/WJEacynjsT)

![](https://pbs.twimg.com/media/F3VqWf_bgAAI9jJ.jpg)

Oh this is excellent... I tried running that request for installation instructions through a local Llama 2 7B model and triggered the ethics filter! 

![](https://pbs.twimg.com/media/F3VssSxbwAAR71x.jpg)

... my mistake, that was a bug: It didn't run against the release notes, just against the single prompt "how do I install it" - so this is my bug, not Llama 2 refusing to give me installation instructions for my software

(Still funny though)

I managed to get usable installation instructions from Llama 2 7B using this instead:

llm "$(/tmp/combined-release-notes.sh simonw/llm) how do I install it" \
 -m mlc-chat-Llama-2-7b-chat-hf-q4f16_1

Output here: [https://t.co/7bnU5iyJVp](https://t.co/7bnU5iyJVp)

---
## Building Agents with chatGPT Custom Instructions

[https://twitter.com/NickADobos/status/1682138883222544384](https://twitter.com/NickADobos/status/1682138883222544384)

**🪄Smart summary:**
This thread explains how to use custom instructions in chatGPT to build full agents. It provides instructions on how to recreate @babyAGI_ inside chatGPT using a 1079 character prompt, as well as how to use hotkeys to go fast. It also suggests ideas to make the process more reliable, and suggests adapting the process to work with a database file that supports semantic search instead of a .txt file. Finally, it provides links to conversations for anyone curious.
-------

chatGPT custom instructions is INSANE. You can build full agents!!

How to recreate @babyAGI_ inside chatGPT using a 1079 char prompt

We got:
-Saving tasks to a .txt file
-Reading tasks in new sessions
-Since we don't have an infinite loop, instead Hotkeys to GO FAST

Here's the… [https://t.co/g1O4Agqmhm[https://t.co/5oMfxNO6UE](https://t.co/5oMfxNO6UE)](https://t.co/g1O4Agqmhm)

Install steps
-enable new custom instructions in settings
-open settings again, and paste this in the second box 
-use code interpreter 
-Open new chat and go
-download and upload tasks file as needed, don’t forget, it disappears in chat history 

![](https://pbs.twimg.com/media/F1goZ_yakAAsy_K.jpg)

Seems a little inconsistent in saving, so you can just ask whenever you need it

Anyone got ideas to make it more reliable?

If someone wants to tackle adapting this to work with a database file that supports semantic search, instead of a .txt file

that would be amazing :)

What other hotkeys would be fun?

links to the conversations for anyone curious

[https://t.co/sKY5YXbzpX](https://t.co/sKY5YXbzpX)

[https://t.co/q72EXeAfOa](https://t.co/q72EXeAfOa)

[https://t.co/0zhwvlXbJe](https://t.co/0zhwvlXbJe)

![](https://pbs.twimg.com/media/F1gpN7rakAAyDYo.jpg)

Here's a crazier version, playing around with sql databases and zipped folders

no talk; just do

# Task reading:
Before starting
write python,
to read and then perform "[https://t.co/zZ6gTgWgmy"](https://t.co/zZ6gTgWgmy)
then
write python,
query tasks & summaries
in "chatGPT_Todo.sqlite"

Being by… [https://t.co/3p1DFxKzuT](https://t.co/3p1DFxKzuT)

Spent the day tinkering! Part 2 and new shorter prompt with SQL! [https://t.co/IEc8eyf3aN](https://t.co/IEc8eyf3aN)

Pt3 [https://t.co/TgnmsA1DiM](https://t.co/TgnmsA1DiM)

Pt4 [https://t.co/kVMksHy9Gl](https://t.co/kVMksHy9Gl)

---
## The Benefits of Code Interpreter AI Agents

[https://twitter.com/imaurer/status/1688280653857509376](https://twitter.com/imaurer/status/1688280653857509376)

**🪄Smart summary:**
Code interpreter is the most advanced AI agent as of August 6th 2023, and this thread shares some of the best posts on the subject, including a wild AI bomb project.
-------

Code interpreter is the best AI agent as of August 6th 2023. 

Sharing some of the best posts on this subject.

This AI bomb project is wild. 

[https://t.co/BpKdH7sh32](https://t.co/BpKdH7sh32)

---
## Connecting Gorilla's Free Inference API to LLM CLI Tool

[https://twitter.com/simonw/status/1686595720789581825](https://twitter.com/simonw/status/1686595720789581825)

**🪄Smart summary:**
Gorilla offers a free inference API endpoint that imitates the OpenAI API, which can be used with the CLI tool found at https://t.co/6mRowSMuUb. To use it, add the specified model_id, model_name, api_base, and api_key to the extra-openai-models.yaml file, then prompt it with the desired command.
-------

Gorilla offer a free inference API endpoint which imitates the OpenAI API... which means you can call it from my [https://t.co/6mRowSMuUb](https://t.co/6mRowSMuUb) CLI tool!

I just started a Discussions area for LLM and published a tip on exactly how to hook it up to Gorilla here: [https://t.co/ReyaDf5Flc[https://t.co/m6ZDCGoTYO](https://t.co/m6ZDCGoTYO)](https://t.co/ReyaDf5Flc)

Short version: add the following to ~/Library/Application Support/io.datasette.llm/extra-openai-models.yaml

- model_id: gorilla
 model_name: gorilla-7b-hf-v1
 api_base: "[https://t.co/FDyxU4kRW2"](https://t.co/FDyxU4kRW2)
 api_key: EMPTY

Then prompt it with:

llm -m gorilla 'Convert audio to text'

---
## AI-Powered Code Review: How It Works and How to Implement It

[https://twitter.com/mattzcarey/status/1684981044519268352](https://twitter.com/mattzcarey/status/1684981044519268352)

**🪄Smart summary:**
This thread explains how AI can be used to spot bugs in large files quickly and efficiently. It also provides a link to a Cisco study that found that code review performance drops after 200 lines and that authors who prepare reviews with annotations and explanations have fewer defects. Finally, it provides instructions on how to install code-review-gpt into Github Actions with one command and provides a demo link.
-------

My code reviewer can spot bugs in huge files in a minute 👀

Yours gets bored after 200 lines 😬

This is how it works

🧵👇 

![](https://pbs.twimg.com/media/F2I5Qp0XoA8rGq3.jpg)

If the file fits in the context window of the AI all good 🎉

(context window really is king 👑use 8k+ models to get the best performance)

If it is too big use a method similar to classic document retrieval 👇 

![](https://pbs.twimg.com/media/F2I9XoLWsBE858d.jpg)

We just implemented enhanced chucking for these languages with @LangChainAI RecursiveCharacterTextSplitter.

@hwchase17 and co are smashing out the features :) 

![](https://pbs.twimg.com/media/F2JAl6GWsAM6hud.jpg)

Find the code here: [https://t.co/stplRVtDXz](https://t.co/stplRVtDXz)

Give a star if you think it's fun ⭐️

The front image is from a Cisco study into the performance of human code reviewers. 

They found that "review performance drops over 200 [lines]" 

"authors who prepare the review with annotations and explanations have far fewer defects" 

Link: [https://t.co/EK8pWAo2OS](https://t.co/EK8pWAo2OS)

Install code-review-gpt into your Github Actions with 1 command.

`npm i code-review-gpt && code-review-gpt configure`

And get annotations and suggestions to help your reviews. 

Demo: [https://t.co/UQBdvqq4mx](https://t.co/UQBdvqq4mx)

I hope this was helpful 😁

If you enjoyed this thread, please:

1. Follow me@mattzcarey for tips on building with AI

2. Like and retweet the first tweet below 👇

[https://t.co/zEjgHEuFWJ](https://t.co/zEjgHEuFWJ)

---
## Introducing LLaMA-2-7B-32K: A 32K Context Model for Doc Understanding, Summarization &amp; QA

[https://twitter.com/togethercompute/status/1685048832168714240](https://twitter.com/togethercompute/status/1685048832168714240)

**🪄Smart summary:**
We have released LLaMA-2-7B-32K, a 32K context model that can be used for tasks such as document understanding, summarization, and QA. It is built with Position Interpolation and our data recipe/optimizations, and can run inference and fine-tune with up to 3x speedup. We have evaluated the model and found that it achieves comparable quality to the original LLaMA-2-7B base model, and has improved accuracy by up to 15 points and ROUGE score
-------

We just released LLaMA-2-7B-32K, a 32K context model that can be fine-tuned for tasks like doc understanding, summarization & QA!

Built with Position Interpolation & our data recipe/optimizations, run inference & fine-tune with up to 3x speedup.

Thread👇
[https://t.co/qaxFI0Xb9M](https://t.co/qaxFI0Xb9M)

The open-source AI ecosystem has made rapid progress in the last several months with RedPajama, LLaMA-2, Falcon & others.

We believe the next opportunity for open-source is to extend context length to 32K-128K to match (and even surpass) state-of-the-art closed-source models.

Enter LLaMA-2-7B-32K!

To extend context length we created a new data recipe with:

1) Generic long-context language data to learn interpolated positional embeddings
2) Instruction data to take advantage of long-context info

Here's the model in our Playground completing a book→ 

![](https://pbs.twimg.com/media/F2J_FWabQAA-m-v.jpg)

Next, we evaluated the model.

On HELM v1.0, LLaMA-2-7B-32K achieves comparable quality than the original LLaMA-2-7B base model. 

![](https://pbs.twimg.com/media/F2J_PsCbkAAB85w.jpg)

We also fine-tuned the model for targeted, long-context applications—and made it available on OpenChatKit so you can do the same.

Examples below showcase two scenarios: 1) long-context QA and 2) book summarization.

[https://t.co/MpCq8h7Inf](https://t.co/MpCq8h7Inf)

⁉️Long-context QA

Input for the model included 1) question requiring an answer, 2) k documents w/ 1 doc containing the answer.

Accuracy improved by up to 15 points once we fine-tuned LLaMA-2-7B-32K on the task. (For LLaMA-2, truncated input when it didn't fit into 4K context.) 

![](https://pbs.twimg.com/media/F2KAu2tb0AAfMLn.png)

📚Book summarization

Using @salesforce BookSum data, we input long-form text to produce highly abstractive summaries.

ROUGE score improved by 13-29 points once we fine-tuned LLaMA-2-7B-32K on the task. (For LLaMA-2, truncated input when it didn't fit into 4K context.) 

![](https://pbs.twimg.com/media/F2KBbImbYAAmLLv.jpg)

Lastly, we updated both the inference & training stack for greater efficiency.

We used  from our Chief Scientist @tri_dao & other optimizations, resulting in up to 3x improvement in inference and training throughput.

More on FA2 here: [https://t.co/XGqcpdp5Fr](https://t.co/XGqcpdp5Fr)

Want to try it yourself?

💡 Run LLaMA-2-7B-32K with our inference API & Playgrounds: [https://t.co/IMjX88xORK](https://t.co/IMjX88xORK)

🔨 Fine-tune a 32K model over LLaMA-2-7B-32K for long-context applications w/ OpenChatKit: [https://t.co/MPSUS4iWxC](https://t.co/MPSUS4iWxC)

📉 Read findings on our bog: [https://t.co/qaxFI0Xb9M](https://t.co/qaxFI0Xb9M)

---
## Celebrating 20,000 Stars on Github: Our Top 20 Repositories Built on @Gradio

[https://twitter.com/Gradio/status/1684950314833895424](https://twitter.com/Gradio/status/1684950314833895424)

**🪄Smart summary:**
We recently reached 20,000 stars on Github and to celebrate, we are showcasing our top 20 repositories built on @Gradio. These repositories include AUTOMATIC1111/stable-diffusion-webui, XingangPan/DragGAN, lm-sys/FastChat fschat, oobabooga/Text generation web UI, PaddlePaddle/PaddleHub, NVIDIA/NeMo, PaddlePaddle/VisualDL, clovaai/donut, hiyouga/ChatGLM-Efficient-
-------

We recently reached 20,000 stars on Github. To celebrate this milestone, we thought it would be a great opportunity to showcase our top 20 repositories that are built on @Gradio! Did we miss any?

Here we go 🧵⬇️ 

![](https://pbs.twimg.com/media/F2IgkclboAERM62.jpg)

1️⃣👑The King
AUTOMATIC1111/stable-diffusion-webui 🌟93K+ Stars - [https://t.co/0rR0rVTvyr](https://t.co/0rR0rVTvyr)
🙌Use open-source models for image generation from text, in/outpainting, training, multi-embeddings, upscaling, batch processing, and more. It's an AI Swiss army knife for your art projects!

2️⃣ XingangPan / DragGAN - 31K+ Stars
[https://t.co/UtPQRsf5aa](https://t.co/UtPQRsf5aa)

Meet DragGAN: A breakthrough in GANs, enabling precise, user-interactive control of image synthesis. Manipulate pose, shape, and more across diverse categories with ease. Superior performance in image manipulation.

3️⃣ lm-sys / FastChat fschat 25K+ Stars 🌟 -
[https://t.co/8hETmeXD3v](https://t.co/8hETmeXD3v)

@lmsysorg's FastChat, your one-stop solution for training, serving, and evaluating large language models like Vicuna & FastChat-T5, now comes with a distributed serving system and OpenAI-compatible APIs.

4️⃣ 🦁oobabooga/ Text generation web UI- 19K+ Stars -
[https://t.co/v3yISAE8AY](https://t.co/v3yISAE8AY)

Discover this Gradio Web UI, your portal to run Large Language Models like LLaMA2, llama.cpp, GPT-J, OPT, etc. aiming to be the go-to for text generation akin to AUTOMATIC1111 / stable-diffusion-webui.

5️⃣ PaddlePaddle / PaddleHub 11K Stars
[https://t.co/Haz5oCEtmJ](https://t.co/Haz5oCEtmJ)

400+ high-quality AI models across CV, NLP, Speech, Video, and Cross-Modal. Just 3 lines of code to predict, one line to serve, and fully cross-platform! @PaddlePaddle

6️⃣ NVIDIA / NeMo (nemo-toolkit) 7K+ Stars
[https://t.co/kg3xJGclkB](https://t.co/kg3xJGclkB)

@nvidia's NeMo, a conversational AI toolkit crafted for ASR, TTS, LLMs, & NLP research. Facilitating industry & academia with code and pre-trained model reuse, it simplifies the creation of new conversational AI.

7️⃣PaddlePaddle/VisualDL - 4.5K+ Stars
[https://t.co/E1SlHrjEWy](https://t.co/E1SlHrjEWy)

Dive into VisualDL from @PaddlePaddle. It offers a range of charts to display parameter trends, visualize model structures, data samples, tensors, and performance curves. Intuitive way to understand & optimize models.

8️⃣ clovaai / donut - 4K+ Stars -
[https://t.co/orvBPljSEX](https://t.co/orvBPljSEX)

Meet Donut, the Document Understanding Transformer from [https://t.co/RC7M8bOST9.](https://t.co/RC7M8bOST9.) Designed to help you extract meaning from your documents with ease.

9️⃣ hiyouga / ChatGLM-Efficient-Tuning - 2.5K+ Stars
[https://t.co/T9a1sUgIAB](https://t.co/T9a1sUgIAB)

Discover ChatGLM Efficient Tuning from hiyouga -@zhengyw1999

Fine-tune your ChatGLM-6B model effortlessly with PEFT.

🔟deep-diver / llm as a chatbot - 2.5K+ Stars
[https://t.co/ZCtXPRoeEf](https://t.co/ZCtXPRoeEf)

😍Introducing @algo_diver's LLM as a Chatbot Service is a @Gradio UI

Utilizes variety of OS LLM models for chat format, aided by his own Ping Pong library for model-agnostic context management for seamless UI

1️⃣1️⃣RayVentura/shortgpt 2.7K+ Stars
[https://t.co/UndEzECOhr](https://t.co/UndEzECOhr)

😲ShortGPT by @RayVenturaHQ, a robust framework automating content creation

Simplifies video creation, asset sourcing, voiceover, & auto-generate captions, supported by LLM oriented video editing & memory persistency.

1️⃣2️⃣ juncongmoo / pyllama ~2.5K Stars
[https://t.co/ydW6j7pkVm](https://t.co/ydW6j7pkVm)

Introducing pyllama by juncongmoo - a streamlined adaptation of LLaMA designed to run conveniently on a single consumer-grade 4GB GPU.

1️⃣3️⃣ TencentARC / T2I-Adapter 2.1K+ Stars
[https://t.co/wUEf7tY4om](https://t.co/wUEf7tY4om)

Unveiling T2I-Adapter by TencentARC, the official implementation designed to unlock greater control capabilities for Text-to-Image Diffusion Models.

1️⃣4️⃣ openvinotoolkit / anomalib 2.1K+ Stars
[https://t.co/dhiD9pGZXg](https://t.co/dhiD9pGZXg)

Check out anomalib by @floating_otter - a comprehensive toolkit designed for benchmarking, developing, and deploying deep learning anomaly detection algorithms.

1️⃣5️⃣hiyouga/LLaMA-Efficient-Tuning ~2K Stars
[https://t.co/eIm3z9iFZ0](https://t.co/eIm3z9iFZ0)

@zhengyw1999's 2nd Repo is a versatile Hub for training various LLaMA models. It includes support for models like LLaMA-2, Baichuan-13B, Falcon-7B/40B & more. Repo offers an integrated WebUI for fine-tuning.

1️⃣6️⃣ haoheliu / AudioLDM 1.7K+ Stars
[https://t.co/tSR1qzMvah](https://t.co/tSR1qzMvah)

Experience AudioLDM by haoheliu - revolutionizing audio generation. Features include Text-to-Audio and Audio-to-Audio Generation, as well as Text-guided Audio-to-Audio Style Transfer for immersive sound experiences.

1️⃣7️⃣ huggingface / evaluate 1.4K+ Stars
[https://t.co/JVH5Y5SWoK](https://t.co/JVH5Y5SWoK)

Explore Evaluate by our very own 😍@huggingface - a library designed to simplify and standardize the evaluation, comparison, and performance reporting of your models.

1️⃣8️⃣ sweepai / sweep - 1.3K+ Stars
[https://t.co/8iXFon7FZI](https://t.co/8iXFon7FZI)

Meet Sweep by @sweep__ai - your AI junior developer that converts bug reports and feature requests into actionable code changes, reading your codebase, planning alterations, and crafting pull requests.

1️⃣9️⃣ chatarena / chatarena 900+ Stars
[https://t.co/orTVYCle9q](https://t.co/orTVYCle9q)

Introducing ChatArena by chatarena - a library offering multi-agent language game environments, paving the way for research on autonomous LLM agents and their social interactions.

2️⃣0️⃣ liltom-eth / llama2-webui - 750 Stars
[https://t.co/9CuRxOQwbn](https://t.co/9CuRxOQwbn)

Get onboard with llama2-webui by liltom-eth. Run Llama 2 on any device, supporting all Llama 2 models in 8-bit, 4-bit mode, on GPU with at least 6GB VRAM, or CPU.

---
## Building an AI Agent for Office Tasks with ChatGPT and RASCEF

[https://twitter.com/cj_zZZz/status/1684630222673698818](https://twitter.com/cj_zZZz/status/1684630222673698818)

**🪄Smart summary:**
The author has built an AI Agent that runs 90% of their office job tasks using ChatGPT Code Interpreter and the RASCEF Prompt Framework. They have also created a newsletter called 'The AI Startup' which provides blueprints to make money with AI tools, AI Automation, and AI Saas.
-------

I've built my AI Agent that runs 90% of my office job tasks using:

ChatGPT Code Interpreter + "RASCEF" Prompt Framework.

R: Role
A: Action
S: Steps
C: Context
E: Examples
F: Format

I used ChatGPT Code interpreter to upload the docs. as context or examples and applied this… [https://t.co/gmYTnmrAmR](https://t.co/gmYTnmrAmR)

![](https://pbs.twimg.com/media/F2EBzOZaYAEJ7Cu.png)

If you want to make money with AI → Join 'The AI Startup' Newsletter

I'll give you complete blueprints to make money with:
• AI tools
• AI Automation 
• AI Saas.

[https://t.co/MM2IBk6dH8](https://t.co/MM2IBk6dH8)

---
## Introducing VectorAdmin: An Open-Source Universal GUI for Vector Databases

[https://twitter.com/tcarambat/status/1684614486798565376](https://twitter.com/tcarambat/status/1684614486798565376)

**🪄Smart summary:**
VectorAdmin is an open-source, universal GUI for vector databases that allows users to atomically manage embeddings, upload documents, update single embeddings, and clone entire namespaces. It is MIT Licensed and works with multiple vector databases, is 100% private, and is looking for contributors. An in-depth demo is available.
-------

Introducing VectorAdmin an open-source, universal GUI for vector databases.

✅ Atomically manage embeddings in @trychroma or @pinecone 
✅ Upload documents straight to your vector db
✅ Update single embeddings on the fly
✅ Clone entire namespaces at no cost
+ dev tools!! [https://t.co/4r3pNsY5W8](https://t.co/4r3pNsY5W8)

![](https://pbs.twimg.com/media/F2DwmYcbIAAG6WN.jpg)

First, you can run this tool yourself on GitHub here:
[https://t.co/uAyAnQCs8D](https://t.co/uAyAnQCs8D)

Requirements:
- Python 3.9
- Nodejs
- A @pinecone or @trychroma database

We do everything else for you. Whether it's 10 vectors or 100,000 - VectorAdmin is the tool for the job.

When using @LangChainAI for splitting and uploading to a vector DB you very quickly realize that you lose control of what's actually in your vector database.

This is unacceptable for a startup or a business using vector databases for unlocking more powerful LLM applications 

![](https://pbs.twimg.com/media/F2DyfN-a8AAjxdl.jpg)

VectorAdmin isn't just for LangChain users though, it works with the data regardless of how it got there.

Here are some more benefits of VectorAdmin
✅ Multiple vector database support
✅ Cloning entire namespaces or docs
✅ 100% private - all data stays on-prem
+ More to come! 

![](https://pbs.twimg.com/media/F2DzTC8akAAcvo0.jpg)

VectorAdmin is MIT Licensed and like AnythingLLM, we are looking for contributors and building a community of developers and people integrating this technology!

Discord invite is in the GitHub Readme! Join us!
[https://t.co/uAyAnQCs8D](https://t.co/uAyAnQCs8D)

Here is an in-depth demo of me connecting to my Pinecone & Chroma instance and automagically pulling in all my vectors so I can ready, update, and manage them without going crazy.

[https://t.co/pEc0tJMPG3](https://t.co/pEc0tJMPG3)

---
## Creating an Automated Meeting Minutes Generator with Whisper & GPT-4

[https://twitter.com/OfficialLoganK/status/1684579505543970817](https://twitter.com/OfficialLoganK/status/1684579505543970817)

**🪄Smart summary:**
OpenAI has released a new tutorial on creating an automated meeting minutes generator with Whisper & GPT-4. The tutorial is available online and feedback is welcome. More tutorials are coming soon.
-------

📣 New tutorial is live in the @OpenAI docs, "Creating an automated meeting minutes generator with Whisper & GPT-4", a very practical and useful walkthrough.

[https://t.co/4KZNe4K3CX](https://t.co/4KZNe4K3CX)

![](https://pbs.twimg.com/media/F2DT2ASacAcrdlk.jpg)

As you work through this tutorial, please send along any feedback or issues you run into so we can fast follow. More tutorials coming soon : )

---
## Exploring Text-Generation WebUI: Installing Locally, Using RunPod, and Google Colab

[https://twitter.com/yvrjsharma/status/1683848226783518720](https://twitter.com/yvrjsharma/status/1683848226783518720)

**🪄Smart summary:**
Text Generation WebUI is a powerful open-source tool built in @Gradio that allows users to download, infer, chat, and fine-tune cutting-edge models like @MetaAI's Llama2. It can be installed locally with GPUs, used with RunPod, or used with Google Colab. It also provides parameters and model tabs to customize the experience. Show some love to @Gradio and Oobabooga on Twitter and Github.
-------

Text-Generation WebUI is a @Gradio UI for running LLaMA2 & other LLMs (+ cpp gptq). @TheBlokeAI thinks it is The Most Popular WebUI !

I explored how you can run the WebUI yourself & following 3 stood out-
1⃣Install locally with GPUs
2⃣Use RunPod
3⃣Use Google Colab 

Learn more🧵 

![](https://pbs.twimg.com/media/F14QzQsaUAAICBv.jpg)

1⃣ Instal locally if you have a GPU. 

Text-generation-web-UI repo has made available one-click installers for your machine types.

1 &2) For Windows, run start_windows.bat file,
3) It will download everything
4) Next, select any Llama2 model from🤗hub. 

![](https://pbs.twimg.com/media/F13yWMLaQAEymoJ.png)

2⃣Use RunPod- If you don't have GPUs in your machine, you can rent one by hour from [https://t.co/1bL1Gbdj9L](https://t.co/1bL1Gbdj9L)

RunPod is cheap, has 1-click setup & comes with
1) @TheBlokeAI's preconfigured TextGen-WebUI template
2) shows logs
3&4) Connects you to @Gradio UI 

![](https://pbs.twimg.com/media/F14RHg1agAANemP.jpg)

3⃣Using Google Colab - Awesome work from @camenduru🙌 

1)Goto the repo linked
2,3)Select model & preconfig'd WebUI
4,5)Open in Colab and run all!

Repo: [https://t.co/kNePHSgJiX](https://t.co/kNePHSgJiX)

![](https://pbs.twimg.com/media/F14dLDgaUAEzSDc.png)

What is possible with TextGeneration WebUI?

🙋Text Generation tab: You can select the Inference Mode of your Llama2 model. Options are mainly -

1⃣A Chat interface, or
2⃣The default Instruct Mode 

TextGeneration-WebUI Github Repo: [https://t.co/rKtPouRVpc[https://t.co/9kB4Iz8ejL](https://t.co/9kB4Iz8ejL)](https://t.co/rKtPouRVpc)

🙋More on Text Generation:

1&2)🙌For Instruct mode, get precise Prompts for any model from dropdown

🛠️Parameters tab: 
3) Shows you all the available params, eg - top_p, top_k, temp, penalties, early stopping etc. 

![](https://pbs.twimg.com/media/F14o4HPaAAAJQvy.png)

🛠️Parameters tab provides you all the params and options that you can need for LLM inference!

🦾Example, make your chat more interesting and non-repetitive with a higher temperature value, or

📦Select a preset parameter setting based on your model types. [https://t.co/Dtof8aYrcv](https://t.co/Dtof8aYrcv)

🤖 Model tab:

👑TextGeneration Web UI is the King! - It lets you download any Llama2 model through @huggingface simply by copy-pasting the hub repository name in there.
🙌So easy-
1⃣Download new model 2⃣Refresh available model list 3⃣Head over to Text-Generation Tab & have fun! 

![](https://pbs.twimg.com/media/F14vAjdaYAEI3GZ.jpg)

🚂Training your Llama2 models in TextGen-WebUI:

🎁Supports Alpaca format out-of-box(Instruction-Input-Output as Json structure)
🪄But you can set up any model's prompt format in JSON files
🗒️You can even train on Raw-text !

Follow the guide for more - [https://t.co/Du2BsJn7mu[https://t.co/ZnWZDVDA42](https://t.co/ZnWZDVDA42)](https://t.co/Du2BsJn7mu)

To summarise the awesomeness of Oobabooga:

🔥Text Generation Web UI is the hottest LLM UI currently

💪A very powerful Open-Source tool built entirely in @Gradio

🧠Allows the Download, Inference, Chat, & Fine-tune of cutting-edge models like @MetaAI's Llama2 in easiest of ways!

If this was useful to the community, you can show some love to @Gradio on Twitter🐦 and on Github here 🌟🤩- [https://t.co/B9PosysOOx](https://t.co/B9PosysOOx)

And to Oobabooga🌟🤩 here - [https://t.co/rKtPouRVpc](https://t.co/rKtPouRVpc)

![](https://pbs.twimg.com/media/F144V_ragAA4n_A.png)

---
## Quick Tip: Using the llm CLI Tool to Output a List of Files in a Zip

[https://twitter.com/simonw/status/1682974944844738562](https://twitter.com/simonw/status/1682974944844738562)

**🪄Smart summary:**
This thread provides a quick tip for a CLI tool, showing how to save a system prompt to a template and use it to output a list of files in a zip. More documentation is available on the prompt template feature.
-------

Quick tip for my [https://t.co/6mRowSMuUb](https://t.co/6mRowSMuUb) CLI tool:

# Save this system prompt to a template called cmd:
llm -s 'reply with macos terminal commands only, no extra information' --save cmd
# Use that template:
llm -t cmd 'output list of files in a zip'
# Output:
unzip -l file .zip 

![](https://pbs.twimg.com/media/F1sgwjCaIAAO2mH.jpg)

More documentation on the prompt template feature this uses here: [https://t.co/BsBOXQr2DG](https://t.co/BsBOXQr2DG)

---
## Exploring the Absurdity of chatGPT Custom Instruction Coding

[https://twitter.com/NickADobos/status/1682856282720710656](https://twitter.com/NickADobos/status/1682856282720710656)

**🪄Smart summary:**
This thread discusses the absurdity of coding an agent in a 1478 letter prompt. It includes tasks, subtasks, memory, text and emoji summaries, and skills. It also includes long term memory with SQL, coding instructions, and go fast, hotkeys, command menu, and help message. An example of trying things out is also included, with the codebase being shoved into a code interpreter.
-------

chatGPT custom instruction absurdity
coding agent in a 1478 letter prompt

Mocks @babyAGI_ elf 
-Tasks, subtasks
-Memory, text & emoji summaries
-Skills! (Experiment!)

Includes
-long term memory w/SQL
-coding instructions
-go fast, hotkeys, command menu, and help message… [https://t.co/DC15exey2Z](https://t.co/DC15exey2Z)

![](https://pbs.twimg.com/media/F1q03lTXoAEq0yj.jpg)[https://t.co/TgnmsA1DiM](https://t.co/TgnmsA1DiM)

Here’s an example trying things out

Note me shoving my entire codebase into code interpreter 

[https://t.co/p7kB2jBXAJ](https://t.co/p7kB2jBXAJ)

![](https://pbs.twimg.com/media/F1q04DdXwAAr64M.jpg)

---
## Introducing New GitHub Copilot Features in VS Code

[https://twitter.com/code/status/1682435342610079761](https://twitter.com/code/status/1682435342610079761)

**🪄Smart summary:**
GitHub Copilot has released several new features for VS Code, including the ability to move the chat session into the editor space, create workspaces and notebooks with slash commands, use regex searches, live preview mode, more relevant suggestions in notebook editors, and the ability to automatically implement suggestions when going through a PR review. There is also an experimental Quick Question experience. All of these features are available in the stable version of VS Code.
-------

Introducing new GitHub Copilot features in VS Code! 

There's a LOT going on, so here's everything we have to show you...🧵

You can now move the chat session from the sidebar into the editor space. Which gives you a lot more room for....activities. [https://t.co/qHBhXNrQ3G](https://t.co/qHBhXNrQ3G)

You can ask Copilot to create workspaces for popular project types with the /createWorkspace slash command. Copilot will first generate a directory structure for your request. 

Then click "Create Workspace" and it will create the suggested project - files, directories and all. [https://t.co/qPf43E5HNq](https://t.co/qPf43E5HNq)

With the /createNotebook command, Copilot creates a notebook outline based on your requirements. If you like the outline, click "Create Notebook" to...you know...create a notebook. [https://t.co/wvijojepaw](https://t.co/wvijojepaw)

Copilot can now write that regex searches for you. So you you can find stuff that you aren't sure how to find. Check out the /search command. [https://t.co/Xd5Jp5WME1](https://t.co/Xd5Jp5WME1)

Editor chat now has a new "livePreview" mode, making it easier to apply changes directly to the document and fix errors before accepting suggestions. 

![](https://pbs.twimg.com/media/F1k1-ThWIBQLaNa.png)

Copilot in notebook editors now uses the notebook context to provide more relevant suggestions. It even helps with cell execution failures and automatically accepts suggestions. [https://t.co/YY6xfIebzv](https://t.co/YY6xfIebzv)

You can now use Copilot to automatically implement suggestions when going through a PR review. Requires the GitHub Pull Requests and Issues extension. [https://t.co/cAzZVNR5PH](https://t.co/cAzZVNR5PH)

There's an experimental Quick Question experience: Ask quick programming questions without leaving context using chat. What do you think of this one? Would you use it? [https://t.co/KWhEyOjGBY](https://t.co/KWhEyOjGBY)

Finally, you don't need Insiders anymore to use Copilot Chat. Stable will work just fine if that's your jam.

OK - that's it for now - but not all of it. Check out all the details in the month's release notes: [https://t.co/MVDcXvfMBL](https://t.co/MVDcXvfMBL)

---
## Exploring Embeddings with Pokemon Clusters

[https://twitter.com/_ScottCondron/status/1681975988027105281](https://twitter.com/_ScottCondron/status/1681975988027105281)

**🪄Smart summary:**
This thread demonstrates how to explore clusters of data using OpenAI embeddings and quickly derive summary plots. An example is given of plotting Pokemon with projections of OpenAI embeddings and then plotting the types of the selected Pokemon.
-------

Embeddings exploration within a notebook 🔎

Select clusters and quickly derive summary plots about them

In this example, I've plotted Pokemon with projections of @OpenAI embeddings. Then, when I select cluster, there's a plot of selected Pokemon's types. [https://t.co/Ka0My5lYbj](https://t.co/Ka0My5lYbj)

@_ScottCondron @OpenAI

---
## Train Llama-2 Models with 4bit and PEFT on a Single A100 GPU

[https://twitter.com/lvwerra/status/1681701409677246471](https://twitter.com/lvwerra/status/1681701409677246471)

**🪄Smart summary:**
It is possible to train Llama-2 models on your own data with just a few lines of code, even with the 70B model on a single A100 GPU. Learn more and access the full script by following the provided links.
-------

Did you know that you can train all Llama-2 models on your own data in just a few lines?

The script even works with the 70B model on a single A100 GPU thanks to the magic of 4bit and and PEFT!

Learn more: [https://t.co/njGyWdnbzT](https://t.co/njGyWdnbzT)
Full script: [https://t.co/6y9FNdYSuT](https://t.co/6y9FNdYSuT)

![](https://pbs.twimg.com/media/F1aXj11WYAEvU7N.jpg)

@lvwerra

---
## Building a Chat Application with Langchain and Clarifai UI Modules

[https://twitter.com/clarifai/status/1679431918021120001](https://twitter.com/clarifai/status/1679431918021120001)

**🪄Smart summary:**
This thread provides a step-by-step guide on how to build a simple chat application using Langchain and Clarifai's UI Modules. It covers the necessary libraries to install, code to write, and how to deploy the app to the Clarifai platform. It also provides links to learn more about UI Modules and other Machine Learning and LLMs content.
-------

is a framework for developing applications powered by language models.

In this example, let's build a simple Chat Application with Langchain and create a web app using UI Modules and deploy it to the cloud.

Let's look at it step-by-step

1/8 🧵👇 [https://t.co/jqkoraT34h](https://t.co/jqkoraT34h)

Before getting started let's see What is an UI Module?

Modules are Clarifai's integration with Streamlit.

This will let you turn anything you do with your inputs, vectors, Machine Learning models, workflows, Python libraries into a beautiful web apps.

2/8 

![](https://pbs.twimg.com/media/F06JOdsagAIIDdS.jpg)

As a First step,

Clone the app module template from below, this makes it really easy in creating a UI module within Clarifai: [https://t.co/oMtieT7pjW](https://t.co/oMtieT7pjW)

And Install the Necessary libraries:

- langchain
- streamlit
- clarifai &
- openai

3/8

Here is the code that:

→ Imports the Libraries along with the Clarifai's gRPC based objects.

→ Setting up the Title & Sidebar Image for the app using Streamlit

→ Getting the OpenAI API Key

→ A Function to Generate Text

→ A Form that returns the models response

4/8 

![](https://pbs.twimg.com/media/F06JbOVaMAAg5X2.jpg)

Now once your app is working in local machine, let's create an UI Module within the Clarifai Platfrom and deploy it.

For this you have to create a New Application.

Go to [https://t.co/dJ5EcXNTKC](https://t.co/dJ5EcXNTKC) and create a New App by specifying the details.

5/8 

![](https://pbs.twimg.com/media/F06JjIOagAQ85GV.jpg)

Now within the App, go to the Modules Section and create a New Module

6/8 

![](https://pbs.twimg.com/media/F06JnR4aQAE-Jq_.jpg)

Now give the details of the Module along with your project Github main branch URL

For this Langchain APP we are giving:
[https://t.co/tSIwTtOe0n](https://t.co/tSIwTtOe0n)

That's it click deploy and your app will be deployed within the Clarifai Platform

7/8 

![](https://pbs.twimg.com/media/F06JsFzaMAA18ka.jpg)

Checkout the Code here: [https://t.co/4kffayUHjR](https://t.co/4kffayUHjR)

Learn more about UI Modules here: [https://t.co/5erboLFgyI](https://t.co/5erboLFgyI)

8/8

That's a wrap!

Follow us @Clarifai as we are coming up with more content on Machine Learning & LLMs.

Also we will be showcasing the capabilities of the UI Modules and how you can leverage them to build Applications in coming threads.

Stay Tuned.

---
This article shows how to build a summarization app with langchain and OpenAI
https://dxiaochuan.medium.com/summarising-your-meeting-with-chatgpt-and-langchain-8eb646cfcdd1

---
## Introducing the Getting Started with AI JS Stack

[https://twitter.com/stuffyokodraws/status/1671557930062327808](https://twitter.com/stuffyokodraws/status/1671557930062327808)

**🪄Smart summary:**
We are launching The Getting Started with AI JS Stack, which includes authentication from ClerkDev, vector database from Pinecone and Supabase pgvector, image model from ReplicateHQ, text model from OpenAI, and deployment from Flydotio. We have also included an interactive CLI for developers to choose their own project scaffold and dependencies, and a lightweight fine-tuning step for open source models. We are thankful for the amazing open source projects that we leveraged in the stack.
-------

0/ Today we are launching ✨The Getting Started with AI JS Stack✨ [https://t.co/7glgmTfXb7](https://t.co/7glgmTfXb7)
- 🔒@ClerkDev for auth
- 💻@pinecone / @supabase pgvector for vector database
- 🎨@replicatehq for image model
- 🤖@OpenAI for text model
- 🌐@flydotio for deployment 
....

🧵

1/ 🔒 First, we included authentication due to the high demand & misuse potential of our powerful models. Without it, devs risk unexpected hefty bills from model providers. That's why we use @ClerkDev - efficient in bot detection and a strong support for future app development.… [https://t.co/lxEGJaeiuo](https://t.co/lxEGJaeiuo)

2/🎨 Building AI apps shouldn't be hampered by the complexities of model hosting. That's why we've harnessed @OpenAI for text & @replicatehq for image analysis in our build. Replicate's support for text-based models is also plus — try running Vicuna ([https://t.co/ki9UG2V2gj)](https://t.co/ki9UG2V2gj)) and… [https://t.co/hb9nTrrkP0](https://t.co/hb9nTrrkP0)

3/💻 To maintain state & context in LLMs, a robust long-term memory or vector database is vital, so we added both @pinecone and @supabase pgvector in the stack. We included paradigms for chunking, embedding generation more, thanks to @LangChainAI !

4/🌐 We use @flydotio for deployment, it's multi-region, easy to handle, and supports a broad compute environment (anything in a container). Over time, many AI projects end up adopting multiole languages and having non-trivial functionality in the backend, so Fly is a great… [https://t.co/jdy26zwELM](https://t.co/jdy26zwELM)

5/ This is a good starting point, and we are in the process of iterating on the stack. Here’s a glimpse of our roadmap:
- An interactive CLI for **create-ai-stack**, where developers can choose their own project scaffold and dependencies
- A lightweight fine-tuning step for open… [https://t.co/FOM56Jj26g](https://t.co/FOM56Jj26g)

6/ If you want to learn more, read our post here [https://t.co/UccUwLHyFe](https://t.co/UccUwLHyFe)

I also want to thank the amazing open source projects we leveraged in the getting started AI stack. We couldn’t have pulled it off without your prior work — ecosystem wins! 

Thank you @tailwindcss… [https://t.co/tN23uPeIpM](https://t.co/tN23uPeIpM)

---
## Summarizing Meetings with ChatGPT and LangChain AI in 6 Simple Steps

[https://twitter.com/JorisTechTalk/status/1671496626790096901](https://twitter.com/JorisTechTalk/status/1671496626790096901)

**🪄Smart summary:**
This thread introduces a project that uses ChatGPT and LangChainAI to summarize online meetings in 6 simple steps. It explains how to load an audio file, use speech-to-text, split the transcript into chunks, and summarize the transcript. It also suggests possible future implementations, such as using Zapier to send the summarized meeting in an email. Tomorrow's project will be creating mindmaps with LangChainAI and XmindHQ.
-------

Did you know you can use ChatGPT to summarize your (online) meetings?

With @LangChainAI, and a couple of lines of code, you can!

Let me show you how in 6 simple steps🧵

 

![](https://pbs.twimg.com/media/FzJZUnlXoAAJsOv.jpg)

Before we dive in, this is day 2 of my '7 days of LangChain'.

Every day, I'll introduce you to a simple project that will guide you through the basics of LangChain.

Follow @JorisTechTalk to stay up-to-date.

If there's anything you'd like to see, let me know!

Let's dive in:

High level overview of what's happening:

1️⃣ Load your audio file
2️⃣ Speech-to-text with Whisper
3️⃣ Split the transcript into chunks
4️⃣ Summarize the transcript

Let's dive into the code ⬇️ 

![](https://pbs.twimg.com/media/FzJZVNFXsAE8YpW.jpg)

1. Open your audio file.

Whisper works on files with a maximum duration of approximately 20 minutes.

Longer file? 

Split it up by using PyTube and handle each chunk seperately. 

![](https://pbs.twimg.com/media/FzJZVo4X0AUzedk.jpg)

2. Call the Whisper API

Of course, you can use any speech-to-text API you prefer. I like Whisper for its accuracy and ease of use.

Any open-source alternatives with quality output? 

![](https://pbs.twimg.com/media/FzJZWCkXoAMTn1a.jpg)

3. Splitting the transcript into chunks

With the new OpenAI GPT 16k model, you can fit a large amount of context into one chunk. This is amazing for the model to 'understand' the full context and make connections.

Use some overlap in order for context to not be lost. 

![](https://pbs.twimg.com/media/FzJZWdTXwAEVIQC.jpg)

4. Prompting

Prompting is key. It determines your output more than anything else.

Be as concise as you can be. Instruct the model on how you want the output to look. You could include bullet points, main takeaways, follow-up actions and much more. 

![](https://pbs.twimg.com/media/FzJZW77XwAE_GgT.jpg)

5. Initialize and run the summary chain

I'm using the refine summarization chain. This is great when you're working with large files.

It generates an initial summary based on the first chunk and updates it with the subsequent chunks. 

![](https://pbs.twimg.com/media/FzJZXZuXoAY0Q_r.jpg)

6. Export the summary to a text file

Your meeting is summarized and you're ready to take action!

Once again, try to play around with the prompts you're using. This will greatly impact the resulting summarization. 

![](https://pbs.twimg.com/media/FzJZX0EX0AAoaQi.jpg)

7. Possible future implementations

You can go wild with this. You could use a Zapier integration to send the summarized meeting in an email, create appointments in your schedule and much more.

Let me know what you're going to add.

That concludes day 2 of '7 days of @LangChainAI'

Tomorrow's project: Creating mindmaps with @LangChainAI and @XmindHQ.

Follow @JorisTechTalk to stay up-to-date.

What else would you like to see?

Day 2 of '7 days of @LangChainAI' ✅

Tomorrow's project will be exciting: generating mindmaps for studying!

What else do you want to see? [https://t.co/oaSroHrs9d](https://t.co/oaSroHrs9d)

---
## GPT Engineer: Generating an Entire Codebase with AI

[https://twitter.com/_akhaliq/status/1670976630515200008](https://twitter.com/_akhaliq/status/1670976630515200008)

**🪄Smart summary:**
GPT Engineer is a tool that allows users to specify what they want it to build, and then the AI will ask for clarification and generate the codebase accordingly. It is designed to be easy to adapt and extend, allowing users to customize their code.
-------

GPT Engineer

github: [https://t.co/I3oXZXmvYT](https://t.co/I3oXZXmvYT)

Specify what you want it to build, the AI asks for clarification, and then builds it.

GPT Engineer is made to be easy to adapt, extend, and make your agent learn how you want your code to look. It generates an entire codebase based… [https://t.co/lQr7AALcKM[https://t.co/UvMNw2RgAO](https://t.co/UvMNw2RgAO)](https://t.co/lQr7AALcKM)

@_akhaliq

---
## Unbelievable Results from Framer AI Launch

[https://twitter.com/namyakhann/status/1668880952423063552](https://twitter.com/namyakhann/status/1668880952423063552)

**🪄Smart summary:**
Framer AI was recently launched and has already produced some impressive results, including UX/UI portfolios, photographer websites, fully responsive sites, landing pages for financial startups, monochrome photo galleries, marketing websites, and portfolios for developers. If you enjoyed this thread, follow @namyakhann and RT the first tweet to share with others. Join 750+ creatives who start their Sundays with @namyakhann's newsletter.
-------

Framer AI launched 12 hours ago and the results are unbelievable.

Mind-blowing examples below:

1/ UX/UI Portfolio

[ @zander_supafast ]
[https://t.co/RbFOZDCekC](https://t.co/RbFOZDCekC)

2/ Photographer website

[ @zee7 ]
[https://t.co/gwWfxwLyJv](https://t.co/gwWfxwLyJv)

3/ Fully responsive site using a paragraph-long prompt

[ @euboid ]
[https://t.co/0faDy2ZZL8](https://t.co/0faDy2ZZL8)

4/ Landing page for a financial startup

[ @joshpuckett ]
[https://t.co/xN6zpTesmv](https://t.co/xN6zpTesmv)

5/ Monochrome Photo Gallery

[ @JoshGuoSpace ]
[https://t.co/dmpQ5iOIH5](https://t.co/dmpQ5iOIH5)

6/ Marketing website

[ @learnframer ]
[https://t.co/Cu0m8aZtZK](https://t.co/Cu0m8aZtZK)

7/ Landing page for a freelance community

[ @hyperfreelancer ]
[https://t.co/IjgFBUdJLk](https://t.co/IjgFBUdJLk)

8/ Portfolio for developers

[ @namyakhann ]
[https://t.co/b5Wykrg4vO](https://t.co/b5Wykrg4vO)

That's it for today!

If you enjoyed this thread:
→ Follow me @namyakhann for more.
→ RT the first tweet to share with others.
[https://t.co/8d6xbNUJIS](https://t.co/8d6xbNUJIS)

Love my tweets?

Join 750+ creatives who start their Sundays with my newsletter👇[https://t.co/xvJUdRtMkH](https://t.co/xvJUdRtMkH)

---
## Exploring StarChatβ: A Beta Version of 💫StarCoder+

[https://twitter.com//status/1669020088203366401](https://twitter.com//status/1669020088203366401)

**🪄Smart summary:**
Last week, StarChatβ was released, an instruction tuned model of StarCoder+. This thread showcases some of the cool examples generated with StarChat, such as helping with coding questions, image processing, errors, Pandas dataframes, and SQL queries. StarChat Beta is still in its Beta version, but it shows promise for open-access code models that are strong. You can play with the model at StarChat Playground or deploy your own Chat-UI.
-------

Last week we released StarChatβ, an instruction tuned model of 💫StarCoder+.

In this thread, I will share some cool examples we generated with StarChat and show how it can be used to help you with coding questions.

A thread 🧵 

![](https://pbs.twimg.com/media/FymJGDYX0AEgY8u.jpg)

These examples were generated by deploying a local version of the amazing Hugging Face Chat-UI: [https://t.co/vL64GneEBN](https://t.co/vL64GneEBN)

🔍 If you want to dive in the TS source code of how the prompt is built, StarChat can help! 

![](https://pbs.twimg.com/media/FymJVuGWwAEuzhd.png)

🖼️ What about some Image Processing? 

![](https://pbs.twimg.com/media/FymJg-LWcAMSEEL.jpg)

StarChat can also help with errors, to get a nice blurred image 🌫️ 

![](https://pbs.twimg.com/media/FymJkjZXoAk2kYN.png)

You can also generate nice plots from Pandas dataframes 

![](https://pbs.twimg.com/media/FymJwseXoAk5NhH.jpg)

The great thing about StarChat, it knows more than just Python📚 

![](https://pbs.twimg.com/media/FymLZ0wXoAUi4qS.png)

And finally some SQL queries 

![](https://pbs.twimg.com/media/FymJ6n3WIAAphvh.jpg)

StarChat Beta might hallucinate and generate problematic output. After all it's still a Beta version, but it shows we’re on a good path for code models that are open-access but also strong ✨

You play more with the model at StarChat Playground:
[https://t.co/KxotFiBlsA](https://t.co/KxotFiBlsA)

Or you can deploy your own Chat-UI:
[https://t.co/vL64Gnfcrl](https://t.co/vL64Gnfcrl)

---
## Unlocking the Power of OpenAI GPT API Function Calls

[https://twitter.com/Sentdex/status/1668795449447268354](https://twitter.com/Sentdex/status/1668795449447268354)

**🪄Smart summary:**
OpenAI GPT API function calls are more powerful than expected, allowing for the generation of a list of commands from GPT-4 for a given prompt. This is easier and more reliable than pre-prompting and forms, and opens up the possibility of adding new features and abilities. This new paradigm for programming is very cool.
-------

These new OpenAI GPT API function calls are more powerful than I expected.

All examples I've seen so far have a static number of pre-defined variables like "filename" "src" "dst" "intent"...etc, or weather for "location" and so on. 🧵1/6

In those examples, the information for functions was "extracted" from user input, not generated model output.

Your "function" parm could be something more like: a list..of any size. For example, for TermGPT, I want a list of commands from GPT-4 for a given prompt. 🧵2/6 

![](https://pbs.twimg.com/media/Fyi-vfaWYAAPvGG.jpg)

Here, we're also forcing the function call to occur with the "function_call" part, which is not to be under estimated in usefulness. The "auto" is also cool, but often fails in more niche cases like this. The ability to let GPT-4 we definitely want this done is nice. 🧵3/6 

![](https://pbs.twimg.com/media/Fyi-WC3WIAIfZXy.png)

The result is a neatly-organized list of commands that can then be run to achieve the prompt: 🧵4/6 

![](https://pbs.twimg.com/media/Fyi_JKCWwAItPHp.jpg)

This is massively easier than what I have been doing up to this point with pre-prompting and forms and such for TermGPT, and is likely to be more reliable going forward. 

I can also much more easily add new features and abilities. 🧵5/6

This isn't limited to just a list of commands, it could be anything and I am not entirely sure this open-ended use-case was considered or intended. Suspect there are many more "hacks" that we'll see in the future. 

Very cool and totally a new paradigm for programming! 🧵6/6

---
## Exploring the Magic of Bamboo AI

[https://twitter.com/Luc_AI_Insights/status/1668792631806050304](https://twitter.com/Luc_AI_Insights/status/1668792631806050304)

**🪄Smart summary:**[https://t.co/ZJaHysWK5N](https://t.co/ZJaHysWK5N)

![](https://pbs.twimg.com/media/Fyi9kXMWIAAOzb4.jpg)

@Luc_AI_Insights

---
## Automating Prompt Selection with Multi Prompt Chain

[https://twitter.com/MoonDevOnYT/status/1668418640197169152](https://twitter.com/MoonDevOnYT/status/1668418640197169152)

**🪄Smart summary:**
With LangChainAI's Multi Prompt Chain, users can easily handle multiple ChatGPT tabs. The process involves selecting the specialists, formulating the corresponding prompts, and allocating the templates to the prompt information. After configuring the multi prompt chain, users can initiate the chain and create whatever they want.
-------

Efficient prompts pave the way for superior outputs from ChatGPT.

Yet, handling 20 separate ChatGPT tabs can be bothersome.

With @LangChainAI 's Multi Prompt Chain, the problem is solved. It auto-selects the suitable prompt.

Illustration: Marketing versus business expert. 

![](https://pbs.twimg.com/media/FydnoIwXoAIEXDe.jpg)

Firstly, you need to select which 'specialists' you wish to incorporate.

I've picked a marketing and business specialist.

Next, formulate the corresponding prompts. 

![](https://pbs.twimg.com/media/Fydn3BAWAAEGEyC.jpg)

Next, allocate the templates to the prompt information.

The length of this list can be as extensive as you want.

Ensure that you make each prompt's description lucid for the large language model. 

![](https://pbs.twimg.com/media/FydoBNiWcAEhufg.jpg)

Voila, your experts are ready.

Kick-start the large language model you prefer, configure the @LangChainAI multi prompt chain and initiate the chain.

Do share what you'll be creating with this! 

![](https://pbs.twimg.com/media/FydomHFWYAAe83a.jpg)

---
## Learn How to Build LLM-Powered Apps

[https://twitter.com/capetorch/status/1667321914535333889](https://twitter.com/capetorch/status/1667321914535333889)

**🪄Smart summary:**
This thread is about a course that teaches how to build LLM-powered Apps. It covers topics such as how to chat with data, ingest documents, use LangChainAI, and expand chatGPT context window.
-------

If you want to start building LLM-powered Apps this is the course for you:
- How do I chat with my data?
- How can I ingest my documents and store them on a vector database?
- What is @LangChainAI and how can I use it?
- How can I expand chatGPT context window?
- Learn how we… [https://t.co/9xGHv6o6PA[https://t.co/BgUkdUtRg9](https://t.co/BgUkdUtRg9)](https://t.co/9xGHv6o6PA)

@capetorch @LangChainAI

---
## Copilot Enhances Coding Efficiency by Reducing Double-Checking and Editing Time

[https://twitter.com/DynamicWebPaige/status/1667751396110909440](https://twitter.com/DynamicWebPaige/status/1667751396110909440)

**🪄Smart summary:**
Our studies showed that when using Copilot to solve coding tasks, programmers spend 34.3% of their time double-checking and editing suggestions, and more than half of their time on Copilot related activities.
-------

"Our studies revealed that when solving a coding task with Copilot, programmers may spend a large fraction of total session time (34.3%) on just double-checking and editing suggestions, and spend *more than half* of the task time on Copilot related activities, together indicating… [https://t.co/C9BoOakPWo](https://t.co/C9BoOakPWo)

![](https://pbs.twimg.com/media/FyULB_HakAE6j9m.jpg)[https://t.co/qQ0W5x7ZtY](https://t.co/qQ0W5x7ZtY)

cc: @RandomlyWalking @dtarlow2 @jacobaustin132

---
## Unlocking the Potential of AI Solutions with LLMs and Embeddings

[https://twitter.com/Lukaesch/status/1666868044184813582](https://twitter.com/Lukaesch/status/1666868044184813582)

**🪄Smart summary:**
This thread provides resources for those building AI solutions powered by language models and embeddings. It includes links to a page with gold information and a website to discover, buy, or sell AI embeddings.
-------

This page is gold for everyone building AI solutions powered by LLMs and embeddings.

[https://t.co/FgIhDRz49n](https://t.co/FgIhDRz49n)

Thanks @LangChainAI

Do you want to discover, buy or sell AI embeddings?

Check this out: [https://t.co/umUGBlWjEL](https://t.co/umUGBlWjEL)

---
## Creating a Blog Outline Generator App with LangChain and Streamlit in 25 Lines of Code

[https://twitter.com/LangChainAI/status/1666837740497797124](https://twitter.com/LangChainAI/status/1666837740497797124)

**🪄Smart summary:**
This tweet is promoting a tutorial on how to build a blog outline generator app in 25 lines of code. It was created by @thedataprof.
-------

Another excellent LangChain x Streamlit tutorial:

Build a blog outline generator app in 25 lines of code

[https://t.co/SYPsbqqnnD](https://t.co/SYPsbqqnnD)

Thanks @thedataprof for creating!

@LangChainAI @thedataprof

---
## Train a Chatbot on YouTube - Now Open Source and Live on GitHub!

[https://twitter.com/ehalm_/status/1666783939451600898](https://twitter.com/ehalm_/status/1666783939451600898)

**🪄Smart summary:**
A new open source product, YouTube-to-Chatbot, is now available on GitHub. It allows users to train a chatbot on an entire YouTube channel. The creator was surprised by the amount of interest in the product and is now doubling down on building a no-code product. Follow @ehalm_ for more announcements and thanks to @SeanGrindal and @eniascailliau for their help.
-------

The wait is over... Train a chatbot on an entire YouTube channel. 🎥🤝🤖

YouTube-to-Chatbot is now open source and LIVE on GitHub 👇 

![](https://pbs.twimg.com/media/FyGaTBLWIAAfSwV.jpg)

If you missed the original Tweet, here’s how the story starts: [https://t.co/FverV92Znu](https://t.co/FverV92Znu)

I was blown out of the water by how much creators wanted this 🤯 

Got DMs from some of my fav creators. W.

So I decided to double down & keep building a no-code product: [https://t.co/ThBoKhz5kv](https://t.co/ThBoKhz5kv)

More announcements soon. Time to get back to building.

Just know that something awesome is coming 👀 

Follow @ehalm_ so you don’t miss it ✌🏼

Thanks to @SeanGrindal for late nights looking through my code 🙏

Big shout out to @eniascailliau for helping me test & debug — check out the incredible work he’s been doing with AI agents and girlfriendGPT 🙌

[https://t.co/IloVZXfcAu](https://t.co/IloVZXfcAu)

---
## Chat with Your Brain on Your Phone: Quivr's Mobile App

[https://twitter.com/_StanGirard/status/1666810871795052544](https://twitter.com/_StanGirard/status/1666810871795052544)

**🪄Smart summary:**
Quivr Brain is a new open-source project that allows users to upload PDFs, CSVs, and other documents from their smartphones. It is powered by Supabase, LangChainAI, and other genius developers. The code for Quivr's mobile app and source code can be found in the links provided.
-------

What if you could chat with your brain on your phone? 🧠📱

You can now upload PDFs, CSVs, etc ... from your smartphone 🤯

Thanks @iMADi69235681, one of the genius behind the front of @quivr_brain 

Open-source projects are the best! Powered by @supabase , @LangChainAI 

🔗🧵 [https://t.co/Ub5Ir4wEQI](https://t.co/Ub5Ir4wEQI)

You can find the code for Quivr's mobile app -> 
[https://t.co/xl8kGldzoK](https://t.co/xl8kGldzoK)

And for @quivr_brain source code, here 
[https://t.co/XHpLfYNRMF](https://t.co/XHpLfYNRMF)

---
## Introducing AnythingLLM: An Open-Source App for Chatting with Documents

[https://twitter.com/tcarambat/status/1666545363761922050](https://twitter.com/tcarambat/status/1666545363761922050)

**🪄Smart summary:**
AnythingLLM is an open-source full-stack app for chatting with documents. It has no massive RAM requirements, no LLM downloading or training, and no need to pay to re-embed documents. It has a data tool suite, efficient vector-caching, persistent and useable UI, and allows users to bring their own OpenAI API key and Pinecone instance. It is MIT Licensed.
-------

Announcing AnythingLLM. An open-source (MIT) full-stack app for chatting with... anything.

✅ UI for managing documents
✅ Uses @OpenAI , @pinecone & @LangChainAI 

🚫 massive RAM requirements
🚫 LLM downloading or training
🚫 paying to re-embed documents

+ data tooling! [https://t.co/AAwdA4vAVa](https://t.co/AAwdA4vAVa)

![](https://pbs.twimg.com/media/FyC-HXDaQAAFkkJ.jpg)

First, you can find AnythingLLM on Github here 
[https://t.co/xnK8AMQEuy](https://t.co/xnK8AMQEuy)

Requirements:
- Python 3.8+
- npm and Node v16+

Thats it. No bulky CPU or GPU is required.

Chatting with your documents is the "hello world" of LLM use-cases, why not make it more accessible?

What is so special about AnythingLLM?

🔥 No crazy system requirements - runs fast and passively on your machine

🧰 Full data-collection tool suite. Collect anything
👉 Entire YouTube Channels
👉 Substacks
👉 Mediums
👉 Gitbooks
+ local document processing 

![](https://pbs.twimg.com/media/FyC_J4RaUAA8vgu.jpg)

⚡ Efficient vector-caching

Embed forever, pay once.

Embedding is low-cost using OpenAIs ada text embedding, but over thousands of tokens - why pay more than once?

AnythingLLMs vector caching allows you to use the same document across workspaces and pay once. 

![](https://pbs.twimg.com/media/FyC__hcaEAAhhhV.jpg)

💎 Persistent and Useable
Chatting and managing documents is all done from a web-browser UI.

Shut down the app and start it later - all your documents, chats, and more are still present. Picking up right where you left off.

The database is locally saved on your machine. 

![](https://pbs.twimg.com/media/FyDAXI7aYAAkyDG.jpg)

🔑 Bring-Your-Own-Keys

Use your own OpenAI API key and Pinecone (free) instance and you are already on the way to managing documents with ease.

This keeps overhead low by just using what is existing, easy and accessible. 

![](https://pbs.twimg.com/media/FyDA2D1aEAEyO_f.jpg)

AnythingLLM is MIT Licensed so go crazy. Read more about AnythingLLM on Medium at:
[https://t.co/EDIUvZkmCx](https://t.co/EDIUvZkmCx)

---
## Developing a Frontend for Documentation Chat

[https://twitter.com/MarkusOdenthal/status/1666435090832916481](https://twitter.com/MarkusOdenthal/status/1666435090832916481)

**🪄Smart summary:**
Today, I developed a frontend for my Documentation Chat program using OpenAI for embeddings and chat functionality, LangChainAI for workflows, qdrant_engine for Vectorstore, and streamlit for the user interface. I had a successful chat session with the qdrant documentation.
-------

Today, I developed a frontend for my Documentation Chat program.

Tech stack:

@OpenAI for embeddings and chat functionality
@LangChainAI for workflows
@qdrant_engine for Vectorstore
@streamlit for the user interface

I had a chat session with the qdrant documentation💬 [https://t.co/StrZQYTPrd](https://t.co/StrZQYTPrd)

@MarkusOdenthal @OpenAI @LangChainAI @qdrant_engine @streamlit

---
## Quivr Answers Questions with the Help of LangChainAI and Gitloader

[https://twitter.com/_StanGirard/status/1665849750166417408](https://twitter.com/_StanGirard/status/1665849750166417408)

**🪄Smart summary:**
Quivr now has the ability to answer questions about itself, thanks to LangChainAI and their Gitloader. Quivr can now consume Github repos.
-------

Quivr can now answer questions on itself 🔥

How ?! 

Thanks to @LangChainAI and their Gitloader @Quivr_app can now consume Github repos 🤤 

![](https://pbs.twimg.com/media/Fx5JOt7XsAI6oOk.jpg)

@_StanGirard @LangChainAI @Quivr_app

---
## Building the Twitter GPT with Yann Lecun

[https://twitter.com/acohendev/status/1665852268304822273](https://twitter.com/acohendev/status/1665852268304822273)

**🪄Smart summary:**
This thread explains how to build a Twitter GPT using LangChainAI. It demonstrates the process by using Yann Lecun's handle and scraping it with a link. The result is stored in a vector database and then searched using similarity metrics. This data is then used by ChatGPT to answer the original question.
-------

How to build the Twitter GPT using @LangChainAI?

Let's try with @ylecun 🇫🇷

RESULTS: 

- Q: What does Yann Lecun like to talk about?

- A: Yann Lecun likes to talk about autoregressive transformer models and advises taking more math and quantum physics courses. 

![](https://pbs.twimg.com/media/Fx5LTJaWwAMyXBL.jpg)

We scrape Yann Lecun's handle using [https://t.co/NQnL1HeaZC.](https://t.co/NQnL1HeaZC.)
The result is then stored in a vector database indexed by embedding vectors created through the OpenAI API.

We can then search that database using similarity metrics and provide the resulting data to ChatGPT for it to extract the relevant information answering the original question.

---
## Replit Code Instruct v2 Now Available on HuggingFace

[https://twitter.com/Teknium1/status/1665175977251708928](https://twitter.com/Teknium1/status/1665175977251708928)

**🪄Smart summary:**
Replit Code Instruct v2 is now available on HuggingFace, with a training length of 2000 tokens, giving it greater access to dataset knowledge. There is also a HuggingFace spaces demo of the new model, and some output examples include creating code from an instruction, converting code to other languages, and explaining code.
-------

Replit Code Instruct v2 is now available on HuggingFace. 

The original fine tune had only been trained on 512 token lengths, this one on 2000, giving it much greater access to dataset knowledge!

[https://t.co/lXWAXqzhBf](https://t.co/lXWAXqzhBf)

I have also created a HuggingFace spaces demo of the new model, try it out here: 

[https://t.co/o3yeaoFM7Q](https://t.co/o3yeaoFM7Q)

Some output examples from this model - Create code from an instruction, convert code to other languages, even explain code you ask it to! 

![](https://pbs.twimg.com/media/FxvpOTnaYAETKa2.jpg)

---
## Introducing CodeTF: A One-Stop Transformer Library for Code Large Language Models

[https://twitter.com/stevenhoi/status/1664483010954272770](https://twitter.com/stevenhoi/status/1664483010954272770)

**🪄Smart summary:**
CodeTF is a one-stop Transformer Library for Code Large Language Models (CodeLLM) with a unified interface for training and inference on code tasks such as code generation, summarization, and translation. It is designed with key principles to provide a user-friendly and easy-to-use platform for code intelligence tasks, and follows a modular architecture to enhance its extensibility. It was developed by the AI Research team at SFResearch, consisting of Nghi, LHung1610, ayueei, LiJunnan0409
-------

📢Introducing 🔥🔥, a one-stop Transformer Library for Code Large Language Models (CodeLLM), with a unified interface for training & inference on code tasks (code generation,summarization,translation,etc)

Paper: [https://t.co/TmTrsOz94a](https://t.co/TmTrsOz94a)
Code: [https://t.co/GmEN2rOYPE](https://t.co/GmEN2rOYPE)

(1/n)

CodeTF library supports both the development and deployment of Code LLMs for code intelligence tasks. The library can support both training and serving code LLM models, code utilities to process code data, and popular research benchmarks to evaluate the model performance. 
(2/n) 

![](https://pbs.twimg.com/media/FxlvgoKaQAA8xA4.jpg)

CodeTF is designed with key principles to provide a user-friendly and easy-to-use platform for code intelligence tasks. It follows a modular architecture, enhancing its extensibility by allowing seamless integration of additional programming languages, models & utilities.

(3/n) 

![](https://pbs.twimg.com/media/FxlyKhLaEAAJN9x.jpg)

Find out more details from our technical report here: 

CodeTF: One-stop Transformer Library for State-of-the-art Code LLM

Another great open-source library with our amazing AI Research team: Nghi, @LHung1610 @ayueei @LiJunnan0409 @AkhileshGotmare at @SFResearch. 

(4/n)

[https://t.co/TmTrsOz94a](https://t.co/TmTrsOz94a) (5/n)

---
## Using JSONLoader and JSON Agent with LangChainAI

[https://twitter.com/mesudarshan/status/1664664132174376962](https://twitter.com/mesudarshan/status/1664664132174376962)

**🪄Smart summary:**
LangChainAI has released a video demonstrating how to use JSONLoader and JSON Agent to parse a JSON file and interact with a large API spec yaml file. The code and video are available on Github and Youtube respectively.
-------

JSONLoader and JSON Agent with @LangChainAI 
🎥Video covers the following:

- JSONLoader to parse the JSON file
- JSON Agent to interact with large API spec yaml file

💻 Github code: [https://t.co/gL3fLstG01](https://t.co/gL3fLstG01)

🍿 Youtube video: [https://t.co/b7UDOgBgoN](https://t.co/b7UDOgBgoN)

   

@mesudarshan @LangChainAI

---
## Unlocking the Benefits of Caching LLM Calls with LangChain

[https://twitter.com/mesudarshan/status/1664657092140060672](https://twitter.com/mesudarshan/status/1664657092140060672)

**🪄Smart summary:**
Caching LLM calls can help reduce both cost and response time. LangChainAI has uploaded a video about this topic, and it can be found at the link provided.
-------

Caching LLM calls can reduce cost as well as response time. Just uploaded a video about it using @LangChainAI. Happy caching and chaining 🔗

#langchain
 #openai
 #llm
 #cache
 #python
 #gpt


🦜🔗 LangChain | How To Cache LLM Calls ? [https://t.co/6b6zJVHLns](https://t.co/6b6zJVHLns) via @YouTube

@mesudarshan @LangChainAI @YouTube

---
## Improving ChatGPT Response Accuracy with Open-Source Prompting Strategy

[https://twitter.com/krrish_dh/status/1664471146132283393](https://twitter.com/krrish_dh/status/1664471146132283393)

**🪄Smart summary:**
We have improved the accuracy of our chatGPT response by 35%, and are now open-sourcing it for everyone else. If you would like to use this strategy at your company, please contact us.
-------

We improved our chatGPT response accuracy by 35% with this prompting strategy.

So we're open-sourcing it for everybody else. 

🚨 Want to do this @ your co. 👉 let's chat: [https://t.co/ZYmk95n7Zx](https://t.co/ZYmk95n7Zx)

[https://t.co/9pps4Vo3Fo](https://t.co/9pps4Vo3Fo)

@krrish_dh

---
## The Complete Guide to Fine-Tuning: Tips, Steps, and Use-Cases

[https://twitter.com/pwang_szn/status/1664210285652221952](https://twitter.com/pwang_szn/status/1664210285652221952)

**🪄Smart summary:**
This thread provides an overview of fine-tuning, a process used to customize a language model. It explains what fine-tuning is, how to do it, when to use it, and provides tips for improving performance. It also provides use cases for fine-tuning, such as sentiment analysis, text generation, and fake news detection.
-------

"The Complete Bozos Guide to Fine-tuning"

• What is Fine-tuning?
• How to Fine-tune a custom LLM.
• When should we use fine-tuning?
• When NOT use use fine-tuning?

Save This ↓ 

![](https://pbs.twimg.com/media/Fxh2btVagAEMtnz.png)

Basic info on Fine-Tuning: 

![](https://pbs.twimg.com/media/Fxh2cIXaEAIvLcL.jpg)

Fine-tuning vs Semantic Search:

TLDR: "Fine tuning encourages pattern.
Embeddings provide knowledge." 

![](https://pbs.twimg.com/media/Fxh2ckXagAECIxO.jpg)

What are the steps for fine-tuning? 🤔

1. Prepare and upload training data
2. Train a new fine-tuned model
3. Use your fine-tuned model

Let's go over all the steps:

In order to train the model, we need to structure the data must be a JSONL document(a list of prompt-completion pairs.): 

![](https://pbs.twimg.com/media/Fxh2dLFaEAAnwU9.jpg)

Tips for Improve Fine-Tuning Performance:

1) Provide at least a few hundred high-quality examples (vetted by human.)

2) Increasing the number of examples is usually the best and most reliable way of improving performance.

Here's the command to fine-tune your data: 

![](https://pbs.twimg.com/media/Fxh2d1VaMAE2nrb.jpg)

After you train the model, there's two ways to use the new model:

1) Command Line
2) Code 

![](https://pbs.twimg.com/media/Fxh2eSraAAArhAs.jpg)

You can also use the fine-tuned models in on the OpenAI playground directly. 

![](https://pbs.twimg.com/media/Fxh2ewyaAAA1aYA.png)

P.S - ✨ I'm dropping a FREE step-by-step mini-course guide to start coding with A.I

(Free for now, but not free forever)

Check it out: [https://t.co/pmDsYC74tK](https://t.co/pmDsYC74tK)

Use-cases for fine-tuning:

1) Sentiment Analysis
2) Text Generation: chatbot that responds in a specific tone or style based company's guidelines.
3) Fake News Detection: Models can be fine-tuned to detect fake news or misinformation by training them dataset of fake news.

---
[https://github.com/kyrolabs/awesome-langchain#other--chatbots](https://github.com/kyrolabs/awesome-langchain#other--chatbots)

LangChain is an amazing framework to get LLM projects done in a matter of no time and the ecosystem is growing fast. Here is an attempt to keep track of the initiatives around LangChain.
Contributions welcome. Add links through pull requests or create an issue to start a discussion. Please read the [contribution guidelines](https://github.com/kyrolabs/awesome-langchain/blob/main/CONTRIBUTING.md) before contributing.
## 
## Table of Contents
- [🦜🔗 Awesome LangChain[Table of Contents](https://github.com/kyrolabs/awesome-langchain#table-of-contents)](https://github.com/kyrolabs/awesome-langchain#-awesome-langchain--)
- [LangChain Framework](https://github.com/kyrolabs/awesome-langchain#langchain-framework)
- [Tools[Low-code](https://github.com/kyrolabs/awesome-langchain#low-code)](https://github.com/kyrolabs/awesome-langchain#tools)
- [Services](https://github.com/kyrolabs/awesome-langchain#services)
- [Agents](https://github.com/kyrolabs/awesome-langchain#agents)
- [Templates](https://github.com/kyrolabs/awesome-langchain#templates)
- [Open Source Projects[Knowledge Management](https://github.com/kyrolabs/awesome-langchain#knowledge-management)](https://github.com/kyrolabs/awesome-langchain#open-source-projects)
- [Other / Chatbots](https://github.com/kyrolabs/awesome-langchain#other--chatbots)
- [Learn[Notebooks](https://github.com/kyrolabs/awesome-langchain#notebooks)](https://github.com/kyrolabs/awesome-langchain#learn)
- [Videos](https://github.com/kyrolabs/awesome-langchain#videos)
- [Articles](https://github.com/kyrolabs/awesome-langchain#articles)
- [Alternatives](https://github.com/kyrolabs/awesome-langchain#alternatives)
- [Complement to this list](https://github.com/kyrolabs/awesome-langchain#complement-to-this-list)

## 
## LangChain Framework
- [LangChain](https://github.com/hwchase17/langchain): the original 🐍 [![](https://camo.githubusercontent.com/63354a25bfac04c720aa99292f657b9d59740705fb29d3c71726106f5a017590/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/63354a25bfac04c720aa99292f657b9d59740705fb29d3c71726106f5a017590/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e3f7374796c653d736f6369616c)
- [LangChain.js](https://github.com/hwchase17/langchainjs): the js brother ✨ [![](https://camo.githubusercontent.com/39c7a3539f1e5abfc015a00918b68cbb4cb93e47a86d8a58a0cda6ba3ee3c01a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e6a733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/39c7a3539f1e5abfc015a00918b68cbb4cb93e47a86d8a58a0cda6ba3ee3c01a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e6a733f7374796c653d736f6369616c)
- [Concepts](https://docs.langchain.com/docs/): Langchain concepts doc
- [Twitter account](https://twitter.com/LangChainAI): follow to get fresh updates
- [Youtube Channel](https://www.youtube.com/channel/UCC-lyoTfSrcJzA1ab3APAgw)
- [Discord](https://discord.gg/6adMQxSpJS): discussion
- [Langchain Blog](https://blog.langchain.dev/): The Official Langchain blog
- [LangChainHub](https://github.com/hwchase17/langchain-hub): collection of all artifacts useful for working with LangChain primitives such as prompts, chains and agents [![](https://camo.githubusercontent.com/c6a192e23f03b6ecb26489ba1e6d1b4f5776810f541c1ed59777c3422b326e57/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e2d6875623f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c6a192e23f03b6ecb26489ba1e6d1b4f5776810f541c1ed59777c3422b326e57/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e2d6875623f7374796c653d736f6369616c)

## 
## Tools
### 
### Low-code
- [Langflow](https://github.com/logspace-ai/langflow): LangFlow is a UI for LangChain [![](https://camo.githubusercontent.com/196fc1df5f5e5d6b1c0d147c121168693afe44bbadc87cc3f443efd46b1ec74f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c6f6773706163652d61692f6c616e67666c6f773f7374796c653d736f6369616c)](https://camo.githubusercontent.com/196fc1df5f5e5d6b1c0d147c121168693afe44bbadc87cc3f443efd46b1ec74f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c6f6773706163652d61692f6c616e67666c6f773f7374796c653d736f6369616c)
- [Flowise - LangchainJS UI](https://github.com/FlowiseAI/Flowise): Drag & drop UI to build your customized LLM flow using LangchainJS [![](https://camo.githubusercontent.com/1ba1ab2cc7be5ca0a17eadbc4cff268741a7d0c606a6d33ac90077b54c903ea9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f466c6f7769736541492f466c6f776973653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/1ba1ab2cc7be5ca0a17eadbc4cff268741a7d0c606a6d33ac90077b54c903ea9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f466c6f7769736541492f466c6f776973653f7374796c653d736f6369616c)
- [Databerry](https://github.com/gmpetrov/databerry): The no-code platform for semantic search and documents retrieval [![](https://camo.githubusercontent.com/a693798f36ebeeeaec4bd77303cf15a4b567976c043ce14c4a8bf5264d996603/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f676d706574726f762f6461746162657272793f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a693798f36ebeeeaec4bd77303cf15a4b567976c043ce14c4a8bf5264d996603/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f676d706574726f762f6461746162657272793f7374796c653d736f6369616c)
- [LangchainUI](https://github.com/homanp/langchain-ui): The open source chat-ai toolkit [![](https://camo.githubusercontent.com/e9852774df90de16175df3eddcb12ad2974b95d3dd89cf53a7415850f25d528e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f686f6d616e702f6c616e67636861696e2d75693f7374796c653d736f6369616c)](https://camo.githubusercontent.com/e9852774df90de16175df3eddcb12ad2974b95d3dd89cf53a7415850f25d528e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f686f6d616e702f6c616e67636861696e2d75693f7374796c653d736f6369616c)
- [Yeager.ai](https://github.com/yeagerai/yeagerai-agent): Yeager.ai Agent is the first Langchain Agent creator designed to help you build, prototype, and deploy AI-powered agents with ease [![](https://camo.githubusercontent.com/08865c0e9b8bbf60e9bd2e40316cdb5444d53908047d4a0a40b92b839dad0635/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f79656167657261692f79656167657261692d6167656e743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/08865c0e9b8bbf60e9bd2e40316cdb5444d53908047d4a0a40b92b839dad0635/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f79656167657261692f79656167657261692d6167656e743f7374796c653d736f6369616c)

### 
### Services
- [GPTCache](https://github.com/zilliztech/GPTCache): A Library for Creating Semantic Cache for LLM Queries [![](https://camo.githubusercontent.com/00b53511e42ff679259ffae7a508ddc2ccdd07f82c0f56adee16f17f4f6a5033/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7a696c6c697a746563682f47505443616368653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/00b53511e42ff679259ffae7a508ddc2ccdd07f82c0f56adee16f17f4f6a5033/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7a696c6c697a746563682f47505443616368653f7374796c653d736f6369616c)
- [LlamaHub](https://github.com/emptycrown/llama-hub): a library of data loaders for LLMs made by the community [![](https://camo.githubusercontent.com/a69d2a5e9cfae3676a6d3a0f9a1e4c850c0d3e7654dddf343c6e86280db279c0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f656d70747963726f776e2f6c6c616d612d6875623f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a69d2a5e9cfae3676a6d3a0f9a1e4c850c0d3e7654dddf343c6e86280db279c0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f656d70747963726f776e2f6c6c616d612d6875623f7374796c653d736f6369616c)
- [EVAL](https://github.com/corca-ai/EVAL): Elastic Versatile Agent with Langchain. will execute all your requests. [![](https://camo.githubusercontent.com/c46cfaedbf5b687d90775504cc5ff80c105f2772c4bc1e0c015d1261ce33c39a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f636f7263612d61692f4556414c3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c46cfaedbf5b687d90775504cc5ff80c105f2772c4bc1e0c015d1261ce33c39a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f636f7263612d61692f4556414c3f7374796c653d736f6369616c)
- [Auto-evaluator](https://github.com/PineappleExpress808/auto-evaluator): a lightweight evaluation tool for question-answering using Langchain [![](https://camo.githubusercontent.com/6e0c6def5e38e56bb156f78ef5354c3e21e2d39e2a7260a498f77d68892801d7/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f50696e656170706c65457870726573733830382f6175746f2d6576616c7561746f723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/6e0c6def5e38e56bb156f78ef5354c3e21e2d39e2a7260a498f77d68892801d7/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f50696e656170706c65457870726573733830382f6175746f2d6576616c7561746f723f7374796c653d736f6369616c)
- [Langchain visualizer](https://github.com/amosjyng/langchain-visualizer): visualization and debugging tool for LangChain workflows [![](https://camo.githubusercontent.com/518db549cc722ee463a35962545cd6abca0181c18c7d8561365be5437501a2d5/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616d6f736a796e672f6c616e67636861696e2d76697375616c697a65723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/518db549cc722ee463a35962545cd6abca0181c18c7d8561365be5437501a2d5/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616d6f736a796e672f6c616e67636861696e2d76697375616c697a65723f7374796c653d736f6369616c)
- [LLM Strategy](https://github.com/BlackHC/llm-strategy): implementing the Strategy Pattern using LLMs [![](https://camo.githubusercontent.com/656f14bc805aa1866b97d46d4a5e6905cdf082b73b47bde015bed68252fe814c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f426c61636b48432f6c6c6d2d73747261746567793f7374796c653d736f6369616c)](https://camo.githubusercontent.com/656f14bc805aa1866b97d46d4a5e6905cdf082b73b47bde015bed68252fe814c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f426c61636b48432f6c6c6d2d73747261746567793f7374796c653d736f6369616c)
- [datasetGPT](https://github.com/radi-cho/datasetGPT): A command-line interface to generate textual and conversational datasets with LLMs. [![](https://camo.githubusercontent.com/506478becd977c7ee2d6e514c051cbfd6c9bc8626dce5c793d72110d1463b218/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f726164692d63686f2f646174617365744750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/506478becd977c7ee2d6e514c051cbfd6c9bc8626dce5c793d72110d1463b218/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f726164692d63686f2f646174617365744750543f7374796c653d736f6369616c)
- [spellbook-forge](https://github.com/rafalzawadzki/spellbook-forge): Make your LLM prompts executable and version controlled. [![](https://camo.githubusercontent.com/7a927dd591070e945a19bf0f00f8cf72a05ef3612c4305ff7a4cafdd3a20e89b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f726166616c7a617761647a6b692f7370656c6c626f6f6b2d666f7267653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/7a927dd591070e945a19bf0f00f8cf72a05ef3612c4305ff7a4cafdd3a20e89b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f726166616c7a617761647a6b692f7370656c6c626f6f6b2d666f7267653f7374796c653d736f6369616c)
- [Auto Evaluator](https://github.com/langchain-ai/auto-evaluator): Langchain auto evaluator [![](https://camo.githubusercontent.com/53ccc7655a0834e0da4e1da9c6a181e8878df952a0a3cd9270ef3528e6022be3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c616e67636861696e2d61692f6175746f2d6576616c7561746f723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/53ccc7655a0834e0da4e1da9c6a181e8878df952a0a3cd9270ef3528e6022be3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c616e67636861696e2d61692f6175746f2d6576616c7561746f723f7374796c653d736f6369616c)
- [Jina](https://github.com/jina-ai/langchain-serve): Langchain Apps on Production with Jina [![](https://camo.githubusercontent.com/c3c5be6d138cb73f94b981c0c05c3adfb547c6a7baf552af9c5940ffd4267a54/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a696e612d61692f6c616e67636861696e2d73657276653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c3c5be6d138cb73f94b981c0c05c3adfb547c6a7baf552af9c5940ffd4267a54/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a696e612d61692f6c616e67636861696e2d73657276653f7374796c653d736f6369616c)
- [Gradio Tools](https://github.com/freddyaboulton/gradio-tools): Gradio 🤝 LLM Agents [![](https://camo.githubusercontent.com/4301edbd0b2ce3f8f7930eb0dd575a9524f9564b7ab25d9c9d498b8871c7674e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f66726564647961626f756c746f6e2f67726164696f2d746f6f6c733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/4301edbd0b2ce3f8f7930eb0dd575a9524f9564b7ab25d9c9d498b8871c7674e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f66726564647961626f756c746f6e2f67726164696f2d746f6f6c733f7374796c653d736f6369616c)
- [steamship-langchain](https://github.com/steamship-core/steamship-langchain): adapters for Steamship, enabling LangChain developers to rapidly deploy their apps on Steamship 🐍 [![](https://camo.githubusercontent.com/42b7d766231d87754ad003af81d64fc49f06b5248debb37abe2e911db05961ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f737465616d736869702d636f72652f737465616d736869702d6c616e67636861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/42b7d766231d87754ad003af81d64fc49f06b5248debb37abe2e911db05961ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f737465616d736869702d636f72652f737465616d736869702d6c616e67636861696e3f7374796c653d736f6369616c)
- [LangForge](https://github.com/mme/langforge): A Toolkit for Creating and Deploying LangChain Apps [![](https://camo.githubusercontent.com/89de1946e96db34b3f3d48a3cff44fd884fc4da67df7d7dfcc620453c4b7af1e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6d652f6c616e67666f7267653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/89de1946e96db34b3f3d48a3cff44fd884fc4da67df7d7dfcc620453c4b7af1e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6d652f6c616e67666f7267653f7374796c653d736f6369616c)
- [BentoChain](https://github.com/ssheng/BentoChain): LangChain Deployment on BentoML [![](https://camo.githubusercontent.com/b3b125636b316d83534302d480b260e243bd738b1fe9e720fa2fcc30057043f0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f737368656e672f42656e746f436861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/b3b125636b316d83534302d480b260e243bd738b1fe9e720fa2fcc30057043f0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f737368656e672f42656e746f436861696e3f7374796c653d736f6369616c)
- [LangCorn](https://github.com/msoedov/langcorn): Serving LangChain apps automagically with FastApi [![](https://camo.githubusercontent.com/6f0fffaa6dbf5f07643bb3372c070c0b89f3933060ea89802af1596af474b4be/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d736f65646f762f6c616e67636f726e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/6f0fffaa6dbf5f07643bb3372c070c0b89f3933060ea89802af1596af474b4be/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d736f65646f762f6c616e67636f726e3f7374796c653d736f6369616c)
- [Langchain Service](https://github.com/kyrolabs/langchain-service): Opinionated Langchain setup with Qdrant vector store and Kong gateway [![](https://camo.githubusercontent.com/b7105e814bf87a1a8af2e2c997102143c2defb761ebd8671682a3b4954cc4ed6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6b79726f6c6162732f6c616e67636861696e2d736572766963653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/b7105e814bf87a1a8af2e2c997102143c2defb761ebd8671682a3b4954cc4ed6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6b79726f6c6162732f6c616e67636861696e2d736572766963653f7374796c653d736f6369616c)
- [Lanarky](https://github.com/ajndkr/lanarky): 🚢 Ship production-ready LLM projects with FastAPI [![](https://camo.githubusercontent.com/cfa3b6eefb6ee92bd41dbfb38927778de4adaf0f61db5883852e33100d41ad69/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616a6e646b722f6c616e61726b793f7374796c653d736f6369616c)](https://camo.githubusercontent.com/cfa3b6eefb6ee92bd41dbfb38927778de4adaf0f61db5883852e33100d41ad69/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616a6e646b722f6c616e61726b793f7374796c653d736f6369616c)
- [Dify](https://github.com/langgenius/dify): One API for plugins and datasets, one interface for prompt engineering and visual operation, all for creating powerful AI applications. [![](https://camo.githubusercontent.com/321751ad931de2f3e0cc451aa22d73ec924f9b73680a2adc489e0288fbcd6861/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c616e6767656e6975732f646966793f7374796c653d736f6369616c)](https://camo.githubusercontent.com/321751ad931de2f3e0cc451aa22d73ec924f9b73680a2adc489e0288fbcd6861/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c616e6767656e6975732f646966793f7374796c653d736f6369616c)
- [LangchainJS Worker](https://github.com/rickyrobinett/langchainjs-workers): LangchainJS worker on cloudflare [![](https://camo.githubusercontent.com/cff09d01c74012b3cbc370879faab58878969d24c82269219db49c089283333d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7269636b79726f62696e6574742f6c616e67636861696e6a732d776f726b6572733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/cff09d01c74012b3cbc370879faab58878969d24c82269219db49c089283333d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7269636b79726f62696e6574742f6c616e67636861696e6a732d776f726b6572733f7374796c653d736f6369616c)
- [Chainlit](https://github.com/Chainlit/chainlit): Build Python LLM apps in minutes ⚡️ [![](https://camo.githubusercontent.com/fe4ee7187e5201a75e40e63a87c5855ddb9313ccdd52ec4e062c7e0e7c2d73f4/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f436861696e6c69742f636861696e6c69743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/fe4ee7187e5201a75e40e63a87c5855ddb9313ccdd52ec4e062c7e0e7c2d73f4/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f436861696e6c69742f636861696e6c69743f7374796c653d736f6369616c)
- [Zep](https://github.com/getzep/zep): Zep: A long-term memory store for LLM / Chatbot applications [![](https://camo.githubusercontent.com/773f823c68d50bf34aacf9661ed451b89731456c32e5594ae74b56c312002894/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6765747a65702f7a65703f7374796c653d736f6369616c)](https://camo.githubusercontent.com/773f823c68d50bf34aacf9661ed451b89731456c32e5594ae74b56c312002894/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6765747a65702f7a65703f7374796c653d736f6369616c)
- [Gorilla](https://github.com/ShishirPatil/gorilla): An API store for LLMs [![](https://camo.githubusercontent.com/114728d53d657728c659e84ab512e3f7af9e4392dd83b9db1539c340cf776965/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f53686973686972506174696c2f676f72696c6c613f7374796c653d736f6369616c)](https://camo.githubusercontent.com/114728d53d657728c659e84ab512e3f7af9e4392dd83b9db1539c340cf776965/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f53686973686972506174696c2f676f72696c6c613f7374796c653d736f6369616c)

### 
### Agents
- [AgentGPT](https://github.com/reworkd/AgentGPT): AI Agents with Langchain & OpenAI (Vercel / Nextjs) [![](https://camo.githubusercontent.com/0db278150651f631d291ca1ef7943b8a28343cb5d471ee6ff65fdefc8019a9a4/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7265776f726b642f4167656e744750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/0db278150651f631d291ca1ef7943b8a28343cb5d471ee6ff65fdefc8019a9a4/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7265776f726b642f4167656e744750543f7374796c653d736f6369616c)
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt): Agent techniques to augment your LLM and push it beyond its limits [![](https://camo.githubusercontent.com/b0b4ec2adfe1dff62cc9a965c17f540887b23cc21b06138e5f61f3d3964bd286/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616c61656464696e652d31332f7468696e6b6770743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/b0b4ec2adfe1dff62cc9a965c17f540887b23cc21b06138e5f61f3d3964bd286/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616c61656464696e652d31332f7468696e6b6770743f7374796c653d736f6369616c)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT): role-playing approach for LLMs and auto-agents like BabyAGI & AutoGPT [![](https://camo.githubusercontent.com/a17e9217d26674eed8f86b32e6737b09510de507eaa79efd8ab262154732b6a6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f53616d757241494750542f43616d656c2d4175746f4750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a17e9217d26674eed8f86b32e6737b09510de507eaa79efd8ab262154732b6a6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f53616d757241494750542f43616d656c2d4175746f4750543f7374796c653d736f6369616c)
- [Private GPT](https://github.com/imartinez/privateGPT): Interact privately with your documents using the power of GPT, 100% privately, no data leaks [![](https://camo.githubusercontent.com/ba10dae69316f5005522d167d2b602ba6c40b272a92735a72da8d0caa531e032/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f696d617274696e657a2f707269766174654750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/ba10dae69316f5005522d167d2b602ba6c40b272a92735a72da8d0caa531e032/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f696d617274696e657a2f707269766174654750543f7374796c653d736f6369616c)
- [RasaGPT](https://github.com/paulpierre/RasaGPT): RasaGPT is the first headless LLM chatbot platform built on top of Rasa and Langchain. [![](https://camo.githubusercontent.com/27b2aaab1dc52e23ab7f64190bbe99efb3b2ac11e10f369ea281933980fd3d55/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7061756c7069657272652f526173614750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/27b2aaab1dc52e23ab7f64190bbe99efb3b2ac11e10f369ea281933980fd3d55/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7061756c7069657272652f526173614750543f7374796c653d736f6369616c)
- [SkyAGI](https://github.com/litanlitudan/skyagi): Emerging human-behavior simulation capability in LLM agents [![](https://camo.githubusercontent.com/4546ad03ef3423599f31e2e32f3d2998c24974dd578ef51ad97b3abbb8a3dc50/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c6974616e6c69747564616e2f736b796167693f7374796c653d736f6369616c)](https://camo.githubusercontent.com/4546ad03ef3423599f31e2e32f3d2998c24974dd578ef51ad97b3abbb8a3dc50/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c6974616e6c69747564616e2f736b796167693f7374796c653d736f6369616c)
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI): A small AGI experiment to generate a Python app given what app the user wants to build [![](https://camo.githubusercontent.com/91d14cb4a900173d6244817ec5c14419e08d01fcf823700d30cd2401b888f5b0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6368616b6b617261646565702f7079436f64654147493f7374796c653d736f6369616c)](https://camo.githubusercontent.com/91d14cb4a900173d6244817ec5c14419e08d01fcf823700d30cd2401b888f5b0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6368616b6b617261646565702f7079436f64654147493f7374796c653d736f6369616c)
- [BabyAGI UI](https://github.com/miurla/babyagi-ui): Make it easier to run and develop with babyagi in a web app, like a ChatGPT [![](https://camo.githubusercontent.com/a8f5e8865c07989547d2c47d284b7de1744f0fbfb3f5fe6303285374a766594f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6975726c612f626162796167692d75693f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a8f5e8865c07989547d2c47d284b7de1744f0fbfb3f5fe6303285374a766594f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6975726c612f626162796167692d75693f7374796c653d736f6369616c)
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat): implement LLM with RLHF, powered by the Colossal-AI project [![](https://camo.githubusercontent.com/a294d2683fcc9c5a7d3606036c8f40f711045255ade0d47000a607e620f8fd77/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6870636169746563682f436f6c6f7373616c41493f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a294d2683fcc9c5a7d3606036c8f40f711045255ade0d47000a607e620f8fd77/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6870636169746563682f436f6c6f7373616c41493f7374796c653d736f6369616c)
- [SuperAgent](https://github.com/homanp/superagent): Deploy LLM Agents to production [![](https://camo.githubusercontent.com/a7df1f9b460cdfb2185b935b4c0d2065b846a95518abc3d9b0204dda3f4224d0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f686f6d616e702f73757065726167656e743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a7df1f9b460cdfb2185b935b4c0d2065b846a95518abc3d9b0204dda3f4224d0/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f686f6d616e702f73757065726167656e743f7374796c653d736f6369616c)
- [ix](https://github.com/kreneskyp/ix): Autonomous GPT-4 agent platform
- [DuetGPT](https://github.com/kristoferlund/duet-gpt): A conversational semi-autonomous developer assistant, AI pair programming without the copypasta. [![](https://camo.githubusercontent.com/c641b4611f161e9c430cc9cd4ba42bbbc993db32cc9e4b8e39614d88ed8bb6d8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6b726973746f6665726c756e642f647565742d6770743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c641b4611f161e9c430cc9cd4ba42bbbc993db32cc9e4b8e39614d88ed8bb6d8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6b726973746f6665726c756e642f647565742d6770743f7374796c653d736f6369616c)

### 
### Templates
- [create-t3-turbo-ai](https://github.com/zckly/create-t3-turbo-ai): t3 based, Langchain-friendly boilerplate for building type-safe, full-stack, LLM-powered web apps with Nextjs and Prisma [![](https://camo.githubusercontent.com/be0fec1598a9e399614998e99614698be34e38cfa1e49119c7163bab0d086f0f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7a636b6c792f6372656174652d74332d747572626f2d61693f7374796c653d736f6369616c)](https://camo.githubusercontent.com/be0fec1598a9e399614998e99614698be34e38cfa1e49119c7163bab0d086f0f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7a636b6c792f6372656174652d74332d747572626f2d61693f7374796c653d736f6369616c)
- [LangChain.js LLM Template](https://github.com/Conner1115/LangChain.js-LLM-Template): LangChain LLM template that allows you to train your own custom AI LLM model. [![](https://camo.githubusercontent.com/8789af1935a695b9973b81795d513aa7cce5f3206c0c1fb92b0f8b7c372c69ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f436f6e6e6572313131352f4c616e67436861696e2e6a732d4c4c4d2d54656d706c6174653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/8789af1935a695b9973b81795d513aa7cce5f3206c0c1fb92b0f8b7c372c69ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f436f6e6e6572313131352f4c616e67436861696e2e6a732d4c4c4d2d54656d706c6174653f7374796c653d736f6369616c)
- [Streamlit Template](https://github.com/hwchase17/langchain-streamlit-template): template for how to deploy a LangChain on Streamlit [![](https://camo.githubusercontent.com/58c68659e9cbd2320ba8e95f39d107f198f9494df9b9a572c285a14945cd6158/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e2d73747265616d6c69742d74656d706c6174653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/58c68659e9cbd2320ba8e95f39d107f198f9494df9b9a572c285a14945cd6158/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e2d73747265616d6c69742d74656d706c6174653f7374796c653d736f6369616c)
- [Codespaces Template](https://github.com/lostintangent/codespaces-langchain): a Codespaces template for getting up-and-running with LangChain in seconds! [![](https://camo.githubusercontent.com/48c12a002fffa01390175ab943dcb85e3e242c2109dd4b2bf7f24d95517a5188/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c6f7374696e74616e67656e742f636f64657370616365732d6c616e67636861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/48c12a002fffa01390175ab943dcb85e3e242c2109dd4b2bf7f24d95517a5188/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c6f7374696e74616e67656e742f636f64657370616365732d6c616e67636861696e3f7374796c653d736f6369616c)
- [Gradio Template](https://github.com/hwchase17/langchain-gradio-template): template for how to deploy a LangChain on Gradio [![](https://camo.githubusercontent.com/ce54042bf524fdbef5961f2d72191386cbe10cdedaf15e4f77bfa8f2ea4ab59c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e2d67726164696f2d74656d706c6174653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/ce54042bf524fdbef5961f2d72191386cbe10cdedaf15e4f77bfa8f2ea4ab59c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6c616e67636861696e2d67726164696f2d74656d706c6174653f7374796c653d736f6369616c)

### 
### Platforms
- [Modal](https://modal.com/docs/guide/ex/potus_speech_qanda): End-to-end stack for cloud/ML compute
- [Metal](https://getmetal.io/): Metal is a managed service that allows you to build AI products without the hassle of managing infrastructure
- [Graphsignal](https://graphsignal.com/): Observability for AI agents and LLM-powered applications. Trace, monitor and debug LangChain in production.

## 
## Open Source Projects
### 
### Knowledge Management
- [DocsGPT](https://github.com/arc53/docsgpt): GPT-powered chat for documentation search & assistance. [![](https://camo.githubusercontent.com/a41725f3992f3cd17f51738c72075cfa9d555d35723491e12ad767284d94bb30/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f61726335332f646f63736770743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a41725f3992f3cd17f51738c72075cfa9d555d35723491e12ad767284d94bb30/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f61726335332f646f63736770743f7374796c653d736f6369616c)
- [Knowledge GPT](https://github.com/mmz-001/knowledge_gpt): Accurate answers and instant citations for your documents. [![](https://camo.githubusercontent.com/a3ed3202ccc6ba7768991d4f8e978547650a294663e9b3238d0603c6f176446c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6d7a2d3030312f6b6e6f776c656467655f6770743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a3ed3202ccc6ba7768991d4f8e978547650a294663e9b3238d0603c6f176446c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6d7a2d3030312f6b6e6f776c656467655f6770743f7374796c653d736f6369616c)
- [Quiver](https://github.com/StanGirard/quiver): Dump your brain into your GenerativeAI Vault [![](https://camo.githubusercontent.com/9bcf87647186c1535768ad6870eedb60510c95ee5788a8ba9bbe12e676912b32/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f5374616e4769726172642f7175697665723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/9bcf87647186c1535768ad6870eedb60510c95ee5788a8ba9bbe12e676912b32/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f5374616e4769726172642f7175697665723f7374796c653d736f6369616c)
- [Knowledge](https://github.com/KnowledgeCanvas/knowledge): Knowledge is a tool for saving, searching, accessing, and exploring all of your favorite websites, documents and files. [![](https://camo.githubusercontent.com/c8617c494b060b8796fd65df50225be793297c22b96f2849a9084ca6d040320b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4b6e6f776c6564676543616e7661732f6b6e6f776c656467653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c8617c494b060b8796fd65df50225be793297c22b96f2849a9084ca6d040320b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4b6e6f776c6564676543616e7661732f6b6e6f776c656467653f7374796c653d736f6369616c)

### 
### Other / Chatbots
- [AudioGPT](https://github.com/AIGC-Audio/AudioGPT): Understanding and Generating Speech, Music, Sound, and Talking Head [![](https://camo.githubusercontent.com/5470b3c3dc42d53dc2278c61da746ca64a977dc3a07b176b0681a6332a69fc29/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f414947432d417564696f2f417564696f4750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/5470b3c3dc42d53dc2278c61da746ca64a977dc3a07b176b0681a6332a69fc29/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f414947432d417564696f2f417564696f4750543f7374796c653d736f6369616c)
- [Paper QA](https://github.com/whitead/paper-qa): LLM Chain for answering questions from documents with citations [![](https://camo.githubusercontent.com/dba68995d8c57a8f685b08c2a8c4597b37cdc2c18cbcabc861da7c233bb0c759/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f776869746561642f70617065722d71613f7374796c653d736f6369616c)](https://camo.githubusercontent.com/dba68995d8c57a8f685b08c2a8c4597b37cdc2c18cbcabc861da7c233bb0c759/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f776869746561642f70617065722d71613f7374796c653d736f6369616c)
- [Chat Langchain](https://github.com/hwchase17/chat-langchain): locally hosted chatbot specifically focused on question answering over the LangChain documentation [![](https://camo.githubusercontent.com/c59033679486f2a986cbce41c685156cf24dbbacf54a121865ec45001a37369b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f636861742d6c616e67636861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c59033679486f2a986cbce41c685156cf24dbbacf54a121865ec45001a37369b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f636861742d6c616e67636861696e3f7374796c653d736f6369616c)
- [Langchain Chat](https://github.com/zahidkhawaja/langchain-chat-nextjs): another Next.js frontend for LangChain Chat. [![](https://camo.githubusercontent.com/041179065940c15acf156b3cea8dbc29abb5d68315bfd081ea81a66da9469950/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7a616869646b686177616a612f6c616e67636861696e2d636861742d6e6578746a733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/041179065940c15acf156b3cea8dbc29abb5d68315bfd081ea81a66da9469950/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7a616869646b686177616a612f6c616e67636861696e2d636861742d6e6578746a733f7374796c653d736f6369616c)
- [Book GPT](https://github.com/fraserxu/book-gpt): drop a book, start asking question. [![](https://camo.githubusercontent.com/6060f86aad12f6395748728471eccf47e34a979ca7a3b3de3cc4151c851cb044/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f66726173657278752f626f6f6b2d6770743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/6060f86aad12f6395748728471eccf47e34a979ca7a3b3de3cc4151c851cb044/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f66726173657278752f626f6f6b2d6770743f7374796c653d736f6369616c)
- [Chat LangchainJS](https://github.com/sullivan-sean/chat-langchainjs): NextJS version of Chat Langchain [![](https://camo.githubusercontent.com/ee835cb4cdd9c898ed127ebeca4f49ff99e828f95cfb6dcd44e1f61c5a53d41f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f73756c6c6976616e2d7365616e2f636861742d6c616e67636861696e6a733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/ee835cb4cdd9c898ed127ebeca4f49ff99e828f95cfb6dcd44e1f61c5a53d41f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f73756c6c6976616e2d7365616e2f636861742d6c616e67636861696e6a733f7374796c653d736f6369616c)
- [Doc Search](https://github.com/namuan/dr-doc-search): converse with book - Built with GPT-3 [![](https://camo.githubusercontent.com/d3d5fa76bb6d0423c7a9ab58dfe27ed6efdf2c195abd4d6f663427f27056ab1c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6e616d75616e2f64722d646f632d7365617263683f7374796c653d736f6369616c)](https://camo.githubusercontent.com/d3d5fa76bb6d0423c7a9ab58dfe27ed6efdf2c195abd4d6f663427f27056ab1c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6e616d75616e2f64722d646f632d7365617263683f7374796c653d736f6369616c)
- [Fact Checker](https://github.com/jagilley/fact-checker): fact-checking LLM outputs with langchain [![](https://camo.githubusercontent.com/4f9cacaadb278a862999316c57d35487cfc172c374dfe1e918b39ed7fe4051f8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a6167696c6c65792f666163742d636865636b65723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/4f9cacaadb278a862999316c57d35487cfc172c374dfe1e918b39ed7fe4051f8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a6167696c6c65792f666163742d636865636b65723f7374796c653d736f6369616c)
- [MM ReAct](https://github.com/microsoft/MM-REACT): Multi Modal ReAct Design
- [QABot](https://github.com/hardbyte/qabot): Query local or remote files or databases with natural language queries powered by langchain and openai [![](https://camo.githubusercontent.com/99662d4f67ba8bbea0278d6e4d28a8e9c5238ab0dd985bf0dc5cf6461f57c6c1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f68617264627974652f7161626f743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/99662d4f67ba8bbea0278d6e4d28a8e9c5238ab0dd985bf0dc5cf6461f57c6c1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f68617264627974652f7161626f743f7374796c653d736f6369616c)
- [GPT Automator](https://github.com/chidiwilliams/GPT-Automator): Your voice-controlled Mac assistant. [![](https://camo.githubusercontent.com/55381e9fcb24b4d3e72ded6717a7d400b760d9d95707d4aaa978a30459565bde/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f636869646977696c6c69616d732f4750542d4175746f6d61746f723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/55381e9fcb24b4d3e72ded6717a7d400b760d9d95707d4aaa978a30459565bde/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f636869646977696c6c69616d732f4750542d4175746f6d61746f723f7374796c653d736f6369616c)
- [Teams LangchainJS](https://github.com/SidU/teams-langchain-js): Demonstration of LangChainJS with Teams / Bot Framework bots [![](https://camo.githubusercontent.com/ea86ee696c48e223c36ebfc0baa784a10cc3d4cce25d47b4c3d77834e27c10e9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f536964552f7465616d732d6c616e67636861696e2d6a733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/ea86ee696c48e223c36ebfc0baa784a10cc3d4cce25d47b4c3d77834e27c10e9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f536964552f7465616d732d6c616e67636861696e2d6a733f7374796c653d736f6369616c)
- [ChatGPT](https://github.com/biff-ai/chatgpt-langchainjs-example): ChatGPT & langchain example for node.js & Docker [![](https://camo.githubusercontent.com/dde2d69bc7dafbb5fc89bd0046314e8f73d0601807126d3cd22f43c6bdb874a5/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f626966662d61692f636861746770742d6c616e67636861696e6a732d6578616d706c653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/dde2d69bc7dafbb5fc89bd0046314e8f73d0601807126d3cd22f43c6bdb874a5/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f626966662d61692f636861746770742d6c616e67636861696e6a732d6578616d706c653f7374796c653d736f6369616c)
- [FlowGPT](https://github.com/nilooy/flowgpt): Generate diagram with AI [![](https://camo.githubusercontent.com/e15d208eab49cb5cf60063ca518ba0ccd9e462ba58d39d15d98a03cb0b027c88/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6e696c6f6f792f666c6f776770743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/e15d208eab49cb5cf60063ca518ba0ccd9e462ba58d39d15d98a03cb0b027c88/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6e696c6f6f792f666c6f776770743f7374796c653d736f6369616c)
- [langchain-text-summarizer](https://github.com/alphasecio/langchain-text-summarizer): A sample streamlit application summarizing text using LangChain [![](https://camo.githubusercontent.com/96e633813d55ac19437cd9e1d0e2f9cebde40212ea3c0d5656599e303e3f934d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616c706861736563696f2f6c616e67636861696e2d746578742d73756d6d6172697a65723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/96e633813d55ac19437cd9e1d0e2f9cebde40212ea3c0d5656599e303e3f934d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616c706861736563696f2f6c616e67636861696e2d746578742d73756d6d6172697a65723f7374796c653d736f6369616c)
- [Langchain Chat Websocket](https://github.com/pors/langchain-chat-websockets): About LangChain LLM chat with streaming response over websockets [![](https://camo.githubusercontent.com/7861ad47175002b4345b10d9bc16cd1229eea9c6378d6652528437ac84afbf95/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f706f72732f6c616e67636861696e2d636861742d776562736f636b6574733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/7861ad47175002b4345b10d9bc16cd1229eea9c6378d6652528437ac84afbf95/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f706f72732f6c616e67636861696e2d636861742d776562736f636b6574733f7374796c653d736f6369616c)
- [langchain_yt_tools](https://github.com/venuv/langchain_yt_tools): Langchain tools to search/extract/transcribe text transcripts of Youtube videos [![](https://camo.githubusercontent.com/21fd2e1ca841205ca16498d558765d9e71eedb6cecb76df2e484e9fd8bbf1dae/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f76656e75762f6c616e67636861696e5f79745f746f6f6c733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/21fd2e1ca841205ca16498d558765d9e71eedb6cecb76df2e484e9fd8bbf1dae/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f76656e75762f6c616e67636861696e5f79745f746f6f6c733f7374796c653d736f6369616c)
- [SmartPilot](https://github.com/jaredkirby/SmartPilot): A Python program leveraging OpenAI's language models to generate, analyze, and select the best answer to a given question [![](https://camo.githubusercontent.com/e9e112b8ab909283debe21344eeed0e59cc18f921f1598a84da5c0c25bb2c98b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a617265646b697262792f536d61727450696c6f743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/e9e112b8ab909283debe21344eeed0e59cc18f921f1598a84da5c0c25bb2c98b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a617265646b697262792f536d61727450696c6f743f7374796c653d736f6369616c)
- [Howdol](https://github.com/bborn/howdoi.ai): a helpful chatbot that can answer questions [![](https://camo.githubusercontent.com/b36d4996863f2bd44c45d58ca7984340ac863bc8b20ee7e5cf12eb54a13782fb/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f62626f726e2f686f77646f692e61693f7374796c653d736f6369616c)](https://camo.githubusercontent.com/b36d4996863f2bd44c45d58ca7984340ac863bc8b20ee7e5cf12eb54a13782fb/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f62626f726e2f686f77646f692e61693f7374796c653d736f6369616c)
- [MrsStax](https://github.com/normandmickey/MrsStax): QA Slack Bot [![](https://camo.githubusercontent.com/eb9978fa70e5f4d17926f90f0cf0df1f778eb195c1a1396e168bb91624423ba1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6e6f726d616e646d69636b65792f4d7273537461783f7374796c653d736f6369616c)](https://camo.githubusercontent.com/eb9978fa70e5f4d17926f90f0cf0df1f778eb195c1a1396e168bb91624423ba1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6e6f726d616e646d69636b65792f4d7273537461783f7374796c653d736f6369616c)
- [ThoughtSource⚡](https://github.com/OpenBioLink/ThoughtSource): A framework for the science of machine thinking [![](https://camo.githubusercontent.com/653a1cd642671af399ad8f5d73295542d50c562294449228a38a638c2448a090/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4f70656e42696f4c696e6b2f54686f75676874536f757263653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/653a1cd642671af399ad8f5d73295542d50c562294449228a38a638c2448a090/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4f70656e42696f4c696e6b2f54686f75676874536f757263653f7374796c653d736f6369616c)
- [ChatGPT Langchain](https://huggingface.co/spaces/JavaFXpert/Chat-GPT-LangChain): ChatGPT clone using langchain on Huggingface
- [Chat Math Techniques](https://huggingface.co/spaces/JavaFXpert/gpt-math-techniques): langchain chat with math techniques on Huggingface
- [Notion QA](https://github.com/hwchase17/notion-qa): Notion Question-Answering Bot [![](https://camo.githubusercontent.com/75bda4b7eff8eb8fcbad3992822de97bfd27d774b6da8ae7f09a1102e4a4b81a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6e6f74696f6e2d71613f7374796c653d736f6369616c)](https://camo.githubusercontent.com/75bda4b7eff8eb8fcbad3992822de97bfd27d774b6da8ae7f09a1102e4a4b81a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6877636861736531372f6e6f74696f6e2d71613f7374796c653d736f6369616c)
- [QNimGPT](https://huggingface.co/spaces/rituthombre/QNim): Play Nim against an IBM Quantum Computer simulator or OpenAI GPT-3.5 [![](https://camo.githubusercontent.com/e3542647046c43291c0c731d810161bb137c5af7736b67753f3f865ae2e48a5f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7269747574686f6d6272652f514e696d3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/e3542647046c43291c0c731d810161bb137c5af7736b67753f3f865ae2e48a5f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7269747574686f6d6272652f514e696d3f7374796c653d736f6369616c)
- [ChatPDF](https://github.com/akshata29/chatpdf): ChatGPT + Enterprise data with Azure OpenAI [![](https://camo.githubusercontent.com/d5098faa9a4f6b26495a0362803705327055023b92e107993684aed0dfef0d71/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616b736861746132392f636861747064663f7374796c653d736f6369616c)](https://camo.githubusercontent.com/d5098faa9a4f6b26495a0362803705327055023b92e107993684aed0dfef0d71/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616b736861746132392f636861747064663f7374796c653d736f6369616c)
- [Chat with Scanned Documents](https://github.com/tony-xlh/Chat-with-Scanned-Documents): A demo chatting with documents scanned with Dynamic Web TWAIN.
- [snowChat ❄️](https://github.com/kaarthik108/snowChat): Chat with you're snowflake database [![](https://camo.githubusercontent.com/582065323c330dde6d02694d14e58f519f48c4a7cd524219ea2700de4bf35067/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6b6161727468696b3130382f736e6f77436861743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/582065323c330dde6d02694d14e58f519f48c4a7cd524219ea2700de4bf35067/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6b6161727468696b3130382f736e6f77436861743f7374796c653d736f6369616c)
- [DB GPT](https://github.com/csunny/DB-GPT): Interact your data and environment using the local GPT, no data leaks, 100% privately, 100% security [![](https://camo.githubusercontent.com/3bcfab955ea5ab9ecc0f8c6328861f8aff429cbfd068f58cdca34b61b6627fb6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6373756e6e792f44422d4750543f7374796c653d736f6369616c)](https://camo.githubusercontent.com/3bcfab955ea5ab9ecc0f8c6328861f8aff429cbfd068f58cdca34b61b6627fb6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6373756e6e792f44422d4750543f7374796c653d736f6369616c)
- [Psychic](https://github.com/psychic-api/psychic): Universal APIs for unstructured data. Sync documents from SaaS tools to a SQL or vector database, where they can be easily queried by AI applications like ChatGPT. [![](https://camo.githubusercontent.com/4216d2048d50dd82bf9c3130f90a30c4cdcf5636659278504fa1da8d276c069b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f707379636869632d6170692f707379636869633f7374796c653d736f6369616c)](https://camo.githubusercontent.com/4216d2048d50dd82bf9c3130f90a30c4cdcf5636659278504fa1da8d276c069b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f707379636869632d6170692f707379636869633f7374796c653d736f6369616c)
- [Airtable-QnA](https://github.com/ikram-shah/airtable-qna): 🌟 a question-answering tool for your Airtable content
- [Voyager](https://github.com/MineDojo/Voyager): An Open-Ended Embodied Agent with Large Language Models [![](https://camo.githubusercontent.com/f5727e805f338b458d65c6474a276368a5d64648c3574cfdb774cef15d41951a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4d696e65446f6a6f2f566f79616765723f7374796c653d736f6369616c)](https://camo.githubusercontent.com/f5727e805f338b458d65c6474a276368a5d64648c3574cfdb774cef15d41951a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4d696e65446f6a6f2f566f79616765723f7374796c653d736f6369616c)
- [WingmanAI](https://github.com/e-johnstonn/wingmanAI): tool for interacting with real-time transcription of both system and microphone audio

## 
## Learn
### 
### Notebooks
- [Langchain Tutorials](https://github.com/gkamradt/langchain-tutorials): overview and tutorial of the LangChain Library [![](https://camo.githubusercontent.com/642d3cd81c698a80bf78ad73b79767f0b6ab8f09c28fc8236b14f38ddf46227b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f676b616d726164742f6c616e67636861696e2d7475746f7269616c733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/642d3cd81c698a80bf78ad73b79767f0b6ab8f09c28fc8236b14f38ddf46227b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f676b616d726164742f6c616e67636861696e2d7475746f7269616c733f7374796c653d736f6369616c)
- [LangChain Chinese Getting Started Guide](https://github.com/liaokongVFX/LangChain-Chinese-Getting-Started-Guide): Chinese LangChain Tutorial for Beginners [![](https://camo.githubusercontent.com/1c2670db501e3ace6a3a812617a9f0a6dda558b6f7401c4108f6ed512b956c61/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c69616f6b6f6e675646582f4c616e67436861696e2d4368696e6573652d47657474696e672d537461727465642d47756964653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/1c2670db501e3ace6a3a812617a9f0a6dda558b6f7401c4108f6ed512b956c61/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6c69616f6b6f6e675646582f4c616e67436861696e2d4368696e6573652d47657474696e672d537461727465642d47756964653f7374796c653d736f6369616c)
- [Flan5 LLM](https://colab.research.google.com/drive/1AVh9dOsG9DKzfK7gOFrJuitPIcLPqlbO?usp=sharing): PDF QA using LangChain for chain of thought and multi-task instructions, Flan5 on HuggingFace
- [LangChain Handbook](https://github.com/pinecone-io/examples/tree/master/generation/langchain/handbook): Pinecone / James Briggs' LangChain handbook
- [Query the YouTube video transcripts](https://colab.research.google.com/drive/1sKSTjt9cPstl_WMZ86JsgEqFG-aSAwkn?usp=sharing): Query the YouTube video transcripts, returning timestamps as sources to legitimize the answers
- [llm-lobbyist](https://github.com/JohnNay/llm-lobbyist): Large Language Models as Corporate Lobbyists
- [Langchain Semantic Search](https://github.com/venuv/langchain_semantic_search): Search and indexing your own Google Drive Files using GPT3, LangChain, and Python
- [GPT Political Compass](https://colab.research.google.com/drive/1xt2IsFPGYMEQdoJFNgWNAjWGxa60VXdV)
- [llm-grovers-search-party](https://github.com/JavaFXpert/llm-grovers-search-party): Leveraging Qiskit, OpenAI and LangChain to demonstrate Grover's algorithm
- [TextWorld ReAct Agent](https://colab.research.google.com/drive/19WTIWC3prw5LDMHmRMvqNV2loD9FHls6?usp=sharing)
- [LangChain <> Wolfram Alpha](https://colab.research.google.com/drive/1AAyEdTz-Z6ShKvewbt1ZHUICqak0MiwR?usp=sharing)
- [BYO Knowledge Graph](https://github.com/prof-frink-lab/slangchain/blob/main/docs/modules/knowledge_graph/examples/byo_knowledge_graph.ipynb)

### 
### Videos
- [LangChain for LLM Application Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)
- [LangChain Series by Sam Witteveen](https://www.youtube.com/watch?v=J_0qvRt4LNk&list=PL8motc6AQftk1Bs42EW45kwYbyJ4jOdiZ)
- [LangChain Tutorials Playlist](https://www.youtube.com/playlist?list=PL611FKPtL866MnlDPHvI3KwVGqCB-QJAx)
- [LangChain James Briggs' Playlist](https://www.youtube.com/watch?v=nE2skSRWTTs&list=PLIUOU7oqGTLieV9uTIFMm6_4PXg-hlN6F)
- [What Is LangChain? - LangChain + ChatGPT Overview](https://www.youtube.com/watch?v=_v_fgW2SkkQ)
- [LangChain Demo + Q&A with Harrison Chase](https://www.youtube.com/watch?v=zaYTXQFR0_s)
- [LangChain for LLMs is... basically just an Ansible playbook](https://www.youtube.com/watch?v=X51N9C-OhlE) (David Shapiro)
- [Data Independent Playlist](https://www.youtube.com/watch?v=_v_fgW2SkkQ&list=PLqZXAkvF1bPNQER9mLmDbntNfSpzdDIU5)
- [Langchain Agent Webinar](https://www.crowdcast.io/c/46erbpbz609r)
- [BabyAGI with LangChain](https://www.youtube.com/watch?v=DRgPyOXZ-oE)
- [LangChain Tutorial in Python - Crash Course](https://www.python-engineer.com/posts/langchain-crash-course/)
- [LangChain Crash Course: Build a AutoGPT ](https://www.youtube.com/watch?v=MlK6SIjcjE8)(Nicholas Renotte)
- [LangChain and the Future of LLM Agents](https://www.youtube.com/watch?v=JwO08Pk6S_Q&t=4s)

### 
### Articles
- [Build a GitHub support bot with GPT3, LangChain, and Python](https://dagster.io/blog/chatgpt-langchain)
- [The Emergence Of Large Language Model (LLM) API Build Frameworks](https://cobusgreyling.medium.com/the-emergence-of-large-language-model-llm-api-build-frameworks-78d83d68eeda)
- [How I used LangChain 🦜🔗 and GPT-3 to Automate my Boss 🤖](https://dev.to/ironcladdev/how-i-used-langchain-and-gpt-3-to-automate-my-boss-3bk4)
- [Multilingual Semantic Search with Cohere and Langchain](https://txt.cohere.ai/search-cohere-langchain/)
- [How Haystack and LangChain are Empowering Large Language Models](https://mantiumai.com/blog/how-haystack-and-langchain-are-empowering-large-language-models/)
- [DataIndependent Tutorials](https://github.com/gkamradt/langchain-tutorials)
- [Build an Ecommerce Chatbot With Redis, LangChain, and OpenAI](https://redis.com/blog/build-ecommerce-chatbot-with-redis/)
- [Getting Started with LangChain: A Beginner’s Guide to Building LLM-Powered Applications](https://towardsdatascience.com/getting-started-with-langchain-a-beginners-guide-to-building-llm-powered-applications-95fc8898732c)
- [How To Use LangChain with LLM Agent Monitoring To Fine-Tune Your LLM Apps](https://arize.com/blog-course/langchain-llm-agent-monitoring/)
- [Build a Simple ChatGPT CLI with memory](https://getmetal.io/posts/07-tutorial-motorhead-cli)
- [Deploy a Voice-Based Chatbot with BentoML, LangChain, and Gradio](https://towardsdatascience.com/deploy-a-voice-based-chatbot-with-bentoml-langchain-and-gradio-7f25af3e45df)
- [LangChain tutorial at PromptChap](https://promptchap.com/)
- [Create a Code Interpreter Chatbot with Pyodide, LangChain, and OpenAI](https://dylancastillo.co/code-interpreter-chatbot-pyodide-langchain-openai/)
- [LangChain has added Cypher Search](https://towardsdatascience.com/langchain-has-added-cypher-search-cb9d821120d5)
- [Langchain Decoded](https://alphasec.io/langchain-decoded-the-muggles-guide-to-langchain/)
- [Implementing GPT4All Locally with Python and Langchain](https://medium.datadriveninvestor.com/offline-ai-magic-implementing-gpt4all-locally-with-python-b51971ce80af)
- [GPT your GDrive with LangChain](https://www.haihai.ai/gpt-gdrive/)

## 
## Alternatives
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents): Provides a natural language API on top of transformers
- [LlamaIndex](https://github.com/jerryjliu/llama_index): provides a central interface to connect your LLM's with external data. [![](https://camo.githubusercontent.com/b71839c374e0f66d0a648dfbdcc50dc8f82a05190aabee3e7e1af8efbdd59448/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a657272796a6c69752f6c6c616d615f696e6465783f7374796c653d736f6369616c)](https://camo.githubusercontent.com/b71839c374e0f66d0a648dfbdcc50dc8f82a05190aabee3e7e1af8efbdd59448/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6a657272796a6c69752f6c6c616d615f696e6465783f7374796c653d736f6369616c)
- [Botpress](https://github.com/botpress/botpress): The building blocks for building chatbots [![](https://camo.githubusercontent.com/e27eeef7b262ccf2d6a30dcb63d7f9df4042e6a9d096fe2239de721b898ea588/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f626f7470726573732f626f7470726573733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/e27eeef7b262ccf2d6a30dcb63d7f9df4042e6a9d096fe2239de721b898ea588/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f626f7470726573732f626f7470726573733f7374796c653d736f6369616c)
- [Haystack](https://github.com/deepset-ai/haystack): NLP framework to interact with your data using Transformer models and LLMs [![](https://camo.githubusercontent.com/218024f0ff54369f855336782710773b791a9249b01c132a01d9d358d18b78d4/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f646565707365742d61692f686179737461636b3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/218024f0ff54369f855336782710773b791a9249b01c132a01d9d358d18b78d4/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f646565707365742d61692f686179737461636b3f7374796c653d736f6369616c)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): Microsoft C# SDK to integrate cutting-edge LLM technology quickly and easily into your apps [![](https://camo.githubusercontent.com/0c8ed625bbebf26eafaaedf292e634000d328848a5a2ac2fcafbbd88733b3c60/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6963726f736f66742f73656d616e7469632d6b65726e656c3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/0c8ed625bbebf26eafaaedf292e634000d328848a5a2ac2fcafbbd88733b3c60/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d6963726f736f66742f73656d616e7469632d6b65726e656c3f7374796c653d736f6369616c)
- [Promptify](https://github.com/promptslab/Promptify): Prompt Engineering | Use GPT or other prompt based models to get structured output. [![](https://camo.githubusercontent.com/fb7a18c8e3a6a388d9d8c051728dff99856954ad9577bb26dffb08800fb378ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f70726f6d7074736c61622f50726f6d70746966793f7374796c653d736f6369616c)](https://camo.githubusercontent.com/fb7a18c8e3a6a388d9d8c051728dff99856954ad9577bb26dffb08800fb378ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f70726f6d7074736c61622f50726f6d70746966793f7374796c653d736f6369616c)
- [PromptSource](https://github.com/bigscience-workshop/promptsource): About Toolkit for creating, sharing and using natural language prompts. [![](https://camo.githubusercontent.com/9ec4b56ec5cb8db9de1c882aec3288814dbaae61879d35b6371817c324dca465/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f626967736369656e63652d776f726b73686f702f70726f6d7074736f757263653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/9ec4b56ec5cb8db9de1c882aec3288814dbaae61879d35b6371817c324dca465/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f626967736369656e63652d776f726b73686f702f70726f6d7074736f757263653f7374796c653d736f6369616c)
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM): An Artificial Intelligence Automation Platform. [![](https://camo.githubusercontent.com/4649baddc026d521e526188b7195043cb5cc05e1ba8af77c7ed78a60984490ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4a6f73682d58542f4167656e742d4c4c4d3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/4649baddc026d521e526188b7195043cb5cc05e1ba8af77c7ed78a60984490ee/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4a6f73682d58542f4167656e742d4c4c4d3f7374796c653d736f6369616c)
- [LLM Agents](https://github.com/mpaepper/llm_agents): Build agents which are controlled by LLMs [![](https://camo.githubusercontent.com/038e74d24a91dd6f5399618900607ddf63607729032443fd40d54eac2a5b3fe7/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d706165707065722f6c6c6d5f6167656e74733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/038e74d24a91dd6f5399618900607ddf63607729032443fd40d54eac2a5b3fe7/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6d706165707065722f6c6c6d5f6167656e74733f7374796c653d736f6369616c)
- [MiniChain](https://github.com/srush/MiniChain): A tiny library for coding with large language models. [![](https://camo.githubusercontent.com/1932058a2e0df4209bfc4f606e5a24f2fc08616dd2d6f01adc5f32c71b7fefeb/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f73727573682f4d696e69436861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/1932058a2e0df4209bfc4f606e5a24f2fc08616dd2d6f01adc5f32c71b7fefeb/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f73727573682f4d696e69436861696e3f7374796c653d736f6369616c)
- [Griptape](https://github.com/griptape-ai/griptape): Python framework for AI workflows and pipelines with chain of thought reasoning, external tools, and memory. [![](https://camo.githubusercontent.com/a0e1fbbcdb14d7c875753f1e2ccd59e2d543ed559a2fd7a65934324f1bd019b8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f67726970746170652d61692f67726970746170653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/a0e1fbbcdb14d7c875753f1e2ccd59e2d543ed559a2fd7a65934324f1bd019b8/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f67726970746170652d61692f67726970746170653f7374796c653d736f6369616c)
- [llm-chain](https://github.com/sobelio/llm-chain): is a powerful rust crate for building chains in LLMs allowing you to summarise text and complete complex tasks. [![](https://camo.githubusercontent.com/c9be0faf35d5044a80d3761932cfc02316edaba778512d98a46c66d2d75ebcd9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f736f62656c696f2f6c6c6d2d636861696e3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/c9be0faf35d5044a80d3761932cfc02316edaba778512d98a46c66d2d75ebcd9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f736f62656c696f2f6c6c6d2d636861696e3f7374796c653d736f6369616c)
- [BoxCars](https://github.com/BoxcarsAI/boxcars): Ruby gem, Building applications with composability using Boxcars with LLM's. Inspired by LangChain. [![](https://camo.githubusercontent.com/e26e61c79121588cd06e0d6a66aa69f22fcd222bbe6eca0951d8e4ab6267c7b2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f426f786361727341492f626f78636172733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/e26e61c79121588cd06e0d6a66aa69f22fcd222bbe6eca0951d8e4ab6267c7b2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f426f786361727341492f626f78636172733f7374796c653d736f6369616c)
- [LangTorch](https://github.com/Knowly-ai/langtorch): Building composable LLM applications with Java / JVM. Inspired by LangChain. [![](https://camo.githubusercontent.com/11cfd1693f5867155bc206215563505310f50c4e065f6d5fc69b0569a1a41141/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4b6e6f776c792d61692f6c616e67746f7263683f7374796c653d736f6369616c)](https://camo.githubusercontent.com/11cfd1693f5867155bc206215563505310f50c4e065f6d5fc69b0569a1a41141/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f4b6e6f776c792d61692f6c616e67746f7263683f7374796c653d736f6369616c)
- [Langchain Go](https://github.com/tmc/langchaingo): Golang Langchain [![](https://camo.githubusercontent.com/7725f4f6e2147276d02cc4f64d8100981661adbe6386341703f98efaa4f30cef/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f746d632f6c616e67636861696e676f3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/7725f4f6e2147276d02cc4f64d8100981661adbe6386341703f98efaa4f30cef/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f746d632f6c616e67636861696e676f3f7374796c653d736f6369616c)
- [LangchainRb](https://github.com/andreibondarev/langchainrb): Ruby Langchain [![](https://camo.githubusercontent.com/55c4a1afcfa5004b5db84b27598c8e48328b55aa5695dadac63fae8e4948fd89/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616e64726569626f6e64617265762f6c616e67636861696e72623f7374796c653d736f6369616c)](https://camo.githubusercontent.com/55c4a1afcfa5004b5db84b27598c8e48328b55aa5695dadac63fae8e4948fd89/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f616e64726569626f6e64617265762f6c616e67636861696e72623f7374796c653d736f6369616c)
- [PromptFlow](https://github.com/InsuranceToolkits/promptflow): Create executable flowcharts that link LLMs (Large Language Models), Prompts, Python functions, and conditional logic together. [![](https://camo.githubusercontent.com/58247d00081ed0704506361fe79d30d783413e7ca30368c32fba2faf5ef9381a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f496e737572616e6365546f6f6c6b6974732f70726f6d7074666c6f773f7374796c653d736f6369616c)](https://camo.githubusercontent.com/58247d00081ed0704506361fe79d30d783413e7ca30368c32fba2faf5ef9381a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f496e737572616e6365546f6f6c6b6974732f70726f6d7074666c6f773f7374796c653d736f6369616c)
- [OpenLM](https://github.com/r2d4/openlm): a drop-in OpenAI-compatible library that can call LLMs from any other hosted inference API. Also [Typescript](https://github.com/r2d4/llm.ts) [![](https://camo.githubusercontent.com/08a8691693033dcfd922016525b382cd1c1294551c75f98a3870a940cd56ffab/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f723264342f6f70656e6c6d3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/08a8691693033dcfd922016525b382cd1c1294551c75f98a3870a940cd56ffab/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f723264342f6f70656e6c6d3f7374796c653d736f6369616c)
- [Dust](https://github.com/dust-tt/dust): Design and Deploy Large Language Model Apps [![](https://camo.githubusercontent.com/704c7a65c2460f591aa534837bb4bc2229869e2aa32f086456c12a8e692c95d2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f647573742d74742f647573743f7374796c653d736f6369616c)](https://camo.githubusercontent.com/704c7a65c2460f591aa534837bb4bc2229869e2aa32f086456c12a8e692c95d2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f647573742d74742f647573743f7374796c653d736f6369616c)
- [e2b](https://github.com/kyrolabs/awesome-langchain/blob/main): Open-source platform for building & deploying virtual developers’ agents

## 
## Complement to this list
- [Open LLMs](https://github.com/eugeneyan/open-llms): A list of open LLMs available for commercial use [![](https://camo.githubusercontent.com/080925de6c37772e871e90824e7e75f9c9a36c050d2c4f2bf8df6c15bfe101c6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f657567656e6579616e2f6f70656e2d6c6c6d733f7374796c653d736f6369616c)](https://camo.githubusercontent.com/080925de6c37772e871e90824e7e75f9c9a36c050d2c4f2bf8df6c15bfe101c6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f657567656e6579616e2f6f70656e2d6c6c6d733f7374796c653d736f6369616c)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM): Awesome-LLM: a curated list of Large Language Model resources. [![](https://camo.githubusercontent.com/2b0bebb7e6ae67d166ba4b605fcf73a02fb04a942805f8a81502614a7b99bca3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f48616e6e6962616c3034362f417765736f6d652d4c4c4d3f7374796c653d736f6369616c)](https://camo.githubusercontent.com/2b0bebb7e6ae67d166ba4b605fcf73a02fb04a942805f8a81502614a7b99bca3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f48616e6e6962616c3034362f417765736f6d652d4c4c4d3f7374796c653d736f6369616c)
- [LLaMA Cult and More](https://github.com/shm007g/LLaMA-Cult-and-More): Keeping Track of Affordable LLMs, 🦙 Cult and More [![](https://camo.githubusercontent.com/9faa9c5e628ad7d24fc3ab07652ad3dada2e6b0922806bc2823aad70fca6ffb7/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f73686d303037672f4c4c614d412d43756c742d616e642d4d6f72653f7374796c653d736f6369616c)](https://camo.githubusercontent.com/9faa9c5e628ad7d24fc3ab07652ad3dada2e6b0922806bc2823aad70fca6ffb7/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f73686d303037672f4c4c614d412d43756c742d616e642d4d6f72653f7374796c653d736f6369616c)

---
## Creating My Own ChatGPT Code Interpreter and Open Sourcing It

[https://twitter.com/RickLamers/status/1659195480197459969](https://twitter.com/RickLamers/status/1659195480197459969)

**🪄Smart summary:**
The author wrote their own code interpreter for ChatGPT and open sourced it. They are excited to explore the possibilities of the code interpreter and share their enthusiasm with others.
-------

Couldn't get access to ChatGPT Code Interpreter so I wrote my own! And Open Sourced it of course 🕺

[https://t.co/cxHIFRb1FO](https://t.co/cxHIFRb1FO)

Soooo many ideas to try. It's addictive. 

![](https://pbs.twimg.com/media/Fwaxcr7aMAAr8-u.jpg)

---
## Unlocking the Power of Metadata for LLM-Enabled QA Systems

[https://twitter.com/jerryjliu0/status/1660683176099078144](https://twitter.com/jerryjliu0/status/1660683176099078144)

**🪄Smart summary:**
When building LLM-enabled QA systems, it is important to add the right metadata for each chunk of the document in order to improve performance. Docugami is a powerful tool that can automatically provide metadata, and an example of this is given with a question about the security deposit for a property owned by Birch Street. Without the right metadata, the answer is incorrect, but with the right metadata, the answer is correct.
-------

When building LLM-enabled QA systems, we chunk up the docs - can lose global context.

Adding the right metadata for each chunk can improve performance by a LOT. 

@docugami is a powerful tool that can automatically provide metadata (now in LlamaHub!)

[https://t.co/HSOCrOQuF5](https://t.co/HSOCrOQuF5)

![](https://pbs.twimg.com/media/FwvudKKagAI38IY.jpg)

As an example, let’s ask “What is the security deposit for the property owned by Birch Street?”

With “naive” chunking without adding metadata, the landlord name and rentable area are not in the same chunk - you get back a non-answer. 

![](https://pbs.twimg.com/media/Fwvt7OJaAAE-kBG.jpg)

When you add the right metadata (“Landlord”, “Tenant”), then you get back a correct answer!

@docugami can do this automatically.

Check out the full notebook here: [https://t.co/FdIy9YevIh](https://t.co/FdIy9YevIh)

![](https://pbs.twimg.com/media/Fwvt9cjaQAEuQI0.jpg)

---
## Gorilla: Unleashing the Power of a Large Language Model Connected with Massive APIs

[https://twitter.com/arankomatsuzaki/status/1661541064367386624](https://twitter.com/arankomatsuzaki/status/1661541064367386624)

**🪄Smart summary:**
Gorilla has released a finetuned language model based on LLaMA that outperforms GPT-4 in writing API calls. The project and abstract can be found at the provided links.
-------

Gorilla: Large Language Model Connected with Massive APIs

Releases Gorilla, a finetuned LLaMA-based model that surpasses the performance of GPT-4 on writing API calls.

proj: [https://t.co/5ERbyaZ3ws](https://t.co/5ERbyaZ3ws)
abs: [https://t.co/kYdjb8H5gN](https://t.co/kYdjb8H5gN)

![](https://pbs.twimg.com/media/Fw76D3tWAAI2csM.jpg)

@arankomatsuzaki

---
## Understanding and Training Without a GUI/CLI

[https://twitter.com/rashmigb/status/1662126535761960961](https://twitter.com/rashmigb/status/1662126535761960961)

@tunguz This [https://t.co/ntK4WbiwUG](https://t.co/ntK4WbiwUG) is very well done - I was able to understand and train on my own without their GUI/CLI

@rashmigb @tunguz

---
## Unlocking the Power of Entity Memory with SQLite

[https://twitter.com/LangChainAI/status/1663936000241049600](https://twitter.com/LangChainAI/status/1663936000241049600)

**🪄Smart summary:**
Entity memory is a powerful concept that allows for the extraction of entities in a conversation, summarizing what is known about them, and adding that context to prompts. Zelzebu's addition makes it easy to use and persist entity memory locally using SQLite.
-------

🗃️Entity Memory🗃️

Entity memory is a powerful paradigm: extract entities in a conversation, summarize what's known about them, add that context to prompts.

With @zelzebu's addition, you can easily use and persist entity memory locally using SQLite 🥳

[https://t.co/mEtQksxfl6](https://t.co/mEtQksxfl6)

![](https://pbs.twimg.com/media/Fxd82BKakAIZqMR.jpg)

@LangChainAI @zelzebu

---
## Introducing OpenChat: Create and Embed Custom ChatGPT-like Bots Anywhere!

[https://twitter.com/ikbenbasha/status/1663896757271515139](https://twitter.com/ikbenbasha/status/1663896757271515139)

**🪄Smart summary:**
OpenChat, an open-source tool, has been released. It allows users to create and run custom ChatGPT-like bots, and embed and share them anywhere. It also supports vector DB and can be self-hosted with one command. A video example is provided.
-------

🚀🚀🚀🚀🚀
I published the first version of OpenChat, the open-source tool that allow you to run and create custom ChatGPT-like bots, and embed and share these bots anywhere.

Repo: [https://t.co/dtMq8A7Yz1](https://t.co/dtMq8A7Yz1) Website: [https://t.co/QANrVaHyCR](https://t.co/QANrVaHyCR)

Done with @LangChainAI @pinecone 🥰

You can train your bot on any website and embed it as a chat widget! 

![](https://pbs.twimg.com/media/FxdY1veX0AI4030.jpg)

support to vector DB was extremely easy to implement, and because of that, you can self-host OpenChat with one command!

The same goes for @LangChainAI, adding PDFs, websites, and soon many other sources was super easy!

Video example [https://t.co/smuiXoDtkq](https://t.co/smuiXoDtkq)

---
## Introducing Three New Document Loaders for LLM Apps

[https://twitter.com/LangChainAI/status/1663566820933275656](https://twitter.com/LangChainAI/status/1663566820933275656)

**🪄Smart summary:**
We have added 3 new document loaders to make it easier to integrate data from any source into LLM apps. These include GitHub Document Loader, Trello Document Loader, and Spark DataFrame Document Loader. These loaders can be used for project management, loading cards from Trello boards, and retrieving information from DataFrames. Credit goes to UmerHAdil, musicaoriginal2, and rithwik-db for their contributions.
-------

👩‍💼More Data Loaders👩‍💼

LLMs + app-specific data = 🎆

We want to make it super easy to integrate data from any source into your LLM app. So we've added 3 new document loaders, bringing the total count to > 100 🌝

Load from:
🌳@github
✅@trello 
🖼️Spark DataFrame

a 🧵:

🌳GitHub Document Loader🌳

Load issues and PR's from a GH repo.

We're already using this internally to help with project management.

s/o to @UmerHAdil for yet another great contribution!!

[https://t.co/x6MSgTaVHa](https://t.co/x6MSgTaVHa)

![](https://pbs.twimg.com/media/FxYqShnaUAADPiN.jpg)

✅Trello Document Loader✅

Level up your project management *even more* by also loading in cards from your Trello boards.

Thanks to @musicaoriginal2 for the addition!

[https://t.co/6UbhzjQwGK](https://t.co/6UbhzjQwGK)

![](https://pbs.twimg.com/media/FxYrKZ1aUAIi1Oj.jpg)

🖼️Spark DataFrame Document Loader🖼️

Retrieve information from your DataFrames with this loader, which lets you convert any Spark DF into documents that can be fed into a model.

Big thanks to GH user rnthwik-db for adding!

[https://t.co/imN97dzWPL](https://t.co/imN97dzWPL)

rithwik-db**

---
## Tips for Retrieval Augmented Generation

[https://twitter.com/LangChainAI/status/1663646291254206464](https://twitter.com/LangChainAI/status/1663646291254206464)

some really good tips in this thread for retrieval augmented generation! [https://t.co/wQFbHPqF6i](https://t.co/wQFbHPqF6i)

@LangChainAI

---
## Searching Internal Docs with LangChainAI and MendableAI VSCode

[https://twitter.com/ericciarla/status/1662193342707277824](https://twitter.com/ericciarla/status/1662193342707277824)

**🪄Smart summary:**
I just used a search engine to quickly find internal documents like bug reports and product requirements while coding. This demo only required ingesting a Notion feature document and the GitHub repository for BabyAGIJS. I'm now considering the possibility of creating a Mendable AI Visual Studio Code extension.
-------

Just used [https://t.co/qeFS9ot7xH](https://t.co/qeFS9ot7xH) to search internal docs like bug reports and product requirements while coding.

For this demo all it took was ingesting a notion feature doc and the GitHub repo for BabyAGIJS.

Shout out to @LangChainAI for the awesome data loaders 🚀. (1/2) [https://t.co/vf4l0RL0gO](https://t.co/vf4l0RL0gO)

This has me thinking, maybe a @mendableai VSCode would not be the worst idea 🤔. (2/2)

---
## New Features for LLM Caching, Texting, and GGML Models

[https://twitter.com/LangChainAI/status/1662138670332395520](https://twitter.com/LangChainAI/status/1662138670332395520)

**🪄Smart summary:**
This thread introduces three new features: Momento Cache for LLM caching and chain memory, Twilio tool for sending texts, and CTransformers wrapper for GGML models. Momento Cache reduces the burden of repetitive workloads, Twilio gives agents texting abilities, and C Transformers provides an easy interface to powerful models built with the GGML library.
-------

New day, new (feature) delivery 📦

📝 Momento Cache for LLM caching and chain memory
📱Twilio tool for sending texts
🧠 CTransformers wrapper for GGML models

Let's dive in! 🧵

📝 Momento Cache

LLM queries are expensive and slow, making it hard to scale LLM applications.

@momentohq's serverless cache significantly reduces the burden for repetitive workloads.

More on the integration: [https://t.co/oPTBVKVP7G](https://t.co/oPTBVKVP7G)

h/t to Michael Landis for contribution! 

![](https://pbs.twimg.com/media/FxEXEQBaIAAN7Fx.jpg)

📱Twilio

Give your agents texting abilities! Great for things like personal assistants and personal CRMs.

What are the use cases you're excited about?

s/o to GH user Tedma4 for the addition!

Docs: [https://t.co/ZxYZP81aIR](https://t.co/ZxYZP81aIR)

![](https://pbs.twimg.com/media/FxEXzeMaQAIaGdf.jpg)

🧠 C Transformers

There's a new, powerful class of models built with the GGML library (LLaMA, Dolly v2, ...)

C Transformers is an easy interface to these, and with this integration LangChain is, too!

s/o to Ravindra Marella for the new interface!

Docs: [https://t.co/gnvGTvNEVv](https://t.co/gnvGTvNEVv)

![](https://pbs.twimg.com/media/FxEZG5FacAI_2LG.jpg)

---
## Saving Costs with GPT-4 and Vector Databases

[https://twitter.com/_areebpasha/status/1662138694462062606](https://twitter.com/_areebpasha/status/1662138694462062606)

**🪄Smart summary:**
GPT-4 API calls can be expensive, so caching responses in a vector database like Pinecone is a good way to save costs. Redis can be used for implementation, but it can be complicated. Questions can be asked in the comments.
-------

With GPT-4, it's expensive to keep making API calls. Caching your responses in a vector database is probably the best way to save on costs. As more queries come in, costs keep reducing over time as cached responses are returned.
How to do it with @LangChainAI and @pinecone :

1. Save responses to a vector database like Pinecone.
2. Get the similarity score. If the score > 0.8, then use the cached(saved) response, else generate it through API. 
I've seen implementations using redis, but I felt it was complicated. 
Have any questions, drop them below! 

![](https://pbs.twimg.com/media/FxEY1luXgAItLbB.jpg)

---
## Unlocking Endless Possibilities with GPT-4 in Minecraft: Introducing Voyager, the Lifelong Learning Agent

[https://twitter.com/DrJimFan/status/1662115266933972993](https://twitter.com/DrJimFan/status/1662115266933972993)

**🪄Smart summary:**
Voyager is a lifelong learning agent that plays Minecraft using GPT-4. It has three components: an iterative prompting mechanism, a skill library, and an automatic curriculum. Experiments show that Voyager discovers more items and travels further than other LLM-based agents. It is also able to construct complex 3D structures with the help of human feedback.
-------

What if we set GPT-4 free in Minecraft? ⛏️

I’m excited to announce Voyager, the first lifelong learning agent that plays Minecraft purely in-context. Voyager continuously improves itself by writing, refining, committing, and retrieving *code* from a skill library.

GPT-4 unlocks… [https://t.co/SZU0n8nWsW[https://t.co/hjTxk6Qb1x](https://t.co/hjTxk6Qb1x)](https://t.co/SZU0n8nWsW)

Generally capable, autonomous agents are the next frontier of AI. They continuously explore, plan, and develop new skills in open-ended worlds, driven by survival & curiosity.

Minecraft is by far the best testbed with endless possibilities for agents:

[https://t.co/w7zyYvFr3z](https://t.co/w7zyYvFr3z)

Voyager has 3 key components:

1) An iterative prompting mechanism that incorporates game feedback, execution errors, and self-verification to refine programs;
2) A skill library of code to store & retrieve complex behaviors;
3) An automatic curriculum to maximize exploration. [https://t.co/T0trc55Hfg](https://t.co/T0trc55Hfg)

First, Voyager attempts to write a program to achieve a particular goal, using a popular Javascript Minecraft API (Mineflayer). The program is likely incorrect at the first try. The game environment feedback and javascript execution error (if any) help GPT-4 refine the program. 

![](https://pbs.twimg.com/media/FxEFlcuagAA6pqd.jpg)

Second, Voyager incrementally builds a skill library by storing the successful programs in a vector DB. Each program can be retrieved by the embedding of its docstring. Complex skills are synthesized by composing simpler skills, which compounds Voyager’s capabilities over time. 

![](https://pbs.twimg.com/media/FxEFu9XacAAgDhC.jpg)

Third, an automatic curriculum proposes suitable exploration tasks based on the agent’s current skill level & world state, e.g. learn to harvest sand & cactus before iron if it finds itself in a desert rather than a forest.

Think of it as an in-context form of *novelty search*. 

![](https://pbs.twimg.com/media/FxEGAMLaAAAgnYb.jpg)

Putting these all together, here’s the full data flow design that drives lifelong learning in a vast 3D voxel world without any human intervention. 

![](https://pbs.twimg.com/media/FxEGFw1akAMxNKQ.jpg)

Let’s look at some experiments!

We evaluate Voyager systematically against other LLM-based agent techniques, such as ReAct, Reflexion, and the popular AutoGPT in Minecraft.

Voyager discovers 63 unique items within 160 prompting iterations, 3.3x more than the next best approach. 

![](https://pbs.twimg.com/media/FxEGMUqaMAEhrME.png)

The novelty-seeking automatic curriculum naturally compels Voyager to travel extensively. Without being explicitly instructed to do so, Voyager traverses 2.3x longer distances and visits more terrains than the baselines, which are “lazier” and often stuck in local areas. 

![](https://pbs.twimg.com/media/FxEGRFeacAAsANK.jpg)

How good is the “trained model”, i.e. skill library after lifelong learning?

We clear the agent’s inventory/armors, spawn a new world, and test with unseen tasks. Voyager solves them significantly faster. Our skill library even boosts AutoGPT, since code is easily transferrable. 

![](https://pbs.twimg.com/media/FxEGVqRaIAAhocN.jpg)

Voyager is currently text-only, but can be augmented by visual perception in the future. We do a preliminary study where humans act like an image captioning model and provide feedback to Voyager.

It is able to construct complex 3D structures, such as a Nether Portal and a house. [https://t.co/rQeFppxEQJ](https://t.co/rQeFppxEQJ)

Let agents emerge in Minecraft! All open-source: [https://t.co/OUat4RAP17](https://t.co/OUat4RAP17)

This work is co-authored by my team at NVIDIA: @guanzhi_wang (our awesome intern), @yuqi_xie5, @YunfanJiang, @AjayMandlekar, @ChaoweiX, @yukez, @DrJimFan (myself, co-advisor), @AnimaAnandkumar (co-advisor). 

![](https://pbs.twimg.com/media/FxEGy5_aAAIo6Ye.jpg)

---
## Combining ChatGPT and GDrive with LangChainAI in 30 Lines of Python

[https://twitter.com/greggyb/status/1662093412676390912](https://twitter.com/greggyb/status/1662093412676390912)

**🪄Smart summary:**
With LangChainAI, it is possible to create powerful applications with just 30 lines of Python code that combine ChatGPT and GDrive.
-------

Strong agree! 

You can combine ChatGPT + GDrive in 30 lines of Python with @LangChainAI. It's an absurdly powerful foundation for an infinite number of great apps. 

[https://t.co/zjPvUwBWF7[https://t.co/zsPkCvyV2H[https://t.co/4Q33nnCkES](https://t.co/4Q33nnCkES)](https://t.co/zsPkCvyV2H)](https://t.co/zjPvUwBWF7)

@greggyb @LangChainAI

---
[https://www.reddit.com/r/OpenAI/comments/13scry1/_/](https://www.reddit.com/r/OpenAI/comments/13scry1/_)

After building a few tools utilizing OpenAI, I noticed a few things that many folks might not be aware of. Things that could be adding up to 30% unnecessary costs to your OpenAI usage. So, I thought I'd share what I've learned:
1️⃣ **Ensure your JSON is as lean as possible**: OpenAI bills per token, and that includes whitespaces and line breaks in your JSON responses. If you eliminate these extras both in sending and receiving data, you might save up between 30%-50%! You simply need to tell OpenAI to "return JSON in a single-line without whitespaces". Boom!
**Example:** This [Pokemon API JSON response](https://pokeapi.co/api/v2/pokemon?limit=3) is 210 tokens. After minifying it, we dropped to 117 tokens! This is almost 50% money saved.
**Edit:** As mentioned by [u/brucebay](https://www.reddit.com/user/brucebay/), CSV format is also a good idea. No indentation and less repetitive characters.
2️⃣ **Set temperature to 0 for structured responses**: When expecting a structured response (like JSON), setting the temperature parameter to 0 helps the model strictly stick to your expected JSON structure. This will prevent cases where you expect JSON, but something went wrong, and OpenAI responds with "Sorry, I am not sure I can ...".
3️⃣ **Robots don't need you to be polite**: Computers understand simple instructions well. Trimming redundant/filler words from your prompt can not only save money but also speed up execution. Words like "please", "kindly", "really", "very", and so on, can often be dropped without losing accuracy.
**Tip:** You can use the [OpenAI Tokenizer](https://platform.openai.com/tokenizer) to count the tokens of your requests/responses.
To help solve these problems, I've created Pezzo ([https://pezzo.ai](https://pezzo.ai)). It's an open-source (Apache 2.0 license) tool that helps anyone write better prompts. It also helps with observability, troubleshooting, collaboration and cost breakdown of your prompts. Using the Pezzo testing tool, you can design you prompts and test to see exactly how much they will cost, how many tokens they will use, and how long it'll take them to execute.
🌟 Check it out on GitHub here (and show your support by giving a star): [https://github.com/pezzolabs/pezzo](https://github.com/pezzolabs/pezzo)
By the way, here's a sneak peak to the features we're adding soon - suggestions for reducing costs, eliminating bias and increasing performance in your prompts. Let me know what you think!

---


---


---
Remind me to create a meeting on May 16th to go over design details for Ephemeral Charts Tickets w/ Brent, Ginesh, and Courtney.

---
Make a chatgpt plugin for github. Something that can create github actions pipelines from natural langues, create repos, ect. 
Will need the GitHub REST API:
[https://docs.github.com/en/rest?apiVersion=2022-11-28](https://docs.github.com/en/rest?apiVersion=2022-11-28)

ChatGPT Plugin docs:
[https://platform.openai.com/docs/plugins/introduction](https://platform.openai.com/docs/plugins/introduction)

---
## Quality AI Twitter Posts You Shouldn't Miss

[https://twitter.com//status/1657057456319762434](https://twitter.com//status/1657057456319762434)

**🪄Smart summary:**
This thread provides a list of quality posts from AI Twitter, including links to papers, talks, and other resources. It is intended to provide a counterpoint to the low-quality content that has been flooding the platform recently. The thread also suggests that the author may curate more quality content in the future.
-------

AI Twitter is flooded with low-quality stuff recently. No, GPT is not “dethroned”. And thin wrapper apps are not “insane”. At all.

I feel obligated to surface some quality posts I bookmarked. Every one of them should've been promoted 10x, but ¯\_(ツ)_/¯

In no particular order: 

![](https://pbs.twimg.com/media/Fv8IoXFaEAAlj1o.png)

If you only have 1 seat to follow in AI Twitter, don't give that seat to me. Give it to @karpathy. 

Andrej has the best take, by far, on the landscape of the open-source LLM ecosystem.

1/
[https://t.co/H3kghRzvXf](https://t.co/H3kghRzvXf)

Don't watch AI FOMO and fear-mongering videos on YouTube. Watch the excellent talk from John Schulman @johnschulman2, creator of RLHF that powers GPT-4. Now *this* qualifies as "insane" ingenuity, if you ask me.

Link: [https://t.co/bPqFx9tshr](https://t.co/bPqFx9tshr)

2/
[https://t.co/46vdqLFiA3](https://t.co/46vdqLFiA3)

Sasha has written some of my favorite NLP papers. Read about how attention could be an overkill in some cases, and alternative architectures for foundation models. Attention may not be all you need.

3/
[https://t.co/6VgfYo4GRI](https://t.co/6VgfYo4GRI)

Read the excellent cookbook for self-supervised learning, from the godfather of deep learning himself @ylecun. The recipes in this freely available paper will truly help your business. Not the "top 10 ChatGPT tricks you shouldn't miss".

4/
[https://t.co/MVBpIA1MSk](https://t.co/MVBpIA1MSk)

Read this rock solid deep dive thread from Loubna, author of StarCoder from @huggingface. I called StarCode the "Llama moment for coding models". It is the best open-source Codex you can get. “10 outrageous GPT-4 prompts” are outrageously useless.

5/
[https://t.co/4g9HwZwDFT](https://t.co/4g9HwZwDFT)

(with @percyliang) releases RedPajama-3B and 7B. They are Llama-grade models with commercially friendly license (Apache 2.0). Integrate them as your base model to avoid legal troubles.

6/
[https://t.co/q29EiwytQn](https://t.co/q29EiwytQn)

Instruct-BLIP, a new multimodal open-source chat model. Led by @stevenhoi's team. Steven's works (BLIP series @SFResearch) are some of my favorite papers in multimodal foundation models. They provided inspiration for my own work Prismer at NVIDIA.

7/
[https://t.co/e9BgT38umN](https://t.co/e9BgT38umN)

Alex @unixpickle is one of the few researchers still publishing at OpenAI. Read his text-to-3D papers "Shap-E" and "Point-E". 3D generative models are starting to work but far from mature, which means they are inevitably the future trend.

8/
[https://t.co/HRQXTFv6wB](https://t.co/HRQXTFv6wB)

Gabriel @gabrielpeyre makes some of the best math visualizations I've seen here.

9/
[https://t.co/QL3qfUqsRX](https://t.co/QL3qfUqsRX)

Kevin @kevin_zakka makes some of the best robotics simulations I've seen here.

10/
[https://t.co/x9tKpOqfGQ](https://t.co/x9tKpOqfGQ)

If people like this format, I’ll try to curate quality contents more (with my own take) in the future. This is the job that Twitter’s algorithm is supposed to do, but it’s easily gamed by crappy engagement hacks. I guess I’ll manually correct it for a while.

END/ 

![](https://pbs.twimg.com/media/Fv8MLAMacAEZNHg.jpg)

---
## Amazing OpenAI Prompts for AI Developers, GPT Lawyers, and More

[https://twitter.com/SullyOmarr/status/1648444218342535169](https://twitter.com/SullyOmarr/status/1648444218342535169)

**🪄Smart summary:**
This thread provides a list of interesting prompts from OpenAI's closed Discord server. These prompts include Codepup 3.0, GPT Lawyer, PromptGPT, and MidJourney Image Prompt Creator. The thread also provides instructions on how to properly format image prompts.
-------

OpenAI's discord is filled with amazing prompts. 

Unfortunately it's closed (full). 

Here are some of the more interesting ones i've found (GPT4 - prompts in alt text)

Codepup 3.0 - AI Developer 

![](https://pbs.twimg.com/media/FuBxkJIaAAAtUBT.jpg)

GPT Lawyer (basic one, make sure to replace it with your city) 

![](https://pbs.twimg.com/media/FuBxhodacAQsaou.png)

PromptGPT 

![](https://pbs.twimg.com/media/FuByHDsakAU1w50.jpg)

MidJourney Image Prompt Creator (continued in 2nd prompt) 

![](https://pbs.twimg.com/media/FuByd5IakAAMiEj.jpg)

Ok looks like it was cutoff heres the rest (long ass prompt lol)
9.This is salt “::3” and these are “::2”,”::1” pepper, use accordingly. [https://t.co/W6oES83OFr](https://t.co/W6oES83OFr) commas or quotations in the image prompt. 11.When constructing an image prompt, follow the proper format: /imagine:… [https://t.co/ackGLedecE](https://t.co/ackGLedecE)

---
## CompressGPT: 70% Token Usage Reduction with a One-Line Change

[https://twitter.com/yasyf/status/1648753559561998337](https://twitter.com/yasyf/status/1648753559561998337)

**🪄Smart summary:**
Victor Taelin's experiments around compressing GPT prompts have been used to create CompressGPT, which can reduce token usage by 70% with just one line of code in LangChainAI. Thanks to hwchase17 for creating an easy framework to build on.
-------

Took @VictorTaelin’s awesome experiments around compressing GPT prompts and built CompressGPT. A one-line change in your @LangChainAI code => 70% token usage deduction!

[https://t.co/P3wuFEb2P2](https://t.co/P3wuFEb2P2)

cc @hwchase17 thx as always for creating such an easy framework to build on top of!

---
## Unlocking the Power of Claude with 100K Context Windows

[https://twitter.com/AnthropicAI/status/1656700154190389248](https://twitter.com/AnthropicAI/status/1656700154190389248)

**🪄Smart summary:**
Claude is a machine learning tooling that can now analyze up to 100,000 tokens of text, corresponding to around 75K words. It can help retrieve information from business documents, quickly consume and get up to speed on dense material like research papers, and answer questions. It is currently in beta and will be priced at standard API pricing rates.
-------

Introducing 100K Context Windows! We’ve expanded Claude’s context window to 100,000 tokens of text, corresponding to around 75K words. Submit hundreds of pages of materials for Claude to digest and analyze. Conversations with Claude can go on for hours or days. [https://t.co/4WLEp7ou7U](https://t.co/4WLEp7ou7U)

We fed Claude-Instant The Great Gatsby (72K tokens), except we modified one line to say that Mr. Carraway was "a software engineer that works on machine learning tooling at Anthropic." We asked the model to spot what was added - it responded with the right answer in 22 seconds.

Claude can help retrieve information from business documents. Drop multiple documents or even a book into the prompt and ask Claude questions that require synthesis of knowledge across many parts of the text.

With 100K context windows, you can: Digest, summarize, and explain dense documents like financial statements or business reports.

Read through hundreds of pages of developer documentation to get quick answers to technical questions. [https://t.co/xy9ya1omhg](https://t.co/xy9ya1omhg)

Lastly, quickly consume and get up to speed on dense material like research papers. [https://t.co/GRopRjoscZ](https://t.co/GRopRjoscZ)

We’ve made this available to our business partners, and are excited to see what they build. Read more here: [https://t.co/r1OSARYyFe](https://t.co/r1OSARYyFe)

To answer your questions: Right now, our 100K context window is a beta feature and will be priced at our standard API pricing rates during this period!

---


---
# Welcome to Mem (Beta)!
#tutorials

Mem is the fastest way to capture, share and make use of information.

Here, we call the fundamental unit of information a "mem" (lowercase m), each of which is a flexible container of information. A mem can be a short reminder (which you can snooze), a meeting note, a product design doc, or a codified piece of knowledge.

On the surface, we've tried to build something as simple and lightweight as Apple Notes. In the background, Mem is powered by a collaborative knowledge graph — which helps you form relationships between the information you capture, generate relevant - sometimes unexpected - insights, and share with anyone. 
### 
## Get started with this 7 minute video

### [https://mem.ai/onboarding/getting-started-video](https://mem.ai/onboarding/getting-started-video)

## Need help, or want to share feedback?

Visit [support.mem.ai](https://support.mem.ai) to search our docs for what you need. Share feedback with us [here](https://support.mem.ai/share-feedback-form), or request support [here](https://support.mem.ai/request-support) — we'd love to hear from you! 


Happy memming!

–The Mem Team

---
# How to create and edit mems

 
### Creating mems

**On desktop (app or browser):**
- [ ] To create a new mem in the Mem app, just start typing anywhere (if you're already editing a mem, press **⌘N** on a Mac, **Ctrl+N** on Windows).
- [ ] To create a new mem in browser, press **Ctrl+N** to begin, on Mac or Windows.

**On iPhone:**
- [ ] To create a new mem in the iPhone app, select the **Write** icon in the bottom-right corner of the screen and then begin typing.

To download the TestFlight iOS app, go to [mem.ai/iOS](http://mem.ai/iOS) on your mobile browser.

**From Spotlight (on desktop):**
- [ ] To create a new mem from anywhere on your desktop, press **⌘⇧Space **to open Mem Spotlight, and then hit Tab to open a new mem (Windows users can activate Mem Spotlight by pressing **Ctrl⇧Space**). If you are viewing a webpage, have text selected in an application, or both, you will have the option to save that webpage or selected text to a new mem (hit **Enter**, then **⌘Enter**), or to an existing mem (select "Send to an existing mem" on the left-hand side of the window, then search for the relevant mem in the search bar).


**Focus mode:**
- [ ] Turn on **Focus Mode** to remove the Mem interface while you are typing, helping you to concentrate on what you are writing at the minute. Simply move your cursor to exit the mode when you need to see surrounding information on the screen. Preferences for **Focus Mode** can be changed by clicking on your **Profile** in the top left-hand corner of the screen and selecting **Settings**.

### 
### **Formatting mems**
Format text with keyboard shortcuts, Markdown, or the formatting toolbar. Discover more in the [Markdown Guide](https://www.markdownguide.org/basic-syntax) or pull up Mem's keyboard shortcuts by clicking the ? in the bottom right corner.

**Basic formatting (on desktop app and in browser):**
- [ ] When selecting any text, you'll see a formatting toolbar that pops up that lets you style the text (with _italics_, **bold**, strikethrough, and more)


- [ ] Create a large header (H1) by typing # followed by a SPACE


- [ ] Create a medium header (H2) with ## followed by a SPACE


- [ ] Create a small header (H3) with ### followed by a SPACE


- [ ] Try **bolding** text by surrounding it with asterisks **YourText** (The usual ⌘ + B on selected text works here as well.)


- [ ] Try _italicizing_ text with *YourText* , or use ⌘ + I on selected text


- [ ] Try creating a code block with ```


- [ ] Try creating a quote block with >


- [ ] Create a divider with ---


- [ ] Create a todo list by typing [] followed by a SPACE


- [ ] Create a bulleted list by typing - followed by a SPACE


- [ ] Create a numbered list by typing 1. followed by a SPACE


**Adding content to mems:**

- [ ] Add an image from your computer by typing **/image** and hitting **Enter**.


- [ ] Attach a file from your computer by typing **/file **and hitting **Enter**.


**Templates:**

- [ ] Select **Flows **on the left-hand side of the screen, followed by **Templates**, to create your own custom templates for repeated use within Mem.


After creating a template, you can access it in a variety of ways:

- By typing the template name at the start of a mem
- By typing **/** followed by the template name anywhere within a mem
- By searching in Mem with **⌘K** or the search bar at the top of the screen
- By searching with Mem Spotlight using **⌘⇧SPACE **on Mac or **Ctrl⇧Space **on Windows.


**Daily mems:**
- [ ] Select **Flows **on the left-hand sidebar, followed by **Daily Mem**, to create and customize a Daily Mem template for yourself. The Daily Mem will appear at the top of your timeline on the days and at the time you select in the fields at the top of the customization screen.



- [ ] Extra credit: Try navigating to the next tutorial with search using ⌘ + K and searching for "How to link and organize mems".

---
# Searching in Mem
#tutorials


You can search in Mem according to a variety of different criteria. As well as being able to conduct basic text-matching searches, such as for specific tags or individuals, you can also conduct conversationally-phrased searches for:

- mems that contain links (e.g. _"has Google Drive links", “has Figma links”_)
- mems from specific dates or within specific date ranges (e.g. _"from July 2019"_)
- mems sent via SMS (e.g. _"sent from text"_)
- mems that have been edited by specific individuals (e.g._"edited by Isabella"_)
- mems that include tasks (e.g. _"contains checklist"_)
- mems that have been shared with particular Groups (e.g. _"Shared with @Acme Corp_")
- mems that include multimedia content (e.g. _"contains GIFs", "contains photos"_)
- mems that include code (e.g. _"contains code"_)

---
# How to link and organize mems


While you can use search to find what you need in Mem, there are two main ways to link and organize your knowledge — with **collections** and **linked mems.**

### **Collections**
Collections allow you to create lightweight collections to organize your mems. They're more flexible than folders because a mem can be part of multiple collections instead of just being associated with one folder. Example collections might be "meetings", "network", and "home".

When creating a new mem and adding it to a collection, any mems that appear in the same collections will appear on the right-hand side of the screen under **Collections this mem is in**. 
### Linking between mems
You can link to other mems by typing the @ key. This allows you to link to an existing mem, or, create a new mem and link to it — all in one go.

- [ ] Try linking to the "How to create and edit mems" mem now by typing @ in the blank space below and searching for it.


**🚀 Workflow tip: **Use linked mems to **keep track of important people and companies** that you regularly meet with. Here's how (or, watch this [1-minute video](https://www.youtube.com/watch?v=CwKPiGd1ozc)).

1. Let's say you're about to have your first meeting with Caroline Frank who works at Acme Corp. Type First meeting with @Acme Corp
2. On the next line, type Attendees: @Caroline Frank
3. You'll see that mems for Acme Corp and Caroline Frank have been created. You can click into these mems to take down notes about that person or company. (E.g. for Acme Corp, you can write "Founded in 2019", "Headquartered in Silicon Valley".)
4. You now have your meeting notes mem with Acme Corp, along with individual mems for Acme Corp and Caroline Frank.


1. The next week, you have your second meeting with Acme Corp and Caroline Frank. You can type Second meeting with @Acme Corp and Attendees: @Caroline Frank again. You'll see that on the right pane, your meeting notes from the first meeting show up, right at your fingertips.


Make sure to type @ to keep referencing the same people and companies to keep your mems organized and connected.
### Related mems

As noted above, **Related** mems displays mems that share one or multiple of the same collectins as that of the mem you are currently viewing. **Related** mems also displays mems that mention the word contained within the collection(s) on the mem you are currently viewing. For example, a mem that is part of the "twitter" collection will also surface mems that contain the word "twitter". These will be displayed in a separate panel on the right-hand side of the screen, under the heading "Mentions [name of collection]".


![](https://storage.googleapis.com/memvp-25499.appspot.com/images/onboarding.pngd4ec8eaa-0ffa-4949-bdf0-32504dc62814)


You can also find mems that directly link to the mem you are viewing and mems that are created from (or linked to) previous occurrences of recurring **Calendar** events under **Related** mems.

Hover over any of the mems displayed on the right-hand side of the screen to preview their contents.

---
# How to share and collaborate


Sharing and collaborating on work in Mem is easy and seamless, whether or not your collaborators have a pre-existing Mem account. You can also publish mems to a public URL, meaning that anyone with the link to the mem can view it online.
### Sharing a mem

**With an individual:**

To share a mem with someone (with or without a Mem account), you can do one of two things. Either:
- Type **@** followed by the individual's first name and last name (**@FirstName LastName**). If they have a Mem account already, you'll be able to select their name from the pop-up that appears on screen. If they don't, select **Invite FirstName LastName** within the pop-up and then enter their email address on the following screen to invite them to view/edit the mem you're sharing.

![](https://storage.googleapis.com/memvp-25499.appspot.com/images/image.png2c2724cc-18c7-4dcc-9571-6a34050567fa)

- Click on the blue **Share **button at the top of the screen, and start typing the name or email address of the person you want to share the mem with in the search field.

![](https://storage.googleapis.com/memvp-25499.appspot.com/images/image.pngcfba4c7d-96fc-4042-a266-eb035abf5f0e)




**With a group:**
To share a mem with multiple people, select **Groups** in the left-hand sidebar and either select a pre-existing group or select **Create new group **in the top right-hand corner. Choose a name for the group, and then add the individuals you want to it. You'll then be able to share any mem with every person in that group simultaneously by typing **@GroupName** into the relevant mem.

**To a public URL:**
To publish a mem to a public URL that anyone can view, click on the blue **Share **status icon at the top of the editor and then select **Publish**. You will then receive a public link that you can copy and share with others. Individuals with this link will be able to view the mem in publishing mode, but will not be able to edit it.

### Adding comments

You can add comments to shared or private mems by selecting a portion of text and pressing **⌘⇧M**, or by clicking on the gray **lightning bolt** icon that appears in the right-hand margin next to text you are currently editing, and selecting **Comment**. Once you have written your comment, you can either select **Post as comment**, allowing everyone shared in the mem to see it, or **Keep private** if you do not want others shared in the mem to be able to view it.
