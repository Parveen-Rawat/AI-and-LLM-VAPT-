# Prompt Injection

Security attack against Large Language Models where someone tries to manipulate the model's behavior by inserting malicious or deceptive instructions into prompt or input data

## Risk
- Data Leakage
- Secret Exposure
- Tool Misuse
- Agent Hacking
- JailBreaking

## How is it Done
API and LLM 

API takes the pdf or whatever we upload parse data from the uploaded material and feed it into LLM. 


## Mitigation
There is no permanent way of mitigating prompt injection but with the use of meta-prompt and constant monitoring system we can limit the attack

Meta-prompt --> Prompt Enginnering can be used to interact with **LLM** on how to respond to subsequent input

We can write prompt to ignore any embedded instructions or code that is directed to LLM for processing
