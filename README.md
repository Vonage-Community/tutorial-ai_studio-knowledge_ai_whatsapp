# Smarter WhatsApp Bots: Prevent AI Hallucinations with Knowledge AI
A node application that connects AI Studio WhatsApp agents with Slack to allow for live human customer support agents directly from Slack.

> You can find full step-by-step instructions on the [Vonage Developer Blog](https://developer.vonage.com/en/blog)

## Prerequisites
1. [Vonage Developer Account](https://developer.vonage.com/sign-up)
2. [Vonage Virtual Number](https://dashboard.nexmo.com/your-numbers)
3. Slack Account and permission to install apps in your workspace
4. [Node](https://nodejs.org/en/download) 


## Instructions
1. Download the AI Studio Zip File
2. Import your agent in the [AI Studio Dashboard](https://studio.ai.vonage.com/agents), click the "Import Agent" button:
![Screenshot showing how to configure the Q&A node in AI Studio](https://studio.docs.ai.vonage.com/~gitbook/image?url=https%3A%2F%2F3877181490-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-L_81A0PNZfdawu_TPAO%252Fuploads%252Fbb9qcoiWm2RKB6t9LMPx%252FScreen%2520Shot%25202022-05-23%2520at%252019.02.54.png%3Falt%3Dmedia%26token%3D08394646-a73b-4522-9d57-b80121e1f7cf&width=768&dpr=1&quality=100&sign=def52e6a&sv=2)
3. Create a [Knowledge Base](https://studio.docs.ai.vonage.com/ai-studio/knowledge-ai) called "Pricing KB" according to the blog post, see: _How to Create a Knowledge Base with Knowledge AI_
4. Publish your agent with a Vonage Virtual Number
5. Try out your new WhatsApp AI agent!
