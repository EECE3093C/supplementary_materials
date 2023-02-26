# Resources for EECE3093C Spring 2023 Semester Project

This document provides information and resources necessary for the semester project.

### Dev Containers

Containerization will be done through the use of Visual Studio Code Dev Containers.  The expectation is that any repo can be downloaded, and through Visual Studio Code Dev Containers, you are guarnteed to have a consistent development environment.

<br/>

> **Warning**
> 
> Containerization **must be done** through Dev Containers.

<br/>

<details>
  <summary>Resources for Dev Containers</summary>
  
  - [Dev Containers tutorial](https://code.visualstudio.com/docs/devcontainers/tutorial)
  - [Manually create a dev container](https://code.visualstudio.com/docs/devcontainers/create-dev-container)
  - [Developing Inside a Container](https://code.visualstudio.com/docs/devcontainers/containers)
</details>

<br/>

### Git Branching Strategy

It is recommended that you use a per developer branching strategy, where each developer has their own dev branch that is named `dev-[lastname]` (e.g., dev-margeson, dev-cimini).  You may consider a per issue branching strategy, where each task or issue has its own dev branch, such as `dev-issue-1`, `dev-issue-2`, `dev-issue-3`, etc.  The final option to consider would be a feature branching strategy, this is where each feature in development has its own dev branch.  By feature we mean a discrete feature, such as `dev-frontend-scaffolding`, `dev-frontend-menu`, `dev-frontend-authentication`, etc. 

<br/>

<details>
  <summary>Resources for Git Branching</summary>
  
  - [Git Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
  - [Branching Strategies](https://github.com/EECE3093C/supplementary_materials/blob/main/branching_strategies.md)
</details>

<br/>

### Git Commits

For a commit to be considered good, it should be singular (atomic) and describe only one change. This makes it easier for other developers to understand the change and to roll back the change if necessary.

> **Warning**
> 
> Commit messages must include a reference to a single issue.


<br/>

<details>
  <summary>Resources for Git Commits</summary>
  
  - [Git Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
  - [Branching Strategies](https://github.com/EECE3093C/supplementary_materials/blob/main/branching_strategies.md)
</details>

<br/>

### GitHub Actions

GitHub Actions is an automation tool that allows you to define workflows to build, test, and deploy your code in response to different events, such as code pushes, pull requests, or issue creation. In addition to reacting to events, you can also schedule GitHub Actions to run at specific times, such as daily or weekly. This can be useful for running automated tests or backups, generating reports, or any other tasks that need to be performed regularly.  GitHub Actions extend far beyond continuous integration and continuous delivery (CI/CD) platform automation, you can automate many routine tasks and free up your time to focus on creating great software.

A GitHub Action workflow is a set of automated steps that can be defined in a YAML file. The workflows are flexible and can run on different operating systems, including Linux, Windows, macOS, and cloud platforms such as Amazon Web Services (AWS). You can create workflows using various programming languages and frameworks, such as Node.js and Python. 

<br/>

<details>
  <summary>Resources for GitHub Actions</summary>
  
  - [Understanding GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
  - [Quickstart for GitHub Actions](https://docs.github.com/en/actions/quickstart)
</details>

<br/>

### GitHub GUI

It is recommended that you use either [GitHub Desktop](https://desktop.github.com) or use [Visual Studio Codes git functionality](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git).

<br/>

<details>
  <summary>Resources for GitHub GUI</summary>
  
  - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop)
  - [Intro to git for Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)
</details>

<br/>

### .gitignore

A `.gitignore` file specifies intentionally untracked files that Git should ignore.  Ignored files are usually operating system, IDE, build artifacts and machine generated files which should not be committed.  Please read [ignoring files in Git](https://www.atlassian.com/git/tutorials/saving-changes/gitignore) from Atlassian for an introduction.

<br/>

> **Warning**
> 
> Changes to `.gitignore` do not impact files that have already been checked in.  They will remain unless until you remove them.
>

Toptal provides a REST API to generate a `.gitignore` file for you. For example, the following command will create a `.gitignore` file that includes the most common files and directories to ignore for Linux, Visual Studio Code, Python, Node, and React:

```sh
curl https://www.toptal.com/developers/gitignore/api/linux,visualstudiocode,python,node,react --output .gitignore
```

You can also use the API interactively through their website:

[https://www.toptal.com/developers/gitignore](https://www.toptal.com/developers/gitignore)

<br/>

<details>
  <summary>Resources for .gitignore</summary>
  
  - [ignoring files in Git](https://www.atlassian.com/git/tutorials/saving-changes/gitignore)
  - [Toptal gitignore website](https://www.toptal.com/developers/gitignore)
  - [Toptal gitignore REST API](https://www.toptal.com/developers/gitignore/api/)
</details>

<br/>


### GitHub Project and Issues

Every team must have a single GitHub Project created from the `Feature` project template.  

- You must actively maintain a [product backlog](https://www.atlassian.com/agile/scrum/backlogs).

You must clearly demonstrate per iteration planning, and have an overall objective of what working software will be delivered for that iteration.

<br/>

> **Warning**
> 
> All work done by all team members must be accounted for through issues.  If it is not an issue, you **cannot** get credit for the work.  Therefore, even researching a particular concept should be documented as an issue, with what you learned and the direct outcome as it pertains to the issue documented through a comment (on the issue).

<br/>

- During iteration planning (or prior), issues must:
  - be assigned to the [iteration](https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields/about-iteration-fields)
  - be assigned to a developer
  - classified by assigning a label
- Team discussions about an issue must be captured through issue comments.

<br/>

<details>
  <summary>Resources for GitHub Projects and Issues</summary>
  
  - [Quickstart for Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects)
  - [Quickstart for Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart)
  - [The product backlog: your ultimate to-do list](https://www.atlassian.com/agile/scrum/backlogs)
  - [Creating an Issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)
  - [Iteration field](https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields/about-iteration-fields)
  - [Managing labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)
</details>

<br/>

### Issue Writting

You can use the acronym **INVEST** to remember six essential concepts for effective issue writing. INVEST stands for **I**ndependent, **N**egotiable, **V**aluable, **E**stimable, **S**mall (sized appropriately), and **T**estable.

- *Independent* means that the issue should be self-contained and not dependent on other issues. An independent issue can be worked on without relying on the completion of other issues, which can help to keep the development process moving forward more efficiently.
- *Negotiable* means that the issue should be flexible and open to negotiation. The issue should be written in a way that allows for discussion and refinement, and there should be room for adjustments and changes based on feedback and other factors.
- *Valuable* means that the issue should provide value to the end-user or customer. The issue should be focused on solving a real problem or delivering a useful feature that meets the needs of the user, rather than just being a technical exercise.
- *Estimable* means that the issue should be able to be estimated in terms of time, effort, and resources required to complete it. This helps to ensure that the issue is realistic and feasible, and that it can be properly prioritized and scheduled within the development process.
- *Small* means that the issue should be small enough (sized appropriately) to be completed within a reasonable amount of time, preferably a few hours to a day. Small issues are easier to manage and prioritize, and they can help to ensure a steady flow of progress within the development process.
- *Testable* means that the issue should be testable in order to ensure that it meets the necessary requirements and works correctly. Testability is an essential aspect of quality assurance, and it can help to catch and fix issues before they reach the end-user or customer.

Additional writing guidelines:

- Break down complex issues into smaller, more manageable parts.  An issue should be focused on a single problem or feature as it will help the development team prioritize and address it effectively.
- The issue should have a clear and concise title that summarizes the issue in a few words.
- The issue description should use simple language and avoid technical jargon or complex vocabulary that may be difficult to understand.
- If the issue is a bug, it is important to provide clear and concise steps to reproduce the problem. This will help the development team identify the root cause and fix the problem efficiently.
- Provide specific requirements or expectations, so the development team knows exactly what is expected of them.  This can include functional requirements, performance goals, or other key metrics.
- Include any relevant information or resources that may be needed to solve the issue, such as error messages, logs, or screenshots.
- Includes relevant user research.

<br/>

<details>
  <summary>Resources for Issue Writing</summary>
  
  - [Writing effective user stories](https://tech.gsa.gov/guides/effective_user_stories/)
  - [Write good issues](https://tilburgsciencehub.com/building-blocks/collaborate-and-share-your-work/project_management/write-good-issues/)
</details>


