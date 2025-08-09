# Cursor Rules Collection

This repository contains a collection of cursor rules for different projects. Each branch contains specific rules tailored for different types of projects and development environments.

## How to Use

### Step 1: Clone the Repository

First, clone this repository to your project's `.cursor/rules` directory:

```bash
git clone git@github.com:Chrissi1601/cursor-rules.git .cursor/rules
```

### Step 2: Navigate to the Rules Directory

```bash
cd .cursor/rules
```

### Step 3: Switch to Your Project Branch

**Important:** This repository uses branches to organize different sets of cursor rules. You need to switch to the correct branch that matches your project type.

```bash
git checkout <branch-name>
```

### Available Branches

Each branch contains cursor rules optimized for specific project types:

- `main` - General purpose rules (you are here)
- `vue-typescript` - Vue.js projects with TypeScript
- `react-typescript` - React projects with TypeScript  
- `python-fastapi` - Python FastAPI projects
- `nodejs-express` - Node.js Express projects
- `laravel` - Laravel PHP projects

## Contributing

To add rules for a new project type:

1. Create a new branch: `git checkout -b <project-type>`
2. Add your cursor rules
3. Update this README with the new branch information
4. Submit a pull request
