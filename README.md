# \<random-number\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ebabel-eu/random-number)

Generate a random number

## Installation

```
bower install --save ebabel-eu/random-number
```

## Usage

```
<random-number id="randomGenerator"></random-number>
```

This component does not produce a visible template.

In a script where random-number instance is accessible, call its function randomNumber:

```
// returns a number from 0 to 9.
const result = this.$.randomGenerator.randomNumber(10);

// returns a number from 1 to 6.
const dice = this.$.randomGenerator.randomNumber(7, 1);
```

The parameters max and min are integers. max is not included, min is.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* **2.0.0:** randomNumber moved from global namespace to public method of each component
* **1.0.1:** small fix to the documentation
* **1.0.0:** first official release
* **0.1.3:** pre-release that full works but wasn't ready for webcomponents.org

## License

GPL-3.0
