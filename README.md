# Ollama + Open WebUI

- [Docker](https://www.docker.com/)
- [Nvidia Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) 
- [Ollama](https://hub.docker.com/r/ollama/ollama)
- [Open-WebUI](https://github.com/open-webui/open-webui)

## Installation
```bash
git clone https://github.com/strtab/ollama-open-webui.git
cd ollama-open-webui
```
### Create volumes
```
docker volume create ollama
docker volume create open-webui
```
- Uncomment line 7 in compose.yaml if you want to use gpus
## Launch
```bash
docker compose up -d
```
WebUI will be avaible on `localhost:3000`
