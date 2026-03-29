# learning-python-vector-ai

## Application overview
This is a small POC done for one of the VectorDB course from udemy where at the end there is a small project to be done in order to showcase the learning and understanding of the application.<br>
The <b>objective</b> of this project was to extract the speech from a video and perform semantic search on the words.

### Project explanation
> The video source and the vectorDB source which I've used is provided in the ipynb file at the start.
> 
> For sample I've uploaded only a single video file as the source contains 2GB of data, so uploading that all data is not required.
> 
> Used only limited amount of data to extract and perform semantic search.
> 
> Fill up your details of the azure service and vector db in the environment file.
> 

### Technical configuration
> Install python SDK and other necessary libraries required.
>
> For extracting text from audio file(obtained by converting video file) use Azure OPEN AI transcribe model(I've used, you can choose other also)
>
> After creating azure open AI foundry service -> goto foundry portal as deployment is now not available directly into service section.
>
> Create new deployment with proper model and use the deployment's name, endpoint and API key to feed into environment file.
>
> Setup an account into vector DB providers(I've used Pinecone) and use the API key for initializing it.(Necessary libraries to be installed before using)
>
