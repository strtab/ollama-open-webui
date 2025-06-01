# Ollama + Open WebUI

## Requirements
- [Docker](https://www.docker.com/)
- [Nvidia Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) 
- [Ollama](https://hub.docker.com/r/ollama/ollama)
- [Open-WebUI](https://github.com/open-webui/open-webui)

## Install
```bash
git clone https://github.com/strtab/ollama-open-webui.git
cd ollama-open-webui
```
Uncloment line 7 in compose.yaml for use gpus
### And run
```bash
docker compose up -d
```
WebUI will be avaible on `localhost:3000`
