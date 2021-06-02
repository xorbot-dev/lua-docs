# input

## send\_attack

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec3 | + |

```lua
input.send_attack( position: vec3 ): void
```

## send\_spell

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| slot | spell\_slot\_t | + |
| position | vec3 | - |

```lua
input.send_spell( slot: spell_slot_t, position: vec3 | nil ): void
```

## is\_key\_down

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| key\_code | key\_t | + |

```lua
input.is_key_down( key_code: key_t ): bool
```

## send\_key\_down

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| key | key\_t | + |

```lua
input.send_key_down( key: key_t ): void
```

## send\_key\_up

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| key | key\_t | + |

```lua
input.send_key_up( key: key_t ): void
```

## set\_cursor\_position

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec2 | + |

```lua
input.set_cursor_position( position: vec2 ): void
```

## get\_cursor\_position

```lua
input.get_cursor_position( ): vec2
```

