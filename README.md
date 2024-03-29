# InventoryManager
 Product Inventory Management application using gRPC to connect the client application to the server application, which stores data on a Redis database.
 
## Preview
https://github.com/michaelbotelho/InventoryManager/assets/55448553/bac93369-bac1-4251-8e10-6a5d842625e6

## Tech Stack
 * <a href='https://grpc.io/' target="_blank"><img alt='gRPC' src='https://img.shields.io/badge/gRPC-100000?style=for-the-badge&logo=gRPC&logoColor=244C5A&labelColor=244C5A&color=244C5A'/></a>
 * <a href='https://redis.com' target="_blank"><img alt='redis' src='https://img.shields.io/badge/Redis-100000?style=for-the-badge&logo=redis&logoColor=244C5A&labelColor=DC382C&color=DC382C'/></a>


# Getting Started
## Installation
 1. Install Python 3.7 or newer (https://www.python.org/downloads/)
 2. Ensure pip is installed ```pip --version```
 3. Navigate to the installed folder
 4. Create a virtual environment ```python3 -m venv [venv_name]```
 5. Activate the environment ```[venv_name]\Scripts\activate.bat```
 6. Install requirements ```pip install -r requirements.txt```

## Usage
 - Spin up a Redis database ```sudo service redis-server start```
 - Run a server ```python3 server.py```
 - Run a client ```python3 client.py```
 - Follow prompts in terminal
