# Junteng Liu's Homepage

Personal academic website of **Junteng Liu**, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and deployed on GitHub Pages.

The site contains:

- **About** — personal details and research interests
- **Academic background** — Ph.D. at HKUST and B.Eng. at Shanghai Jiao Tong University
- **Research experience** — MINIMAX, Tencent WXG, and Shanghai AI Lab
- **Publications** — papers at NeurIPS, ICML, and EMNLP, and arXiv preprints
- **Skills & research interests** — NLP, machine learning, LLM reasoning, and more
- **Contact** — email, GitHub, Google Scholar, and X (Twitter)

## Local development

```bash
bundle install
npm run build
bundle exec jekyll serve -l -H localhost
```

## Deployment

The site is built and deployed by the GitHub Actions workflow in
`.github/workflows/jekyll.yml`. GitHub Pages must be configured once under
**Settings → Pages → Source: GitHub Actions**.
