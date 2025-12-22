# Research Highlights

This repository serves the website [mannlabs.github.io/research-highlights](https://mannlabs.github.io/research-highlights), a website that summarizes the main innovations of the MannLabs at the MPI Munich and the Centre for Protein Research Copenhagen. 

## Users

Please visit [mannlabs.github.io/research-highlights](https://mannlabs.github.io/research-highlights)


## Contributors 

### Local development 

1. [Install hugo](https://gohugo.io/installation/), the engine that builds the website

2. Clone the repository 

```bash 
git clone https://github.com/MannLabs/research-highlights.git
```

3. Make edits to the content (see [Development Workflow](#development-workflow))

3. Test it locally. 

```shell
# -D: Autoupdate the site after changes
hugo server -D 
```

#### Development Workflow

- **Content**: Edit Markdown files in the `content/` directory
- **Configuration**: Modify `hugo.toml` for site-wide settings
- **Layouts**: Custom layouts are in `layouts/` directory. Specifically, you can generate templates for specific structures (e.g. the Package/Contributor Cards and grids in `/layouts/shortcodes` with templated HTML+CSS)
- **Static files**: Images and other assets go in `static/` directory

#### Theme Configuration

Key configuration options in `hugo.toml`:

- **Site metadata**: Title, description, author
- **Navigation menu**: Top-level menu items
- **PaperMod parameters**: Theme-specific settings
- **Social links**: GitHub, Twitter, etc.


### Deployment

### GitHub Pages (Automatic)

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch using GitHub Actions.

### Manual Deployment

To build the site manually:

```bash
hugo --minify
```

The generated site will be in the `public/` directory.



### Contribution guidelines 

We will only consider contributions of current and former MannLabs members. Please use clear, concise, and non-violent language when contributing content. 

To contribute content

1. Please open a Pull Request. The code should follow [Hugo best practices](https://gohugo.io/getting-started/) and the website should build locally. 
2. Explain the rational of the changes made
3. Add appropriate tags to news posts


## License 
[CC-BY-SA (Attribution-ShareAlike 4.0 International)](LICENSE)

## Acknowledgments

- [Hugo](https://gohugo.io/) - Static site generator
- [PaperMod](https://github.com/adityatelange/hugo-PaperMod) - Hugo theme
- [GitHub Pages](https://pages.github.com/) - Hosting platform
- All contributors who help improve the site

--
**Built with ❤️ by the MannLabs community**
