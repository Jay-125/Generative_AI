Linux Based

A small introduction on how to run models using autogen.

Requirements:

Need to install ollama and litellm.

apt-get install ollama
pip install litellm

To run models using ollama, first have to download models using command

ollama pull mistral

NOTE: Can pull only those models that are available on Ollama models library. To go to ollama library, click below link.
https://ollama.com/library

For this demonstration, I will be using mistral and codellama.

Run two different models - mistral and codellama - using command

litellm --model ollama/mistral:7b-instruct-q4_0
 litellm --model ollama/codellama 
 
 Once the models are up and running, they will run on some endpoint. F
 or example in my case mistral ran on http://0.0.0.0:8000 and codellama ran on http://0.0.0.0:17165.
