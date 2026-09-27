# Contextra
## Motivation
Not sure if anyone has already built this or not, but when I'm using my local models and running them on my decently big enough vram sized gpu (8gb vram) then it's running the into OOM, so I have decided to make a helper code, so I can use it on any agent harness, and the idea is that it won't try to fit everything at once but instead route the context throughout, so even tho the model will take time to give output, it will still generate the output regardless, instead of running into an issue

## Tools

I will be using PI harness, and ollama based deepseek r1 but the goal would be to make it as versatile as I can possibly can make without least possible trade-offs 