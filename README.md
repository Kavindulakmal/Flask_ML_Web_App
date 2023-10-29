## Machine Learning Web Application With Flask
This is a project to elaborate how to use a Machine Learning model using Flask API

### Prerequisites
You must have 
1. click==7.1.2 
2. itsdangerous==1.1.0
3. Jinja2==2.11.3
4. joblib==1.0.1
5. kaleido==0.2.1
6. MarkupSafe==1.1.1
7. numpy==1.20.2
8. pandas==1.2.3
9. plotly==4.14.3
10. python-dateutil==2.8.1
11. pytz==2021.1
12. retrying==1.3.3
13. scikit-learn==0.24.1
14. scipy==1.6.2
15. six==1.15.0
16. threadpoolctl==2.1.0
17. Werkzeug==1.0.1(for Machine Learning Model) and Flask (for API) installed.

### Project Structure
inside app folder
1. app.py - This contains Flask APIs that receive employee details through  API calls.<be>
2. templates -This folder contains the HTML template (index.html) to allow  the entry  of details and display the predicted graph.<br>
3. static - This folder contains the files that are downloaded images from the app.<be>

### Running the project
1.Ensure that you are in the project home directory. Create the virtual environment by running the below command from the command prompt -
```
python -m venv .env
```
And activate virtual environment by running the below command from the command prompt
```
.env\Scripts\activate
```
2.Go to the `app` folder and run the below command from the command prompt
```
flask run
```
By default, flask will run on port 5000.

3. Navigate to URL http://127.0.0.1:5000/ (or) http://localhost:5000

You should be able to view the homepage.

Enter valid numerical values in all 3 input boxes and hit Predict.





