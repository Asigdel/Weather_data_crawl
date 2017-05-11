# Weather_data_crawl
```
import re
import urllib

url = "https://www.wunderground.com/history/airport/KAGC/2015/11/25/DailyHistory.heml?&format=1"
html = urllib.request.urlopen(url).read()
print(html)
```
