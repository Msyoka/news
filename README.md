## NEWS

## Author

[David-Mumo](https://github.com/Msyoka)

## Description

News is a web application thatg alerts you on most current news highlights.

### Set-up instructions

1. You will need to have Python3 installed in your machine together with venv and pip.
2. Set up the virtual environment and activate it

```bash
$ python3 -m venv virtual
$ source virtual/bin/activate

```
3. Install all the necessary modules

```bash
$ pip install -r requirements.txt
```

4. Get an API key from [newsapi](https://newsapi.org/)

5. Create a config.py file  inside the instance folder
```bash
$ touch instance/config.py
```
6.  Paste in the API key inside the new config.py file
```python
  NEWS_API_KEY='Your API KEY HERE'
```
7. Run the application

```bash
$ python3 run.py
```
## Technologies Used

* Python3

## Contact Information

If you may have any question or contributions, please contact me via email at [daviemumo37@gmail.com]

## License

GNU GENERAL PUBLIC LICENSE &copy;2021 [David-Mumo]