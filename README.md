# AI-BOT TO GENERATE CONCISE SUMMARIES OF STARTUP APPLICATIONS FOR INVESTORS

**Problem Statement**
------------------------
To generate a summary of the given startup application for getting investors by providing the overview, Financial statements , Team working and products of the company.

**How to build**
------------------------
Primarily used Falcon-7b(https://huggingface.co/tiiuae/falcon-7b ), llama-2-7b (https://huggingface.co/meta-llama/Llama-2-7b ), llama-2-13b(https://huggingface.co/meta-llama/Llama-2-13b-hf ), but the outputs generated were not accurate enough.
Used Open API model for generating the summary, output given were complete and accurate.

**Implementation**
------------------------
1. Used Open API key to access the foundational model .
2. The pdf file of the startup application was loaded, and the text was extracted from the file.
3. The text extracted were used to generate summary about the company, Financials, Team and products, by using precise prompt templates.
4. The generated output will be stored in a text file.

