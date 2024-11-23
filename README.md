# FastAPI Base Template For OpenAI with Serverless Config for AWS Lambda

## Setup

1. Clone the repository: 

```bash
git clone https://github.com/chrismaresca/fast-api-base-ai.git
```

2. cd into the directory:

```bash
cd fast-api-base-ai
``` 

3. Create a new virtual environment:

```bash
python -m venv .venv --python=3.12
```

or 

```bash
virtualenv -p python3.12 venv 
```

4. Activate the virtual environment:

```bash
source venv/bin/activate
```

5. Install the dependencies:

```bash
pip install -r requirements.txt
```

6. Clone the `.env.local.sample` file to `.env.local` and populate with your API keys.  

7. Run locally with:

```bash
python -m uvicorn src.main:app --reload      
```

8. Deploy with:

```bash
serverless deploy --stage production   
```


