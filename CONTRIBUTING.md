# Contribution Guidelines

Welcome to the Awesome Livepeer List! 👋 This is a community-curated collection of projects, tutorials, demos, and resources within the Livepeer ecosystem. Livepeer is a decentralized video streaming network built on the Ethereum blockchain. We aim to foster a vibrant community by encouraging contributions from everyone, regardless of experience level. 😊

## Introduction

The purpose of this list is to serve as a comprehensive resource for anyone looking to engage with the Livepeer ecosystem. Whether you're a developer, content creator, or enthusiast, your contributions are valuable and help grow the Livepeer community.

## Code of Conduct

We are committed to providing a welcoming and inclusive experience for everyone. Therefore, we expect all participants to adhere to our [Contributor Code of Conduct](code_of_conduct.md). By participating in this project, you agree to abide by its terms and promote a respectful and collaborative environment.

## Pull Requests (PRs)

- **Branching**: ALWAYS create a new branch for your proposed changes. This helps maintain the project's stability and ensures that changes can be adequately reviewed.
- **Descriptive Titles**: Use clear and descriptive titles for your PRs to help maintainers understand your contributions at a glance.

### How to Submit a PR

1. Fork the repository.
2. Create a new branch in your forked repository.
3. Make your changes in the new branch.
4. Submit a pull request from your branch to the main repository.

## Adding a New Item

Before adding a new item, please ensure it adheres to the following guidelines:

- **Find the Right Section**: Try to fit your item into an existing section. If you believe a new section is warranted, [open an issue](https://github.com/rickstaa/awesome-livepeer/issues/new) to discuss your proposal. Please provide clear reasons why the new section would be a valuable addition.
- **Placement**: Add new items to the bottom of the relevant section's list.
- **Duplicates**: If a similar item already exists, please discuss in an issue why your suggested item provides a unique value.
- **Format**: Each submission must follow the format: `- [Item Name](https link) - Description starting with a capital letter and ending with a period.`

Example:

```markdown
- [Livepeer Studio](https://livepeer.studio) - An intuitive interface for live video streaming on the Livepeer network.
```

## Build Locally

Follow these steps to build and test the GitHub Pages site locally using Jekyll:

1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [Bundler](https://bundler.io/guides/getting_started.html). We recommend using [rbenv](https://github.com/rbenv/rbenv) to manage Ruby versions.
2. Fork the repository and clone it to your local machine.
3. Navigate to the repository directory and set the Ruby version to 2.7.2 by running `rbenv local 2.7.2`. This is necessary because the [GitHub Pages gem](https://github.com/github/pages-gem/) currently does not support Ruby 3.0.0 (refer to this [issue comment](https://github.com/github/pages-gem/issues/752#issuecomment-764758292) for more details).
4. Install Jekyll and other dependencies by running `bundle install`.
5. Start the local server by running `bundle exec jekyll serve`.
6. Access the site by opening `http://localhost:4000` in your web browser.

For a more comprehensive guide, check out [GitHub's documentation on testing a GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).

## Contribution Review Process

Maintainers review all contributions for relevance, accuracy, and adherence to guidelines. We aim to process contributions promptly, but review times may vary depending on the current workload.

## Acknowledgments

We appreciate every contribution and thank everyone who has contributed to the Awesome Livepeer List! Special acknowledgements may be given to frequent contributors or those who provide precious insights or resources. 🏆

## Community Interaction

For general discussions, questions, or to engage with the Livepeer community, please visit our [community forums](https://forum.livepeer.org) or join us on [Discord](https://discord.livepeer.org).

Thank you for contributing to the Awesome Livepeer List and helping grow the Livepeer ecosystem! 🙏
