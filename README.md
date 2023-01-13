# Omnivore API import-demo

This app demonstrates using [Omnivore's](https://omnivore.app) `uploadImportFile` GQL API endpoint to initiate a bulk import of data into Omnivore.

## Building

1. Install dependencies: `npm install`

## Usage

1. Create a csv file of URLs (one url per row), name the file `import.csv`.
2. Create an API key at <https://omnivore.app/settings/api>.
3. Run the app using `OMNIVORE_API_TOKEN=<your token> npm run import`

This app is based on <https://github.com/davidohlin/instapaper-to-omnivore-import>
