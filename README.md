# Detection-of-Anemia-from-Eye-Conjunctiva-Images-using-Deep-Learning
It will take input from user and predict whether a patient has anemia or not. User must upload the cropped photo only exposing the conjunctiva portion.

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n anemia python=3.11 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```
