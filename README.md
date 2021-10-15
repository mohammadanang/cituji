# CSV to JSON Parser

Converter tool using command line.

### Using Run

You can run:

```
go run main.go [options] <csvfilepath>
```

### Using Build

or you can build:

```
go build .
```

and then execute:

```
./cituji [options] <csvfilepath>
```

### Options

You can see the options by run:

`go run main.go --help`

or

`./cituji --help`

options:
- `--pretty`, to make return json formatted.
- `--separator=<type>`, __type__ = `comma` or `semicolon`, based on your csv separator value.

### Run Test

```
go test -v
```

### Enjoy!