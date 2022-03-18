---
client: Outlook
version:
platform: PWA
status: Working
contributor: Mark Robbins
---

```css
@media (display-mode: standalone) {
  [class~=""x_foo""]{}
}
```

Outlook PWA supports the same targeting as Outlook.com and Outlook apps. However, its `display-mode` is set to `standalone` so we can target it with the `display-mode` media query.