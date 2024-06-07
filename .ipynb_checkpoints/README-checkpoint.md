# FinBank Credit Prediction App

This repository contains the code for a credit prediction application using Streamlit and FastAPI, deployed on Heroku.

## Project Structure

- **fastapi-server/**: Contains the FastAPI server code.
  - `fastapi_server.py`: FastAPI server script.
  - `requirements.txt`: Dependencies for FastAPI.
  - `Procfile`: Heroku configuration for FastAPI.
  - `setup.sh`: Setup script for FastAPI.

- **streamlit-app/**: Contains the Streamlit app code.
  - `streamlit_app.py`: Streamlit app script.
  - `requirements.txt`: Dependencies for Streamlit.
  - `Procfile`: Heroku configuration for Streamlit.
  - `setup.sh`: Setup script for Streamlit.

## Deployment

The app is deployed on Heroku. To deploy your own instance, follow these steps:

### FastAPI Server

1. Navigate to the `fastapi-server` directory:
   ```bash
   cd fastapi-server
2.heroku create
git push heroku main
3.cd ../streamlit-app
4.heroku create
git push heroku main



### Final Commit and Push

Une fois que tous les fichiers nécessaires sont ajoutés et configurés, effectuez un commit final et poussez vers GitHub :

```bash
git add .
git commit -m "Add initial project files"
git push origin main
