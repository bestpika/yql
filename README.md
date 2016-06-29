# YQL
## HTML POST
```SQL
use "https://github.com/bestpika/yql/raw/master/tables/htmlpost.xml" as htmlpost;
select * from htmlpost where url="http://foo.tld" and args="foo=foo&bar=bar" and xpath="//body";
```
