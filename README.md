# [Adafruit IO](https://io.adafruit.com/)

Tested on Raspberry Pi 3 Model B V1.2

[Tutorial](https://mybinder.org/v2/gh/brentru/adafruit_io_python_jupyter/master?filepath=adafruit-io-python-tutorial.ipynb)

Feeds will be named after metric being logged. Feeds will be created automatically

```
python3 -m pip install -r adafruit_io/requirements.txt

gardnr add driver adafruit-io adafruit_io.driver:AdafruitIO -c username=IO_USER -c key=IO_KEY
```
