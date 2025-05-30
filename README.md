# Movie-Recommender-System
A Web Base user-item Movie Recommendation Engine using Collaborative Filtering By matrix factorizations algorithm and
The recommendation based on the underlying idea that is if two persons both liked certian common movies,then the movies that one person has liked that the other person has not yet watched can be recommended to him.   

## Technologies Used
- Python
- Libraries: pandas, numpy, scikit-learn, Surprise (or any other recommendation libraries)
- APIs: TMDb API / IMDb API (optional, for movie metadata)
- Optional: Flask/Django for web interface, React/Vue for frontend

##### Requirements
```
python 3.6

pip3

virtualenv
```
##### Setup to run

Extract zip file in your computer

Open terminal/cmd promt

Goto that Path

Example

```
cd ~/Destop/Movie-Recommender-System
```
Create a new virtual environment on that directory

```
virtualenv .
```

Activate Your Virtual Environment

for Linux
```
source bin/activate
```
for Windows
```
cd Scripts
then
activate
```
To install Dependencies

```
pip install -r requirements.txt
```

### Creating Local Server

Goto src directory, example

```
cd ../Movie-Recommender-System/src
```
To run
```
python manage.py runserver
```
Now open your browser and go to this address
```
http://127.0.0.1:8000
```
