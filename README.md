# Nova Explorer

Nova Explorer would be a utility application that helps users better organize their files.

- The tag can have any value like a name, date, etc.
- They can be associated with one or more files.
- Similarly a file can also have one or more tags.
- A user should be able to locate all their files by using tags.

## Technology Stack

- TypeScript
- Tauri (Rust + Vite + ReactJS + CSS)

## How to run

- Clone the repository
- Run `yarn` to install dependencies
- Run `yarn tauri dev` to start the tauri application
- Run `yarn build` to build the application
- Run `yarn tauri preview` to preview the build

## How to contribute

First Fork and Clone the repository. Then follow the steps below:

Start working on a new feature:

```bash
git checkout master
git pull origin master
git checkout -b feature-branch
[...work on the feature...]
git add --all
git commit -m 'My super-duper feature'
git push -u origin feature-branch
```

After Testing and validating. If more changes are required:

```bash
git checkout feature-branch
git pull origin master
[...add more commits]
git push
```

Once everything is validated:

```bash
git checkout master
git pull origin master
git merge feature-branch
git push origin master
```
