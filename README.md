# Semantic Search Demo

- #### To use a local Llama model switch to 'local' branch of this repository
- Create a `consume` folder in the project base directory and place the PDF files in the directory.
- Create a `.env` file -
```bash
# not required for local model
HUGGINGFACEHUB_API_TOKEN=_______

# URL for embeddings endpoint of the local model e.g. - http://100.105.38.57:3001/v1/embeddings
EMBEDDINGS_URL=_______
```
- Create virtual environment and install requirements
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

- Alternatively, create conda environment and install requirements

```
conda deactivate
conda env remove -n sahil
conda create --name sahil python=3.10 -y
conda activate sahil
pip install -r requirements.txt
```


- Execute the `main.py` file
```
python main.py
```
