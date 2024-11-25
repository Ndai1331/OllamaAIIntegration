1. install docker desktop
2. install ollama 
    docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
3. docker exec -it ollama ollama run llama3
4. pull llama3 model with api
5. start blazor app