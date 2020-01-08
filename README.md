# KTX stats Scraping tool

This script retrieves JSON data containing all available QTV hosts and tries to download available KTX stats.

## Usage:

### Install:
`pip3 -i requirements.txt`

### Use:
`python3 scrape.py`

Collects server info and download links:

```
Working on server 194.14.206.10 (1/21) 
Working on server 194.132.9.82 (2/21) 
Working on server 185.189.48.45 (3/21) 
Working on server 95.216.202.86 (4/21) 
Working on server 91.102.91.59 (5/21) 
Working on server 51.144.235.192 (6/21) 
Working on server 195.201.133.22 (7/21) 
...
```

Then download files if they were not downloaded yet:
```
...
File /Users/andrestone/dev/repos/statscraper/stats/4on4/all_maps/4on4_-gg-_vs_buff[e3m7tdm]200107-2144.txt exists, skipping.
File /Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_1[e1m5tdm]200107-2059.txt exists, skipping.
File /Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_2[cmt1b]200107-2046.txt exists, skipping.
File /Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_1[e3m3tdmb]200107-2034.txt exists, skipping.
/Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_1[e3m7tdm]200102-1736.txt (70/465) -> Working on 18.196.7.115 (7/21)
/Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_1[ctl8]200102-1724.txt (71/465) -> Working on 18.196.7.115 (7/21)
/Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_1[e3m6tdm]200102-1712.txt (72/465) -> Working on 18.196.7.115 (7/21)
/Users/andrestone/dev/repos/statscraper/stats/other/all_maps/ffa_1[cmt3]200102-1659.txt (73/465) -> Working on 18.196.7.115 (7/21)
...
```

