# Pieces Google Summer of Code'24 Participant Guide

## **Communication**

Welcome to the Pieces Open Source GSoC projects page. 

Your enthusiasm and unique perspectives are valuable additions to our open-source community. We believe in fostering an inclusive environment where everyone can learn, grow, and collaborate. 

Our [Discord server](discord.com/getpieces) is the best place to connect with other open source contributors or our maintainers. To make the most out of our discord server, ask your questions under the Open Source Chat channel, having the messages in the right place makes it easy for our team to respond quite fast. 


## **General suggestions for contributors**
- **Code and prototypes are preferred over detailed documentation**:
  Rather than investing extensive time in detailed application documents or unreliable estimates, we encourage applicants to channel their efforts into creating functional prototypes. The emphasis lies on tangible code and prototypes, 

- **Project goal setting**:
 While project ideas articulate overarching goals, they acknowledge the need for further refinement during the project lifecycle. Students are encouraged to conduct independent research, present innovative solutions, and be adept at navigating uncertainty and overcoming challenges that may arise throughout the project

## **Projects List**

### Python-Cli Project

The Python CLI makes it easy to use the client inside of the terminal. It would be great to queue up the goals that we have set the CLI currently to bring it closer to our full feature set:
	

#### Skills Required
  - Python
  - CLI
  - PyPi Packaging
  - Pieces Client SDK’s
- **Time Estimate:** 175 hours
- **Difficulty:** Medium

#### Task List

- Add further functionality to the CLI-Agent project
- Add Copilot Functionality
  - Copilot fix
  - Copilot Ask
- Add Pieces core functionality
  - Search
  - Saving
  - Start
  - Assets


### Drag & Drop IntelliJ Project

Drag and drop plugin allowing for additional functionality around dragging and dropping different asset types for custom IntelliJ plugins.

#### Skills Required

- Kotlin
- IntelliJ SDK
- Pieces Client SDK

- **Time Estimate:** 90 hours
- **Difficulty:** Small

#### Task List

- Expand data flavors to allow for more file type interaction
- Drag and drop images
- Enhance Readme to include more related examples using Pieces APIs in ways that could expand the drag and drop project

### Chrome Extension (Web Extensions) Open Sourced

- **Skills Required:**
  - Dart
  - Pieces Client SDK
  - Chrome Web Extensions
- **Time Estimate:** 225 hours
- **Difficulty:** Medium

#### Task List

- Moving a closed source project to open source
- Extract hyperlinks in the selection and add to the snippet metadata
- Brave browser side panel support
- Add browser notification callbacks confirming if an asset is saved successfully or other snippet-related information
- Update documentation throughout the codebase

### Pieces-github-bot

An AI github bot that assists with maintaining, triaging, and contributions to an open source project completely on device and free inside of Github Actions pipelines. In order to create an easier to manage workflow system for community maintainers, this project would help provide insights and maintainability for extremely small repositories to very large repositories.

- **Skills Required:**
  - Github Actions
  - YAML
  - Pieces Client SDK
  - Bash
- **Time Estimate:** 300 hours
- **Difficulty:** Hard

#### Task List

- Test spinning up a Pieces OS version in CI/CD
- Understand the context of the repository it is in
- Provide insights and maintainability for repositories
- Install Pieces OS
- AI bot to respond to issues, triage bugs, and build better documentation

