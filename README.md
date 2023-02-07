# Web UI Kit Documentation

[Visit the live site](https://hmdshfq.github.io/wuidocs/)
## New Breakpoints

These are the new breakpoints and they can be enabled using the class `grid-container`

| Size | Breakpoint | Max Width |
|:---- |:---------- |:--------- |
| xxs  | 0          |           |
| xs   | 360        | 324       |
| sm   | 576        | 540       |
| md   | 768        | 720       |
| lg   | 992        | 960       |
| xl   | 1200       | 1140      |
| xxl  | 1440       | 1240      |

### Old Breakpoints

| Size | Breakpoint | Max Width |
| ---- | ---------- | --------- |
| xxs  | 0          |           |
| xs   |            |           |
| sm   | 650        |           |
| md   | 1030       |           |
| lg   | 1230       |           |
| xl   | 1480       |           |
| xxl  |            |           |

## Flexbox

Flexbox can be enabled by using the `d-flex` class

### Order

The flexbox children can be ordered using the `order-n` class, where `n` is the number of the order. We can also add breakpoint to enable/disable the order class by `order-breakpoint-n`.  For example, `order-md-1` will make the flexbox child element the first child above `650px`.

## Colors

Each color in the palette has `txt-` and `bg-` suffix. For example, if the text is in `accent-1` color then the text will be given a class of `txt-clr-accent-1`.

### Palette

#### Primaries

![#20B1FD](https://placehold.co/15x15/20B1FD/20B1FD.png) `clr-accent-1`
![#097EB2](https://placehold.co/15x15/097EB2/097EB2.png) `clr-accent-2`
![#173647](https://placehold.co/15x15/173647/173647.png) `clr-accent-4`

#### Neutrals

![#FFFFFF](https://placehold.co/15x15/FFFFFF/FFFFFF.png) `clr-neutral-1`
![#F8FAFB](https://placehold.co/15x15/F8FAFB/F8FAFB.png) `clr-neutral-2`
![#D8DDE4](https://placehold.co/15x15/D8DDE4/D8DDE4.png) `clr-neutral-6`
![#212529](https://placehold.co/15x15/212529/212529.png) `clr-neutral-14`

## Typography

### Font-Weight

Bold - 700: `font-weight-bold`

## Margin and padding

### Scale System

The scale system for margin and padding is as following:

`m-1` where 1 is equal to `0.25rem` or `4px`\*

`m-2` where 2 is equal to `0.5rem` or `8px`

`m-3` where 3 is equal to `1rem` or `16px`

`m-4` where 4 is equal to `1.5rem` or `24px`

`m-5` where 5 is equal to `3rem` or `48px`

`m-6` where 6 is equal to `6rem` or `96px`

`m-7` where 7 is equal to `9rem` or `144px`

\*Considering 1 rem is equal to 16px

`m-1` and `p-1` means margin and padding of `0.25rem` on all four sides

`mx-1` and `px-1` means margin and padding of `0.25rem` on left and right sides

`my-1` and `py-1` means margin and padding of `0.25rem` on top and bottom sides

`mx-auto` means margin equally distributes the available space on the left and right side
