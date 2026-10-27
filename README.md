# portfolio
# Personal Portfolio Website

A responsive personal portfolio website showcasing my background, technical skills, and projects, with interactive project search, light/dark mode, and an API-powered AI chatbot.

> **Academic Project:** Internal Assessment — Personal Portfolio Website with API-Based Chatbot Integration

## Live Demo

- **Portfolio:** [Add your deployed Vercel URL](https://your-vercel-url.vercel.app)
- **GitHub Repository:** [Add your repository URL](https://github.com/your-username/your-repository)

> Replace the example links above with your real URLs before publishing.

## Overview

This portfolio is designed to present my learning journey and development work in one place. Visitors can learn about me, explore my technical skills, search and filter projects, open project repositories or live demos, and ask the integrated chatbot questions about the information published on the site.

The website was developed from the portfolio starter created in class and personalized for this assessment.

## Features

- **Home:** Introduction and quick navigation to key sections.
- **About Me:** Personal introduction and educational background.
- **Skills:** Technical skills and tools relevant to my learning journey.
- **Projects:** Individual project cards with descriptions, technologies, repository links, and live demos where available.
- **Project Search and Filter:** Find projects by name or technology, such as Python, Quiz, or Book.
- **Light/Dark Mode:** Switch between themes for a more comfortable viewing experience.
- **AI Chatbot:** Ask questions about my profile, skills, and projects.
- **Responsive Layout:** Designed to work on desktop and mobile screens.
- **Contact Information:** Links or details for getting in touch.
- **Error Handling:** The chatbot displays a useful message if an API request fails.

## Projects Showcased

The portfolio includes the following five project entries required for the assessment. Update each entry to match the actual files and links in your repositories.

| Project | Description | Technologies |
|---|---|---|
| Python Programs Collection | A collection of Python programs, including factorial, Fibonacci, and structure-to-dictionary conversion, with an updated README. | Python, Git, GitHub |
| Messy Python Code Improvement | A Python script improved with AI-assisted review, with changes evaluated and understood. | Python, Cursor AI |
| Bug Fixing Using Cursor AI | An incorrect or buggy program examined and corrected with Cursor AI. | Relevant language, Cursor AI |
| Interactive Quiz Application | A quiz application developed as part of the coursework. | Technologies used in the actual project |
| Book Reading List Application | A reading-list application developed in class, with a README that includes its deployed link. | Technologies used in the actual project |

For every project card, include a brief summary, the actual technology stack, a working GitHub repository link, and a live application link when one exists.

## Technology Stack

List only the technologies actually used in your implementation.

- **Frontend:** HTML, CSS, JavaScript
- **Development Environment:** Cursor AI
- **Version Control and Hosting:** Git, GitHub
- **Deployment:** Vercel
- **Chatbot:** The API provider and model configured in the project

## AI Chatbot

The chatbot allows visitors to ask questions about information available in the portfolio, such as:

- Who are you?
- What are your technical skills?
- Which projects have you completed?
- What does the Python Programs Collection contain?
- What was corrected in the bug-fixing project?
- How does the reading-list application work?
- Where can I find your GitHub repositories?

### API and Security

- The chatbot should answer using accurate portfolio and project information.
- It should display a helpful message if the API request fails.
- **Never commit API keys or other secrets to client-side JavaScript or a public GitHub repository.**
- If the API requires a secret key, route requests through a secure server-side function (for example, a Vercel Function) and store the key in Vercel Environment Variables.
- Configure required environment variables in the deployment settings and redeploy after changing them.
- Do not claim the chatbot is working until it has been tested on the live deployment.

## Run Locally

These steps assume the project is a static HTML, CSS, and JavaScript website. Adapt them if your repository uses a framework or build tool.

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Enter the project directory:

   ```bash
   cd your-repository
   ```

3. Open the folder in Cursor or your preferred code editor.

4. Run the website using a local development server, such as the Live Server extension, or follow the instructions for your project's framework.

5. Open the local URL shown by the development server in your browser.

### Environment Variables

If the chatbot uses a server-side API route, create a local `.env.local` file using the variable names expected by your code. Add real secret values locally, and ensure `.env.local` is listed in `.gitignore`.

Do not put secret API keys in HTML, public JavaScript, README examples, screenshots, or Git commits.

## Deployment on Vercel

1. Push the completed project to GitHub.
2. Sign in to Vercel and import the correct GitHub repository.
3. Confirm the framework preset, build command, and output directory match the project.
4. Add any required environment variables in the Vercel project settings.
5. Deploy the project.
6. Open the deployed URL and verify the portfolio and chatbot.
7. Add the final public URL to this README and to the relevant project card.

## Testing Checklist

- [ ] Personal details and educational information are accurate.
- [ ] No template names, sample details, or unused placeholders remain.
- [ ] All five required project entries are present.
- [ ] Project search returns relevant results for names and technologies.
- [ ] Project filtering works as intended.
- [ ] Light/dark mode works and remains usable across sections.
- [ ] Navigation, GitHub links, and live demo links work.
- [ ] Layout is usable on desktop and mobile.
- [ ] Chatbot answers questions using accurate portfolio information.
- [ ] Chatbot shows a helpful error message if the API request fails.
- [ ] No API secrets are exposed in client-side code or GitHub.
- [ ] The deployed Vercel website loads publicly and has been tested.

## Repository Structure

The exact structure depends on your implementation. A simple static website may look like this:

```text
portfolio/
├── index.html
├── style.css
├── script.js
├── assets/
│   └── images/
├── README.md
└── .gitignore
```

If your project uses a server-side chatbot endpoint, include its actual directory and files in this structure. Do not document files that do not exist in your repository.

## Learning Outcomes

Through this project, I practiced:

- Personalizing and improving a website's visual design.
- Organizing project information into reusable, readable sections.
- Implementing search, filtering, and theme switching.
- Using Git and GitHub to maintain and publish source code.
- Deploying a website using Vercel.
- Integrating an API-powered chatbot and handling request errors.
- Testing navigation, responsiveness, and functionality before deployment.

## Author

**[Your Full Name]**

- **Course / Department:** [Your course or department]
- **GitHub:** [Your GitHub profile URL]
- **Portfolio:** [Your deployed portfolio URL]
- **Contact:** [Your preferred public contact method]

---

*Built as an individual academic assessment. Project descriptions, technologies, links, and implementation details should reflect the actual submitted code.*
