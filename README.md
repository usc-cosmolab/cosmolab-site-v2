# How to edit and use this repository (repo) to make changes to our cosmolab website

1. Copy repo link from github:
	- click green code block
	- copy ssh link
2. Clone to your computer
	- In a terminal, go to the directory/folder you want the repo in
	- type in terminal command:`git clone paste-ssh-link-here`
3. Create a new branch for you to code in
	- `git checkout -b branch_name` where branch_name is the name of the branch you wish to create
	- Can always call `git status` inside a git repo/directory to check up on your branch
4. Make code/file/directory edits
	- For images, copy and paste an image to the `cosmolab-site-v2/images` directory
5. Preview your changes with your browser, e.g.
	- `firefox index.html`
6. Add your changes
 	- `git add /path/to/edited/files`
7. Commit your changes
 	- `git commit -m "Provide a note of what you changed here"`
8. Push your changes to github
 	- `git push origin branch_name`
9. Last steps! Create a pull request:
 	- Go to our github: github.com/usc-cosmolab/cosmolab-site-v2
 	- A message at the top of the page should appear, saying "branch_name had recent pushes"
 	- Click "Compare & Pull Request"
 	- Make sure you are comparing branch_name to base:main 
 	- Leave a comment and click "Create Pull Request"
10. Wait on Mathew/Vera to accept your PR (pull request)


## Summary/Cheat sheet:
There are 5 commands you need to use, listed below.  

`git clone link-to-repo`

`git checkout -b branch_name`

`git add /path/to/file`

`git commit -m "comment addressing the changes you made"`

`git push origin branch_name`

The logic is: Clone the repo to your machine. Checkout (create) a new working branch. Edit, then Add your changed files. Commit your changes. *Push* the changes to github. Creat a *Pull Request* via web interface at the end.
