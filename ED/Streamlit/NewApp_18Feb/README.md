Step:1: Create the App fro GIT file with code or empty file.

1] Created a blank file NewApp_18Feb.py in Git or copy the code from the existing_APP and put that in .py file and place it in git

2] From SiS "Create from repository" 

3] select the branch = test_18feb and create the APP, name it "NewApp_18Feb" from the folder and .py file  in Step-1

4] Opened the NewApp_18Feb.py file and placed the code in the py file

5] Added "Stem_Testing_1.0" in the title/header

6] Updated the README file

7] Push it to GIT on the Branch "test_18Feb"
_____________

Step:2:

1] closed the App after the commit in Step-1

2] reopened the app and updated it, added "Stem_testing_2.0"

3] updated the ReadMe file

4] Push it to GIT on the Branch "test_18Feb"and commit

Observation: 
1] App is created and updated


_____________
Next Step:

1] Create a New DB in Snowflake for App Deployment to higher Env/PROD = DB, schema, roles etc

2] Example DB = (STREAMLIT_APPS_PROD), Schema = TEAM_RND_PROD, Role = STREAMLIT_DEVELOPER_PROD

3] do the merges in Git to have the Code base on Main branch for PROD movement

4] Create new app from the main branch in PROD REPO

5] Create New APP using SiS "Create from repository" 

6] Point to teh newly Created and Defined PROD-DB/Schema + PROD_Repo location

7] Use the MAIN Branch to fetch the APP that was created, merged to mainBranch for deployment as in [3] 




