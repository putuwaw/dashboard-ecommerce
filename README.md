# dashboard-ecommerce

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![BUILD](https://img.shields.io/github/actions/workflow/status/putuwaw/dashboard-ecommerce/streamlit.yml?style=for-the-badge)

Dashboard for E-Commerce Public Dataset - [Dicoding Belajar Analisis Data dengan Python](https://www.dicoding.com/academies/555/) Project Submission.

## Features 💡

- [x] Data analytics with documentation on [notebook](notebook.ipynb).
- [x] Dashboard and interactive visualization on [Streamlit cloud](https://dashboard-ecommerce-putuwaw.streamlit.app).

## Prerequisites 📋

- [Python](https://www.python.org/) 3.10 or higher
- [Docker](https://www.docker.com/) 24.0.5 or higher


## Installation 🛠️
- Clone the repository:
```bash
git clone https://github.com/putuwaw/dashboard-ecommerce.git
```
- Create and activate virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```
- Install requirements:
```
pip install requirements.txt
```
- Run Streamlit on local:
```
streamlit run dashboard/dashboard.py
```
- You can also use Docker, pull the Docker image:
```bash
docker pull putuwaw/dashboard-ecommerce
```
- Run the container:
```
docker run -p 8501:8501 --name dashboard-ecommerce putuwaw/dashboard-ecommerce
```