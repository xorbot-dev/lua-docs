# object\_manager

## get\_local

```lua
object_manager.get_local( ): object | nil
```

```lua
-- example usage
local local_object = object_manager.get_local( )

print( local_object )
```

## get\_by\_index

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| index | number | + |

```lua
object_manager.get_by_index( index: number ): object | nil
```

```lua
-- example usage
local object = object_manager.get_by_index( 0 )

print( object )
```

## get\_valid\_objects

Returns a list of all valid objects.

```lua
object_manager.get_valid_objects( ): table<object>
```

```lua
-- example usage
objs = object_manager.get_valid_objects()

for i,v in ipairs(objs) do print(tostring(v:get_index())) end
```

## get\_enemy\_heroes

Returns a list of all valid enemy heroes.

```lua
object_manager.get_enemy_heroes( ): table<object>
```

## get\_enemy\_minions

Returns a list of all valid minions.

```lua
object_manager.get_enemy_minions( ): table<object>
```

## get\_max\_object\_index

```lua
object_manager.get_max_object_index( ): number
```

## get\_by\_flag

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| flag | object\_t | + |

```lua
object_manager.get_by_flag( flag: object_t ): table<object>
```

## get\_ally\_heroes

```lua
object_manager.get_ally_heroes( ): table<object>
```

## get\_ally\_minions

```lua
object_manager.get_ally_minions( ): table<object>
```

