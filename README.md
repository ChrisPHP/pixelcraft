# Pixelcraft
This project is a Python-based application for texture generation using machine learning techniques. It utilizes libraries such as Pillow, scikit-learn, and img2texture to create and manipulate textures.

## Requirements
Python 3.11
Docker (optional, for containerized deployment)

## Installation
Using pipenv (recommended)

Clone this repository:
```
git clone https://github.com/ChrisPHP/pixelcraft.git)
cd pixelcraft
```

Install pipenv if you haven't already:
```
pip install pipenv
```

Install dependencies:
```
pipenv install
```

Activate the virtual environment and go into src directory and run the python server:
```
pipenv shell
cd src
python main.py
```


## Using Docker

Clone this repository:
```
git clone https://github.com/ChrisPHP/pixelcraft.git)
```
Go into the pixelcraft directory
```
cd pixelcraft
```

Build the Docker image with docker compose:
```
docker compose build
```

Once built run the docker container:
```
docker compose up
```

## Usage
Just simply go to this URL in your browser `http://127.0.0.1:5000`


## Dependencies

pillow==10.4.0
scikit-learn==1.5.1
img2texture
flask
werkzeug
opensimplex

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
## License
This project is licensed under the MIT License - see the LICENSE file for details.