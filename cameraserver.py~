from flask import Flask
app = Flask(__name__)

@app.route('/')
def index():
	return render_template(index.html)

@app.route('/camera/<int:camera_id>')
def showcamera(camera_id):
	return 'Camera number ' + str(camera_id)

if __name__ == '__main__':
	app.run(host='0.0.0.0')
