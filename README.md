# Presentation Library

[Use this template!](https://github.com/codebytes/marp-slides-template/generate)

Create multiple Marp presentation sites that can be built and published on [GitHub Pages] using this template. The site features:

- Multiple Marp presentations in one repository
- A centralized index page for navigation between presentations
- GitHub Pages / Actions workflow for build and publish ([See a preview](http://chris-ayers.com/marp-slides-template/))
- A DevContainer/CodeSpace configuration with Marp and Markdown preview extensions
- Chrome installation for PDF and PowerPoint slide creation on Linux

## Project Structure

```
slides/
├── index.html              # Main landing page with links to all presentations
├── Slides.md              # Sample presentation (original)
├── soradirector.md        # Sora Director presentation
├── img/                   # Shared images folder
└── themes/                # Custom themes folder
    ├── custom-default.css
    ├── custom-gaia.css
    ├── custom-uncover.css
    └── custom.css
```

## Available Presentations

- **Sample Presentation** (`Slides.md`) - A comprehensive sample showcasing various Marp features
- **Sora Director** (`soradirector.md`) - AI-powered video generation platform presentation

## Adding New Presentations

1. Create a new `.md` file in the `slides/` folder
2. Include the required frontmatter:
   ```yaml
   ---
   marp: true
   theme: custom-default
   ---
   ```
3. Update the GitHub Actions workflow in `.github/workflows/marp-pages.yml` to build the new presentation
4. Add a link to the new presentation in `slides/index.html`

## Customization

Feel free to customize the sites created with this template as you like!

## Getting Started

1. Click "[use this template]" to create a new site.
2. Update the content of existing presentations or create new ones in the `slides/` folder.
3. Modify `slides/index.html` to reflect your presentation collection.

## Custom Themes

This template includes four custom themes in the `slides/themes` folder:

- custom
- custom-default (based on the built-in default theme)
- custom-gaia (based on the built-in gaia theme)
- custom-uncover (based on the built-in uncover theme)

To use a custom theme, edit the relevant css file and add its reference in the front matter of `Slides.md`. For example, to use `custom-default` add the following to the `Slides.md` front matter:

```markdown
---
marp: true
theme: custom-default
---
```

For additional themes, add them to the devcontainer and follow the [Marp custom theme documentation](https://marpit.marp.app/theme-css).

## Publishing on GitHub Pages

1. In your GitHub repo, navigate to `Settings` > `Pages` > `Build and deployment`.
2. Select `Source`: `GitHub Actions`.
3. If any Actions failed, go to the `Actions` tab and click on `Re-run jobs`.

## Local Build and Preview

1. Install [Visual Studio Code](https://code.visualstudio.com/).
2. Install the [Marp for VS Code extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).
3. Open any `.md` file in the `slides/` folder in VS Code.
4. Use the Marp extension to preview your presentations.

## Licensing and Attribution

This repository is licensed under the [MIT License]. Reuse or extend the code as you wish, but include the original license. The deployment GitHub Actions workflow is based on GitHub's starter workflows.

## Resources

- [Use this template](https://github.com/codebytes/marp-slides-template/generate)

- GitHub Pages: [https://docs.github.com/en/pages](https://docs.github.com/en/pages)

- CommonMark markdown syntax: [https://commonmark.org/help/](https://commonmark.org/help/)

- Marp Official Repository: [https://github.com/marp-team/marp](https://github.com/marp-team/marp)
- Marp Official Documentation: [https://marpit.marp.app/markdown](https://marpit.marp.app/markdown)
- Marp for VS Code Documentation: [https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)