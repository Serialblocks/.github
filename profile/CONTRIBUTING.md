# 🌟 Contributing

We would ❤️ it if you contributed to the project and helped make Serialblocks even better. We will make sure that contributing to Serialblocks is easy, enjoyable, and educational for anyone and everyone. All contributions are welcome, including features, issues, documentation, guides, and more.

## Found a bug?

If you find a bug in the source code, you can help us by [submitting an issue](https://github.com/serialblocks/serialblocks-app/issues/new?assignees=&labels=bug&title=%F0%9F%90%9B+Bug+Report%3A+) to our GitHub Repository. Even better, you can submit a Pull Request with a fix.

## Missing a feature?

You can request a new feature by submitting a [feature request](https://github.com/serialblocks/serialblocks-app/issues/new?assignees=&labels=feature%20request) to our GitHub Repository.

If you'd like to implement a new feature, it's always good to be in touch with us before you invest time and effort, since not all features can be supported.

- For a Major Feature, first open an issue and outline your proposal. This will let us coordinate efforts, prevent duplication of work, and help you craft the change so that it's successfully integrated into the project.
- Small Features can be crafted and directly [submitted as a Pull Request](URL-TO-BE-ADDED).

## What do you need to know to help?

### If you want to help out with a code contribution, our project uses the following stack:

Client-side (Serialblocks-app)

- [React](https://reactjs.org/docs/getting-started.html)
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction)
- [ShadcnUI](https://ui.shadcn.com/)
- [TailwindCSS](https://tailwindcss.com/)
- [Socket.IO (Client API)](https://socket.io/docs/v4/client-api/)

### Server-side (Serialblocks-local)

- [Node.JS](https://nodejs.org/)
- [Socket.IO (Server API)](https://socket.io/docs/v4/server-api/)
- [Node SerialPort](https://serialport.io/docs/)

### If you want to help out with a starter codes for microcontrollers, you can either:

1) update an existing codebase by refactoring to enhance perf or adding support for more features

2) write an existing codebase for a microcontroller but in it’s native language

3) adding support for more microcontrollers like PIC

# How do I make a code contribution?

## Open to community

You can check all the issues that are open for community contributions. Check [here](URL-TO-BE-ADDED).

## Good first issues

Are you new to open source contribution? Wondering how contributions work in our project? Here's a quick rundown.

Find an issue that you're interested in addressing, or a feature that you'd like to add. You can use [this view](URL-TO-BE-ADDED) which helps new contributors find easy gateways into our project.

## Step 1: Make a fork

Fork the Serialblocks-app or serialblocks-local or microcontrollers-starter repository to your GitHub organization. This means that you'll have a copy of the repository under *your-GitHub-username/repository-name*.

> 
> 

## Step 2: Clone the repository to your local machine

```
git clone -b next https://github.com/{your-GitHub-username}/Serialblocks-app.git
```

## Step 3: Prepare the development environment

Set up and run the development environment on your local machine following the [README](URL-TO-BE-ADDED)

## Step 4: Create a branch

Create a new branch for your changes. In order to keep branch names uniform and easy-to-understand, please use the following conventions for branch naming. Generally speaking, it is a good idea to add a group/type prefix to a branch. Here is a list of good examples:

- for docs change : `docs/{ISSUE_NUMBER}-{CUSTOM_NAME}` for e.g. docs/2233-update-contributing-docs
- for new features : `feat/{ISSUE_NUMBER}-{CUSTOM_NAME}` for e.g. feat/1144-add-plugins
- for bug fixes : `fix/{ISSUE_NUMBER}-{CUSTOM_NAME}` for e.g. fix/9878-fix-invite-wrong-url
- for anything else: `chore/{ISSUE_NUMBER}-{CUSTOM_NAME}` for e.g. chore/111-update-ci-url

```
git checkout -b branch-name-here
```

## Step 5: Make your changes

Update the code with your bug fix or new feature.

## Step 6: Add the changes that are ready to be committed

Stage the changes that are ready to be committed:

```
git add .
```

## Step 7: Commit the changes (Git)

Commit the changes with a short message. (See below for more details on how we structure our commit messages)

```
git commit -m "<type>: <subject>"
```

## Step 8: Push the changes to the remote repository

Push the changes to the remote repository using:

```
git push origin branch-name-here
```

## Step 9: Create Pull Request

In GitHub, do the following to submit a pull request to the upstream repository:

1. Give the pull request a title and a short description of the changes made following the template. Include also the issue or bug number associated with your change. Explain the changes that you made, any issues you think exist with the pull request you made, and any questions you have for the maintainer.⚠️ **Make sure your pull request target the `next` branch.**

> Pull request title should be in the form of <type>(<package>): <subject> as per commit messages. Remember, it's okay if your pull request is not perfect (no pull request ever is). The reviewer will be able to help you fix any problems and improve it!
> 
1. Wait for the pull request to be reviewed by a maintainer.
2. Make changes to the pull request if the reviewing maintainer recommends them.

Celebrate your success after your pull request is merged :-)

## Git Commit Messages

We structure our commit messages like this:

```
<type>: <subject>
```

Example

```
fix: missing entity on init
```

### Types:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Changes to the documentation
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc.)
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**: A code change that improves performance
- **test**: Adding missing or correcting existing tests
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation
