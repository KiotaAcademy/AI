# CHATBOT

A chatbot has both front-end and backend

the front-end interacts with the customer or whoever is asking that question

The backend of a chatbot is where the hard work takes place. The backend operates application logic and has enough memory to remember earlier parts of a conversation as dialog continues.

## BACK-END

let's say we want to recieve the commands to change our password, different humans can request in different languages or ways:

1. “How come I can’t log into my account?!”
2. “I forgot my @#$ password!”
3. “It says my password is wrong.”
4. “fergot paswrd”

all this leads to one thing - how can i reset my password. We need a way in which our chatbot can understand that all this questions are leading to one place, `how can i reset my password?`

this is where the `classifiers` algorithm come into contention.

A chatbot usually include three parts:

1. Intents
2. Entities
3. Dialog

A chatbot's goal is to identify what the `intents` and `entities` are in the prompt, and then it triggers a `dialog`

### INTENT

this is a purpose - a reason why the user is using the chatbot

like a kind of action.

A user might want to ask for direction, file a complaint or even ask to speak to a salesperson

### ENTITY

this is a noun -  a person a place or a thing

### DIALOG

this is a flowchart, an IF/THEN tree structure that illustrates how a machine will respond to user intents.

this is the response that a machine will give to the user

Even if a user gives run on sentences, incomplete, poor grammar chat messaging expressions, the AI will allow the NLP to understand well enough to provide a response.

NLP analyzes sentence components, then uses processes like passage and evidence scoring to classify the sentence components against possible chatbot responses. The result is that when a human user asks a question, the AI system provides the answer with the highest confidence.
