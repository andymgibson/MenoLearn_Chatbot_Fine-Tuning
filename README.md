# MenoLearn_Chatbot_Fine-Tuning
Chatbot for the MenoLearn menopause education project with the UCSD Cognitive Science Dept. using the ChatGPT API. This is the repo for the fine-tuning version of the model. The idea with this version is to add to GPT's pretraining with a curated dataset and special training to decrease the model's surprisal and perplexity for menopause education. We are giving it additional training to make it highly specialized for this task.

This will be compared with the RAG version later.

Note on the fine-tuning model: Each time we need to run fine-tuning it will take about 30mins to retrain the model, so I wrote a script using the time package to check periodically for the status.

PI: Dr. Mary E.T. Boyle
Depts: Cognitive Science, Engineering
University: University of California, San Diego

Project credit:
- Chatbot: Andrew Gibson (Andy)
- Back-end: Alden
- Hardware: Luna
- UI/UX team:
- Data science:
- Survey team:
- Partners:

Final project will include mobile and web applications with an integrated chatbot.

User data is not stored for privacy. User data is not included in the datasets for these models on this GitHub version.

Note: The project's API secrets have been removed for obvious reasons.
