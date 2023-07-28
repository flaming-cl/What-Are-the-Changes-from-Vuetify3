## Docs
- Vuetify 2 Doc: https://v2.vuetifyjs.com/en/api/v-chip
- Vuetify 3 Doc: https://vuetifyjs.com/en/api/v-chip/

## Emojis
- ❌ removed
- 🆕 Added
- ✍️ Changed

## Props

| Prop | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| active | boolean (default: true) | - | ❌ |
| append | boolean (default: false) | - | ❌ |
| dark | boolean (default: false) | - | ❌ |
| exact-active-class | string | - | ❌ |
| exact-path | boolean (default: false) | - | ❌ |
| nuxt | boolean (default: false) | - | ❌ |
| target | string | - | ❌ |
| text-color | string (default: undefined) | - | ❌ |
| large | boolean (default: false) | size: string \| number (default: 'default') | ✍️ Replaced by `size` |
| small | boolean (default: false) | size: string \| number (default: 'default') | ✍️ Replaced by `size` |
| x-large | boolean (default: false) | size: string \| number (default: 'default') | ✍️ Replaced by `size` |
| x-small | boolean (default: false) | size: string \| number (default: 'default') | ✍️ Replaced by `size` |
| active-class | - | string (default: undefined) | 🆕 |
| append-avatar | - | string (default: undefined) | 🆕 |
| append-icon | - | string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: undefined) | 🆕 |
| border | - | string \| number \| boolean (default: false) | 🆕 |
| density | - | 'default' \| 'comfortable' \| 'compact' (default: 'default') | 🆕 |
| elevation | - | string \| number (default: undefined) | 🆕 |
| prepend-avatar | - | string (default: undefined) | 🆕 |
| prepend-icon | - | string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: undefined) | 🆕 |
| rounded | - | string \| number \| boolean (default: false) | 🆕 |
| selected-class | - | string (default: undefined) | 🆕 |
| text | - | string (default: undefined) | 🆕 |
| theme | - | string (default: undefined) | 🆕 |
| active-class | string | string (default: undefined) | ✍️ Default value changed |
| close | boolean (default: false) | closable: boolean (default: false) | ✍️ Renamed |
| input-value | any (default: undefined) | model-value: boolean (default: true) | ✍️ Renamed and default value changed |
| outlined | boolean (default: false) | variant: 'text' \| 'flat' \| 'elevated' \| 'tonal' \| 'outlined' \| 'plain' (default: 'tonal') | ✍️ Replaced by `variant` |
| ripple | boolean or object (default: undefined) | ripple: boolean or { class: string } (default: true) | ✍️ Default value changed |

## Events

| Event | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| input | boolean | - | ❌ |
| update:active | boolean | - | ❌ |
| clickOnce | - | never | 🆕 |
| group:selected | - | [{ value: boolean }] | 🆕 |
| update:modelValue | - | [boolean] | 🆕 |
| click | MouseEvent | [MouseEvent \| KeyboardEvent] | ✍️ Type changed |
| click:close | void | [MouseEvent] | ✍️ Type changed |

## Slots

| Slot | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| append | - | - | 🆕 |
| close | - | - | 🆕 |
| filter | - | - | 🆕 |
| label | - | - | 🆕 |
| prepend | - | - | 🆕 |
| default | The default Vue slot. | The default Vue slot with additional properties: isSelected, selectedClass, select, toggle, value, disabled | ✍️ Properties added |

