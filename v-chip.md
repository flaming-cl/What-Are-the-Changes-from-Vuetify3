### Vuetify 2 Doc: https://v2.vuetifyjs.com/en/api/v-chip/#links
### Vuetify 3 Doc: https://vuetifyjs.com/en/api/v-chip/
## Props

| Prop | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| active | boolean (default: true) | - | Removed |
| append | boolean (default: false) | - | Removed |
| dark | boolean (default: false) | - | Removed |
| exact-active-class | string | - | Removed |
| exact-path | boolean (default: false) | - | Removed |
| large | boolean (default: false) | - | Removed |
| light | boolean (default: false) | - | Removed |
| nuxt | boolean (default: false) | - | Removed |
| small | boolean (default: false) | - | Removed |
| target | string | - | Removed |
| text-color | string (default: undefined) | - | Removed |
| x-large | boolean (default: false) | - | Removed |
| x-small | boolean (default: false) | - | Removed |
| - | - | active-class: string (default: undefined) | Added |
| - | - | append-avatar: string (default: undefined) | Added |
| - | - | append-icon: string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: undefined) | Added |
| - | - | border: string \| number \| boolean (default: false) | Added |
| - | - | density: 'default' \| 'comfortable' \| 'compact' (default: 'default') | Added |
| - | - | elevation: string \| number (default: undefined) | Added |
| - | - | prepend-avatar: string (default: undefined) | Added |
| - | - | prepend-icon: string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: undefined) | Added |
| - | - | rounded: string \| number \| boolean (default: false) | Added |
| - | - | selected-class: string (default: undefined) | Added |
| - | - | size: string \| number (default: 'default') | Added |
| - | - | text: string (default: undefined) | Added |
| - | - | theme: string (default: undefined) | Added |
| active-class | string | string (default: undefined) | Default value changed |
| close | boolean (default: false) | closable: boolean (default: false) | Renamed |
| input-value | any (default: undefined) | model-value: boolean (default: true) | Renamed and default value changed |
| outlined | boolean (default: false) | variant: 'text' \| 'flat' \| 'elevated' \| 'tonal' \| 'outlined' \| 'plain' (default: 'tonal') | Replaced by variant |
| ripple | boolean or object (default: undefined) | ripple: boolean or { class: string } (default: true) | Default value changed |

## Events

| Event | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| input | boolean | - | Removed |
| update:active | boolean | - | Removed |
| - | - | clickOnce: never | Added |
| - | - | group:selected: [{ value: boolean }] | Added |
| - | - | update:modelValue: [boolean] | Added |
| click | MouseEvent | [MouseEvent \| KeyboardEvent] | Type changed |
| click:close | void | [MouseEvent] | Type changed |

## Slots

| Slot | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| - | - | append | Added |
| - | - | close | Added |
| - | - | filter | Added |
| - | - | label | Added |
| - | - | prepend | Added |
| default | The default Vue slot. | The default Vue slot with additional properties: isSelected, selectedClass, select, toggle, value, disabled | Properties added |
