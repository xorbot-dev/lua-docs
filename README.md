# getting started

## Registering a callback

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| callback\_name | string | + |
| callback | function | + |

```lua
register_callback( callback_name: string, callback: function ): bool

-- usage example
register_callback( "draw", function( )
    render.circle( vec2:new( 50, 50 ), color:new( 255, 255, 255, 255 ), 25 )
end )
```

### Available callbacks

* `draw`– this gets called every frame
* `features` – this gets called in the features loop before the actual features call
* `pre_orbwalker` - this gets called before orbwalker
* `post_orbwalker` - this gets called after orbwalker
* `target_switch` - called on orbwalker target switch

## Print

```lua
print( ... )

-- usage example
print( "local: {}", object_manager.get_local( ) )
```

