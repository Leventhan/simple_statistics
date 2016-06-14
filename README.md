# SimpleStatistics

Statistical methods in Elixir.

### [Hex](http://hex.pm/packages/simple_statistics)
### [API Documentation](http://yosriady.com/simple_statistics/)

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add simple_statistics to your list of dependencies in `mix.exs`:

        def deps do
          [{:simple_statistics, "~> 0.0.1"}]
        end

  2. Ensure simple_statistics is started before your application:

        def application do
          [applications: [:simple_statistics]]
        end


## Running Tests

```
mix test
```

## Running Type Checker

> You need to have [dialyxir](https://github.com/jeremyjh/dialyxir) installed.

```
mix dialyzer
```

## Contributing

1. Fork it ( http://github.com/Leventhan/simple_statistics/fork )
2. Create your feature branch (`git checkout -b feature/my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/my-new-feature`)
5. Create new Pull Request (Remember to squash your commits!)

> Report any found bugs or errors using [the issue tracker](https://github.com/Leventhan/simple_statistics/issues).

## License

Copyright (c) 2016 Yos Riady

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
