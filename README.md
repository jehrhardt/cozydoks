# Cozy Doks

Cozy Doks is a Zola theme helping you build modern documentation websites, which is a fork of [AdiDoks](https://github.com/aaranxu/adidoks) theme for Zola.

## Demo

The theme is used by [Cozy Coder](https://cozycoder.app).

## Requirements

Before using the theme, you need to install the [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.19.0.

## Usage

### Step 1: Create a new zola site

Create a website for your project:
```bash
zola init website
```

### Step 2: Install Cozy Doks theme

Install this theme as a Git submodule:

```bash
git submodule add https://github.com/jehrhardt/cozydoks.git website/themes/cozydoks
```

### Step 3: Configuration

Copy the `config.toml.example` from the theme directory to your project's
root directory:

```bash
cd website
cp themes/cozydoks/config.toml.example config.toml
```

### Step 4: Add new content

You can copy the content from the theme directory to your project:

```bash
cp -R themes/cozydoks/content .
```

You can modify or add new posts in the `content/blog`, `content/docs` or other
content directories as needed.

### Step 5: Run the project

Just run `zola serve` in the root path of the project:

```bash
zola serve
```

AdiDoks will start the Zola development web server accessible by default at
`http://localhost:1111`. Saved changes will live reload in the browser.

### Step 6: Deploy to Netlify

Copy the `netlify.toml.example` from the theme to your project:

```bash
cp themes/cozydoks/netlify.toml.example netlify.toml
```
