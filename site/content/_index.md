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
  - [Colors](#colors)
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
		"@crabnebula-dev/style-guide": "https://github.com/crabnebula-dev/style-guide.git#main"
	}
}
```

<br/>

# Typography

<hr/><br/>

## Headings

Headings in UX (User Experience) are important elements that contribute to the organization, structure, and readability
of digital interfaces such as websites, applications, and other interactive systems. They serve multiple purposes and
play a crucial role in enhancing the overall user experience. Here's a brief description of what headings are used for
in UX:

1. Content Hierarchy
1. Scannability and Readability
1. Navigation and Wayfinding
1. Accessibility and Screen Readers
1. SEO (Search Engine Optimization)

<div class="docs-example">
	<h1>h1. heading</h1>
	<h2>h2. heading</h2>
	<h3>h3. heading</h3>
	<h4>h4. heading</h4>
	<h5>h5. heading</h5>
	<h6>h6. heading</h6>
</div>

```html
<h1>h1. heading</h1>
<h2>h2. heading</h2>
<h3>h3. heading</h3>
<h4>h4. heading</h4>
<h5>h5. heading</h5>
<h6>h6. heading</h6>
```

## Inline text elements

These elements enhance the visual appearance and readability of the text, allowing designers to convey emphasis,
hierarchy, or specific meaning.

<div class="docs-example">
	<p>You can use the mark tag to <mark>highlight</mark> text.</p>
	<p><del>This line of text is meant to be treated as deleted text.</del></p>
	<p><s>This line of text is meant to be treated as no longer accurate.</s></p>
	<p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
	<p><u>This line of text will render as underlined.</u></p>
	<p><small>This line of text is meant to be treated as fine print.</small></p>
	<p><strong>This line rendered as bold text.</strong></p>
	<p><em>This line rendered as italicized text.</em></p>
</div>

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

Lists are commonly used to present and organize collections of related information or items in a structured and easily
scannable format. Lists provide a clear visual representation of content and allow users to navigate through the items
efficiently.

<div class="docs-example">
	<ul>
		<li>Use Armelv5 for all 32-bit armel systems</li>
		<li>Use Armhfv6 for all armhf systems with v6+ architecture</li>
		<li>Use Arm64 for all v8 64-bit architectures</li>
	</ul>
	<ol>
		<li>Use Armelv5 for all 32-bit armel systems</li>
		<li>Use Armhfv6 for all armhf systems with v6+ architecture</li>
		<li>Use Arm64 for all v8 64-bit architectures</li>
	</ol>
</div>

```html
<ul>
	<li>Use Armelv5 for all 32-bit armel systems</li>
	<li>Use Armhfv6 for all armhf systems with v6+ architecture</li>
	<li>Use Arm64 for all v8 64-bit architectures</li>
</ul>

<ol>
	<li>Use Armelv5 for all 32-bit armel systems</li>
	<li>Use Armhfv6 for all armhf systems with v6+ architecture</li>
	<li>Use Arm64 for all v8 64-bit architectures</li>
</ol>
```

## Tables

Tables are used to present structured data in a tabular format, allowing users to view and compare information in a
systematic and organized manner. Tables provide a grid-like layout consisting of rows and columns, with each cell
containing specific data.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Colors

Colors enhance the user experience and communicate information effectively. They are available for both backgrounds
(`cn-bg-*`) and foregrounds (`cn-fg-*`).

### Backgrounds

<div class="docs-example text-center">
	<div style="padding:5px;" class="cn-bg-pink">cn-bg-pink</div>
	<div style="padding:5px;" class="cn-bg-berry">cn-bg-berry</div>
	<div style="padding:5px;" class="cn-bg-light-blue">cn-bg-light-blue</div>
	<div style="padding:5px;" class="cn-bg-teal">cn-bg-teal</div>
	<div style="padding:5px;" class="cn-bg-green">cn-bg-green</div>
	<div style="padding:5px;" class="cn-bg-deep-dark-blue">cn-bg-deep-dark-blue</div>
	<div style="padding:5px;" class="cn-bg-dark-blue">cn-bg-dark-blue</div>
	<div style="padding:5px;" class="cn-bg-slate">cn-bg-slate</div>
	<div style="padding:5px;" class="cn-bg-white cn-fg-deep-dark-blue">cn-bg-white</div>
</div>

```html
<div class="cn-bg-pink">cn-bg-pink</div>
<div class="cn-bg-berry">cn-bg-berry</div>
<div class="cn-bg-light-blue">cn-bg-light-blue</div>
<div class="cn-bg-teal">cn-bg-teal</div>
<div class="cn-bg-green">cn-bg-green</div>
<div class="cn-bg-deep-dark-blue">cn-bg-deep-dark-blue</div>
<div class="cn-bg-dark-blue">cn-bg-dark-blue</div>
<div class="cn-bg-slate">cn-bg-slate</div>
<div class="cn-bg-white cn-fg-slate">cn-bg-white</div>
```

### Foregrounds

<div class="docs-example text-center">
	<div style="padding:5px;" class="cn-fg-pink">cn-fg-pink</div>
	<div style="padding:5px;" class="cn-fg-berry">cn-fg-berry</div>
	<div style="padding:5px;" class="cn-fg-light-blue">cn-fg-light-blue</div>
	<div style="padding:5px;" class="cn-fg-teal">cn-fg-teal</div>
	<div style="padding:5px;" class="cn-fg-green">cn-fg-green</div>
	<div style="padding:5px;" class="cn-fg-deep-dark-blue cn-bg-white">cn-fg-deep-dark-blue</div>
	<div style="padding:5px;" class="cn-fg-dark-blue cn-bg-white">cn-fg-dark-blue</div>
	<div style="padding:5px;" class="cn-fg-slate">cn-fg-slate</div>
	<div style="padding:5px;" class="cn-fg-white">cn-fg-white</div>
</div>

```html
<div class="cn-fg-pink">cn-fg-pink</div>
<div class="cn-fg-berry">cn-fg-berry</div>
<div class="cn-fg-light-blue">cn-fg-light-blue</div>
<div class="cn-fg-teal">cn-fg-teal</div>
<div class="cn-fg-green">cn-fg-green</div>
<div class="cn-fg-deep-dark-blue cn-bg-white">cn-fg-deep-dark-blue</div>
<div class="cn-fg-dark-blue cn-bg-white">cn-fg-dark-blue</div>
<div class="cn-fg-slate">cn-fg-slate</div>
<div class="cn-fg-white">cn-fg-white</div>
```

<br/>

# Components

<hr/><br/>

## Badge

Badges in UI (User Interface) design are small graphical elements used to convey specific information or highlight
certain characteristics of an element within an interface. Here are some typical uses of badges in UI design:

- Status Indicators
- Notifications and Alerts
- Achievements and Rewards
- Categorization and Tags
- User Roles and Permissions
- Social Proof and Trust

These are just a few common use cases of badges in UI design. The key is to use badges judiciously, ensuring they
provide relevant and meaningful information without overwhelming or cluttering the user interface.

<div class="docs-example">
	<div class="cn-badge cn-bg-pink">Mac OSX</div>
	<div class="cn-badge cn-bg-berry">Windows</div>
	<div class="cn-badge cn-bg-teal">Linux</div>
	<div class="cn-badge cn-bg-slate cn-fg-green">New</div>
</div>

```html
<div class="cn-badge cn-bg-pink">Mac OSX</div>
<div class="cn-badge cn-bg-berry">Windows</div>
<div class="cn-badge cn-bg-teal">Linux</div>
<div class="cn-badge cn-bg-slate cn-fg-green">New</div>
```

### Badge Group

<div class="docs-example">
	<div class="cn-badge-group-left">
		<div><div class="cn-badge cn-bg-pink">Update available</div></div>
		<div><div class="cn-badge cn-bg-berry">AppStore</div></div>
		<div><div class="cn-badge cn-bg-teal">New Cluster</div></div>
	</div>
</div>

```html
<div class="cn-badge-group-left">
	<div><div class="cn-badge cn-bg-pink">Update available</div></div>
	<div><div class="cn-badge cn-bg-berry">AppStore</div></div>
	<div><div class="cn-badge cn-bg-teal">New Cluster</div></div>
</div>
```

<div class="docs-example">
	<div class="cn-badge-group-right">
		<div><div class="cn-badge cn-bg-pink">Update available</div></div>
		<div><div class="cn-badge cn-bg-berry">AppStore</div></div>
		<div><div class="cn-badge cn-bg-teal">New Cluster</div></div>
	</div>
</div>

```html
<div class="cn-badge-group-right">
	<div><div class="cn-badge cn-bg-pink">Update available</div></div>
	<div><div class="cn-badge cn-bg-berry">AppStore</div></div>
	<div><div class="cn-badge cn-bg-teal">New Cluster</div></div>
</div>
```

## Breadcrumb

Breadcrumbs are a navigational element that provides users with a visual representation of their current location
within a hierarchical website or application structure. Breadcrumbs typically appear near the top of a page or screen.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Buttons

Buttons are interactive elements that are widely used to enable user actions and interactions within a digital
interface. They serve as clickable elements that users can interact with to trigger specific functionalities or
navigate through the interface.

<div class="docs-example">
	<div>
		<button class="cn-bg-pink">I'm a button!</button>
		<button>I'm a button!</button>
		<button class="cn-btn-link">I'm a button!</button>
	</div>
	<br/>
	<div>
		<a href="#" class="cn-btn cn-bg-pink">I'm an anchor!</a>
		<a href="#" class="cn-btn">I'm an anchor!</a>
		<a href="#" class="cn-btn cn-btn-link">I'm an anchor!</a>
	</div>
</div>

```html
<button class="cn-bg-pink">I'm a button!</button>
<button>I'm a button!</button>
<button class="cn-btn-link">I'm a button!</button>

<a href="#" class="cn-btn cn-bg-pink">I'm an anchor!</a>
<a href="#" class="cn-btn">I'm an anchor!</a>
<a href="#" class="cn-btn cn-btn-link">I'm an anchor!</a>
```

## Card

Cards are a self-contained and visually distinct containers that are used to present and organize information or
content. They are rectangular or square-shaped elements resembling physical cards, and they typically consist of
various components such as text, images, buttons, icons, and other interactive elements.

<div class="docs-example">
	<div class="cn-card">
		<h3>Card Title</h3>
		<p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
		<hr/><br/>
		<div class="text-center">
			<button>Download .dmg</button>
		</div>
	</div>
</div>

```html
<div class="cn-card">
	<h3>Card Title</h3>
	<p>
		Some quick example text to build on the card title and make up the bulk of the card's content.
	</p>
	<hr />
	<br />
	<div class="text-center">
		<button>Download .dmg</button>
	</div>
</div>
```

## Dropdowns

Also known as drop-down menus or select boxes, dropdowns typically consist of a clickable control or button that, when
activated, reveals a list of options that can be selected.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## List group

List groups are a component used to organize and present related items or content in a structured manner. List groups
typically appear as a vertical or horizontal list with each item contained within a unified group or container. List
groups are useful for displaying collections of information that share a common theme, category, or purpose.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Modal

Modals, also known as modal windows or dialog boxes, are temporary and focused elements that appear on top of the main
interface to capture user attention and request specific actions or information. Modals are typically used for
secondary tasks, notifications, alerts, or to gather user input. They are designed to temporarily suspend the user's
interaction with the underlying interface until the required action or input is provided.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Navbar

Navbars, short for navigation bar, is a common component used to provide users with navigation options and access to
various sections or functionalities of a website or application. The navbar typically appears at the top of the
interface, serving as a horizontal strip or container that contains navigation links, menus, branding elements, and
sometimes additional interactive elements.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Navs and tabs

Tabs are a common navigational element used to organize and present content or functionality in a compact and intuitive
manner. Tabs typically appear as a row or group of clickable labels or tabs, often positioned horizontally or
vertically, allowing users to switch between different sections or views without navigating to a separate page.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Pagination

Pagination indicators are used to provide visual feedback and navigation controls for multi-page content or data sets.
They help users understand the structure of the content and facilitate easy navigation between pages.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Progress

Progress bars are graphical indicators used to visually represent the progress or completion status of a task, process,
or operation. They provide users with real-time feedback about the progress of an action and help manage user
expectations.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```

## Toasts

Toasts are transient and unobtrusive notifications or alerts that appear momentarily on the screen to provide users with
important, time-sensitive information or feedback. Toasts are typically displayed in a small, rectangular container
positioned either at the top or bottom of the interface. They are designed to grab the user's attention without
interrupting the main workflow or requiring immediate action.

<div class="docs-example">
</div>

```html
<!-- TBD -->
```
