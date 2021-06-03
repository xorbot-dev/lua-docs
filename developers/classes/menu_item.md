# menu\_item

{% hint style="info" %}
If`get_value()`is called for a keybind, it's going to return whether it's active or not.
{% endhint %}

## get\_value

```lua
menu_item:get_value( ): any
```

## set\_callback

Called whenever the value of the menu item changes.

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| callback | function | + |

```lua
menu_item:set_callback( callback: function ): void
```

```lua
-- usage example
local slider = menu.slider_int( "slider", 0, 16 )
slider:set_callback(function(old, new)
    print("old value: {} new value: {}", old, new)
end)
```

