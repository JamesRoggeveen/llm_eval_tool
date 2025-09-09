# Privacy Policy for the LLM Evaluation Tool

**Last updated:** September 9, 2025

This privacy policy explains how the LLM Evaluation Tool ("the Tool"), an application integrated with Google Sheets, collects, uses, and shares your information.

## Data We Collect

When you authorize and use the Tool, we collect the following information:

1.  **Your Google Account Email Address:** We use your email address to verify administrative privileges and to log who performs an evaluation.
2.  **Spreadsheet Content:** The Tool accesses and reads the content of specific cells in the active spreadsheet, specifically the "Prompt," "Solution," and "Parameters" columns for the row you choose to process.
3.  **Evaluation Results:** The Tool writes evaluation results, including the model's response and an equivalence score, back into the spreadsheet.

## How We Use Your Data

Your data is used exclusively for the functioning of the Tool:

* **To Perform Evaluations:** The prompt and solution text from your sheet is sent to our external API to be processed by a Large Language Model (LLM).
* **To Log Activity:** We maintain logs of evaluations, which include the user's email, the model used, and the data processed, for the purposes of debugging and tracking usage.
* **To Control Access:** Your email is checked against a list of administrators to determine access to administrative functions.

## Data Sharing

We do not sell your data. We only share your information with the following parties as a necessary function of the Tool:

1.  **Our External Evaluation API:** The content of your "Prompt" and "Solution" cells is first sent to our secure, intermediary API for processing.
2.  **Third-Party LLM Providers:** Our API then forwards the "Prompt" data to various Large Language Model (LLM) providers, which may include **OpenAI** and **Google**, to generate a model response for evaluation. Please be aware that the data sent to these providers may be subject to their respective privacy policies and terms of service.

## Contact Us

If you have any questions about this privacy policy, please contact James Roggeveen at roggeveen [at] seas dot harvard dot edu.
