# spring2021se
1. Group information 

HARISH REDDY VANGANURU 

VENKATABHASWANTH AKULA 

2. Github URL 

https://github.com/harish1712/spring2021se.git 

3. How your group work together (activities, hours used for each activity etc)
 We worked almost 2 hour to complete the assignment and we both sat together and worked on the lab.

4. Project introduction 
Introduction: 
GitHub is a website where programmers and developers may collaborate on code. The main advantage of GitHub is its version control system, which enables seamless collaboration without jeopardizing the original project's integrity.

5. Majore steps 
# Github and Cloud9 setup using personal access token.
---------------------------------------------------------------------------------------------------------------------

1.	Signed into Github.com and created a new Repository
2.	Edited Readme file in repository and committed
3.	In GitHub under Account settings  Developer settings Personal Access Tokens
4.	Generate a new token
•	Customized date 
•	Select Repo
•	Click Generate token button
5.	Copied ‘personal access token’ and pasted in safe place
6.	Logged into AWS console
7.	Opened cloud9 from services
8.	Created New Environment in Cloud9 environment
•	Fill ‘name’ and ‘description’
•	Click ‘next step’ button
•	Kept the default settings (Again clicked ‘next step’)
9.	Created Environment. So that Cloud9 environment is created.
Note:We are completed Till Step5 (git hub)

10.	Delete Readme file in AWS console
11.	Run command : git config --global credential.helper store in aws terminal
12.	Run command : git clone ‘https clone url’
Note: Copy clone repository
Then it will clone to your repository(SE CIS5755)
13.	Enter Username: ‘is your git username’
14.	Enter Password: ‘is the personal access token’
15.	Once you complete these steps, you can see to files LICENSE and README.md added in your folder ‘SE CIS5755’ and your folder got synchronized.
16.	We can add more information to README.md file
17.	To get/enter into the main, 
run command: 
a.	cd .. 
b.	cd ‘directory name’, so that you see main, then it is said to be synchronized.
18.	To create a basic directory run command: mkdir ‘directory name’ for example, ‘Group-Project’
19.	To enter into directory, run command: cd ‘directory name’
Note: We are done till step11 here.
20.	We have to create environment here, for that run command: python3 -m venv env
Note: Then we can see env folder inside the created directory.
21.	Activate the env using command: source env/bin/activate
22.	Created a new file in folder ‘Group-Project’ as ex1.py 
23.	Edited that file with python code
24.	Run to get the output.
Note: We are done till step15
25.	Now, change the directory using command: cd ‘directory name’ (cd SE-CIS5755)
26.	Run command: git add –all
27.	Run command: git status to check the status
28.	Then commit the changes using command: git commit -m “enter message”.
29.	Push the committed code using command: git push
30.	Created another new file in a folder ‘Group-Project’ as ex.py 
31.	Entered the Basic Flask Code
32.	In the terminal, installed Flask package (library): python3 -m pip install flask
33.	 Upgraded the pip using command: python3 -m pip install –upgrade pip
34.	Run the file ex2-flask.py and click on preview and preview running application to check the flask file working or not.
35.	Run command: pip freeze > requirements.txt
36.	Now commit and push the new created requirements.txt file to git.
37.	So that that file will be synchronized and shown in git repository.