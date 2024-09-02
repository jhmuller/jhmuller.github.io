# Welcome to John Muller's Github.io page

Sorry to redirect you, but go [here](https://html-preview.github.io/?url=https://github.com/jhmuller/jhmuller.github.io/blob/main///index.html) for a nicer HTML page with links to older projects.   

In addition, below are some links to some newer efforts.
The first two are on my HuggingFace spaces.  


[summarize](https://huggingface.co/spaces/jmuller/summarize) is an app to summarize NPR news stories.  


[complain](https://huggingface.co/spaces/jmuller/complaint_letter) is an app to generate a letter complaing to an airline customer service department about issues on a recent flight.

I am also working on extracting text from documents, sort of a RAG application.
I start with a PDF, the NVidia 10Q quarterly filing. I break it into pages and
then a little smaller chunks and use ChromaDB to get embeddings for all the chunks.

Then I give a question and search for chunks that are similar and give all that to 
OpenAI as context.  So far it is not working too well in that it gives different answers to 
the same question.  I am trying to also use LlamaParse on the PDF to see if that yields better results.
This one is still work in progress. 


