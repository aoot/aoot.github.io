<style>
  h1 {
    color: red;
  }

  h2 {
    color: green;
  }

/* Questions are colored as orange */
  .question {
    color: orange;
  }
</style>
# Understanding the file structures

## File Structure Notes
| File Name    | Notes / Descriptions | 
| ---------    | -------------------- |
| config.yml   | <ul><li> jekyll properties and configuration file</li></ul> | 
| .gitignore   | <ul><li> <div class="question">Domain name file needed for rerouting by Wordpress or Github or Netlify?</div> </li></ul> |
| CNAME        | <ul><li> Self explanatory</li></ul> |
| Gemfile      | <ul><li> <div class="question">Executing and running jekyll plugin files?</div></li></ul> | 
| gulpfile.js  | <ul><li> jekyll-build function - Server base dir = _site</li> <li> Pictures are compressed into _site/assets/img</li> <li> Watches changes to execute functions of scss, jekyll-rebuild, img</li></ul> |
| index.html   | <ul><li> Homepage layout template</li></ul> | 
| LICENSE      | <ul><li> GNU</li></ul> | 
| package.json | <ul><li> npm package list</li> <li><div class="question"> ??? Where is index.js?</div></li>  <li><div class="question"> ??? Why is the repo pointed to Artem's Github repo?</div></li> <li> Debug script runs Gulp watch</li></ul>| 
| README.md    | <ul><li> Self explanatory</li></ul> | 
| search.json  | <ul><li> JavaScript search script</li> <li> May be invoked by the search button</li></ul> | 

## Questions

- site.baseurl v url differences, understand how they relate in header.html
- Observe how recent-post.html prepending url injection works to understand baseurl v url

## Git notes

```bash
# git delete remote branch
git push --delete <remote_name> <branch_name>

# git delete local branch
git branch -d <branch_name>

```

# To Do

- [x] Understand Gulp files
- [ ] Install local Jekyll environment to develop Netlify CMS
