# crawler_scrapy
This repo is about crawling website using scrapy

## Get crawler list
Go to intended folder to get it list with `list` command
```
$scrapy list
```

## Running the spider
```
$scrapy crawl toscrape-css
$scrapy crawl toscrape-xpath
```
## Expected result
```
{
  'text': "“I'm the one that's got to die when it's time for me to die, so let me live my life the way I want to.”", 
  'author': 'Jimi Hendrix', 
  'tags': ['death', 'life']
}
```
