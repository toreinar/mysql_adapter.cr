# mysql_adapter

Mysql adapter for [active_record.cr](https://github.com/waterlink/active_record.cr). Uses [crystal-mysql library](https://github.com/waterlink/crystal-mysql)

## Installation

Add it to `Projectfile`

```crystal
deps do
  github "waterlink/mysql_adapter"
end
```

## Usage

```crystal
require "active_record"
require "mysql_adapter"

class Person < ActiveRecord::Model
  adapter mysql
  # ...
end
```

## Contributing

1. Fork it ( https://github.com/waterlink/mysql_adapter/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [waterlink](https://github.com/waterlink) Oleksii Fedorov - creator, maintainer
