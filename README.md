# Version control systems

This page is not a full guide to version control systems. It is merely an introduction for absolute beginners.

## What is version control

Historically when multiple people were working on a software project there wasn't a streamlined way to compile the code. Everybody gave their code to one person who lit a few candles and gave a prayer and then compiled the code. Not to mention when people were sharing their code, they put it on flash drives and passed that around. This way it was often not clear which is the latest version of code which caused some confusion.

While these hurdles are manageable in smaller projects, nowadays, in huge software projects this would be unmanageable. This is where version control comes into play. A version control system is supposed to streamline the development process where everyone is up to date on all the changes.

## Benefits of using version control

- A good version control system allows every developer to make changes to the code at the same time and then see each other's changes. This prevents developers from working with outdated code.
- Version control systems can also manage access of people, making sure that code cannot be deleted by accident. This helps avoid irreversible damage.
- The entire change history is stored by the version control system allowing developers to go back in the code and see when features or problems were introduced.
- Modern version control systems can also plug into other services like Continous Integration, making a pipeline for software development.

## Version Control System and Version Control Repo host

The most common Version Control system nowadays is git. Git is a command-line tool, but some people and companies built User Interfaces around it. Git is the technology which does the heavy lifting. It manages the project, keeps track of the changes and history.

However, git would be useless if others couldn't access it. This is why there are companies specialised in hosting these git repositories. This way anyone you give permission to can see the project and make changes to it. The most popular service for hosting projects is GitHub but there many others too.

## Best version control systems

| <img src="https://img.icons8.com/material/48/000000/github.png"> | <img src="https://img.icons8.com/material/24/000000/bitbucket.png"> | <img src="https://img.icons8.com/ios-filled/50/000000/gitlab.png"> | <img src="https://img.icons8.com/material-sharp/48/000000/amazon.png"> |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [GitHub](https://github.com) | [GitLab](https://gitlab.com) | [BitBucket](https://bitbucket.org) | [AWS CodeCommit](https://aws.amazon.com/codecommit/) |
| GitHub is a development platform inspired by the way you work. From open source to business, you can host and review code, manage projects, and build software alongside 40 million developers. | itLab is a web-based DevOps lifecycle tool that provides a Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features, using an open-source license, developed by GitLab Inc. | Bitbucket is a web-based version control repository hosting service owned by Atlassian, for source code and development projects that use either Mercurial or Git revision control systems. | AWS CodeCommit is a version control service hosted by Amazon Web Services that you can use to privately store and manage assets (such as documents, source code, and binary files) in the cloud. |
