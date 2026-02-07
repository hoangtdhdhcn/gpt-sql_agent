## Setup

1. Clone the repository
2. Install the dependencies: `poetry install`
3. Activate the virtual environment: `poetry shell`
4. Configure the environment variables in the `.env` file
5. Initialize the database: `python -m scripts.init_db`

## Running the Agent

To run the agent in CLI, you can use the following command:

```bash
python main.py
```
To run the agent in Streamlit, you can use the following command:

```bash
streamlit run main.py
```
