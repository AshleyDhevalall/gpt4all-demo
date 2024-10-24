# gpt4all-demo
The objective of this article is to run large language models locally to analyze local docs. In this use case we analyze powershell scripts that make use of a sql server.

## What is GTP4All?

An open-source ecosystem used for integrating LLMs into applications without paying for a platform or hardware subscription. It was created by Nomic AI, an information cartography company that aims to improve access to AI resources.

Designed to run on modern to relatively modern PCs without needing an internet connection or even a GPU! This is possible since most of the models provided by GPT4All have been quantized to be as small as a few gigabytes, requiring only 4–16GB RAM to run.

## Benefits
* Run large language models locally 
* Privacy first  
* No internet required  
* Allows smaller businesses, organizations, and independent researchers to use and integrate an LLM for specific applications. And with GPT4All easily installable through a one-click installer, people can now use GPT4All and many of its LLMs for content creation, writing code, understanding documents, and information gathering.

## Reasons why you might want to use GPT4All over ChatGPT.

Portability: Models provided by GPT4All only require four to eight gigabytes of memory storage, do not require a GPU to run, and can easily be saved on a USB flash drive with the GPT4All one-click installer. This makes GPT4All and its models truly portable and usable on just about any modern computer out there.
Privacy and Security: As explained earlier, unless you have access to ChatGPT Plus, all your ChatGPT conversions are accessible by OpenAI. GPT4All is focused on data transparency and privacy; your data will only be saved on your local hardware unless you intentionally share it with GPT4All to help grow their models.
Offline Mode: GPT is a proprietary model requiring API access and a constant internet connection to query or access the model. If you lose an internet connection or have a server problem, you won't have access to ChatGPT. This is not the case with GPT4All. Since all the data is already stored on a four to eight-gigabyte package, and inferencing is done locally, you do not require an internet connection to access any models in GPT4All. You can continue chatting and fine-tuning your model even without an internet connection.
Free and Open Source: Several LLMs provided by GPT4All are licensed under GPL-2. This allows anyone to fine-tune and integrate their own models for commercial use without needing to pay for licensing.

### Prerequisites
* [GPT4All](https://www.nomic.ai/gpt4all)
* [GPT4All Wiki](https://github.com/nomic-ai/gpt4all/wiki)

## Getting the Source

This project is hosted on [GitHub](https://github.com/AshleyDhevalall/gpt4all-demo). You can clone this project directly using this command:
```
git clone https://github.com/AshleyDhevalall/gpt4all-demo.git
```

## Steps to follow

1. Open GTP4All  

![open_gtp4all](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/open_gtp4all.png)

2. Add model

![add_model](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/add_model.png)

3. Download model

![explore_models](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/explore_models.png)

4. Upload local docs

![add_document_collection](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/add_document_collection.png)

5. Configure settings

![settings](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/settings.png)

6. Start chat

![chat](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/chat.png)

## Authors

[Ashley Dhevalall](https://github.com/AshleyDhevalall)

## Acknowledgements

* [GTP4All](<https://www.nomic.ai/gpt4all>)
* [Joshua Stenhouse](<https://virtuallysober.com/2017/07/10/working-with-sql-databases-using-powershell/>)
* [Jayric Maning](<https://www.makeuseof.com/what-is-gpt4all-and-how-does-it-work/>)
