#Login Application using handlebars

Activity: Create an app from scratch

Part I - Local and Remote Repo Setup
1. Login to your github and create repo ```loginApp-hbs```
1. Click Create. Note: Take the default settings such as do not create ```README.md``` because we will create it locally.
1. Then you have now an empty remote repo.
1. While on your local, create a directory ```loginApp-hbs``` then also create a ```README.md``` and put any text inside.
1. Launch terminal then execute the following commands:
  * $ cd /path_of_your_directory
  * $ git init
  * $ git add README.md
  * $ git config user.email "youremail@example.com"
  * $ git config user.name "yourname"
  * $ git commit -m "first commit"
  * $ git remote add origin https://github.com/yourgithub_username/loginApp-hbs.git
  * $ git push -u origin master
1. Reload your github and observe the changes applied to your repo ```loginApp-hbs```

Part II - Update Remote Repo
1. Go back to your local directory. Create the following file structure
	
	```html
	- loginApp-hbs
	  - public
	  - views
	  	- layouts
	  	  - layout.hbs
	  	- index.hbs
	  	- login.hbs
	```
	
to be continued...