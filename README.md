# code_snippet
memo de code et commande
## Suppression des migration 
```bash
find . -path "*/migrations/*.py" -not -path "./venv/*" -not -name "__init__.py" -delete
```
