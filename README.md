# Ceres Colors for Mac

A handy little Mac app that gives you quick access to the Ceres design color palette.

<img src="https://cdn.dribbble.com/users/6295/screenshots/2594885/colors_2x.png" width="320" alt="Screenshot">

**[Download the app](https://github.com/romannurik/MaterialColorsApp/releases/latest)**

## Build instructions

If you want to customize the app for your own needs, you can do a custom build.

1. First install [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).
2. Clone the repository and in the root directory, run:

   ```shell
   npm install
   ```

3. To run the app:

   ```shell
   npm start
   ```

Note that you'll probably want to disable the auto-updating mechanism by emptying out the `checkForUpdates` method in
[main.js](https://github.com/romannurik/MaterialColorsApp/blob/master/app/main.js).
