# TASK TRACKER

Task Tracker App.




## Local Server Setup

### Clone The Repository

To get started with the local development environment, clone the repository:

```bash
$ git clone https://github.com/mashm3ll0w/task_tracking.git
$ cd task_tracking
```

### Install Dependencies

Set up the environment using `venv`:

```bash
# create Virtual Environment
$ python3 -m venv venv

# Activate Virtual Env
$ source venv/bin/activate

# Install Dependencies
$ pip install -r requirements.txt

# Create a .env file with all the required environment variables from the given .env_example file
$ cp .env_example .env
```

### Run the Server

```bash
$ python3 manage.py runserver 0.0.0.0:8000
```

## Authors

- [@Charles Swaleh](https://github.com/mashm3ll0w)
- [@Pauline Muigai](https://github.com/wanjirumuigai)

## License

MIT License
