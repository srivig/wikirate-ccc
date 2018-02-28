# wikirate-ccc
Clean Clothes Campaign Widget

## developer setup
The site is developed with [Middleman](https://middlemanapp.com). It depends on Ruby and the 
RubyGems package manager. If you don't have that you can follow these [instructions](https://middlemanapp.com/basics/install/). 
 
 
### installation 
```shell
git clone https://github.com/wikirate/wikirate-ccc
cd wikirate-ccc
bundle install
```

### build site
```
bundle exec middleman build
```

### run server
```
bundle exec middleman server
```  

The command returns a url where you can access the site.
Middleman automatically picks up source changes and refreshes
the site in the browser.

