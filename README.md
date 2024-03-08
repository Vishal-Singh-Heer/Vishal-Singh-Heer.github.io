# Hosting Your Resume on GitHub Pages

## Introduction

In the digital landscape, having a standout online presence is akin to holding a key to vast career opportunities. Inspired by Andrew Etter's "Modern Technical Writing," this guide illustrates how GitHub Pages can be a strategic platform to highlight your professional achievements. By hosting your resume here, you not only enhance your personal branding but also attract potential employers, thereby opening doors to numerous future prospects and giving you a competitive edge in the job market.

## Getting Started: What You Need

To successfully host your resume on GitHub Pages, you'll need a few things set up:

- **A GitHub Account**: Consider this as your financial portfolio's online platform, where you engage with a global community, showcasing your projects much like your investments. Registering is free and straightforward. Begin by creating your account [here](https://github.com/join) to share your professional milestones.

- **A Markdown-Formatted Resume**: Markdown, with its simplicity and ease of use, is akin to a fundamental analysis tool in finance, helping you craft your professional narrative without the complexity of HTML. New to Markdown? Kickstart your journey with this beginner-friendly [Markdown Guide](https://www.markdownguide.org/getting-started/).

- **Familiarity with GitHub Pages**: GitHub Pages acts as a digital stage, transforming repositories into professionally hosted web pages. It's your platform to broadcast your skills. Start exploring GitHub Pages [here](https://pages.github.com/).

## Step-by-Step Instructions

### 1. Setting Up Your Repository

At the heart of GitHub is Git, a version control system that tracks changes to your projects over time, similar to maintaining a detailed investment history. This practice mirrors Andrew Etter's advice on the importance of version control for efficient, collaborative documentation, making Git an essential tool for managing your professional narrative.

- **Task**: Begin by creating a new repository on GitHub to house your resume and any related materials.
- **Detailed Steps**: 
  1. Navigate to your GitHub dashboard and click on the "New" button to start a new repository.
  2. Use the format `[YourGitHubUsername].github.io` for your repository name, as it influences your GitHub Page's URL and visibility. The name of your repository is crucial as it becomes part of your public URL and is key to ensuring your resume can be found by potential employers or connections.
  3. Choose whether to keep your repository **Public** or **Private**. A **Public** repository is visible to everyone and is the best choice for hosting your resume, as it allows potential employers and contacts to view your work. A **Private** repository, while keeping your content hidden from the public, would not serve the purpose of showcasing your resume to a wider audience.
  4. Initialize with a README file, which provides an overview of your repository, similar to a business prospectus. This README file is the first thing visitors will see when they visit your repository, so it serves as the "front page" of your project.

### 2. Crafting Your Resume

Embracing the ethos of Andrew Etter's modern technical writing principles, the cornerstone of compelling documentation is its clarity and accessibility to the reader. Markdown, as a lightweight markup language, is instrumental in this regard, offering a straightforward method for content creation. This simplicity aligns perfectly with GitHub's capabilities, allowing for an enhanced visual presentation of your resume without the complexities and intricacies often associated with traditional formatting methods.

- **Task**: Within your new repository, proceed to "Add file" > "Create new file". Name this file `index.md`. This Markdown file will host your resume content.
- **Detailed Steps**:
  1. Use Markdown to craft your resume within `index.md`. Employ headers, bullet points, and hyperlinks to organize your information and highlight key achievements.
  2. Once you have input your content, on the top right, Click green "Commit changes..." button, enter a commit message that summarizes your changes, and click "Commit changes" to save your resume.

### 3. Choosing a Theme with Jekyll

A visually consistent and appealing content layout greatly boosts readability and user interaction, aligning with Etter's principles that advocate for clear and accessible documentation. Through GitHub Pages and Jekyll, a range of themes are available to customize your site's appearance, embodying Etter's emphasis on user-friendly documentation practices.

- **Task**: To select a theme for your resume page, you need to add a `_config.yml` file to your repository. This file is used to configure settings for your GitHub Pages site, including its theme.
- **Detailed Steps**:
  1. In your repository, create a new file named `_config.yml`.
  2. Inside `_config.yml`, specify your chosen theme with a line such as `theme: jekyll-theme-minimal`. GitHub offers a variety of themes, so choose one that best suits your resume's style.
  3. Beyond selecting a theme, you can customize your site further by adding additional configurations to `_config.yml`, such as `title:`, `description:`, and `show_downloads:`. This enhances your page's functionality and presentation, making your online resume more reflective of your professional persona.

### 4. Going Live

With your `index.md` and `_config.yml` in place, your resume is set for online display, illustrating the essence of Andrew Etter's continuous delivery principle in the realm of modern technical writing. This stage marks the transition from preparation to presentation, bringing your professional persona to the digital forefront.

- **Detailed Steps**:
  1. Access your repository's settings by navigating to the "Settings" tab.
  2. In the left sidebar, find and select the "Pages" section.
  3. Under "Source", choose the main branch and "/" (root) as the directory. This action directs GitHub Pages to use the content from the specified location to build your site.

After configuring these settings, your resume will be accessible on the web at `https://[YourGitHubUsername].github.io/`, marking a significant milestone in your professional online presence.


## Visual Guide

![Animation](https://github.com/Vishal-Singh-Heer/Vishal-Singh-Heer.github.io/assets/130388412/c8bec94e-dc44-41a4-9f7e-16b3b88bbd77)


## Additional Resources

- [**Mastering Markdown**](https://guides.github.com/features/mastering-markdown/): A comprehensive guide on using Markdown for content creation.

- [**Understanding GitHub Pages**](https://docs.github.com/en/pages): In-depth tutorials for enhancing your GitHub Pages experience.

- [**Exploring Jekyll**](https://jekyllrb.com/docs/): Insights on customizing your site with Jekyll, covering basics to advanced setups.

- [**Git Basics**](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics): Deepen your understanding of Git, essential for GitHub users of all levels.


## Acknowledgements

Thanks to `Andrew Etter` for his insights on modern technical writing, and appreciation is also extended to `Simran Kaur` and `Hridai Mehta` for their thoughtful peer reviews and contributions to refining this document.

## Frequently Asked Questions

**Q: Why is Markdown recommended for writing a resume?**
A: Markdown is favored for its simplicity and flexibility. It allows you to create well-formatted text with minimal syntax, making it easy to write, read, and maintain. Furthermore, GitHub Pages can seamlessly convert Markdown to HTML, making your resume accessible on the web without needing complex web development skills.

**Q: What should I do if my resume doesn't appear on GitHub Pages after following these steps?**
A: If your resume isn't visible after setting up GitHub Pages, check a few key areas:
  - Verify that your repository's name is correct and follows the `[YourGitHubUsername].github.io` format.
  - Make sure the `index.md` file is in the root directory of your repository and correctly formatted with Markdown.
  - Ensure the GitHub Pages settings are correctly configured to build from the main branch and the root directory.
  - Remember, changes might take a few minutes to propagate, so give it some time before troubleshooting further.
