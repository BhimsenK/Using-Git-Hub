# Using-Git-Hub


Hey there !!!

This is to guide you about how you can create a repo on Git hub. 
And then if you have some files/ folders in your local desktop then how you can push those files/ folders into the perticular git repository. 

# Requirement : Integrating the Git repo with your local folder 
@ Goal: You want to upload the contents of the "Interview Prep" folder to your GitHub repository.
-----------------------------------------------------------------
Details : 
* Local Folder: "Interview Prep" on your E drive (E:\Interview Prep)    Assume there are some files in your folder i.e 'Interview Prep'
* Remote Repository: "Interview-Prep-AI-ML-" on GitHub




# Lets Start : 
= = = = = = = = = = = = 

1. Create a Repository in Git hub.
   - Suppose "Interview-Prep-AI-ML-".
  
2. Copy the Clone code.

3. Come on your local desktop

4. Create a local folder

5. Now open the CMD there itself.
   - Suppose you have created a folder named : "Interview Prep".
   - Then You are currently on "E:\Interview Prep" this path.
   - Now you opend the CMD in this path.
  
6. Command : git clone <clone code>

7. Command : git add .

8. command : git status -v

9. Command : git commit -m "Your message"

10. Command : git push origin <main>
    - Replace <main> with your default branch of the repository.
    - Dont worry ... read below to how you can find the default branch.
    - After opening the repo, below the Repository you can see the branch name.
   

Thats it bro... :)


# Possible error :
---------------------

- Suppose you have modified some sentences, words directly in your Git repo i.e readme.txt or any other file.
- Now you don't have those changes into your local folder in which you have cloned the Git Repo.
- 
- So first you need to use below command to update the changes happened in the Git into your folder.
  * Command : git pull origin main
  (main is the default branch of this repo so)
  
- Then you can add some files into your local folder if you want. Then to update the local folder changes into git repo, you need to use below commands after adding the files/ folders.
  * Commands :

  git add .
  git commit -m "Resolved merge conflicts"
  git push origin main

 
