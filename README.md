# Gobierto ETL for Alcobendas

ETL scripts for Gobierto Alcobendas site: https://participa.alcobendas.org/

## Setup

Install dependencies:

```bash
brew install freetds
sudo ARCHFLAGS="-arch x86_64" gem install tiny_tds
```

Copy `.env` file:

```bash
cp .env.example .env && ln -s .env .rbenv-vars
```

And fill in the values.

This repository relies heavily in [gobierto_data](https://github.com/PopulateTools/gobierto_data)

## Available operations

- gobierto_plans/extractor
- gobierto_plans/importer
