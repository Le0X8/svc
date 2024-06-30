# `svc` by [Leonard Lesinski](https://leox.dev/)

A useful collection of Svelte components. Tailwind compatible. 

## Installation

```bash
npm i -D @leolesinski/svc
```

## Usage

```svelte
<script lang="ts">
  import { Button } from '@leolesinski/svc';
</script>

<Button fia={0.5}>Click me!</Button> <!-- fades in after 0.5s -->
<Button no-tw={true}>Click me!</Button> <!-- not prestyled -->
```