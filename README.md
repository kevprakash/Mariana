# Mariana

To clone for use in Unreal Engine:

1) Make an empty folder (anywhere, you can do it on your desktop if convenient)
2) In the folder, open cmd or gitbash and run:

       git init
     
       git remote add origin https://github.com/kevprakash/Mariana.git
     
       git pull origin master

3) Once you do that, make a new third person example project in Unreal (version 4.20)
4) Close Unreal
5) Inside the project folder, delete the folders called "Content" and "Config"
6) Copy all the files from the intial folder you made into your project folder, overriding all files when asked
7) Open up the project and go to "Source Control" -> Set the type to Git and hit accept

IMPORTANT: DO NOT ADD OR COMMIT FROM CMD ONLY USE THE EDITOR TO ADD AND COMMIT CHANGES. You have to push from cmd though.

If you experience an error when pulling and it says you have uncommited changes, DO NOT commit/stash the files. Just delete those files and pull the latest version.
