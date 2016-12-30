# Npm Boilerplate

[![npm (scoped)](https://img.shields.io/npm/v/@told/npm-boilerplate.svg)](https://www.npmjs.com/package/@told/npm-boilerplate)
[![Build Status](https://travis-ci.org/toldsoftware/npm-boilerplate.svg?branch=master)](https://travis-ci.org/toldsoftware/npm-boilerplate)
[![Coverage Status](https://coveralls.io/repos/github/toldsoftware/npm-boilerplate/badge.svg)](https://coveralls.io/github/toldsoftware/npm-boilerplate)

## Instructions

- Create Empty Github Project
- Copy this repo into directory (except .git)
- Replace README and package.json with BOILERPLATE versions (You might want to make a copy of this file if needed.)
- Find/Replace MODULE_NAME and MODULE_TITLE
- Commit and Push Project to Github
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
- Push Any Change to Git
    - Travis: Verify Test Runs
    - Coveralls: Verify Coveralls Received Report
        - May have to Restart Build (Since Token was just set)
- Publish to *NPM*
    - npm publish --access-public
- Github: Verify Icons have updated
    - Sometimes this can take a while

