from flask import Flask
from flask import url_for
from flask import render_template
app = Flask(__name__)


@app.route('/')
def main_page():
    return render_template('index.html')

if __name__ == '__main__':
    app.run()
    url_for('static', filename='css/style.css')
    url_for('static', filename='css/header.css')
    url_for('static', filename='images/home-6-48.png')
    url_for('static', filename='images/hearts-48.png')
    url_for('static', filename='images/weightlift-48.png')
    url_for('static', filename='images/book-48.png')
    url_for('static', filename='images/knight-48.png')
    url_for('static', filename='images/plus-4-48.png')
    url_for('static', filename='images/star-2-48.png')
