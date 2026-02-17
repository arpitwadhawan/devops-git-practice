#!/bin/bash

# Git Commands Reference

## Setup & Config

### git --version
What it does: Shows installed Git version.
Example:
git --version

### git config --global user.name
What it does: Sets your global Git username.
Example:
git config --global user.name "Your Name"

### git config --global user.email
What it does: Sets your global Git email.
Example:
git config --global user.email "your@email.com"

---

## Basic Workflow

### git init
Initializes a new Git repository.
Example:
git init

### git status
Shows the current state of the working directory.
Example:
git status

---

## Viewing Changes

### git log
Shows commit history.
Example:
git log

### git add
Adds changes to the staging area.
Example:
git add file.txt

### git commit
Records staged changes into repository history.
Example:
git commit -m "message"

### git diff
Shows changes between working directory and last commit.
Example:
git diff

## Branching

### git branch
Lists or creates branches.
Example:
git branch

### git switch
Switches between branches.
Example:
git switch feature-1
