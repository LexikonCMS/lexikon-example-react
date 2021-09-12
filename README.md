# lexikon-example-react

This is an example of using Lexikon to localize a React App with the [i18next](https://react.i18next.com/) package.

## Getting started
This example uses a single key named `hello` and detects the browser language. [Create a new project](https://studio.lexikon.dev/projects/new) in Lexikon and add translations for the `hello` key.

### Create a release
After adding translations, go to the releases page and create a new release.

### Authentication
To access your project, create a new API key and replace the placeholder in the `package.json` file.

**Note:** In an production environment, you should not put your key into the package.json file as it will be committed. Use environment variables.

### Pull translations
To download the latest translation release run the following command:
> npm run lexikon:pull

### Run app
> npm run dev

## Adding new keys
If you add keys, you can use the following command. The Lexikon CLI will extract new keys and add them to the project, so your translators can gat to work:
> npm run lexikon:push