

## Running
1. conda create --name agentic python=3.10
2. conda activate agentic
3. pip install -r requirements.txt
4. Now you can running by `python run.py` (you must to have a Gemini api key before you run)
5.  you can following the Parameters to adjust `run.py` 


## Parameters
- `--api_model`: The agent that receives observations and makes decisions. In our experiments, we use `gemini-2.0-flash`. For text-only setting, models without vision input can be 
- `--test_file`: Specifies the task file to be evaluated. Refer to the `data` directory for the correct file format.
- `--max_iter`: Defines the maximum number of online interactions allowed per task. If this limit is exceeded without task completion, the attempt is considered a failure.
- `--api_key`: Your Gemini API key.
- `--output_dir`: Directory where the web browsing trajectory will be saved.
- `--pdf_path`: add the pdf file 
