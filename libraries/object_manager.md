# object\_manager

## get\_local

```lua
object_manager.get_local( ): object
```

```lua
-- example usage
local local_object = object_manager.get_local( )

print( local_object:is_valid( ) )
```

## get\_by\_index

```lua
object_manager.get_by_index( index: number ): object
```

```lua
-- example usage
local object = object_manager.get_by_index( 0 )

print( object:is_valid( ) )
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

## get\_valid\_enemy\_heroes

Returns a list of all valid enemy heroes.

```lua
object_manager.get_valid_enemy_heroes( ): table<object>
```

## get\_valid\_minions

Returns a list of all valid minions.

```lua
object_manager.get_valid_minions( ): table<object>
```

## get\_max\_objects

```lua
object_manager.get_max_objects( ): number
```

## get\_by\_flag

```lua
object_manager.get_by_flag( flag: object_t ): table<object>
```

