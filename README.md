React Jira Integration

## Parcel Development Server
Parcel has a development server built in, which will automatically rebuild your app as you make changes. 
To start it, run the parcel CLI pointing to your entry file: `yarn parcel src/index.html`
Open http://localhost:1234/ in your browser.

Or use package.json scripts to start the Parcel development server
    "start": "parcel",
    "build": "parcel build"

## Tailwind CSS
https://tailwindui.com/components
Run CLI tool to scn template files for classes and build CSS: `npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch`
