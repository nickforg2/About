# About
[![Angular GitHub CI/CD](https://github.com/nickforg2/About/actions/workflows/cd.yaml/badge.svg)](https://github.com/nickforg2/About/actions/workflows/cd.yaml)

Website available at [https://nickforg2.github.io/About/](https://nickforg2.github.io/About/)


## Development
n
### Running application
- Pull down repo to your machine.
- Ensure you have npm (v18.14.0) and the angular cli installed
- After pulling down the application, run `npm install` to locally download all node_modules
- Run application with `ng serve` or `npm run start`. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Developing Application

- Make sure you are working in a branch other than `main`
- Scaffold things with `ng generate component|directive|pipe|service|class|guard|interface|enum|module <NAME>`

### Pushing changes

- Ensure the following have no issues
   - `npm run start` is working, and everythin functions as expected
   - Ensure that `npm run lint` passes
   - Ensure that `npm run test:ci` passes
   - Ensure that `npm run e2e:ci` passes
- Push development branch
- Go through PR process in GitHub
