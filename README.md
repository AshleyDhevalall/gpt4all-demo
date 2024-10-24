# gpt4all-demo
The objective of this article is to run large language models locally to analyze local docs. In this use case we analyze powershell scripts that make use of a sql server.

## What is GTP4All?

An open-source ecosystem used for integrating LLMs into applications without paying for a platform or hardware subscription. It was created by Nomic AI, an information cartography company that aims to improve access to AI resources.

Designed to run on modern to relatively modern PCs without needing an internet connection or even a GPU! This is possible since most of the models provided by GPT4All have been quantized to be as small as a few gigabytes, requiring only 4–16GB RAM to run.

## Steps to follow

1. Download and install [GPT4All](https://www.nomic.ai/gpt4all)  
<img src="https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/download.png" width="300" height="400">

2. Open GTP4All  
![open_gtp4all](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/open_gtp4all.png)

3. Adding new model (Click `Models` on left menu) and then click `+ Add Model` button  
> [!NOTE]
> See [QuickStart](https://docs.gpt4all.io/gpt4all_desktop/quickstart.html#quickstart) for further instructions on `Adding new model`

![add_model](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/add_model.png)

4. Search for `Llama 3.2 1B Instruct` and then click `Download`
> [!NOTE]
> See [models](https://docs.gpt4all.io/gpt4all_desktop/models.html) for further instructions on `Models`

![explore_models](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/explore_models.png)

5. Clone repository
```
git clone https://github.com/AshleyDhevalall/gpt4all-demo.git
```

6. Click `LocalDocs` on left menu. Provide a `Collection name...`, then click `Browse`. Navigate to cloned repository folder above
> [!NOTE]
> See [localdocs](https://docs.gpt4all.io/gpt4all_desktop/localdocs.html) for further instructions on `LocalDocs`.  

<img src="https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/add_document_collection.png" width="300" height="400">

7. Configure settings
> [!NOTE]
> See [settings](https://docs.gpt4all.io/gpt4all_desktop/settings.html) for further instructions on `Settings`. 

![settings](https://github.com/AshleyDhevalall/gpt4all-demo/blob/main/docs/settings.png)

8. Start chat
> [!NOTE]
> See [settings](https://docs.gpt4all.io/gpt4all_desktop/settings.html) for further instructions on `Chat`. 

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
