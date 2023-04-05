# Docmosis Tornado Demo

[Docmosis Tornado](https://www.docmosis.com/products/tornado) provides the Docmosis engine as a web service that is easy to integrate with most modern platforms.

This demo is to get hands on with Docmosis Tornado.

## Requirements

- Docker
- Node 18.15.0
- [Tornado license key](https://resources.docmosis.com/content/getting-started/tornado)
- [Understanding of Docmosis templates](https://resources.docmosis.com/search?issearch=1&theme=FilterList&isc=1&ordering=zelevance&category_id=2&searchword=Tornado)

### Getting Started

- Clone this repo to your machine
- `cd` into repo directory
- Run: `npm i`
- Create your own .env from the .example.env
- Run: `docker compose up` and Tornado will start running at http://localhost:8080 or the port you set

#### Generating Documents

- Run: `node ./src/renderDocument.js`
- Open the file generated in the `output` directory

#### Other

- [Working with AWS S3](https://resources.docmosis.com/content/faq/how-do-i-render-to-my-amazon-web-services-s3-bucket)
- [Docmosis Security Statement](https://www.docmosis.com/products/tornado/#security-statement)
- [Example Templates](https://resources.docmosis.com/search?issearch=1&theme=FilterList&isc=1&ordering=zelevance&category_id=3)
- [Tornado (v2.8.4) - Template Guide](https://resources.docmosis.com/content/documentation/tornado-v2-8-4-template-guide)
- [Tornado Docs](https://resources.docmosis.com/search?issearch=1&theme=FilterList&isc=1&ordering=zelevance&category_id=2&searchword=Tornado)
