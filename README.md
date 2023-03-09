# symfony-6-project

## Setting up the environment

Before contributing to this project, you will need to set up your environment. This involves creating a .env file and adding the required environment variables.

## Creating the .env file

Create a new file called .env in the root directory of the project.

## Populating the .env file

Add the following environment variables to the .env file with their corresponding values:

```
APP_ENV=
APP_SECRET=
DATABASE_URL=
MESSENGER_TRANSPORT_DSN=
```

## Updating the environment

If you make changes to the .env file, you will need to restart your web server for the changes to take effect. You can do this by stopping and starting your web server, or by running the following command:

```
symfony server:stop
symfony server:start
```

This will stop and start your Symfony web server with the updated environment variables.

That's it! You should now be able to run the project with your new environment variables.
