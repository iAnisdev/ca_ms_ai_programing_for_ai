# Programming for AI - CA
- [Github Repo](https://github.com/iAnisdev/ca_ms_ai_programing_for_ai)

## Prerequisites
- **Python Version**: Python 3.11.x

## Installation
1. Clone or download the repository to your local machine.

2. Install dependencies using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
    ```

## Environment Variables
The project requires two environment variables to function:
- `API_KEY` - Your NASA API key.
- `BASE_URL` - The base URL for the NASA API (`https://api.nasa.gov`).

### Steps to Configure Environment Variables
1. Locate the `.env.example` file in the root directory.

2. Rename the file to `.env`:
   ```bash
   mv .env.example .env
    ```

3. Open the `.env` file and replace the placeholder values with your own:
   ```env
   API_KEY=your_api_key

   BASE_URL=https://api.nasa.gov
    ```

## Running the Notebook
1. Launch the Jupyter Notebook server:

   ```bash
   jupyter notebook
    ```
2. Open the notebook file (index.ipynb) in your browser or IDE.
3. Run the cells sequentially to execute the code.

## Notes
- Ensure your `.env` file is correctly configured before running the notebook.
- For API usage limits and documentation, visit [NASA API Documentation](https://api.nasa.gov/).

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
