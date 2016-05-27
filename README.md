# scraping

From this [DigitalOcean tutorial](https://www.digitalocean.com/community/tutorials/how-to-use-node-js-request-and-cheerio-to-set-up-simple-web-scraping).

## Installing

```sh
git clone git@github.com:kahwee/scraping.git
cd scrapping
npm i
```

## Running

```sh
node index.js
```

This is the expected output

```sh
scraping ❯ node index.js
[ { rank: 1,
    title: 'All European scientific publicly funded articles to be freely accessible by 2020',
    url: 'http://english.eu2016.nl/latest/news/2016/05/27/all-european-scientific-articles-to-be-freely-accessible-by-2020',
    points: 594,
    username: 'whazor',
    comments: 5 },
  { rank: 2,
    title: 'Experts say Olympics must be moved or postponed because of Zika',
    url: 'https://www.washingtonpost.com/news/to-your-health/wp/2016/05/27/125-experts-say-olympics-must-be-moved-or-postponed-because-of-zika/',    points: 135,
    username: 'graeme',
    comments: 2 },
  ...
]
```
