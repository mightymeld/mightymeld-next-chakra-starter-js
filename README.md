# Next.js Chakra UI Starter Template


## Getting Started

1. Clone this template using [degit](https://github.com/Rich-Harris/degit), change "mightymeld-next-chakra-project" with your own project name <br />

   ```bash
    npx degit mightymeld/js-mightymeld-next-chakra-starter "mightymeld-next-chakra-project"
   ```

2. Install all dependencies <br />

   Recommended using yarn

   ```bash
    cd mightymeld-next-chakra-project

    yarn
   ```

   or using npm

   ```bash
    cd mightymeld-next-chakra-project

    npm install
   ```

3. Copy `.env.template` to `.env` and add your MightyMeld instance ID. If you don’t have an instance ID, [sign up for MightyMeld](https://www.mightymeld.com) or join the waitlist and you will receive one.

4. Launch the app using:

   ```bash
    npx mightymeld
   ``` 

5. Once the app has loaded, visit [studio.mightymeld.app](https://studio.mightymeld.app/) to begin editing your app.

6. For customizing options please see [Features](#features) section.

7. Or you can click "Use this template" button above.


### Running the app without MightyMeld

1. Run the following command to start the app:

```bash
    yarn dev
   ``` 
   The app should appear in a browser tab at localhost:3000.

## Features

There is some pre-installed packages in this template:

- [next-seo](https://github.com/garmeeh/next-seo)
- [nprogress](https://github.com/rstacruz/nprogress)
- [react-icons](https://github.com/react-icons/react-icons)

Some features in this template:

1. Custom breakpoints & font <br />
   You can edit breakpoints & font in `styles/theme.js`. <br />
   Import your preferred font in `pages/_document.js` to apply [automatic webfont optimization](https://nextjs.org/blog/next-10-2#automatic-webfont-optimization).
2. Global style <br/>
   You can edit global style in `styles/styles.js`.
3. Page transition <br />
   If you want to custom the page transition go to `pages/_app.js` in `MotionBox` component.
4. Next SEO config file <br />
   You can custom `meta`, favicon, open graph, etc. in `next-seo.config.js`.
5. You also can customize nprogress in `styles/css/nprogress.css`.
6. Using absolute path based on `jsconfig.json` file.

## Documentation

For more guides, please read:

- [Next.js Documentation](https://nextjs.org/docs)
- [Chakra UI Documentation](https://chakra-ui.com/)
- [Mightymeld Documentation](https://www.mightymeld.com/)

## License

This project is under [MIT License](LICENSE)

## Credits

Created by [Hendra Agil](https://github.com/hendraaagil)

