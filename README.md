# News Website
Deployment Link - https://news-website-58z5.onrender.com/
This is a news website built using React Static, a static site generator for React.

## Installation

1. Clone the repository: `git clone <repository-url>`
2. Change into the project directory: `cd news-website`
3. Install dependencies: `npm install`

## Usage

To start the development server:

npm start



To generate a production-ready build:

npm run build




To deploy the website:

1. Modify the `basepath` in `static.config.js` to match your deployment environment.
2. Generate a production build using `npm run build`.
3. Deploy the contents of the `dist` directory to your chosen hosting provider.

## Configuration

The configuration file `static.config.js` contains various settings for the website:

- `siteRoot`: The root URL of the deployed website.
- `basePath`: The base path of the website, useful for deployments in subdirectories.
- `getRoutes`: Function to define the routes of the website.
- `Document`: Custom component for the HTML document.
- `404`: Custom component for the 404 error page.
- `devServer`: Configuration options for the development server.

Feel free to modify the configuration according to your requirements.

## Folder Structure

The project structure is as follows:

.
├── src
│ ├── components # Reusable React components
│ ├── pages # Individual pages of the website
│ ├── templates # Templates for dynamic pages
│ ├── styles # CSS or SCSS styles
│ └── static # Static files (images, fonts, etc.)
├── static.config.js # Configuration file for React Static
└── package.json

python
Copy code

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push the branch to your fork: `git push origin feature/my-feature`.
5. Create a new pull request and provide a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).
