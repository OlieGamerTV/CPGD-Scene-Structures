# Timeline (TL) Entries
This will list the names of all the TL entries that can be found.

## TLItemRoot
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "TLItemRoot". |
| PlayType | String variable. Must be one of the following: "AUTO" |
| StartTime | Float variable. The start of the timeline. |
| EndTime | Float variable. The end of the timeline. |
| LoopType | String variable. Must be one of the following: "ENDLESS" |

## TLModel
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "TLModel". |
| StartTime | Float variable. The start of the timeline. |
| EndTime | Float variable. The end of the timeline. |
| Filename | String variable. The name of the model file including the extension. |
| EntryDraw | Boolean variable. True if the model is to be rendered. |
| EntryShadow | Boolean variable. True if the model is to cast shadows. |
| EntryMirror | Boolean variable. True if the model is to rendered in reflections. |
| EntryBooleanSrc | Boolean variable. No idea what this does. |
| EntryBooleanDst | Boolean variable. No idea what this does. |
| BufferOption | Boolean variable. No idea what this does. |

## TLCharaAnim
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "TLCharaAnim". |
| StartTime | Float variable. The start of the timeline. |
| EndTime | Float variable. The end of the timeline. |
| LoopType | String variable. Must be one of the following: "ENDLESS" |
