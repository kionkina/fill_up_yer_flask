"""
Karina Ionkina
SoftDev1 pd07
HW04 -- Fill Up Yer Flask
2017-09-22
"""

from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello_world():
    retStr1 = "<a href = 'static/pie.png'> Pie </a>"
    retStr2 = "<a href = 'static/ton.png'> Ton </a>"
    retStr3 = "<a href = 'static/flask.png'> Flask </a>"
    return "<font size = '50%'> <center>" + retStr1 + retStr2 + "<br>" + retStr3 + "</font> </center>"

if __name__ == "__main__":
    app.run(debug = True)
