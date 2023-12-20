# Niemann Stories
Niemann Stories is a storytelling website that is coded using the Flask Python web framework. The site features a collection of short stories written by various authors. Users can browse the stories,submit their own stories. The website is designed to be user-friendly, with an intuitive interface and easy navigation.


## Running Locally

Install Virtualenv

```bash
pip install virtualenv
```

Create a virutal Environment

```bash
python<version> -m venv en
```

Activate the Virtual Environment

```bash
source env/bin/activate
```

Install all the necessary libraries

```bash
pip install -r requirements.txt
```

Initialized the database.

```bash
flask --app flaskr init-db
```

Then Run

```bash
flask --app flaskr run --debugger
```

Your Flask application is now available at `http://localhost:3000`.

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fexamples%2Ftree%2Fmain%2Fpython%2Fflask&demo-title=Flask%20%2B%20Vercel&demo-description=Use%20Flask%202%20on%20Vercel%20with%20Serverless%20Functions%20using%20the%20Python%20Runtime.&demo-url=https%3A%2F%2Fflask-python-template.vercel.app%2F&demo-image=https://assets.vercel.com/image/upload/v1669994156/random/flask.png)
