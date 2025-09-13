# Particle Attractors

A simple port to Sveltekit from the three.js example [Compute Attractor Particles](https://threejs.org/examples/?q=tsl#webgpu_tsl_compute_attractors_particles).

## Demo
Demonstration is [here](https://particle-attractors.vercel.app)

## Creating the project

```sh
# create a new project in the current directory
npx sv create particle-attractors

# inputs
# basic sveltekit - yes
# typescript - yes
# eslint and prettier - yes
# use pnpm - yes

# go to directory
cd particle-attractors

# install three.js
pnpm i three

# install types
pnpm i @types/three
```
Copied the code to main page: /src/routes/+page.svelte 

Added event handlers to show/hide transform controls as I think it is cleaner.

## Building, gitting

Once I was happy with the results:

```sh
pnpm build

git init

git add .

git commit -m "Initial commit"

gh repo create --source=. --public --push particle-attractor

```

## Deploy

Login to vercel.com and create a new project from the github repository.

(github and vercel were previously linked).
