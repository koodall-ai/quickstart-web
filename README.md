# Koodall AR Toolkits SDK Web demo app
[![](https://www.koodall.ai/media/images/logo/logo-color.svg)](https://www.koodall.ai/)


## Requirements

- A valid [Koodall client token](#obtaining-koodall-client-token)
- [Node.js](https://nodejs.org/en/) installed on your machine
- A browser that supports [WebGL 2.0](https://caniuse.com/#feat=webgl2)

### How to Get the Koodall SDK Web AR

This demo uses the CDN version of the [@koodall/webar](https://www.npmjs.com/package/@banuba/webar) package.  
For production usage, install the npm package directly.  
Check the [Integration tutorials](https://docs.banuba.com/face-ar-sdk-v1/web/web_tutorials_integrations) for other ways to integrate [@koodall/webar](https://www.npmjs.com/package/@banuba/webar).

### How to Obtain a Koodall Client Token

To activate the SDK, a valid client token is required.  
- Request a **trial token** by contacting our team at [sales@koodall.ai](mailto:sales@koodall.ai).
- For production tokens, connect with our sales team.

## Setting Up the Environment and Running Locally

1. Clone the repository to your local machine:

2. Add your Koodall client token to `KoodallClientToken.js`:

    ```js
    window.KOODALL_CLIENT_TOKEN = "YOUR_CLIENT_TOKEN_HERE";
    ```

3. Start a local server from the project folder:

    ```sh
    npx live-server
    ```

4. Open the demo in your browser at [localhost:8080](http://localhost:8080).

## Adding a New Effect to the Demo

1. Place your `.zip` effect files in the `import/` folder.

2. Update the `./import/effectsList.js` file to include your effect names:

    ```js
    export const importedEffectsList = ["effect_1.zip", "effect_2.zip"];
    ```
