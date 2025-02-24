# LLM-compose

> Use it for local development for free instead of ChatGPT and other paid, unsecured solutions

---

## !!! Prepare

> Run this commands in your terminal to create necessary docker volumes:
>
> ```shell
> docker volume create ollama-local
> ```
>
> ```shell
> docker volume create open-webui-local
> ```

---

### Run

```shell
docker compose up -d
```

---

### Using

> Go to http://localhost:3000 and create your first, **Admin** account.

#### PhpStorm Plugin

> Install `Proxy AI` (ex-`CodeGPT`) plugin from JetBrains Marketplace --> [Link](https://plugins.jetbrains.com/plugin/21056-proxy-ai)

>> It will allow you to use Ollama models in your IDE:
> 
> - code completion
> - commit message generation
> - chat with GPT right from IDE

---

### Links

> - [Medium: How to locally deploy ollama and Open-WebUI with Docker Compose](https://medium.com/@edu.ukulelekim/how-to-locally-deploy-ollama-and-open-webui-with-docker-compose-318f0582e01f/)
> - [ProxyAI/CodeGPT IDE plugin @ JB Marketplace](https://plugins.jetbrains.com/plugin/21056-proxy-ai)
> - [GitHub: Ollama FAQ](https://github.com/ollama/ollama/blob/main/docs/faq.md)
> - [Ollama: All models](https://ollama.com/search)
> - [Open WebUI: RAG](https://docs.openwebui.com/features/rag)
