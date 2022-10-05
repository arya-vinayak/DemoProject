#this is my very first push operation

The steps to be followed are as follows :

#initialize a repository

git init

#make changes in a file editor like vs code

#after making the corresponding changes 
#we can check the changes made wrt to the files that are already present in the master branch on git using

git status -u
git status -uno
git status -uall 

#we will have to add the required files using this command

git -add . -> this is for all the files in the updated directory
git -add filename ->this is for the specific file in the directory

the above commands are used for different purposes for the untracked files

#no before pushing the updated files in the master branch -> we will have to commit to these changes 

git commit -m "name of the file" -m "description"

#now we have to push this into the master branch


git push origin master


#if we wanna create a new repository
-> we will have to manually create one on github
->after that we will have to our local machine and use the git init command
->we need to connect the local repo to the one on git using
git remote add origin repository_link
->we can use the git remote -v command to see our repo connections
->we can then create our desired files and then upload them the usual way


#extras

ls -la to check all the unhidden as well as the hidden files in the directory



#Your now good to go! Happy coding!



