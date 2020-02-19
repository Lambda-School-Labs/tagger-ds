# Tagger - Smarter Email

You can find the project at [TaggerHQ](https://taggerhq.com/).

## Labs 20 Contributors 
|[Rosie Lasota](https://github.com/apathyhill)  |  
[Jean Fraga](https://github.com/JeanFraga)  |  
| :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|                 [<img src="https://avatars3.githubusercontent.com/u/14889913?s=460&v=4" width = "200" />](https://github.com/apathyhill)                       |                      [<img src="https://avatars3.githubusercontent.com/u/12549527?s=460&v=4" width = "200" />](https://github.com/JeanFraga)                       |                      [<img src="https://ca.slack-edge.com/T4JUEB3ME-UJ5GAHMS7-abc28b1e9d94-512" width = "200" />](https://github.com/JeanFraga)                       |       
|[<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/apathyhill)                 |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/JeanFraga)             
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/apathyhill) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/jeanfraga) |

## Labs 18 Contributors 
|[Avraham Jacobsohn](https://github.com/noreallyimfine)  |  
[John Morrison](https://github.com/JohnMorrisonn)  |  
[Samuel Hepner](https://github.com/SamH3pn3r)        |   
| :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | 
|                 [<img src="https://ca.slack-edge.com/T4JUEB3ME-UJJJCQN4R-3d9845ab1b54-512" width = "200" />](https://github.com/noreallyimfine)                       |                      [<img src="https://ca.slack-edge.com/T4JUEB3ME-UL5V3G7A9-f4a14f4623d7-512" width = "200" />](https://github.com/JohnMorrisonn)                       |                      [<img src="https://ca.slack-edge.com/T4JUEB3ME-UJ5GAHMS7-abc28b1e9d94-512" width = "200" />](https://github.com/SamH3pn3r)                       |       
|[<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/noreallyimfine)                 |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/JohnMorrisonn)             |           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/SamH3pn3r)                  |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/avraham-jacobsohn-b88b4526/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/johnjmorrison/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/samuel-hepner-7451b7133/) |



![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)
![Typescript](https://img.shields.io/npm/types/typescript.svg?style=flat)
[![Netlify Status](https://api.netlify.com/api/v1/badges/b5c4db1c-b10d-42c3-b157-3746edd9e81d/deploy-status)](netlify link goes in these parenthesis)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

🚫 more info on using badges [here](https://github.com/badges/shields)

## Project Overview

[Trello Board](https://trello.com/b/39GG7MwY/tagger-smarter-email)

[Product Canvas](https://www.notion.so/Tagger-Smarter-Email-01673a2ed9e54cb8834b959ad39f7de2)

The idea of this project was to develop an email app similar to Gmail, Edison mail, Yahoo mail, etc. but with better organization to help you find emails easier. For the DS, we built an API that generates tags for all emails so they can be put into folders by the BE.


[Tagger - Smarter Email](https://taggerhq.com/)

### Tech Stack

 -   Languages: JSON, Python
 -   Libraries: Pandas, Scikit-Learn, Pickle, NLTK, and Flask
 -   Services: Flask and AWS EB

### Predictions

The DS API takes in a JSON object of an email, generates a tag, and spits out a JSON object with the previous email information + tag. The current API is using TfidfVectorizer, NLTK wordnet Lemmatizer, regexp_tokenize, and a Random Forest Classifier model.

### Explanatory Variables

-   Text of the emails 

### Data Sources

-   Private E-mails

### Python Notebooks

[Functions for gathering the emails](https://github.com/Lambda-School-Labs/tagger-ds/blob/master/Jay/email_functions.ipynb)

[Model Hyperparameter Optimization and Training](https://github.com/Lambda-School-Labs/tagger-ds/blob/sam-branch/labs_sam(3).ipynb)

[Flask API](https://github.com/Lambda-School-Labs/tagger-ds/blob/sam-branch/API/application.py)


### How to connect to the data API

Send a POST request to http://tags2.us-east-2.elasticbeanstalk.com/api/tags with the arguments {'id', 'sender', 'subject', 'message'}

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./code_of_conduct.md.md). Please follow it in all your interactions with the project.

### Issue/Bug Request

 **If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**
 - Check first to see if your issue has already been reported.
 - Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
 - Create a live example of the problem.
 - Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes,  where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

See [Backend Documentation](https://github.com/Lambda-School-Labs/tagger-be) for details on the backend of our project.

See [Front End Documentation](https://github.com/Lambda-School-Labs/tagger-fe) for details on the front end of our project.

## Accessing the API Endpoints

### /train_model
Input:
```
{   
    "address": <email user>,
    "emails": [
        {
            "uid": <id>,
            "from": <email sender>,
            "subject": <email subject>,
            "msg": <email body text>
            "content_type": <unused, keep as blank string>
        },
        ...
    ]
}

```
Output:
```
"Trained a model!"
```

### /predict
Input:
```
{   
    "address": <email user>,
    "emails": [
        {
            "uid": <email uid (optional)>,
            "from": <email sender>,
            "subject": <email subject>,
            "msg": <email body text>
            "content_type": <unused, keep as blank string>
        } 
    ]
}
```
- "emails" array can have a length > 0, but only the first entry will be taken.
- This endpoint can also be used for predicting what real emails are closest to a hypothetical email.

Output:
```
Array of 5 email UID's closest in content to the selected email 
or "No model in database for this address..."
```
