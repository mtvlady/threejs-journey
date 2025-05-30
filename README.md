# threejs-journey

This repository contains the exercises completed by me as part of the [Three.js Journey](https://threejs-journey.com) course by [Bruno Simon](https://bruno-simon.com).


## Setup

Each lesson is developed in a separate branch.
1. Create a new branch using the kebab-case format, for example `01-first-lesson`.
2. Checkout to the new branch
3. Unzip the starter provided in the course lesson
4. Run the following command:
```
npm i && npm i prettier --save-dev && npm pkg set scripts.format="prettier --write ." && npm run format
```
- `Installs` all the lesson dependencies\
- Adds `prettier` as a development dependency\
- Adds a `format` script to the package.json file\
- Runs the `format` script to automatically format the project files with `prettier`\

## Deploy

Each push to a branch initiates a deployment to a separate Vercel project for every lesson.

Each lesson will be available live at `mtvlady.<branch-name>.vercel.app`.

[Go to the Vercel Dashboard](https://vercel.com/login?next=%2Fdammafras-projects)
