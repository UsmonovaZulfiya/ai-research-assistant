# Ai Research Assistant
AI research assistant created during Data Camp 2024 conducted by WomenTechmakers, AlifAcademy, and School-21.

This is a demo-code for the creation of a research assistant with the API from OpenAI, and a sample UI inside the notebook with Gradio. 

How to run:
1. Create a new .env file and enter your OpenAI API key in the form of: OPENAI_API_KEY="key" (you can enter the rest of the API keys here also if you plan to modify). The API keys are fetched with dotenv.
2. Make sure to make available models gpt-3.5-turbo and text-embedding-ada-002 in your limits section in OpenAI API.
3. Install all packages in the first cell.
4. Run the cells!

What you can do here:
- the first thing the assistant can do, is answer any question using GPT LLM;
- the next cell asks for the topic or keywords for the research article/paper to find in Google Scholar (by using the scholarly library), gives the basic information such as name, authors, date published, and abstract, and downloads and stores the paper in vector space (if the paper is available to download);
- you can ask any question from the paper in the next cell;
- then, the assistant can summarize any part of the paper;
- lastly, you can have a conversation with the assistant about the paper and see which parts of the paper were used to generate the answer.

All features/cells are done with Gradio, so the UI is available.
