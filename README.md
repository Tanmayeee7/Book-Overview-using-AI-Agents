# Book-Overview-using-AI-Agents
As the name suggests, the program generates an overview for 'Harry Potter and the Chamber of Secrets' using Agentic AI.

This program uses CrewAI framework and a sequentiel workflow with ollama as the software provider.
The model used is llama 3.2.
The first agent is a searcher who searches the book and provides a summary of the key concepts of the book.
The second agent is a writer who expands each bullet point written by the previous agent to provide a formal overview.
Along with that, the second agent also saves the overview to an output file: overview.md
