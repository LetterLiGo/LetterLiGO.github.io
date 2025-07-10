
<h1 align="center">
AcadHomepage
</h1>

<div align="center">

[![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/forks/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/issues/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/license/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io/blob/main/LICENSE)  | [中文文档](./docs/README-zh.md) 
</div>

<p align="center">A Modern and Responsive Academic Personal Homepage</p>

<p align="center">
    <br>
    <img src="docs/screenshot.png" width="100%"/>
    <br>
</p>

Some examples:
- [Demo Page](https://rayeren.github.io/acad-homepage.github.io/)
- [Personal Homepage of the author](https://rayeren.github.io/)

## Key Features
- **Automatically update Google Scholar citations**: Using the Google Scholar crawler and GitHub Actions, this repository can automatically update author citations and publication citations.
- **Support Google Analytics**: You can track the traffic of your homepage with easy configuration.
- **Responsive**: This homepage automatically adjusts for different screen sizes and viewports.
- **Beautiful and Simple Design**: This homepage is beautiful and simple, which is very suitable for an academic personal homepage.
- **SEO**: Search Engine Optimization (SEO) helps search engines find the information you publish on your homepage easily, then rank it against similar websites.

## Quick Start

1. Fork this repository and rename it to `USERNAME.github.io`, where `USERNAME` is your GitHub username.
2. Configure the Google Scholar citation crawler:
    1. Find your Google Scholar ID in the URL of your Google Scholar page (e.g., https://scholar.google.com/citations?user=SCHOLAR_ID), where `SCHOLAR_ID` is your Google Scholar ID.
    2. Set the `GOOGLE_SCHOLAR_ID` variable to your Google Scholar ID in `Settings -> Secrets -> Actions -> New repository secret` of the repository website with `name=GOOGLE_SCHOLAR_ID` and `value=SCHOLAR_ID`.
    3. Click the `Action` tab of the repository website and enable the workflows by clicking *"I understand my workflows, go ahead and enable them"*. This GitHub Action will generate Google Scholar citation stats data `gs_data.json` in the `google-scholar-stats` branch of your repository. When you update your main branch, this action will be triggered. This action will also be triggered at 08:00 UTC every day.
3. Generate a favicon using [favicon-generator](https://redketchup.io/favicon-generator) and download all generated files to `REPO/images`.
4. Modify the configuration of your homepage in `_config.yml`:
    1. `title`: The title of your homepage.
    2. `description`: The description of your homepage.
    3. `repository`: USER_NAME/REPO_NAME.  
    4. `google_analytics_id` (optional): Google Analytics ID.
    5. SEO Related keys (optional): Get these keys from search engine consoles (e.g., Google, Bing, and Baidu) and paste them here.
    6. `author`: The author information for this homepage, including other websites, emails, city, and university.
    7. More configuration details are described in the comments.
5. Add your homepage content in `_pages/about.md`.
    1. You can use HTML+Markdown syntax, just as in Jekyll.
    2. You can use a `<span>` tag with class `show_paper_citations` and attribute `data` to display the citations of your paper. Set the data to the Google Scholar paper ID. For example:
        ```html
        <span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>
        ``` 
        > Q: How to get the Google Scholar paper ID?   
        > A: Go to your Google Scholar homepage and click the paper name. You can then find the paper ID from `citation_for_view=XXXX`, where `XXXX` is the required paper ID.
6. Your page will be published at `https://USERNAME.github.io`.

## Debug Locally

1. Clone your repository to local using `git clone`.
2. Install the Jekyll build environment, including `Ruby`, `RubyGems`, `GCC`, and `Make`, by following [the installation guide](https://jekyllrb.com/docs/installation/#requirements).
3. Run `bash run_server.sh` to start the Jekyll live-reload server.
4. Open http://127.0.0.1:4000 in your browser.
5. If you change the source code of the website, the live-reload server will automatically refresh.
6. When you finish modifying your homepage, `commit` your changes and `push` to your remote repository using `git`.

# Acknowledgements

- AcadHomepage incorporates Font Awesome, which is distributed under the terms of the SIL OFL 1.1 and MIT License.
- AcadHomepage is influenced by the GitHub repo [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes), which is distributed under the MIT License.
- AcadHomepage is influenced by the GitHub repo [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io), which is distributed under the MIT License.
