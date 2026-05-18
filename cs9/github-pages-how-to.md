# How to Host a Website on GitHub Pages

GitHub Pages lets you publish a static website for free from a GitHub repository. It is a good option for portfolios, class projects, demos, and simple HTML/CSS sites.

Adapted from [GeeksforGeeks: Host a Website on GitHub For Free](https://www.geeksforgeeks.org/git/how-to-host-a-website-on-github-for-free/).

## Step 1 - Create a GitHub Account

Create a free account at [github.com](https://github.com/) if you do not already have one. If you already have an account, sign in.

## Step 2 - Create a New Repository

Create a new repository for your website. The repository can have any name, so choose a name that matches your project.

For example:

```text
my-portfolio
```

or:

```text
kitty-litter-cake-recipe
```

GitHub only requires the special `your-username.github.io` repository name if you are creating your main GitHub profile website. For most projects, use a project name instead.

## Step 3 - Add Your Website Files

Create an `index.html` file in the repository. This is the main page GitHub Pages will load first, so the file must be named exactly `index.html`.

You can also add a CSS file, such as `style.css`, if your website needs custom styling.

Common files might include:

- `index.html`
- `style.css`
- `script.js`
- Images or other assets

After adding your files, commit the changes to GitHub.

## Step 4 - Open GitHub Pages Settings

In your GitHub repository, go to the **Settings** tab.

In the left sidebar, click **Pages**.

## Step 5 - Choose the Pages Source

Once you are in the **Pages** tab, find the **Build and deployment** section.

Under **Source**, choose **Deploy from a branch**.

Then choose:

- **Branch:** `main`
- **Folder:** `/root`

Click **Save**.

GitHub will start publishing your site. It may take a minute or two for the website to become available.

## Step 6 - Visit Your Website

Once GitHub Pages is enabled, a project website will usually be available at:

```text
https://your-username.github.io/repository-name/
```

For example, if your GitHub username is `octocat` and your repository is named `kitty-litter-cake-recipe`, the website URL would be:

```text
https://octocat.github.io/kitty-litter-cake-recipe/
```

If you used the special repository name `your-username.github.io`, then your site will be available at `https://your-username.github.io/` instead.

## Why Use GitHub Pages?

- It is free for static websites.
- It works well for HTML, CSS, and JavaScript projects.
- It connects directly to your GitHub repository.
- Updates are easy: commit and push your changes, and GitHub Pages republishes the site.

