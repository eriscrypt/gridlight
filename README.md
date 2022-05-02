# GridLight css framework

Created by a developer for developers. Enjoy!

` yarn add gridlight ` or
` npm install --save gridlight `

Then, just import  `./gridlight/dist/style.min.css`

Or, use cdn

`https://cdn.jsdelivr.net/npm/gridlight@1.1.2/dist/style.min.css`

## Usage

### Layout (flexbox)
#### Containers

```
12 columns

.container - 1140px
.container-fluid - full width
.container-wide - 1800px
```

### Rows & Cols
```
Prefixes:
1. '-sm' - 540px
2. '-md' - 768px
3. '-lg' - 960px
4. '-xl' - 1140px
5. '-xxl' - 1440px

<div class="row">
  <div class="col col-sm-12 col-md-4">Col</div>
  <div class="col col-sm-12 col-md-4">Col</div>
  <div class="col col-sm-12 col-md-4">Col</div>
</div>
```

### Offsets
Offset x = 5px;
#### Paddings
```
.p-#{x} => .p-1, .p-2 ...
```
#### Margins
```
.m-#{x} => .m-1, .m-2 ...

```
#### Gap
```
Offset between cols or in flex box

.gap-#{x} => .gap-1, .gap-2 ...

```

### Display
```
[block, flex, none]

.d-#{value} => .d-flex, .d-block, .d-none

Also support media queries

.d-sm-none, .d-md-block
```

### Directions
```
.flex-col => flex-direction: colums
.flex-row => flex-direction: rows
```

### Backgrounds, Foregrounds
##### Values [50, 100, 200, 300, 400, 500, 600, 700, 800, 900]
.bg-gray-500 for background
.bg-hover-red-500 change hover background

.fr-gray-400 for foreground
.fr--hover-red-400 change hover foreground
- ![#64748b](https://via.placeholder.com/15/64748b/000000?text=+) `slate`
- ![#6b7280](https://via.placeholder.com/15/6b7280/000000?text=+) `gray`
- ![#71717a](https://via.placeholder.com/15/71717a/000000?text=+) `zinc`
- ![#737373](https://via.placeholder.com/15/737373/000000?text=+) `naturale`
- ![#78716c](https://via.placeholder.com/15/78716c/000000?text=+) `stone`
- ![#ef4444](https://via.placeholder.com/15/ef4444/000000?text=+) `red`
- ![#f97316](https://via.placeholder.com/15/f97316/000000?text=+) `orange`
- ![#f59e0b](https://via.placeholder.com/15/f59e0b/000000?text=+) `amber`
- ![#eab308](https://via.placeholder.com/15/eab308/000000?text=+) `yellow`
- ![#84cc16](https://via.placeholder.com/15/84cc16/000000?text=+) `line`
- ![#22c55e](https://via.placeholder.com/15/22c55e/000000?text=+) `green`
- ![#10b981](https://via.placeholder.com/15/10b981/000000?text=+) `emerald`
- ![#14b8a6](https://via.placeholder.com/15/14b8a6/000000?text=+) `teal`
- ![#06b6d4](https://via.placeholder.com/15/06b6d4/000000?text=+) `cyan`
- ![#0ea5e9](https://via.placeholder.com/15/0ea5e9/000000?text=+) `sky`
- ![#3b82f6](https://via.placeholder.com/15/3b82f6/000000?text=+) `blue`
- ![#6366f1](https://via.placeholder.com/15/6366f1/000000?text=+) `indigo`
- ![#8b5cf6](https://via.placeholder.com/15/8b5cf6/000000?text=+) `violet`
- ![#a855f7](https://via.placeholder.com/15/a855f7/000000?text=+) `purple`
- ![#d946ef](https://via.placeholder.com/15/d946ef/000000?text=+) `fuchsia`
- ![#ec4899](https://via.placeholder.com/15/ec4899/000000?text=+) `pink`
- ![#f43f5e](https://via.placeholder.com/15/f43f5e/000000?text=+) `rose`

### Position
#### Values [absolute, relative, fixed]
```
.position-#{value}
.position-absolute
```

### Overflow
#### Values [hidden, auto, scroll]
```
.overflow-#{value}
.overflow-hidden

x and y axis

.overflow-x-auto
```

### Round
#### Values 1-10
```
.rounded-#{value}
.rounded-10

.circle => make cirlce
```

### Width and Height
```
.w-100 => 100% of width
.w-50 => 50% of width

.h-100 => 100% of height
.h-50 => 50% of height
```

### Z-index
#### Values 1-10
```
.z-#{value}
```

### Align
for flex containers
```
.align-center
.align-start
.align-end

.justify-center
.justify-start
.justify-end
.justify-between
.justify-around
```

### Cursors
#### Values [pointer, default]
```
.cursor-#{value}
```

### Opacity
#### Values [1-10]
```
.opacity-#{value}
```

### Point Events
#### Values [all, none]
```
.pe-#{value}
```

### User Select
#### Values [all, none]
```
.us-#{value}
```