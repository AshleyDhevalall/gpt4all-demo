# gpt4all-demo
The objective of this article is to run large language models locally to analyze local docs. In this use case we analyze powershell scripts that make use of a sql server.

## What is GTP4All?

An open-source ecosystem used for integrating LLMs into applications without paying for a platform or hardware subscription. It was created by Nomic AI, an information cartography company that aims to improve access to AI resources.

Designed to run on modern to relatively modern PCs without needing an internet connection or even a GPU! This is possible since most of the models provided by GPT4All have been quantized to be as small as a few gigabytes, requiring only 4–16GB RAM to run.

## Steps to follow

1. Download GPT4All Desktop [GPT4All](https://www.nomic.ai/gpt4all)
> [!TIP]
> [QuickStart](https://docs.gpt4all.io/gpt4all_desktop/quickstart.html)

<img src="https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/download.png" width="300" height="400">

2. Open GTP4All  
![open_gtp4all](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/open_gtp4all.png)

3. Adding new model (Click `Models` on left menu) and then click `+ Add Model` button  
> [!TIP]
> [Models](https://docs.gpt4all.io/gpt4all_desktop/models.html)

![add_model](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/add_model_1.png)

4. Search for `Llama 3.2 1B Instruct` and then click `Download`. Please patient while to model downloads
> [!TIP]
> [Models](https://docs.gpt4all.io/gpt4all_desktop/models.html)

![explore_models](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/explore_models.png)

5. Clone repository
```
git clone https://github.com/AshleyDhevalall/gpt4all-demo.git
```

6.1 Click `LocalDocs` on left menu. Provide a `Collection name...`
> [!TIP]
> [LocalDocs](https://docs.gpt4all.io/gpt4all_desktop/localdocs.html)

<img src="https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/add_document_collection.png" style='height: 70%; width: 70%;'>

6.2 Click `Browse`. Navigate to cloned repository folder above (Step 5) and then select the folder

<img src="https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/browse.png" style='height: 70%; width: 70%;'>

7. Configure settings
> [!TIP]
> [Settings](https://docs.gpt4all.io/gpt4all_desktop/settings.html)

![settings](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/settings.png)

8. Start chat
> [!TIP]
> [Chat](https://docs.gpt4all.io/gpt4all_desktop/chats.htmll)

![chat](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/chat.png)

## Further reading  
[Quickstart](https://docs.gpt4all.io/gpt4all_desktop/quickstart.html#quickstart)
[Wiki](https://github.com/nomic-ai/gpt4all/wiki)  
[FAQ](https://docs.gpt4all.io/gpt4all_help/faq.html)  
[Settings](https://docs.gpt4all.io/gpt4all_desktop/settings.html)
[What Is GPT4All and How Does It Work?](https://www.makeuseof.com/what-is-gpt4all-and-how-does-it-work/)  

## Authors

[Ashley Dhevalall](https://github.com/AshleyDhevalall)

## Acknowledgements

* [GTP4All](<https://www.nomic.ai/gpt4all>)
* [Joshua Stenhouse](<https://virtuallysober.com/2017/07/10/working-with-sql-databases-using-powershell/>)
* [Jayric Maning](<https://www.makeuseof.com/what-is-gpt4all-and-how-does-it-work/>)
