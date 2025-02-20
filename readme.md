## Document RAG

Execute the commands to set up local development

```shell

git clone https://github.com/ramya487/Document_RAG
cd Document_RAG
python -m venv env
cd env/Scripts
activate
cd ../..
pip install ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
pip install -r requirements.txt

```

1. Open Notebook and select Python(venv) as the kernel
2. Make sure to have python installed on your system
3. Ollama with phi model is required as well

