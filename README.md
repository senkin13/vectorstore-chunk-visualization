# Vectorstore Chunk Visualization App With DataRobot

**Author:** senkin.zhan@datarobot.com

## Problem framing

This AI Accelerator demonstrates how to implement a Streamlit application to gain insight from vectordatabase of chunks, RAG developer can compare similarity between chunks and remove unnecessary data during RAG development.

## Accelerator overview

This accelerator requires a genAI project [built and deployed](https://docs.datarobot.com/en/docs/gen-ai/deploy-llm.html) on DataRobot.

The following steps outline the accelerator workflow.

<b>Step 1</b> From playground, [register and deploy](https://docs.datarobot.com/en/docs/gen-ai/deploy-llm.html) a genAI model.

<b>Step 2 (optional)</b> Deploy multiple models if needed. Update the deployment ID's in the code.

<b>Step 3</b> Run the code as a [streamlit app](https://docs.streamlit.io/develop/concepts/architecture/run-your-app). 


## Select a chatbot and click start:
![Select a chatbot and click start](upload_document.png)

## Chat through the text or voice input via the microphone button:
![Chat through the text or voice input via the microphone button](chat_input.png)

## Playback the response by clicking the speaker button:
![Playback the response by clicking the speaker button](voice_playback.png)

## View analysis and word cloud in the analysis tab:
![View analysis and word cloud in the analysis tab](analysis.png)
