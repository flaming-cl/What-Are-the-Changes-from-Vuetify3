## Docs
- Vuetify 2 Doc: https://v2.vuetifyjs.com/en/api/v-btn
- Vuetify 3 Doc: https://vuetifyjs.com/en/api/v-btn

## Emojis
- ❌ removed
- 🆕 Added
- ✍️ Changed

## Props

| Prop | Vuetify 2 | Vuetify 3 | Changes |
| ---- | --------- | --------- | ------- |
| append | boolean (default: false) | - | ❌ |
| exact-active-class | string (default: undefined) | - | ❌ |
| exact-path | boolean (default: false) | - | ❌ |
| input-value | any (default: undefined) | - | ❌ |
| link | boolean (default: false) | - | ❌ |
| nuxt | boolean (default: false) | - | ❌ |
| shaped | boolean (default: false) | - | ❌ |
| target | string (default: undefined) | - | ❌ |
| tile | boolean (default: false) | - | ❌ |
| type | string (default: 'button') | - | ❌ |
| fab | boolean (default: false) | - | ❌ |
| dark | boolean (default: false) | - | ❌ Props light / dark have been removed from components. Solution: 1. Use v-theme-provider to set the theme for a specific component tree. Solution 2. Components that previously had a dark prop, such as v-app-bar, now accept theme="dark" prop |
| light | boolean (default: false) | - | ❌ same as dark |
| retain-focus-on-click | boolean (default: false) | - | ❌ Removed, buttons use `:focus-visible` instead |
| fixed | boolean (default: false) | - | ❌ Combined into `position` |
| absolute | boolean (default: false) | - | ❌ Combined into `position` |
| top | boolean (default: false) | - | ❌ Combined into `location` |
| bottom | boolean (default: false) | - | ❌ Combined into `location` |
| outlined | boolean (default: false) | - | ❌ Combined into `variant` |
| plain | boolean (default: false) | - | ❌ Combined into `variant` |
| depressed | boolean (default: false) | - | ❌ Renamed to `variant="flat"` |
| text | boolean (default: false) | - | ❌ Combined into `variant` |
| large | boolean (default: false) | - | ❌ Combined into `size` |
| small | boolean (default: false) | - | ❌ Combined into `size` |
| x-large | boolean (default: false) | - | ❌ Combined into `size` |
| x-small | boolean (default: false) | - | ❌ Combined into `size` |
| left | boolean (default: false) | - | ❌ Replaced by `start` |
| right | boolean (default: false) | - | ❌ Replaced by `end` |
| active-class | - | string (default: undefined) | ❌ Renamed to `selected-class` |
| active (new) | - | boolean (default: false) | 🆕 |
| append-icon (new) | - | string, array, function, FunctionalComponent (default: undefined) | 🆕 |
| border (new) | - | string, number or boolean (default: false) | 🆕 |
| density (new) | - | 'default', 'comfortable', 'compact' (default: 'default') | 🆕 |
| location (new) | - | Anchor (default: undefined) | 🆕 |
| position (new) | - | 'static', 'relative', 'fixed', 'absolute', 'sticky' (default: undefined) | 🆕 |
| prepend-icon (new) | - | string, array, function, FunctionalComponent (default: undefined) | 🆕 |
| selected-class (new) | - | string (default: undefined) | 🆕 |
| size (new) | - | string or number (default: 'default') | 🆕 |
| stacked (new) | - | boolean (default: false) | 🆕 |
| symbol (new) | - | any (default: undefined) | 🆕 |
| text (new) | - | string (default: undefined) | 🆕 |
| theme (new) | - | string (default: undefined) | 🆕 |
| variant (new) | - | 'text', 'flat', 'elevated', 'tonal', 'outlined', 'plain' (default: 'elevated') | 🆕 |
| href | string or object (default: undefined) | string (default: undefined) | ✍️ Type changed to string only |
| icon | boolean (default: false) | boolean, string, array, function, FunctionalComponent (default: false) | ✍️ Type changed, now can accept more types |
| loading | boolean (default: false) | string or boolean (default: false) | ✍️ Type changed, now can accept string |
| ripple | boolean or object (default: undefined) | boolean or { class: string } (default: true) | ✍️ Default value changed to true |
| rounded | boolean (default: false) | string, number or boolean (default: false) | ✍️ Type changed, now can accept string and number |
| to | string or object (default: undefined) | unknown (default: undefined) | ✍️ Type changed to unknown |

## Events

| Event | Vuetify 2 | Vuetify 3 | Changes |
|-------|-----------|-----------|---------|
| click | Emitted when the component is clicked | - | ❌ Removed |
| group:selected | - | Emitted when an item is selected within a group | 🆕 Added |

## Slots

| Slot | Vuetify 2 | Vuetify 3 | Changes |
|------|-----------|-----------|---------|
| loader | - | Slot for custom loader (displayed when loading prop is equal to true) | 🆕 Added |
| append | - | Adds an item inside the input and after input content | 🆕 Added |
| prepend | - | Adds an item outside the input and before input content | 🆕 Added |

