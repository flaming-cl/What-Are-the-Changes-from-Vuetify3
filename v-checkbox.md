## Docs
- Vuetify 2 Doc: https://v2.vuetifyjs.com/en/api/v-checkbox
- Vuetify 3 Doc: https://vuetifyjs.com/en/api/v-checkbox

## Emojis
- ❌ removed
- 🆕 Added
- ✍️ Changed

## Props

| Prop | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| background-color | string (default: undefined) | - | ❌ Renamed to bg-color |
| dark | boolean (default: false) | - | ❌ |
| dense | boolean (default: false) | - | ❌ Combined into density prop |
| error-count | number \| string (default: 1) | - | ❌ |
| input-value | any (default: undefined) | - | ❌ Renamed to model-value |
| light | boolean (default: false) | - | ❌ |
| off-icon | string (default: '$checkboxOff') | - | ❌ Renamed to false-icon |
| on-icon | string (default: '$checkboxOn') | - | ❌ Renamed to true-icon |
| success | boolean (default: false) | - | ❌ |
| success-messages | string \| array (default: []) | - | ❌ |
| validate-on-blur | boolean (default: false) | - | ❌ |
| center-affix | - | boolean (default: true) | 🆕 |
| defaults-target | - | string (default: undefined) | 🆕 |
| density | - | 'default' \| 'comfortable' \| 'compact' (default: 'default') | 🆕 Replaces dense prop |
| direction | - | 'horizontal' \| 'vertical' (default: 'horizontal') | 🆕 |
| focused | - | boolean (default: false) | 🆕 |
| max-errors | - | string \| number (default: 1) | 🆕 |
| model-value | - | any (default: undefined) | 🆕 Replaces input-value prop |
| type | - | string (default: undefined) | 🆕 |
| validate-on | - | 'lazy' \| 'blur' \| 'input' \| 'submit' \| 'blur lazy' \| 'input lazy' \| 'submit lazy' \| 'lazy blur' \| 'lazy input' \| 'lazy submit' (default: undefined) | 🆕 |
| validation-value | - | any (default: undefined) | 🆕 |
| append-icon | string (default: undefined) | string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: undefined) | ✍️ Type changed |
| error-messages | string \| array (default: []) | string \| string[] (default: []) | ✍️ Type changed |
| hide-details | boolean \| string (default: undefined) | boolean \| 'auto' (default: false) | ✍️ Default value changed |
| indeterminate-icon | string (default: '$checkboxIndeterminate') | string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: '$checkboxIndeterminate') | ✍️ Type changed |
| messages | string \| array (default: []) | string \| string[] (default: []) | ✍️ Type changed |
| prepend-icon | string (default: undefined) | string \| (string \| [string, number])[] \| (new () => any) \| FunctionalComponent (default: undefined) | ✍️ Type changed |
| ripple | boolean \| object (default: true) | boolean (default: true) | ✍️ Type changed |
| rules | array (default: []) | ValidationRule[] (default: []) | ✍️ Type changed |
| value-comparator | function (default: null) | (a: any, b: any) => boolean (default: undefined) | ✍️ Default value changed |
| hint | string (default: undefined) | string (default: undefined) | ✍️ Hint is now always displayed when focused |
| label | string (default: undefined) | string (default: undefined) | ✍️ Label is now used for `v-label` or `v-field-label` component |
| value | any (default: undefined) | any (default: undefined) | ✍️ Value is now used when the component is selected in a group, not as input value any more |

## Events

| Event | Vuetify 2 | Vuetify 3 | Change |
| --- | --- | --- | --- |
| change | any | - | ❌ Replaced by update:model-value |
| click | MouseEvent | - | ❌ |
| mousedown | MouseEvent | - | ❌ |
| mouseup | MouseEvent | - | ❌ |
| update:error | boolean | - | ❌ |
| click:append | - | never | 🆕 |
| click:prepend | - | never | 🆕 |
| update:focused | - | [boolean] | [boolean] | 🆕 |
| update:modelValue | - | [boolean] | 🆕 Replaces @input event |

## Slots
| Name | Vuetify 2 Definition | Vuetify 3 Definition | Change |
| --- | --- | --- | --- |
| label | Replaces the default label | The default slot of the v-label or v-field-label component | ✍️ Changed |
| message | - | { message: string } | 🆕 Added |
| details | - | Slot for custom input details to modifying the display of messages | 🆕 Added |
| input | - | The slot used for the default input element | 🆕 Added |

