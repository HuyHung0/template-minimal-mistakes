# template-minimal-mistakes
Minimal mistakes jekyll theme - modified from original website
- Do not use remote theme.
- Add plugins "compose" for easier creating post name
- Change some settings in `_config.yml`
- Use github action to automate the build in workflow. (this yml file create by github action - jekyll)

After download the template, can safely remove `Gemfile-starter` and `Gemfile-jekyllnew`. Then modify `baseurl` in `_config.yml` to be the repository name (for example `"/blog"`).

Then run
```bash
bundle
```

If needed, we can remove `.git` and redo `git init` and create a remote repository (change setting in page to deploy using github action), then push the local code to remote repository. The github action will automatically build and deploy the page.