# Add Features with Forms to a Vue.js Reading List Application

This repo contains the code for the Pluralsight Project "Add Features with Forms to a Vue.js Reading List Application"

This Project was created with Vue 2.5.

## Installation Instructions and Verifying Local Environment

### Installation

Run the following command from root folder of the forked project to install all dependencies.

```
npm install
or
docker build -f Dockerfile.future -t test .
```

### Verify Setup

In order to verify that everything is setup correctly, run the following command that should show you the failing tests.

```
npm run test
or
docker run -it --rm test npm run test
```

This is good! We'll be fixing these tests once we jump into the build step. Every time you want to check your work locally you can type that command and it will report the status of every task in the project.  In addition, each module has tests that can be run scoped to just the tasks in that module.  See the instructions at the top of each list of tasks for more information.

### Previewing Your Work

In order to see your changes in a browser, you can type this to start the application.

```
npm run dev
docker run -it --rm -p 8080:8080 -e HOST=0.0.0.0 test npm run dev
```

Then, when you visit http://localhost:8080 in a browser you should see the App.vue component's HTML and CSS rendered on the page.
