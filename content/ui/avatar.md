---
title: Avatar
description: Avatar
alt: Avatar
---

<h3 class="section-header">Preview</h3>

<base-snippet>

  <template v-slot:preview>
    <img class="inline-block rounded-full ring ring-white w-12 h-12"
      src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" />
  </template>

  <!-- snippet -->

  ```html
  <img class="inline-block rounded-full ring ring-white w-12 h-12"
    src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" />
  ```

  <!-- end snippet -->

  <template v-slot:source>
    <a class="btn btn-primary btn-lg" href="https://play.tailwindcss.com/FW6XY91WOp">Live Edit</a>
  </template>

</base-snippet>

<h3 class="section-header">Related</h3>

<div class="flex flex-wrap">
  <card-avatar></card-avatar>
  <card-avatar-stack></card-avatar-stack>
  <card-avatar-initial></card-avatar-initial>
</div>