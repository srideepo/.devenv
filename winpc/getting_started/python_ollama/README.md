### Install python
- Download and install [python](https://www.python.org/downloads/windows/)
- Confirm installation version 3+  
    `python -v` 

### Install ollama
- `pip install ollama`
- Confirm installation  
    `ollama -v`
- Load a specific model from [ollama](https://ollama.com/library). eg: llama2  
    `ollama pull llama2`

### Use in python  
> import ollama  
model = ollama.Model("llama2")  
result = model.generate("What is the capital of France?")  
print(result)

### Use in cli
- In terminal cmd `ollama`
- When prompted ask your question
