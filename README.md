# Book-Overview-using-AI-Agents
As the name suggests, the program generates an overview for any book of your choice using Agentic AI.

This program uses CrewAI framework and a sequentiel workflow with Nvidia as the software provider.
The model used is llama-3.1-nemotron-70b-instruct.
The first agent is a searcher who searches the book and provides a summary of the key concepts of the book.
The second agent is a writer who expands each bullet point written by the previous agent to provide a formal overview.
For the front-end, HTML, CSS and JavaScript has been used.
