# Weclome PIVOT_CO Team ^_^
Kindly run this before running the code  
```
pip install -r requirement.txt
```
> :warning: Also, I am working on Python version 3.9.12, make sure to update your python version!    
------------------------------------------------------------------
**Note:**
To run the **Flask API**, please got to the root and execute this first
```
export FLASK_APP='app.py'
```
then run the flask app
```
run flask
```
To Test the API after running the flask app,  
the Route of the API is: **/Submit**  
and please use this JSON format in Postman program or any other program to test it:
```json
{
    "Entreprise": "pivot&CO",
    "Technologies": "Python/Microsoft Azure/R/SQL",
    "Diplome": "Master",
    "Experience": "7",
    "Ville": "Toulouse"
}
```
- For testing using .csv file, kindly use the Route **/SubmitFile**.  
------------------------------------------------------------------
To run the **ML-model** (Training) please execute this
```
python3 main.py
```
> :warning: It will take some time because of the model tuning, sorry about that ^_^
 
**Note:**
Looking forward to meeting you tomorrow ^_^
