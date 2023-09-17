[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/streamlit/demo-uber-nyc-pickups/main)

# Streamlit Demo: Uber Pickups in New York City
A [Streamlit](https://streamlit.io) demo based on [this github repo](https://github.com/streamlit/demo-uber-nyc-pickups/) to interactively visualize Uber pickups in New York City.

![Final App Animation](https://github.com/streamlit/demo-uber-nyc-pickups/raw/main/uber_demo.png "Uber demo")


## Prerequisites
Read the introduction and follow the prerequisites at [this link](https://docs.streamlit.io/knowledge-base/tutorials/deploy/docker) in order to successfully install the Docker Engine on your machine.

Verify that Docker Engine is installed correctly by running the hello-world Docker image:

sudo docker run hello-world

## Run this demo locally from the demo-uber-pickups/ directory
```
pip install --upgrade streamlit
docker build -t streamlit .
docker run -p 8501:8501 streamlit

You can now view the app at http://localhost:8501 or http://0.0.0.0:8501
```
