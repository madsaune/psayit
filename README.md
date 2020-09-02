# PSayIt

PSayIt (pronounced: say it) is yet another static site generator, but this time written in Powershell.

## Todo

- [ ] Parse markdown files
  - [ ] Fetch markdown files from `./_posts` folder
  - [ ] Parse frontmatter
  - [ ] Convert content from markdown to HTML
  - [ ] Save as `./output/posts/<name_of_file>/name_of_file>.html` using `./post.html` as template
- [ ] Index page
  - [ ] Add `./index.html` as a template for index page
  - [ ] Save parsed version as `./output/index.html`
- [ ] Archive page
  - [ ] Add `./archive.html` as a template for archived posts
  - [ ] Save parsed version as `./output/archive/index.html`
- [ ] Customizable settings 
  - [ ] Settingsfile `./settings.json`
  - [ ] Set page title
