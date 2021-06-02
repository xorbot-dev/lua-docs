# input

## send\_attack

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec3 | + |

```lua
input.send_attack( position: vec3 ): void
```

## send\_spell

| Name | Type | Required |
| :--- | :--- | :--- |
| slot | spell\_slot\_t | + |
| position | vec3 | - |

```lua
input.send_spell( slot: spell_slot_t, position: vec3 | nil ): void
```

## is\_key\_down

```lua
input.is_key_down( key_code: key_t ): bool
```

## send\_key\_down

```lua
input.send_key_down( key: key_t ): void
```

## send\_key\_up

```lua
input.send_key_up( key: key_t ): void
```

## set\_cursor\_position

```lua
input.set_cursor_position( position: vec2 ): void
```

## get\_cursor\_position

```lua
input.get_cursor_position( ): vec2
```

