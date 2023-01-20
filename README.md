# Presentation Template

This is a template for making presentations using AsciiDoc [1].

## Getting started

Run the following once to setup the dependencies.

```sh
ops up
```

## Building presentation

| Action                                                                    | Command     |
| ------------------------------------------------------------------------- | ----------- |
| Generate the presentation HTML into the `build/html` folder               | `ops html`  |
| Monitor for changes in the `src/` folder and run `ops html` automatically | `ops watch` |
| Launch presentation HTML in your default browser                          | `ops open`  |
| Clean up the `build/` folder                                              | `ops clean` |

## Contributing

Bug reports and sugestions are welcome. Otherwise, at this time, this project is closed for code changes and pull requests. I appreciate your understanding.

## License

The library is available as open source under the terms of the [MIT License](LICENSE).

## References

1. [AsciiDoctor reference](https://docs.asciidoctor.org/asciidoctor/latest/)
2. [AsciiDoctor RevealJS reference](https://docs.asciidoctor.org/reveal.js-converter/latest/)
3. [AsciiDoctor Diagram reference](https://docs.asciidoctor.org/diagram-extension/latest/)
