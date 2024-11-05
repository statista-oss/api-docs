# Statista API Docs (2.8)

This repo is using a mintlify template.
It is using Statista's OpenAPI specification from our [Global Search OSS
Repo](https://github.com/statista-oss/global-search/blob/main/api/spec/openapi.yml).

The API Reference is broken down into our accessible product lines in the
`/api-reference` directory.

### Running Locally

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Project Structure

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
