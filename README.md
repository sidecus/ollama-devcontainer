
# An ollama dev container
Easy interactions with ollama within VSCode leveraging the [ollama docker image](https://hub.docker.com/r/ollama/ollama).

# Pre-req
- Docker
- VSCode
- VSCode DevContainers extension

# Instructions

## Open in dev container
Clone repo and choose to open folder in dev container when prompted.
![image](https://github.com/sidecus/ollama-devcontainer/assets/4399408/71d2cb99-a8f5-4939-9de8-80c0bfb0697f)

- Required docker images will be downloaded automatically. 
- Gemma server is auto started upon dev container running as well.
- Port is automatically mapped to host (11434).

## Run a model
After container is started, to run Gemma:2b, just open a terminal in the VSCode session and run below:
```
./gemma2b.sh
```
Then you can interact with the model via the terminal.

Alternatively, you can open the ```requests.http``` file and test via the pre-installed Rest Client VSCode extension.
![image](https://github.com/sidecus/ollama-devcontainer/assets/4399408/facb509b-2155-4f22-a3c9-f8f1c65c939f)
