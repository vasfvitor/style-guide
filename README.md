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
		"@crabnebula-dev/style-guide": "git+ssh://git@github.com/crabnebula-dev/style-guide.git#main"
	}
}
```

## Resources

- [Figma](https://www.figma.com/file/fXTbZbLIwxnyQKOZERng3b/CrabNebula-Brand?type=design&node-id=2398-2856&t=K2wj0EDnp0X16c8v-0)
