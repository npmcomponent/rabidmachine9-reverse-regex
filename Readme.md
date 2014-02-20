*This repository is a mirror of the [component](http://component.io) module [rabidmachine9/reverse-regex](http://github.com/rabidmachine9/reverse-regex). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/rabidmachine9-reverse-regex`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# reverse-regex

  take regex as input, return a valid string

## Installation

  Install with [component(1)](http://component.io):

    $ component install rabidmachine9/reverse-regex

## API
	var regex = '^[a-z0-9_-]{3,16}$';
	var rgrep = new ReverseRegex(regex);
	var result = rgrep.resultString;

## Notes
	no flags are supported yet
	strict regular expressions can give you more relevant strings
	of course there might be bugs, feel free to improve

## License

  MIT
