---
title: Github Actions Walkthrough
date: 31/05/2021 
author:
 - Bhawick Jain
or: 20210531131509
---

[![tests](https://github.com/BhawickJain/github-actions/actions/workflows/test.yml/badge.svg)](https://github.com/BhawickJain/github-actions/actions/workflows/test.yml)


Basic walkthrough of github actions.


## Why use GitHub Actions?

Used to automate developer workflows which are called repeatedly. It is often seen as a CI/CD feature but that is only one usecase. Other use cases may be: (1) running a grammar/linter agaist the code, (2) sending updates to other services, or (3) managing requests to contribute or triaging issues.

## Concepts

Github Actions are triggered by Github Events. Events such as the creation of an Issue or Pull Request or a new contributor joining. You can also listen events happening from other places. This triggers a workflow, which involves a series of Github Actions..

## CI/CD Pattern

This is a classic usecase and here's how it goes:
1. Commit Code 
2. Test
3. Build package
4. Push package
5. Deploy Package

Github Actions isn't just another CI/CD Tool is native to the platform and integrates well with other workflows which are not CI/CD.


