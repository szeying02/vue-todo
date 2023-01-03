# Todo List App 

A todo list app built with the Vue framework. 

## Features

1. Add a task.
2. Delete a task.
3. Check / Complete a task. 
4. Toggle to view all tasks / hide completed tasks. 

## Screenshots

![Vue-Todo](/screenshots/demo.png)?raw=true)

## Getting Started

1. [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) and [Clone](https://docs.github.com/en/get-started/quickstart/fork-a-repo#cloning-your-forked-repository) your forked repo.
2. Open terminal and navigate to the directory contatining the cloned project. 
3. To install dependencies, run:

```bash
npm install
```

4. For development, run:
```bash
npm run dev
```

5. For production, run:
```bash
npm run build
```

## Navigating the Code
```
.
├── node_modules
├── public
├── screenshots
├── src
├── .gitignore
├── README.md
├── index.html
├── package-lock.json
├── package.json
└── vite.config.js
```

### Notable files
- `assets` contains base css files.
- `App.vue` contains the basic html & javascript for the app. 
- `TodoList.vue` contains the bulk of the todo list functionalities.
