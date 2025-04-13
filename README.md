# 🚀 GitHub Actions Learning Repository

<p align="center">
  <img src="imgs/github-actions.png" width="80%" alt="GitHub Actions">
</p>


Welcome to the GitHub Actions Learning Repository! This project is part of a hands-on effort to master GitHub Actions, GitHub’s continuous integration and automation platform.

Having already gained experience with Jenkins for automating CI/CD pipelines, I'm now expanding my knowledge to explore alternative CI/CD solutions. This repository serves as a learning environment where I experiment with creating, testing, and automating workflows to improve my understanding of GitHub Actions and compare it with other CI/CD tools.

## 🎯 Project Overview

The goal of this repository is to explore and experiment with various features of GitHub Actions. Through this repository, I aim to develop the skills needed to build efficient automation pipelines and CI/CD workflows for modern software development processes.

This project will also serve as a collection of practical examples that demonstrate the power and flexibility of GitHub Actions.

## 🚀 Key Features

This repository covers the following key areas:

* Creating and Configuring Workflows: Learn how to define and set up .github/workflows for different tasks.

* Automation with Triggers: Understand how to use triggers such as push, pull_request, schedule, and more.

* Integrating Marketplace Actions: Leverage pre-built actions from the GitHub Marketplace to streamline workflows.

* Writing Custom Actions: Explore how to build and use custom GitHub Actions for specialized tasks.

* CI/CD Pipeline Automation: Automate testing, deployments, and other tasks within your software development pipeline.

## 🧠 Learning Resource

This repository is built around the **[Udemy course: GitHub Actions: The Complete Guide](https://www.udemy.com/course/github-actions-the-complete-guide/)**.


The course provides comprehensive tutorials and real-world examples, making it an excellent resource for mastering CI/CD automation with GitHub Actions. It covers everything from setting up simple workflows to automating complex tasks in your software development lifecycle.


## 📁 Project Structure

Here’s the overall structure of the repository:
```
gh-first-action/
│
├── .github/                      # Workflow files and GitHub Actions configurations
│   ├── workflows/                 # Contains YAML files for workflows
│   │   └── main.yml               # Main workflow file for CI/CD tasks
│
├── imgs/                          # Image assets for documentation
│   └── github-actions.png         # Screenshot of GitHub Actions UI
│
├── README.md                      # This file
└── LICENSE                        # Project license (TBD)
```

## ⚙️ Setup Instructions

Clone the Repository:
```bash
git clone https://github.com/gavinpaultech/gh-first-action.git
cd gh-first-action
```

Set up your GitHub Action workflows in .github/workflows/ by modifying existing YAML files or adding new ones according to your project needs.

**Run your workflows:** Once the repository is set up and your workflows are defined, you can push changes to GitHub, and the workflows will trigger automatically based on your configured events (e.g., push, pull_request, etc.).

## 📊 Status

This repository is in active development and will continue to evolve as new features and automation strategies are explored. 🙂