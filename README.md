# topic-sensitive-pagerank

## Using
Files should be run in order to create the necessary dataframes for query processing.


## Data Sources
### ODP data:
Content RDF Dump March 2017
* https://web.archive.org/web/20170312160530/http://rdf.dmoz.org/rdf/content.rdf.u8.gz.

### CommonCrawl data:  
Web Graph Release cc-main-2017-may-jun-jul (Domain Level)
https://data.commoncrawl.org/projects/hyperlinkgraph/cc-main-2017-may-jun-jul/index.html

* Verticies: http://data.commoncrawl.org/projects/hyperlinkgraph/cc-main-2017-may-jun-jul/domaingraph/vertices.txt.gz
* Edges: http://data.commoncrawl.org/projects/hyperlinkgraph/cc-main-2017-may-jun-jul/domaingraph/edges.txt.gz

## Requirements
* numpy
* pandas
* sqlite3
* fast-pagerank