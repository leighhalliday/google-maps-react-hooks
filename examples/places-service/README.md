# `usePlacesService` Hook Setup Example

This is an example setup to show a **Google Map with places** using the usePlacesService hook with the Google Maps React Hooks library.

## Instructions

To run this project, clone the Google Maps React Hooks repository locally.

Go to the root of the repository and run

```shell
npm install
```

once to install all dependencies.

Then start this example locally with

```shell
npm run start:places-service-example
```

**NOTE**:
To see the examples it is needed to add an `.env` file with a [Google Maps API key](https://developers.google.com/maps/documentation/embed/get-api-key#:~:text=Go%20to%20the%20Google%20Maps%20Platform%20%3E%20Credentials%20page.&text=On%20the%20Credentials%20page%2C%20click,Click%20Close.) in the following format:

```
GOOGLE_MAPS_API_KEY="<YOUR API KEY HERE>"
```

An example can be found in `.env.example`.

**NOTE FOR WINDOWS USERS**:
We are using [cross-env](https://github.com/kentcdodds/cross-env) for environment variables to work on all platforms. There is an issue that `npm` uses `cmd` by default. The workaround is to add `script-shell` to `powershell` in your `.npmrc`. Please follow [this setup](https://github.com/kentcdodds/cross-env/issues/192#issuecomment-513341729) to make it work.

## Output

The project will start at [localhost:1234](http://localhost:1234) and show a Google Map that highlights all nearby Cafes to the central station in Hamburg, and their opening hours. Information is retrieved from Places Service.

![image](https://user-images.githubusercontent.com/39244966/196244324-8d761a8f-25d1-4e87-adb3-9d0d66f97b66.png)
