# Diagnostic-des-tumeurs-c-r-brales-par-IA
Ce projet consiste une solution d’IA dédiée à l’analyse d’images cérébrales, combinant la classification avec TensorFlow et la détection et localisation avec YOLOv8. Il intègre MLflow pour le suivi des expériences, Airflow pour l’orchestration du pipeline, FastAPI pour exposer les modèles via API et Streamlit pour l'interface de prédiction.

# Instructions

### 1. Création d’un environnement virtuel

Exécuter la commande suivante dans le terminal :

```cmd
python -m venv <nom_environnement>
```

Remplacer `<nom_environnement>` par le nom souhaité, par exemple `venv` ou `.venv`.

### 2. Activation de l’environnement virtuel

**Avec CMD :**

```cmd
<nom_environnement>\Scripts\activate.bat
```

**Avec PowerShell :**

```powershell
.\<nom_environnement>\Scripts\Activate.ps1
```
Cette activation concerne la plateforme Windows, vous pouvez consulter la votre sur [Activation selon plateforme](https://docs.python.org/fr/3/library/venv.html).

### 3. Vérification de l’activation

Une fois l’environnement activé, son nom apparaît généralement au début de la ligne de commande, par exemple :

```text
(venv) C:\mon_projet>
```

Pour vérifier quel interpréteur Python est utilisé :

```bash
python -c "import sys; print(sys.executable)"
```