---
title: "CrabNebula Style Guide"
description: ""
---

# CrabNebula Style Guide

- [Installation](#installation)
- [Typography](#typography)
  - [Headings](#headings)
  - [Inline text elements](#inline-text-elements)
  - [Lists](#lists)
  - [Tables](#tables)
- [Components](#components)
  - [Badge](#badge)
  - [Breadcrumb](#breadcrumb)
  - [Buttons](#buttons)
  - [Card](#card)
  - [Dropdowns](#dropdowns)
  - [List group](#list-group)
  - [Modal](#modal)
  - [Navbar](#navbar)
  - [Navs and tabs](#navs-and-tabs)
  - [Pagination](#pagination)
  - [Progress](#progress)
  - [Toasts](#toasts)

<br/>

# Installation

<hr/><br/>

```json
{
	// ...
	"dependencies": {
		// ...
		"@crabnebula-dev/style-guide": "git+ssh://git@github.com/crabnebula-dev/style-guide.git#main"
	}
}
```

<br/>

# Typography

<hr/><br/>

## Headings

<h1>h1. heading</h1>
<h2>h2. heading</h2>
<h3>h3. heading</h3>
<h4>h4. heading</h4>
<h5>h5. heading</h5>
<h6>h6. heading</h6>

```html
<h1>h1. heading</h1>
<h2>h2. heading</h2>
<h3>h3. heading</h3>
<h4>h4. heading</h4>
<h5>h5. heading</h5>
<h6>h6. heading</h6>
```

## Inline text elements

<p>You can use the mark tag to <mark>highlight</mark> text.</p>
<p><del>This line of text is meant to be treated as deleted text.</del></p>
<p><s>This line of text is meant to be treated as no longer accurate.</s></p>
<p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
<p><u>This line of text will render as underlined.</u></p>
<p><small>This line of text is meant to be treated as fine print.</small></p>
<p><strong>This line rendered as bold text.</strong></p>
<p><em>This line rendered as italicized text.</em></p>

```html
<p>You can use the mark tag to <mark>highlight</mark> text.</p>
<p><del>This line of text is meant to be treated as deleted text.</del></p>
<p><s>This line of text is meant to be treated as no longer accurate.</s></p>
<p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
<p><u>This line of text will render as underlined.</u></p>
<p><small>This line of text is meant to be treated as fine print.</small></p>
<p><strong>This line rendered as bold text.</strong></p>
<p><em>This line rendered as italicized text.</em></p>
```

## Lists

<ul>
  <li>Use Armelv5 for all 32-bit armel systems</li>
  <li>Use Armhfv6 for all armhf systems with v6+ architecture</li>
  <li>Use Arm64 for all v8 64-bit architectures</li>
</ul>

```html
<ul>
  <li>Use Armelv5 for all 32-bit armel systems</li>
  <li>Use Armhfv6 for all armhf systems with v6+ architecture</li>
  <li>Use Arm64 for all v8 64-bit architectures</li>
</ul>
```

## Tables

<!-- TBD -->

<br/>

# Components

<hr/><br/>

## Badge

<div class="cn-badge cn-bg-pink">Update available</div>
<div class="cn-badge cn-bg-berry">AppStore</div>
<div class="cn-badge cn-bg-teal">New Cluster</div>

```html
<div class="cn-badge cn-bg-pink">Update available</div>
<div class="cn-badge cn-bg-berry">AppStore</div>
<div class="cn-badge cn-bg-teal">New Cluster</div>
```

## Breadcrumb

<!-- TBD -->

## Buttons

<!-- TBD -->

## Card

<div class="cn-card">
	<h3>Card Title</h3>
	<p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
	<hr/>
</div>

```html
<div class="cn-card">
	<h3>Card Title</h3>
	<p>
		Some quick example text to build on the card title and make up the bulk of the card's content.
	</p>
	<hr/>
</div>
```

## Dropdowns

<!-- TBD -->

## List group

<!-- TBD -->

## Modal

<!-- TBD -->

## Navbar

<!-- TBD -->

## Navs and tabs

<!-- TBD -->

## Pagination

<!-- TBD -->

## Progress

<!-- TBD -->

## Toasts

<!-- TBD -->
