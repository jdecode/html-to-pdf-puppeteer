# Google Cloud function to convert a HTML file to PDF

## Requirements

- NODE >= 20
- Google Cloud SDK Installed

## Usage

- Method: POST
- Required fields in POST body: html

```
{
  html: html,
  opts: {
    ...# Puppeteer Options
  }
}
```

Puppeteer PDF Options
https://github.com/puppeteer/puppeteer/blob/puppeteer-v21.5.1/docs/api/puppeteer.pdfoptions.md

## Deploy

```
npm run deploy
```
