# FlaskBlog
FlaskBlog is a simple yet more than a basic blog website built using FLask.

****
## Local installation guide:
**Clone the repository**
```bash
 git clone https://github.com/shubham7743/FlaskBlog.git
```

**Install virtual enviornment**
```bash
python -m pip install --user enviroment
python -m enviroment --help
```

**Activate the  virtual enviornment**
```bash
cd flaskblog\enviornment
Scripts\activate
```

****
## Installing dependencies
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install dependencies in blog directory.
```bash
python -m pip install --upgrade pip	// to update pip
pip install flask
pip install Flask-wtf
pip install flask-sqlalchemy
pip install flask-bcrypt
python -m pip install --upgrade pip	// to update pip
python -m pip install --no-use-pep517 bcrypt // if bcrypt show error
pip install flask-login
pip install email_validator
pip install Pillow
pip install flask-mail
pip install flask-serialize
```
****
## Build the Database
**Build the datbase in blog directory. Write the following in terminal**
```bash
 from flaskblog import db
 db.create_all()
 exit()
 ```
 ****
## Set Username and password 
**Set Username and password for sending link to change password**
```bash
 1. Go in search and write enviroment varible and click on edit the system envrioment varible
 2. Now got to Enviroment varible option
 3. now set two system varible:-
   a. EMAIL_USER as varible name and <a valid gmail id> as varible value
   b. EMAIL_PASSWORD as varible name and <a valid gmail password> as varible value
 ```
 ****
 
## Run the code at your local envn
**Run it as**
```bash
 python run.py
 ```
>Open your browser and the site can be found running at http://127.0.0.1:5000/ 


## Screenshot of assignment 
**Home page**
 #### Since you are not logined you will only see Login and register buttons
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590218410.png)
 ****

**Register page**
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590327249.png)
 ****

**Successful Register Page**
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590297394.png)
 ****

**Login Page**
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590392437.png)
 ****
 
 **After Successful Login Page**
  ####Now you can see new post , account and logout buttons
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590409223.png)
 ****
 
 **New Post**
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590466105.png)
 ****
 
 **Successful New Post Creation**
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590487776.png)
 ****
 
**User Account Page**
  ####User can change his image here and chanhe their username and email id
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590507876.png)
 ****

**User Liked Post**
  ####User can like post if and only if he is logged in
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590532424.png)
 ****
 
 **Update and Delete Post**
  ####User can update and delete only his uploaded post by clicking on the post title he can come on this page
  ![](https://github.com/NayanMogra/FlaskBlog-Assignment/blob/main/screenshot/1614590600820.png)
 ****
 
 
