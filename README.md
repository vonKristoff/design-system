# threejjjs Design System

CSS Design system built to be used alongside Tailwind.

A layer tier is the core concept: Base, Mid and Top, with vaiants which provide colour ambience to convey design pattern.

| Base | Mid     | Top    |
| ---- | ------- | ------ |
| Zero | Neutral | Accent |
|      | Wash    |        |
| One  | Twist   | Pop    |

This is a monorepo, with two core packages: `www` and `cli`

- FE base app to develop guide UI and CSS layouts
- Bun executable to install or update base styles on FE app

It works by installing the core stylesheets using the Design System to the `./src/styles/` directory.

A special `root.css` file is created that stipulates your colour palette.

As the styles evolve, you can update these base styles using the executable in your FE application where you are using this system.

## Usage

At root of project, in terminal: `bunx @threejjs/design-system`

### `www` FE Design System

> start: `bun run dev:www`

When **developing**: use `bun sync:styles` to update the stylesheets to the cli application.

### `cli` Install CSS template styles

> develop locally: `bun run dev:cli`

### Publishing cli

🚨 because Bun has some workspace issues, best practice pre publish is to `cd cli` and `npm version patch` followed by `bun publish`

**nb.** dont forget to be logged into npm, and have a working token with 2fa bypassed in order to enable publishing.
