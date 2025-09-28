# Company-Brochure-using-LLM
Given the name and the primary website of a company, this python code utilizes BeautifulSoup (for html parsing) and gpt-4o-mini LLM model (using OpenAI API) to build a Brochure for a company to be used for prospective clients, investors and potential recruits.

## Setup Steps

1. **Create an OpenAI API key**
   - Sign up for an OpenAI account and add the minimum required funds.
   - Generate an API key from your OpenAI dashboard.

2. **Set up a virtual environment and install dependencies**
   - Create an Anaconda or Python virtual environment.
   - Install required packages using the provided `environment.yaml` file:
     ```
     conda env create -f environment.yaml
     conda activate <env_name>
     ```
     *(Replace `<env_name>` with the environment name specified in the yaml file.)*

3. **Configure API key**
   - Create a `.env` file in your project directory.
   - Paste your OpenAI API key inside the file in the format:
     ```
     OPENAI_API_KEY=your_key_here
     ```

4. **Run the code**
   - It's recommended to use a Jupyter environment for running and experimenting with the notebook.

- I have used OpenAI's Chat Completions API in this project, but the newer Responses API could be used too. Check https://platform.openai.com/docs/guides/migrate-to-responses for more details.
