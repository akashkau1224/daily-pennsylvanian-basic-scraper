# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on [ ... date you accessed the file ... ]

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation

### For all bots (User-agent: *):

- Crawl-delay: 10: Requests that bots wait 10 seconds between successive requests to avoid overloading the server.
- Allow: /: Permits all bots to crawl the entire website.

### For SemrushBot (User-agent: SemrushBot):

- Disallow: /: Blocks SemrushBot from accessing any part of the website.