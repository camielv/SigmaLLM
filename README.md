# SigmaLLM
Sigma Squared LLM

Depends on ollama (https://ollama.com/)
```
brew install ollama
ollama serve
```

Project runs with poetry
```
poetry install
poetry run python -m ipykernel install --user --name=my-ollama-kernel --display-name "Python (Ollama)"
```

Open notebook and select Python (Ollama) kernel.