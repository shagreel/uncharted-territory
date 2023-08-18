```sh
$ npm create cloudflare@latest
Need to install the following packages:
create-cloudflare@2.1.1
Ok to proceed? (y) y

using create-cloudflare version 2.1.1

╭ Create an application with Cloudflare Step 1 of 3
│
├ In which directory do you want to create your application?
│ dir ./uncharted-territory
│
├ What type of application do you want to create?
│ type Website or web app
│
├ Which development framework do you want to use?
│ framework Vue
│
╰ Continue with Vue via `npx create-vue@3.6.4 uncharted-territory`

Need to install the following packages:
create-vue@3.6.4
Ok to proceed? (y) y

Vue.js - The Progressive JavaScript Framework

✔ Add TypeScript? … No / Yes
✔ Add JSX Support? … No / Yes
✔ Add Vue Router for Single Page Application development? … No / Yes
✔ Add Pinia for state management? … No / Yes
✔ Add Vitest for Unit Testing? … No / Yes
✔ Add an End-to-End Testing Solution? › No
✔ Add ESLint for code quality? … No / Yes
✔ Add Prettier for code formatting? … No / Yes

Scaffolding project in /Users/pajones/projects/uncharted-territory/uncharted-territory...

Done. Now run:

cd uncharted-territory
npm install
npm run format
npm run dev

╭ Configuring your application for Cloudflare Step 2 of 3
│
├ Installing wrangler A command line tool for building Cloudflare Workers
│ installed via `npm install wrangler --save-dev`
│
├ Adding command scripts for development and deployment
│ added commands to `package.json`
│
╰ Application configured

╭ Deploy with Cloudflare Step 3 of 3
│
├ Do you want to deploy your application?
│ yes deploy via `npm run pages:deploy`
│
├ Logging into Cloudflare checking authentication status
│ logged in
│
├ Selecting Cloudflare account retrieving accounts
│ account Shagreel@gmail.com's Account
│
├ Creating Pages project
│ created via `npx wrangler pages project create uncharted-territory --production-branch main`
│
├ Deploying your application
│ deployed via `npm run pages:deploy`
│
├  SUCCESS  View your deployed application at https://uncharted-territory.pages.dev
│
│ Navigate to the new directory cd uncharted-territory
│ Run the development server npm run pages:dev
│ Deploy your application npm run pages:deploy
│ Read the documentation https://developers.cloudflare.com/pages
│ Stuck? Join us at https://discord.gg/cloudflaredev
│
├ Waiting for DNS to propagate
│ DNS propagation complete.
│
├ Waiting for deployment to become available
│ deployment is ready at: https://uncharted-territory.pages.dev
│
├ Opening browser
│
╰ See you again soon!
```