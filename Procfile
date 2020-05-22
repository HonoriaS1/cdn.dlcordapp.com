from flask import Flask
flask_app = Flask(name)
@flask_app.route('/')
def index():
    return app.send_static_file('templates/index.html')
if __name__ == 'main':
    flask_app.run(host='0.0.0.0', debug=False, port=os.environ.get('PORT', 80))
