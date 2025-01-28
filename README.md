# Lily Pair Website

[![netlify][netlify-shield]][netlify-url]
[![Contributors][contributors-shield]][contributors-url]
[![Discord-Server][discord-shield]][discord-url]


[<img width="1440" alt="Lily Pair Webpage" src="https://github.com/user-attachments/assets/d78c74f6-aedf-43e4-8d3f-b66c8320d4a8">](https://lilypairscheduler.netlify.app)

> [!TIP]
> Click the image to [launch the webpage](https://lilypairscheduler.netlify.app)

<br />
<br />

<!-- shortcuts -->

## Table of Contents
- [ About The Project](#about-the-project)
  - [ Key Features](#key-features)
  - [ Built with](#built-with)
- [ Courses and Tools](#courses-and-tools)
- [ Access our Figma Design](#access-our-figma-design)
- [ How to Contribute](#how-to-contribute)
  - [ Coding Conventions](#conventions)
  - [ Instructions](#instructions)

<br>

## About The Project
Lily pair is a tool to help students find mentors and vice versa. The webpage can launch on any device with internet.


### Key Features
- Displays a collections of mentors and mentees
- Enables user to sort from Eon English's database
- Provides a user-friendly interface to make navigation simple and easy

<br />

### Built With
- ![Static Badge](https://img.shields.io/badge/JavaScript-%23212329?style=for-the-badge&logo=JavaScript)
- ![Static Badge](https://img.shields.io/badge/HTML-%23212329?style=for-the-badge&logo=html5)
- ![Static Badge](https://img.shields.io/badge/HTML-%23212329?style=for-the-badge&logo=css3)
- ![Static Badge](https://img.shields.io/badge/Netlify-%23212329?style=for-the-badge&logo=netlify)
- ![Static Badge](https://img.shields.io/badge/App_script-%23212329?style=for-the-badge&logo=Google)

<br>

## Courses and Tools
Currently, this project uses primarily HTML, CSS, and JavaScript. Therefore, we recommend building foundational knowledge, so feel free to use the courses/materials below

- [Codeacademy's JavaScript Course](https://www.codecademy.com/learn/introduction-to-javascript)

- [Visual Studio Code (Editor)](https://code.visualstudio.com)
  - [Prettier Plug-in (formatter)](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [Live server plug-in](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  - [Preview plug-in](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)

<br>

## Access our Figma Design
You will have permission to view the document. If you would like to make direct changes, contact a team manager for `write` permissions.
- [Figma Design](https://www.figma.com/design/jc9JasAyCoFxGAc6VCNzYE/Lily-Pair-Scheduler?t=NGcFxoLzWNmXSJ6W-1)

<br>

## How to Contribute
Contributions are what make this community such an amazing place to learn, inspire, and create! Therefore, any contributions you make are **greatly appreciated**!

<br />

### Conventions
This project uses common practices to keep the code clean and readable for the entire team. We recommend following to keep the codebase consistent

#### JavaScript
Uses functional programming; written with explicit function declarations for simplicity and readability
```js
async function initialize() {
    submitBtnListener();
    showLoadingCards();
    // other props...
}
```

#### CSS/HTML
Written using BEM naming convention (i.e., block, elements, and modifiers) for readability
```html
<input
  type="submit"
  value="Send"
  class="btn btn--primary"
/>
```
```css
.btn {
  overflow: hidden;
  text-overflow: ellipsis;
  /* other styles... */
}
.btn--primary {
  color: var(--color-white);
  font-weight: 600;
  background: var(--color-blue-normal);
  /* other styles... */
}
```

<br />

## Instructions 

### 1. Set Up Your Environment
Feel free to use the following as guides:
- [Visual Code Studio & Plugins](https://www.youtube.com/watch?v=GCCUwvlbDQ8)

- [How to launch the website](https://www.youtube.com/watch?v=9zteNOpoi-k)

<br />

### 2. Fork or Create a Branch
- Begin by forking the repository or creating a branch from the [GitHub Repo](https://github.com/EonEnglish/Lily-Pair-Scheduler).  

<br />

### 3. Pick a Task
- Visit the **[Planning Tab](https://github.com/orgs/EonEnglish/projects/9/views/1)** on GitHub.  
- Assign a task to yourself or [create one](https://github.com/EonEnglish/Lily-Pair-Website/issues/new?template=Blank+issue) and assign it to yourself.  
- Once assigned, start working on your task.

<br />

### 4. Submit a Pull Request
- Once your task is completed, commit and push your changes to your branch.
- Go to the repository and create a Pull Request (PR) with a detailed description of the changes.
- Mention the issue or task you were working on (if applicable). Wait for the code review.
- If changes are requested, make the updates and push them to the same branch.
- Once approved, your PR will be merged into the main branch.
 
<br />

### 5. Team Meetings
- We hold team meetings **biweekly on Sundays**.  
- The meeting link can be found on [Discord](https://discord.gg/CAzC5bMqzg).  

<br />

Feel free to reach out on [Discord](https://discord.gg/CAzC5bMqzg) if you have any questions or need guidance. Happy contributing!

<!-- Links -->
[contributors-shield]: https://img.shields.io/github/contributors/EonEnglish/Lily-Pair-Website?style=for-the-badge&logo=github&logoColor=white&labelColor=black&color=6e5494&label=contributors
[contributors-url]: https://github.com/EonEnglish/Lily-Pair-Website/graphs/contributors
[discord-shield]: https://img.shields.io/badge/Discord-Join-5865f4?style=for-the-badge&logo=Discord&logoColor=white&labelColor=black
[discord-url]: https://discord.gg/CAzC5bMqzg
[netlify-shield]: https://img.shields.io/badge/Netlify-Website-5ac4b7?style=for-the-badge&logo=netlify&logoColor=white&labelColor=black
[netlify-url]: https://lilypairscheduler.netlify.app
