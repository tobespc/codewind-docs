---
layout: docs
title: "Getting started with Codewind for VS Code"
description: "Getting started with Codewind for VS Code"
keywords: introducing, introduction, overview, tools, get, getting, start, started, install, vscode, visual, studio, code, Codewind for VS Code getting started, VS Code Marketplace, VS Code Extensions view, VS Code workspace,installing Codewind for VS Code
duration: 1 minute
permalink: mdt-vsc-getting-started
type: document
order: 1
parent: mdt-vsc-overview
---

# Getting started with Codewind for VS Code

Codewind for VS Code enables you to develop your containerized projects from within VS Code.

The following information describes how to install Codewind for VS Code, and introduces the tools and the Codewind Explorer view. It then describes how you can create a new project or work with an existing project, and introduces the wide range of Codewind development features available to you.  

To install Codewind for VS Code, complete the following steps:

1. Install [VS Code version 1.38 or later](https://code.visualstudio.com/download).
2. Install [Docker](https://docs.docker.com/install/) 17.06 or later. If you use Linux, you also need to install Docker Compose.
3. Install Codewind by clicking [this link](vscode:extension/IBM.codewind) to install from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=IBM.codewind), or by searching for *Codewind* in the [VS Code Extensions view](https://code.visualstudio.com/docs/editor/extension-gallery#_browse-for-extensions).
    - If you're going to work on Java projects, also install the [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack).
4. Open the Codewind view in the [Explorer view group](https://code.visualstudio.com/docs/getstarted/userinterface), or enter *Focus on Codewind View* into the [Command Palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette).
    - If you do not see the Codewind view in either the Explorer or the Command Palette, the extension did not install correctly.
5. Codewind requires the installation of additional Docker images to run.  Choose **Install** when prompted to complete the installation.  The installation may take a few minutes to complete.
6. Codewind creates a codewind-data directory for storing its metadata. Do not save your projects to the codewind-data directory.  

You are now ready to use the tools. You can use the Codewind view to create new projects or add existing ones.  Right-click a project in the Codewind tree or enter *Codewind* into the Command Palette to look at the features available.

1. Create a new project or work with an existing project.
  - To create a new project, right-click the *Projects (Local)* item and select **Create New Project**, or click on the *+* icon beside the *Projects (Local)* item.
  - To work with an existing project, right-click the *Projects (Local)* item and select **Add Existing Project**.

2. Work with your project from within VS Code including:
    - Editing
    - Debugging MicroProfile/Java EE, Spring, and Node.js projects
    - Opening the application in a browser
    - Viewing the logs
    - Opening a shell into the application container
    - And more
