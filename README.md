# Leaf Disease prediction

## Description
A model which predicts the leaf disease. This model is train by using images, images are flattened, converted into tensors then it's the model is trained with it.

## Steps

### Building Files
1) train_model.py: which has prediction model code
2) requirements.txt: which has the required library names
3) leaf.csv: dataset which contains images of different variety of leafs
4) Dockerfile: which contains the commands to be run in docker
5) templates/index.html: a simple html file used to display the prediction
6) selenium_test.py: code file which contains selenium code for automated testing
7) 
### Git & Other Commands used in Command Prompt
1) `mkdir <file_name>` to create the folder
2) `cd <file name>` to go inside the folder
3) `git init`, initializing folder as git repository
4) manually add all the files
5) `git add .` to add all the files into git track
6) `git commit -m "<message>"`, it commits whatever is there in the track
7) `git remote add origin <GitHub repository link>`, builds connection between git and github
8) `git push --set-upstream origin master`, sends all the files from git to github.

### Jenkins
1) created a new item with item name as **<item_name>**
2) selected *Freestyle project* as the item type
3) selected *Git* in **Source Code Management**
4) added *Execute Windows batch command* step in **Build Steps**
5) Saved the Configurations
6) Clicked build now

#### Output
  ![image](https://github.com/user-attachments/assets/89545290-7c79-4593-a140-b22495c85d66)

### Dockers
1) used `cd` to go forward and `cd..` to do backward, to get to the correct path in command prompt (i.e. the folder where all the files including docerfile is located.
2) executed the command `docker build -t <docker_image_name> .` to build the docker image.
3) executed the command `docker run <docker_image_name>` to run the docker image.

#### Output
  ##### Command Prompt
  ![image](https://github.com/user-attachments/assets/3b9d4f73-22ab-45fd-8325-04747f180145)
  ![test 1 1 1](https://github.com/user-attachments/assets/8f8338be-1aca-4d59-a55a-a3879ecd0466)
  ![test 1 1 2](https://github.com/user-attachments/assets/dcce3b90-9774-407e-9826-a4a4de76f876)
  ![test 1 1 3](https://github.com/user-attachments/assets/d3615a52-0f2d-459b-846f-19a4ba21cc85)

  
  ##### Docker Hub
  ![test 1 2](https://github.com/user-attachments/assets/3335af03-867c-48cf-a58e-c70fa48d84e6)


### Selenium
1) integrated flask into app.py. And build an html file called index.html inside templates folder.
2) created selenium_test.py file which contains the selenium code for autotesting app.py

#### Output
![image](https://github.com/user-attachments/assets/18446094-1dd2-48ca-b30b-48f99a9e3250)
