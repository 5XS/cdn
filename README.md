## cdn.vabby.fun

### Remix Icon CDN

[REMIX ICON](https://github.com/Remix-Design/remixicon)

#### Installation CDN
```html
<link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">
```
#### Use

Add icon with class name, class name rule: ri-{name}-{style}

```html
<i class="ri-admin-line"></i>
<i class="ri-admin-fill"></i>
```
> **Note:** We changed the class name prefixes from `remixicon-` to `ri` from v2.0.0;

> **Note:** You can go to [remixicon.com](https://remixicon.com) to check the name of the icons. `-line` means the outlined style icon, and `-fill` means the filled style icon.

#### Sizing

RemixIcon can be resized by css class integrated by `remixicon.css` . Icons inherit the `font-size` of their parent container and with the following classes you can increase or decrease the size of icons relative to that inherited `font-size`. You can also use `ri-fw` class for a fixed width for icons. For example:

```html
<div style="font-size: 24px;">
  <i class="ri-admin-line ri-fw"></i> <!-- fixed width -->
  <i class="ri-admin-line ri-xxs"></i> <!-- 0.5em -->
  <i class="ri-admin-line ri-xs"></i> <!-- 0.75em -->
  <i class="ri-admin-line ri-sm"></i> <!-- 0.875em -->
  <i class="ri-admin-line ri-1x"></i> <!-- 1em -->
  <i class="ri-admin-line ri-lg"></i> <!-- 1.3333em -->
  <i class="ri-admin-line ri-xl"></i> <!-- 1.5em -->
  <i class="ri-admin-line ri-2x"></i> <!-- 2em -->
  <i class="ri-admin-line ri-3x"></i> <!-- 3em -->
  ...
  <i class="ri-admin-line ri-10x"></i> <!-- 10em -->
</div>
```

>  You can  check the [`remixicon.css`](https://github.com/vabbydev/cdn/blob/master/fonts/remixicon.css) file for more info and details.

### SVG Sprite Usage

Download [`remixicon.symbol.svg`](https://cdn.remixicon.com/releases/v2.5.0/remixicon.symbol.svg) file into your project directory，use icons with the `<use>` element, such as:

```html
<svg class='remix'>
  <use xlink:href="your-path/remixicon.symbol.svg#ri-admin-fill"></use>
</svg>
```
```css
.remix {
  width: 24px;
  height: 24px;
  fill: #333;
}
```

> **Note:** `ri-admin-fill` after the `#` in the above example can be replaced with any valid icon name of Remix Icon. You can go to [remixicon.com](https://remixicon.com) to check the name of the icons. `-line` means the outlined style icon, and `-fill` means the filled style icon.
