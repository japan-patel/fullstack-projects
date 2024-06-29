# fullstack-projects
## 1) sample-express
- Created a sample-express folder and ran command *npm init* to initialize the project
- Command automatically generates package.json file for the project
- npm install - this command will install dependencies, devDependencies from package.json file and also generate package-lock.json
- npm install *package name* - will install the package that you need for project inside node_module folder and add it to package.json file
- npm install --save-dev *package name* - will install dependencies that are only needed for development and not to run the app. Will add to devdependencies in package.json file
- npm audit - will audit all the dependencies inside package.json file for vulnerability
- npm audit fix --force - will fix vulnerabilities automatically
- npm prune - compares dependencies from package.json file with node_module. If something is not mentioned in package.json file then it will remove them from node_module if exists.
- npm update - will update all packages in node_module or dependencies mentioned in package.json
- npm uinstall *package name* - will uninstall package from project's folder ( package.json as well as node_module)
- npm install - with node only package.json and package-lock.json files are needed in order to recreate project/app somewhere else. Running this command will download everything needed from package.json file
- npx - is used to run script/package that is not needed for development or to run the app/project. It doesn't store files in project folder or node_modules
