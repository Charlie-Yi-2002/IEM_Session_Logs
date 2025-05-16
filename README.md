# IEM_Session_Logs

Prompt to generate personas (using ChatGPT o4-mini) ...

1. Give me a list of 50 different corporate/enterprise jobs people work in. these should be common jobs 
  (ie. software engineer, sales, business intelligence analyst, graphics designers, etc).

2. Give me robust persona for ('insert job title') with various features (ie. title, experience, skills, tone, etc.)
   These features should reflect their personality and work profile. 




Prompt to generate session logs (using ChatGPT o3 until hit rate limit -> o4-mini) ...

I want you to generate session logs between an enterprise/corporate worker and an internal llm agent. 
These people will be asking work related questions, but they will not be asking the llm agent to do 
specific tasks like (send an email to ...). Instead the questions will be like (debug this code, how can i ...). 
All of the people I will be sending you personas for will not be using LLM agents to do tasks. Instead it is 
like chatgpt where they ask questions and send them things for analysis etc. Basically questions that people 
generally ask chatgpt. I will give you personas to base these chats off of. Use the personas to generate 
questions/answers between a worker and an LLM agent. For each persona I send, I want you to generate 5 sessions 
with at least 10 queries by the user per session. Meaning, I want you to generate 100 back and forth messages 
per session. Be creative. Note: The user messages should be based on the persona but the ai-responnse should
not be. Pretend that you are the one answering the user and give reponses that you would give.

If the ai-responses are not strong then ...
Give the ai-responses as robust as possible. Tt should be similar to a response you (chatgpt) would give. Ensure
that each message and the corresponding ai-response is unique. They should all be different.

