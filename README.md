
# An ollama dev container
Easy interactions with ollama within VSCode leveraging the [ollama docker image](https://hub.docker.com/r/ollama/ollama).

# Pre-req
- Docker
- VSCode
- VSCode DevContainers extension

# Instructions

## Open in dev container
Clone the repo, open the folder in VSCode and then choose to open in dev container when prompted.
![image](https://github.com/sidecus/ollama-devcontainer/assets/4399408/71d2cb99-a8f5-4939-9de8-80c0bfb0697f)

- Required docker images will be downloaded automatically. 
- Gemma server is auto started upon dev container running as well.
- Port is automatically mapped to host (11434).

## Run a model
After container is started, open a terminal in the VSCode session and run below (using Gemma:2b as an example):
```
./gemma2b.sh
```
All it does is just running ```ollama run gemma:2b```. You can then interact with the model from the terminal.

Alternatively, you can also open the ```requests.http``` file in VSCode and test the model interaction via the pre-installed Rest Client VSCode extension.
![image](https://github.com/sidecus/ollama-devcontainer/assets/4399408/facb509b-2155-4f22-a3c9-f8f1c65c939f)
