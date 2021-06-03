# xmath

## world\_to\_screen

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec3 | + |

```lua
xmath.world_to_screen( position: vec3 ): vec2 | nil
```

```lua
-- example usage
local_player = object_manger.get_local( )
screen_pos = xmath.world_to_screen( local_player:get_position( ) )

print( screen_pos )
```

