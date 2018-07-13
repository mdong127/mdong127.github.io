### https://mdong127.github.io/

## What do you need to do to achieve a minimally viable website for PennApps?
1. transfer *By the Numbers 2*
1. finish about me & remove dummy posts in posts & projects

## To do (Tier 1): 
	DON'T FORGET TO CHANGE URL before pushing
	Fixes: 
		- https://stackoverflow.com/questions/27386169/change-site-url-to-localhost-during-jekyll-local-development
		- https://jekyllrb.com/docs/variables/

1. transfer other posts; how to add drafts
	- Drafts are posts without a date in the filename.  How to build with draft? 
	- add hyperlinks in *why education* & embed videos (look through md syntax post)
1. change email to redirect from a more generic one
1. link to google domain: https://medium.com/@Tnylnc/tnylnc-how-to-set-up-github-pages-with-google-domains-83bd5a4fbc5c 
1. create a dev branch & make pull requests
1. fix back button to use font icon

### To do (Tier 2): 
1. drop a donation
1. fix disqus
1. HOW TO USE analytics CODE? http://jmcglone.com/guides/github-pages/ Try creating an _include file that inserts Google Analytics tracking code into your <head> so you can get stats on the visitors to your website. Here's an example._
	- https://taylantatli.github.io/Moon/moon-theme/
1. Configuring Travis CI on your repo is a great way to track failing builds as well - https://stackoverflow.com/questions/24851824/how-long-does-it-take-for-github-page-to-show-changes-after-changing-index-html
1. regex for all png and jpg files?  `\.(png|jpg)`
1. look into development setting: https://jekyllrb.com/docs/usage/ 
1. add option to search by tags

## Completed: 
1. [x] customize background (picture or color) & logo (prof pic) & favicon
1. [x] insert markdownify into liquid templating for post list & projects layouts
1. [x] fix permalink issue with extra backslash 
1. [x] insert a basic _by the numbers post_ w/ images, YAML header, etc... 
1. [x] redirect post home button to proper `site.url`
1. [x] choose & change theme & link template to your github pages page 

Jekyll commands:

- `jekyll serve --livereload` for local version 
	- vs `bundle exec jekyll serve`? 
	- Note that _config.yml changes are loaded at compile time, not runtime. This means that if you’re running jekyll serve locally and you edit _config.yml, then changes to it won’t be detected. You’ll need to kill and rerun jekyll serve.
- pushing changes will automatically update live website (takes a few seconds)
- `jekyll build` ? 
	jekyll build will wipe everything in /_sites/. The first step of jekyll build is to delete everything in /_sites/ and then build it all again from scratch. So, you can’t store any files in there and expect them to stick around. Everything that goes into /_sites/ should be generated by Jekyll_

Git commands:
- `git remote set-url origin git://new.url.here`
- `git pull origin branchname --allow-unrelated-histories`


