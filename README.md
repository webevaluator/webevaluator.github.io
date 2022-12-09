# WebEvaluator - An Automated Website Tester

[![Slack Channel](https://img.shields.io/badge/slack-webevaluator-blue.svg?longCache=true&logo=slack)](https://join.slack.com/t/webevaluator/shared_invite/zt-1i6rwnif9-hPh9fyg4ZZSpfI79d4hfbA)
[![Docker Pulls](https://img.shields.io/docker/pulls/webevaluator/webevaluator.github.io.svg)](https://hub.docker.com/r/webevaluator/webevaluator.github.io)
[![GitHub stars](https://img.shields.io/github/stars/webevaluator/webevaluator.github.io?style=social)](https://github.com/webevaluator/webevaluator.github.io/stargazers)
## Introduction

Every year tech giants face billion dollar lawsuits against them in the United States of America and the European Union as their website is incompatible with the American with Disability Act (ADA) or the General Data Protection Regulation (GDPR), respectively. So we created a tool named WebEvaluator, ( https://webevaluator.github.io/ ) to help website developers find compliance issues and warnings in their website and it also suggests ways to fix them.
Its features are:
- A super fast crawler written in Go that could process more than 1000 requests/second/core. It looks for URLs in all the HTML, CSS, JavaScript, and sitemap.xml files.
- SSL certificate compliance agent checks for the certificate's validity and analyzes the SSL certificate for security issues.
- Cookie checker agent checks whether cookie consent is asked, deny cookie option is present and it also categorizes all the cookies stored by the website into groups like Advertisement, Analytics, Necessary, Functional, and Others.
- ADA compliance agent looks for various issues on the website, which could make it difficult for people with special needs to access it. It also suggests ways to fix those errors.
- Security headers agent verifies that all the required security headers are present.
- Report generation agent creates a detailed downloadable report in pdf/csv format with a score for each category of analysis.


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
