# Tags

## Legend

`[]` denotes a tag. Any tag can be nested into others.

`.` can be used to enhance the tag name.

## Tags

- `<library-name>` *Where `<library-name>` is the name of some library, e.g., "engine", "cpp_utils", "arc_inventory", etc.*
- `temporary`
- `workaround`
    - `inaccessible_access` *Involves accessing something not intended by the provider. E.g., accessing a private member via template code in c++. This is scary because anything private is fair game to be changed by the providers, without notice and without even deprecated support.*
- `code_modification`
- `duplicate_code`

## Catalog

`[temporary]`

`[workaround.inaccessible_access[engine]]`

`[duplicate_code[engine]]`

`[code_modification[engine]]`

`[code_modification[duplicate_code[engine]]]`
