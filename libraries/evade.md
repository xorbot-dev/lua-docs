---
description: These functions only work when evade is active.
---

# evade

## is\_position\_safe

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec3 | + |
| bounding\_radius | number | - |

```lua
evade.is_position_safe( position: vec3, bounding_radius: number = 65 ): bool
```

## get\_safe\_position

```lua
evade.get_safe_position( ): vec3 | nil
```

## is\_evading

```lua
evade.is_evading( ): bool
```

## get\_active\_spells

```lua
evade.get_active_spells( ): list<spell>
```

