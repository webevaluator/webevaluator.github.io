# WebEvaluator - An Automated Website Tester

## Introduction

This is an advanced web crawling tool that will not only discover the active URLs within the website but also provide information about SSL certificate compliance, Cookie checker and ADA compliance and details about the security headers.

## Deployed Link
https://webevaluator.github.io/

## Pre-requisites

Your machine should have Npm(or Yarn) installed to use it locally.

## Setting up the repository locally

1. Fork the repo to your account.

2. Clone your forked repo to your local machine:
Replace `<YOUR_GITHUB_USERNAME>` with your actual GitHub username in the below command. This will clone the code to your local machine.
```
git clone https://github.com/<YOUR_GITHUB_USERNAME>/webevaluator.github.io.git (https)
```
or
```
git clone git@github.com:<YOUR_GITHUB_USERNAME>/webevaluator.github.io.git (ssh)
```

3. Change directory to `webevaluator.github.io`.
```
cd webevaluator.github.io
```

4. Check the remote of your local repo by:
```
git remote -v
```
It should output the following:
```
origin	https://github.com/<YOUR_GITHUB_USERNAME>/webevaluator.github.io.git (fetch)
origin	https://github.com/<YOUR_GITHUB_USERNAME>/webevaluator.github.io.git (push)
```
or
```
origin	git@github.com:<YOUR_GITHUB_USERNAME>/webevaluator.github.io.git (fetch)
origin	git@github.com:<YOUR_GITHUB_USERNAME>/webevaluator.github.io.git (push)
```

5. Add remote upstream by running the below command:
```
git remote add upstream https://github.com/webevaluator/webevaluator.github.io.git (https)
```
or
```
git remote add upstream git@github.com:webevaluator/webevaluator.github.io.git (ssh)
```

6. Running `git remote -v` should then print the following:
```
origin	https://github.com/<username>/webevaluator.github.io.git (fetch)
origin	https://github.com/<username>/webevaluator.github.io.git (push)
upstream	https://github.com/webevaluator/webevaluator.github.io.git (fetch)
upstream	https://github.com/webevaluator/webevaluator.github.io.git (push)
```
or
```
origin	git@github.com:<username>/webevaluator.github.io.git (fetch)
origin	git@github.com:<username>/webevaluator.github.io.git (push)
upstream	git@github.com:webevaluator/webevaluator.github.io.git (fetch)
upstream	git@github.com:webevaluator/webevaluator.github.io.git (push)
```

## Run locally

- For installing dependencies run
```
npm install
```

- For starting the frontend run:
```
npm start
```

- Go to: http://localhost:3000