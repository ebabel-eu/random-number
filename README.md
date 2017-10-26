# \<random-number\>

Generate a random number

## Installation

```
bower install --save random-number
```

## Usage

This component does not produce a visual template.

Call randomNumber(max) to get a random number between 0 and max (max is not included).

Example below sets result to be a number from 0 to 9.

```
const result = randomNumber(10);
```

Call randomNumber(max, min) to get a random number between min and max.

Example below sets result to be a number from 1 to 12.

```
const result = randomNumber(13, 1);
```

The parameter min and max are integers. min is included but max is not.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

1.0.0 is the first release

## License

GPL-3.0
