# discarbon-main-website

The website can be accessed under `https://www.discarbon.earth/`. This directly reflects the main branch. This is in development so expect things to change and break.

## How to develop

`npm i` to install all components

Should install tailwind CSS and Daisy UI for the UI components.

Open a console and start the tailwind css watcher which compiles the css automatically depending on the used components:

`npx tailwindcss -i ./css/input.css -o ./css/output.css --watch`

Run site for local development with HTTPS via [https-localhost](https://github.com/daquinoaldo/https-localhost):
```sh
npm i -g --only=prod https-localhost
sudo serve .
```