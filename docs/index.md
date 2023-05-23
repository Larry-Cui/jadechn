# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

![beauty](assets/beauty.jpg){align=left}

Now, when a new commit is pushed to either the master or main branches, the static site is automatically built and deployed. Push your changes to see the workflow in action.

![small beauty](assets/small.jpg){align=left}

If the GitHub Page doesn't show up after a few minutes, go to the settings of your repository and ensure that the publishing source branch for your GitHub Page is set to gh-pages.

Your documentation should shortly appear at <username>.github.io/<repository>.

with MkDocs¶
If you prefer to deploy your project documentation manually, you can just invoke the following command from the directory containing the mkdocs.yml file:
