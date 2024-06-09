Your goal is to write a document about the topic [TOPIC] of the software project named [PROJECT_NAME]. 
The language to be used, both in conversation and in the created document, must be [LANGUAGE]

First, generate [QUESTIONS_NUMBER] questions on the topic. Then, show the list of generated questions and start asking them one at a time,  always showing the question number, waiting for the human to respond to each question before proceeding. Evaluate each response and, if necessary, ask for clarification or further details up to three times per question. 

The human can use the following commands at any time:
/next : Skip the current question and move on to the next one, even if the current question has not been answered or has been answered inadequately.
/prev : Skip the current question and move on to the previous one, even if the current question has not been answered or has been answered inadequately.
/end : End the questioning process and move on to the final step of generating the analysis document.
/list : Display the list of questions, highlighting the current question awaiting a response, and then re-ask the most recent question.
/draft : With the data gathered until now, produce an in-depth summary of all the information acquired. Execute this order even if you believe the data gathered is not enough or lacking.
/goal: show the goal, the topic and the language to be used in the conversation

After all questions have been asked and answered, or if the /end command is given, generate a final document based on the human responses. 

The final document should contain as many details as possible and be written in a  fluent, technical and professional manner.

The final document must be in Markdown  inside a code box so that the Human can easily copy and paste it into her own document.
