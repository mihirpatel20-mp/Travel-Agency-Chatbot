# Travel Agency Chatbot Deployment with Flask and JavaScript

In this project, I deployed the travel agency chatbot using Flask and JavaScript.

This project provides two deployment options:

- Deploy within Flask app with Jinja2 template.
- Serve only the Flask prediction API. The HTML and JavaScript files used can be included in any frontend application with slight modifications and can run completely separate from the Flask app.

## Initial Setup:
This repository contains the starter files.

### Download the Project Zip File:

Download the project zip file from the following link:  
    [Travel Agency Chatbot Project Zip File](https://drive.google.com/file/d/1GUVIfqfnRMa-VvT9shZ1f1JFqcKqN2Pb/view?usp=sharing)


### Install dependencies:
```bash
$ (venv) pip install Flask torch torchvision nltk
```

### Install the nltk package:
```bash
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```

### Modify `intents.json` with different intents and responses for your travel agency chatbot.

```markdown
### Run:
```bash
$ (venv) python train.py
```
### This will create a data.pth file. Then run the following command to test it in the console:
```bash
$ (venv) python chat.py
```

### Now, for deployment, follow the tutorial to implement 'app.py' and 'app.js'.


### Watch the Tutorial
[![Alt text](https://img.youtube.com/vi/a37BL0stIuM/hqdefault.jpg)](https://youtu.be/a37BL0stIuM)  
[https://youtu.be/a37BL0stIuM](https://youtu.be/a37BL0stIuM)

### Note
In the video we implement the first approach using jinja2 templates within our Flask app. Only slight modifications are needed to run the frontend separately. I put the final frontend code for a standalone frontend application in the [standalone-frontend](/standalone-frontend) folder.

### Credits:
This repo was used for the frontend code:
https://github.com/hitchcliff/front-end-chatjs

Initially, I watched the tutorial linked above and made significant enhancements by following the provided guidance. The enhancements reflect my work while crediting the original source.



