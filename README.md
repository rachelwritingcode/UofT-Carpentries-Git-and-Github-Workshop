## University of Toronto Carpentries Community Git & Github Workshop 👩🏻‍🏫

- This workshop introduces users on how to use git and create their first pull request.
- I created a repo with haiku poems and walk attendees through the process of adding their own haiku poems to the repo.
- Attendees do not need to have any prior knowledge to attending the workshop.

## What is Carpentries?
- A non-profit that teaches data and coding skills to build global capacity in essential data and computational skills.
- More information about them can be found [here](https://carpentries.org/about/).

---

## Workshop Steps for Participants

1. Open your terminal and clone the repository to your local machine. You can clone the project by running this command.

  `git clone https://github.com/rwangca/git-workshop.git `
  
2. Navigate inside the git project folder using `cd git workshop`

3. In the terminal, create a new branch by running this command `git checkout -b (your_firstname_lastname)`

3. Open http://www.everypoet.com/haiku/ generate your own haiku poem by clicking New Haiku.

4. Copy the haiku text and place it in a text editor like notepad++ or sublime text.

5. Save the file as a .txt file type.

5. Using the terminal, type `git status` and you will see some highlighted text which notify you of changes made to the project. 

You will see the name of the file you created listed. 

6. Add your files to the project and push it to the remote project. 
    ```
    git add *file_name*
    git commit -m "Adding my haiku poem"
    git push
    ```
7. Navigate to the project page on the Github UI and create a pull request. 

8. I will review your pull request and merge it! 

9. You're done! Congratulations! 🎉🎉🎉

