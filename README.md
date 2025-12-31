# XAuth Ecosystem Documentation

This repository stores all the Markdown articles for the official [XAuth Ecosystem website's wiki](https://xauth.fyennyi.pp.ua/wiki).

## How It Works

The main website fetches the `_wiki_structure.json` file to build the sidebar navigation. When a user clicks a link, the website fetches the corresponding Markdown file from the `articles/` directory in this repository and renders it dynamically.

This approach allows the documentation to be updated independently of the main website's deployment cycle. Changes pushed to the `main` branch of this repository will be reflected on the live site, though a delay of up to 5 minutes may occur due to CDN caching.

## Contributing

To contribute to the documentation, please follow these steps:

1. Fork this repository
2. Create a new branch (`git checkout -b docs/your-new-article`)
3. Create a new `.md` file inside the `articles/` directory
4. Add a reference to your new article in the `_wiki_structure.json` file
5. Commit and push your changes
6. Open a Pull Request

Your contributions are greatly appreciated!

## License

The content of this documentation is licensed under the CC0 1.0 Universal. See the [LICENSE](LICENSE) file for details.
