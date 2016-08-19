# YQL
## HTML POST
```SQL
use "https://bestpika.github.io/yql/tables/htmlpost.xml" as htmlpost;
select * from htmlpost where url="http://foo.tld" and args="foo=foo&bar=bar" and xpath="//body";
```
