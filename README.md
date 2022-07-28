# fiqremovebg

[fiqremovebg](https://fiqremovebg.herokuapp.com/) is a free service for removing any photo's background. It operates completely automatically: You don't have to manually separate the background/foreground layers - simply select your image and receive the output image with the background removed!

## Dependencies
- [Pillow](https://pypi.org/project/Pillow/) - Pillow is the friendly PIL fork by [Alex Clark and Contributors](https://github.com/python-pillow/Pillow/graphs/contributors). PIL is the Python Imaging Library by Fredrik Lundh and Contributors. As of 2019, Pillow development is supported by [Tidelift](https://tidelift.com/subscription/pkg/pypi-pillow?utm_source=pypi-pillow&utm_medium=readme&utm_campaign=enterprise).
- [loguru](https://github.com/Delgan/loguru) - Python logging made (stupidly) simple
- [python_dotenv](https://pypi.org/project/python-dotenv/) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables. 
- [rembg](https://github.com/danielgatis/rembg) - Rembg is a tool to remove images background.
- [streamlit](https://streamlit.io/) - Streamlit turns data scripts into shareable web apps in minutes.


## Demos
![Demo](demo/fiqremovebg.gif)

[![Demo](https://www.herokucdn.com/deploy/button.svg)](https://fiqremovebg.herokuapp.com/)

## Install
1. Clone this repository
```bash
git clone https://github.com/fiqgant/fiqremovebg.git
cd fiqremovebg
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Start web-application
```bash
streamlit run app.py
```
