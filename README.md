# Purpose

This repo is only to meet to minimal requirement to get a swag. I learn how to use Contentful to create this api in 30 minutes.  Good Job Contentful team!!!

## Installation

Run this in your terminal



```bash
curl --location --request POST 'https://graphql.contentful.com/content/v1/spaces/a52pzv0h94gs/environments/master' \
--header 'Authorization: Bearer Q54TOrQZPWV7r0Qny-Ob03czWid7rSceDMhNWqWA7a8' \
--header 'Content-Type: application/json' \
--data-raw '{"query":"query test($id: String!) {\n    superhero(id:$id) {\n        name\n    }\n}","variables":{"id":"gB6fS7OGN6qpmbFVABDCB"}}'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
