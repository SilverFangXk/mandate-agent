\# Agent de conformité des mandats d'investissement



Mini-projet MLOps (ENSAF / ISDIA3) : agent à outils avec RAG à accès contrôlé.

L'agent vérifie la conformité d'un portefeuille à son mandat et prépare un

dossier pour approbation humaine. Il n'exécute jamais d'ordre.



> Outil d'aide à la conformité, pas de conseil en investissement.

> Toutes les données sont synthétiques.



\## Installation



&#x20;   python -m venv .venv

&#x20;   .venv\\Scripts\\activate

&#x20;   pip install -r requirements.txt

&#x20;   copy config.example.yaml config.yaml



Python 3.14.5, modèle local : Ollama (llama3.1:8b).



\## Tests



&#x20;   python -m pytest

&#x20;   ruff check .

