## `03.1` Running your new application

After creating our app, we need to run it, we need to start the application.

When the application runs it will take over your command line, you will not be able to type on it anymore because a server application (like flask) never stops running, it keeps waiting for "requests" forever.

## 📝Instructions

Add the following lines to the end of your `src/app.py` file:

```python
# These two lines should always be at the end of your app.py file.
if __name__ == '__main__':
  app.run(host='0.0.0.0', port=3245, debug=True)
```

> This two lines should always be at the very end of your file.

Run your new server by typing on a **new separate terminal** the following command:

```bash
$ pipenv run python src/app.py
```

> Open a new terminal to run this command.

![Running Terminal](https://github.com/breatheco-de/python-flask-api-tutorial/blob/master/.breathecode/assets/running-flask-app.gif?raw=true)
