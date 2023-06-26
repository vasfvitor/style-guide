# style-guide

This repository contains SASS that's used to generate common CSS styles that can be shared across the product
(platform, devrel, security, etc).

**Why SASS?**

Currently, we use a number of different component libraries across our products. This allows our teams to experiment
around with different tools and frameworks to figure out which one works best for them. To avoid prescribing a solution
we decided to generate CSS as a stepping stone to a more thorough component library.

## Installation

Currently, the assets need to be installed using git+ssh. To do this, add the following to your `package.json` file and
then install using `npm i` or `pnpm i`.

```json
{
	// ...
	"dependencies": {
		// ...
		"@crabnebula-dev/style-guide": "http://github.com/crabnebula-dev/style-guide.git#main"
	}
}
```

## Documentation

Until we get this shipped somewhere, you'll need to spin up a local server to access docs. This will also perform live
recompilation of scss files and automatic rebuilding of the docs.

```shell
npm run serve
```

## Resources

- [addlicense](https://github.com/google/addlicense)

## License

```
Copyright (C) 2023 CrabNebula Ltd.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
