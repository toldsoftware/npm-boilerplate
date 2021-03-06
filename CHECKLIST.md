Steps to setup a new project using this boilerplate.

Note: You might want to make a copy of this file if needed

- Create Empty Github Project
- Copy this repo into directory (except .git)
- Rename Notes/HoursNAME.md and start tracking time
- Replace README and package.json with BOILERPLATE versions
- Find/Replace MODULE_NAME and MODULE_TITLE
- Setup NPM

        npm install
        npm test 
        
- Create *Coveralls* Project for repo: https://coveralls.io
    - Add Repo
    - Sync repos (At bottom)
    - Find and Add Repo
    - Copy Token: 
        - Settings > Repo Token > [Copy]
- Create *Travis* Project for repo: https://travis-ci.org
    - Add Repo
    - Sync Account
    - Set Environment Variable for *Coveralls*
        - Settings > Environment Variables
            - repo_token
            - TOKEN_FROM_COVERALLS
            - Click "Add"
- Commit and Push Project to Github
- Publish to *NPM*

        npm publish --access public

- Verify Deployment 
    - Github: Verify Icons have updated
    - Travis: Verify Test Runs
    - Coveralls: Verify Coveralls Received Report
    - Sometimes this can take a while or the images get cached by the browser.

## OPTIONAL

- Open the OPTIONAL folder and follow the directions in one of the subfolders to add it's boilerplate
- Once done, delete the OPTIONAL folder to remove unneeded boilerplate