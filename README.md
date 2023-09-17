[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/streamlit/demo-uber-nyc-pickups/main)

# Streamlit Demo: Uber Pickups in New York City
A [Streamlit](https://streamlit.io) demo [written in pure Python](https://github.com/streamlit/demo-uber-nyc-pickups/blob/main/streamlit_app.py) to interactively visualize Uber pickups in New York City.

![Final App Animation](https://github.com/streamlit/demo-uber-nyc-pickups/raw/main/uber_demo.png "Uber demo")

## Run this demo locally from the demo-uber-pickups/ directory
```
pip install --upgrade streamlit
docker build -t streamlit .
docker run -p 8501:8501 streamlit

You can now view the app at http://localhost:8501 or http://0.0.0.0:8501
```
