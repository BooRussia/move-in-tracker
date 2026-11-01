# Design

## Color
- background: `#ffffff` (dark: `#000000`)
- foreground: `#111111` (dark: `#f2f2f2`)
- muted: `#6b6b6b` (dark: `#9a9a9a`)
- hairline: `#e5e5e5` (dark: `#262626`)
- accent: `#1f6bff`
- accent-on: `#ffffff`

Neutrals only besides `accent`. No second chromatic color.

Status remaps:
- Buy first, at or below target price, primary action: accent.
- Done: foreground fill on the check, muted strikethrough text.
- Wait for Black Friday, big ticket, overdue: neutral outline tag or foreground text.

## Type
- text: Geist
- mono: Geist Mono (countdown, prices, counts)
- sizes: display 40px / body 15px / meta 13px

## Radius
- family: all-soft
- value: 12
- exception: None

## Space
- base: 4px

## Motion
- duration: 150ms
- easing: ease-out

Used only for disclosure (chevron) and check feedback.
