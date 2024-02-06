# Google Summer of Code 2024 | Open Source by Pieces
Welcome to the Pieces GSoC 2024 guide and projects page, where you can find information on the projects planned for this year and other information.

[Join our Discord](https://discord.gg/getpieces) for updates and to meet the community.

We are planning to open up proposal submissions at the beginning of March - so stay tuned.

## What is Google Summer of Code?
Google Summer of Code is a 10+ year old program that brings students closer to development through open source and support the community as a whole through summer projects. 

Open source organizations and projects can become mentor organizations to provide summer projects that are planned out between the mentors and the contributors before and during the project. Learn more about the program [here](https://summerofcode.withgoogle.com/how-it-works).

## Tagline
An Open Source Copilot with Context using Large Local Language Models that helps you code, save code snippets, and more throughout your workflow.

## Organization Details

- **Primary Open Source License:** MIT
- **Organization Categories:**
  - AI
  - Dev Tool
  - Infra & Cloud

## Mentors

- [Shivay Lamba](https://github.com/shivay-at-pieces)
- [Jordan Freeman](https://github.com/jordan-pieces)
- [Rutvik Tak](https://github.com/rutvik110)
- [Sophia Irogebu](https://github.com/Sophyia7)
- [Sam Jones](https://github.com/sam-at-pieces)

## Projects

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

## Org Technologies

- Dart
- Python
- Kotlin
- Typescript
- Javascript

## Org Topics

- Large local language models
- Copilots
- Machine learning models
- Local on device
- Developers
- Code tools

## Org Description

**Pieces Copilot and Snippet manager** are built to unify your entire toolchain with an on-device copilot that helps you capture, enrich, and reuse useful materials, streamline collaboration, and solve complex problems through a contextual understanding of your workflow. At Pieces.app, we have opened up the core functionality of Pieces OS to give all developers the opportunity to build their own copilots using our toolset.

## Mission Statement

At Open Source by Pieces, we are dedicated to advancing the principles of open source innovation and collaboration. Our mission is to foster a vibrant community of experienced developers, emerging novices, and contributors united in building and shaping our platform through shared knowledge and collective effort. Through the Pieces OS Client SDKs, we strive to empower developers globally to create amazing tools and solutions they would love.

Powered by community-driven development, where diverse perspectives come together to drive meaningful progress through fostering inclusivity, collaboration, and continuous learning, we encourage active participation among our members. Together, we aim to achieve a future where technology serves as a force for positive change and where users and developers alike can build whatever tool fits their needs.

## Our Goals

- Provide powerful workflow tools for developers to assist in maintaining and managing the open-source community as a whole
- Educate developers on using copilots responsibly and to their advantage, while also allowing for learning and growth in their skill set
- Allow developers in locations with limited or poor connections work from home with access to a fast and functional copilot
- Make documentation globally available for all developers regardless of language or race
- Provide the tools needed to switch between different LLMs for any specific tasks
