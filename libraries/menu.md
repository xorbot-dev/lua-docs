# menu

## checkbox

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| label | string | + |
| default\_value | bool | - |

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

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| label | string | + |
| min | number | + |
| max | number | + |
| default\_value | number | - |

```lua
menu.slider_int( label: string, min: number, max: number, default_value: number ): menu_item
```

```lua
-- example usage
local slider = menu.slider_int( "slider", 0, 5 )

print( slider:get_value( ) )
```

## slider\_float

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| label | string | + |
| min | number | + |
| max | number | + |
| default\_value | number | - |

```lua
menu.slider_float( label: string, min: number, max: number, default_value: number ): menu_item
```

```lua
-- example usage
local slider = menu.slider_float( "slider", 0, 1 )

print( slider:get_value( ) )
```

## dropdown

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| label | string | + |
| options | table&lt;string&gt; | + |

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

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| label | string | + |

```lua
menu.text_input( label: string ): menu_item
```

## help\_marker

```lua
menu.help_marker( label: string ): menu_item
```

## keybind

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| label | string | + |

```lua
menu.keybind( label: string ): menu_item
```

