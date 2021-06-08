# crypto

Tracking our descent into the rabbit hole

## Installation

Right now getting this set up requires experience with the command line and GitHub. We plan on making it simpler. But for now, if you do not have experience with a CLI and familiarity with Git please find someone who does. Request a half hour of an engineers time to get you set up. We provide the instructions for what they need to do.

When you are ready to learn more about the command line and GitHub check out the following:

- CLI for normies
- Git started

P.S. you probably should read the links above. You need those skills later.

### Instructions

Open the CLI of your choice and...

1. Navigate to the directory where you want to start the project
2. Create the scaffolding for the project website

`npx @docusaurus/init@latest init [name] classic`

Relace `[name]` with what you want to call the project. This will be the parent directory.

Do we need to create a starter template?

What if you already have an existing project?

3. Start the server

- `cd [name]`
- `npm start`

4. View the site in your browser (which better be [Brave](https://brave.com/) 🦁)

- `http://localhost:3000/`

5. Update `docusaurus.config.js`

Replace the following attributes with details specific to your project:

- `title: 'My Site',`
- `tagline: 'Dinosaurs are cool',`
- `url: 'https://your-docusaurus-test-site.com',`
- `organizationName: 'facebook', // Usually your GitHub org/user name.`
- `projectName: 'docusaurus', //`
- `title: 'My Site',`

For the `url` use `http://localhost:3000/` until the site is deployed.

For details on how the site is layed out please check out [Project structure](https://docusaurus.io/docs/installation#project-structure)

#### Later

- `favicon: 'img/favicon.ico',`
- `alt: 'My Site Logo',`
- `src: 'img/logo.svg',`

6. Verify the configuration changes

- `npm start`
- `http://localhost:3000/`

7. Create a repo

- Go to [GitHub](https://github.com/)
- Create an empty new repository named after the project `[name]`
- Copy the location of the repository to your clipboard

8. Add remote URL to your local repo

Return the command line and add the following:

- `git init`
- `git remote add origin your-remote-url`

Replace `your-remote-url` with the location of the repository on your clipboard

9. Push the changes to GitHub

- `git add .`
- `git commit -m "Initial commit"`
- `git push --set-upstream origin master`

7. Show them how to make a change to README

It would be super dope if you could walk them through their first edits.

How does the person who sets the projects up and the person who is just editing look different?

## Making Changes

You need to get to understand a few things:

1. What is a README?
2. How do I write Markdown?

### Steps

1. Clone the repo onto your local machine (should this be Fork instead?)
2. Add Folder to Workspace in VS Code
3. Open the file `README.md`
4. Replace all the content in the file with a heading and short description
5. Save the file
6. Push to GitHub

- `git add .`
- `git commit -m "Replace README"`
- `git push --set-upstream origin master`
- Verify changes on GitHub in your browser
