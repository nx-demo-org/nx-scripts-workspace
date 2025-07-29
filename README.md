# Nx + NPM Scripts Example

This is to show that you can run npm scripts just as if they are Nx targets.

To run the root level scripts, there needs to be a root-level project structure by either defining `project.json` file on the root OR defining `nx` as a prop in the `package.json`.

You can then configure said script as any other Nx target!

To try out: run `npx nx foobar`

Reference docs: https://nx.dev/recipes/running-tasks/root-level-scripts