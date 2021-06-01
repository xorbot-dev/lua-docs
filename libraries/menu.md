# menu

## checkbox

```lua
menu.checkbox( label: string, default_value: bool ): menu_item
```

```lua
-- example usage
local checkbox = menu.checkbox( "enable" )

-- prints true or false
print( checkbox:get_value( ) )
```

## label

```lua
menu.label( label: string ): menu_item
```

The `get_value( )` function does not work on menu labels.

## slider\_int

```lua
menu.slider_int( label: string, min: number, max: number, default_value: number ): menu_item
```

```lua
-- example usage
local slider = menu.slider_int( "slider", 0, 5 )

print( slider:get_value( ) )
```

## slider\_float

```lua
menu.slider_float( label: string, min: number, max: number, default_value: number ): menu_item
```

```lua
-- example usage
local slider = menu.slider_float( "slider", 0, 1 )

print( slider:get_value( ) )
```

## dropdown

```lua
menu.dropdown( label: string, options: table<string> ): menu_item
```

```lua
-- example usage
local dropdown = menu.dropdown( "mode", { "first", "second", "third" } )

-- will print 0 when "first" is selected; 1 when "second" is selected, ...
print( dropdown:get_value( ) )
```

## text\_input

```lua
menu.text_input( label: string ): menu_item
```

## help\_marker

```lua
menu.help_marker( label: string ): menu_item
```

## keybind

```lua
menu.keybind( label: string ): menu_item
```

