# 🗂️ Intelligence Archive
### A curated intelligence repository

---

# Pre-requisites
Before you start, make sure you have the following installed on your system:

- Ruby (version 3.4.5)
- RubyGems (Ruby's package manager)
- GCC (GNU Compiler Collection)
- Make (build automation tool)

These tools are essential for setting up and running this Jekyll site.

---

# Setting Up for Local Development

Follow these steps to set up your local environment for developing the Jekyll static site:

## 1. Install Bundler
Navigate to the project root directory in your terminal and run:

```bash
gem install bundler
```

Bundler manages Ruby gem dependencies, making it easier to handle Jekyll's requirements.

## 2. Install Dependencies
Install the required gems specified in your `Gemfile`:

```bash
bundle install
```

This command installs all the necessary dependencies for your Jekyll site.

## 3. Build the Site
Compile your site's source code into static files:

```bash
jekyll build
```

This step generates the static site files in the `_site` directory.

## 4. Serve the Site Locally
Start a local server to view your Jekyll site:

```bash
bundle exec jekyll serve
```

This allows you to view your site in a web browser at:

```
http://localhost:4000
```

---

# Accessing the Site Locally

Once you've successfully run the above commands, you can access your Jekyll site by navigating to:

```
http://localhost:4000
```

The local server will automatically reflect changes as you develop.

---

# Accessing the Site on the Web

The live version of the site is available at:

```
https://lizzypokerface.github.io/intelligence-archive/
```

This version is deployed via GitHub Pages.

---

# Troubleshooting

1. [Resolving Ruby Installation Error '__rvm_make -j12' on ARM64 Macs](https://github.com/rvm/rvm/issues/5379)
