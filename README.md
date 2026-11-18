# juc-astro

Custom layout and primitive components library for [Astro](https://astro.build), designed to maintain 1:1 parity with the Drupal 11 [juc_sdc](https://github.com/Juc1/juc_sdc) module.

## Overview

This package ports Drupal Single Directory Components (SDC) for layout and typography primitives into native, type-safe `.astro` components. Props and slots defined in Drupal's `*.component.yml` schemas are mapped directly to TypeScript interfaces.

## Components

The following components are targeted for parity with `juc_sdc`:

- `box`: Layout box / container wrapper
- `grid`: CSS grid layout component
- `group`: Container grouping component
- `heading`: Heading element with responsive typography & CVA variant styling
- `icon`: Standalone icon component
- `icon-text`: Paired icon with text label
- `section`: Page section layout wrapper
- `text`: Body typography wrapper
- `wavesurfer`: Audio waveform player

## Installation

```bash
# In your Astro project
npm install github:Juc1/juc-astro
```

Or for local development:

```json
"dependencies": {
  "juc-astro": "file:../juc-astro"
}
```

## License

MIT
