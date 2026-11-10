# jupyterintro

> Du måste installera vs code-pluginet "jupyter" från Microsoft för att kunna köra Jupyter-notebooks i VS Code.

Börja med att skapa ett virtual environment och installera beroenden från `requirements.txt`

1. Öppna terminalen
2. Kör `python -m venv .venv` för att skapa ett virtual environment.
3. `.\.venv\Scripts\python -m pip install --upgrade pip` för att uppdatera pip till senaste version.
4. `.\.venv\Scripts\python -m pip install -r requirements.txt` för att installera alla beroenden från `requirements.txt`
5. Öppna nu ovning1_jupyter.ipynb 
6. Se till att sätta kernel till det virtual environment du just skapade (.venv) genom att klicka på "Select kernel" uppe till höger i dokumentet.