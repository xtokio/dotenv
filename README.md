# dotenv

Simple Crystal lang .env file loader

## Installation

1. Add the dependency to your `shard.yml`:

   ```yaml
   dependencies:
     dotenv:
       github: xtokio/dotenv
   ```

2. Run `shards install`

## Usage

```crystal
require "dotenv"
```

When .env file is in the same directory
```crystal
Dotenv.load
```

When .env file is in a specific folder
```crystal
Dotenv.load(path: "/var/www/app/.env")
```

## Contributing

1. Fork it (<https://github.com/xtokio/dotenv/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [Luis Gómez](https://github.com/xtokio) - creator and maintainer