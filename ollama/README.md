# OLLAMA Stack für Docker

## Den Stack auf Portainer Deployen

## Modelle laden
'''
# Beispiel: Chat (Llama 3.1, 8B, für CPU mit Q4-Quantisierung)
docker exec -it ollama ollama pull llama3.1:8b-instruct-q4_K_M

# Code-Modell
docker exec -it ollama ollama pull qwen2.5-coder:7b-instruct-q4_K_M

# Embeddings
docker exec -it ollama ollama pull nomic-embed-text
'''

