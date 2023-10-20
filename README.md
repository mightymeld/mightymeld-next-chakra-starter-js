# Next.js Chakra UI Starter Template

## Getting Started

1. Clone this template using [degit](https://github.com/Rich-Harris/degit), change "mightymeld-next-chakra-project" with your own project name <br />

   ```bash
    npx degit mightymeld/js-mightymeld-next-chakra-starter "mightymeld-next-chakra-project"
   ```
   Or you can click "Use this template" button above.

2. Run `npm install` to install depenendencies.

3. Download a mightymeld.secrets file from the [MightyMeld Portal](https://mightymeld.app/instances) and place it in your project root 

4. Run `npx mightymeld` to launch MightyMeld studio in a browser tab.


## Running the app without MightyMeld

1. Type `npm install` to install dependencies.

2. Run `npm run dev`, the app should then appear in a browser tab on [localhost:3000](localhost:3000)

## Using Another Package Manager

If you would like to use an alternative package manager like yarn or pnpm, make sure to also update the run command in your mightymeld.json file


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
