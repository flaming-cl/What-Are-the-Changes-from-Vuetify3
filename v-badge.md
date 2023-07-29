## Docs
- Vuetify 2 Doc: https://v2.vuetifyjs.com/en/api/v-badge
- Vuetify 3 Doc: https://vuetifyjs.com/en/api/v-badge

## Emojis
❌ removed
🆕 Added
✍️ Changed

## Props
| Prop | Vuetify 2 | Vuetify 3 | Changes |
| ---- | --------- | --------- | ------- |
| avatar | boolean (default: false) | - | ❌ Removed |
| bottom | boolean (default: false) | - | ❌ Removed |
| dark | boolean (default: false) | - | ❌ Removed |
| light | boolean (default: false) | - | ❌ Removed |
| mode | string (default: undefined) | - | ❌ Removed |
| origin | string (default: undefined) | - | ❌ Removed |
| tile | boolean (default: false) | - | ❌ Removed |
| overlap | boolean (default: false) | - | ❌ Renamed to `floating` |
| value | any (default: true) | - | ❌ Replaced by `model-value` |
| left | boolean (default: false) | - | ❌ Replaced by `start` |
| floating | - | boolean (default: false) | 🆕 Added |
| location | - | Anchor (default: 'top end') | 🆕 Added |
| model-value | - | boolean (default: true) | 🆕 Added |
| rounded | - | string \| number \| boolean (default: false) | 🆕 Added |
| tag | - | string (default: 'div') | 🆕 Added |
| text-color | - | string (default: undefined) | 🆕 Added |
| theme | - | string (default: undefined) | 🆕 Added |
| color | string (default: 'primary') | string (default: undefined) | ✍️ Default value changed |

## Slots
| Slot | Vuetify 2 | Vuetify 3 | Changes |
| ---- | --------- | --------- | ------- |
| badge | The slot used for the badge’s content | The slot used for the badge’s content | - No change |
| default | The default Vue slot | The default Vue slot | - No change |
