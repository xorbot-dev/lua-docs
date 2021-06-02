# render

Render functions can only be called from `draw` callback

## circle

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec2 | + |
| radius | number | + |
| color | color | + |

```lua
render.circle( position: vec2, radius: number, color: color ): void
```

```lua
-- example usage
render.circle( vec2:new( 100, 100 ), 50, color:new( 255, 255, 255 ) )
```

## filled\_circle

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec2 | + |
| radius | number | + |
| color | color | + |

```lua
render.filled_circle( position, radius, color ): void
```

```lua
-- example usage
render.filled_circle( vec2:new( 100, 100 ), 50, color:new( 255, 255, 255 ) )
```

## text

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec2 | + |
| text | string | + |
| font\_size | number | + |
| color | color | + |

```lua
render.text( position, text, font_size, color ): void
```

```lua
-- example usage
render.text( vec2:new( 100, 100 ), "im a text", 32, color:new( 255, 255, 255 ) )
```

## text\_shadow

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec2 | + |
| text | string | + |
| font\_size | number | + |
| color | color | + |

```lua
render.text_shadow( position, text, font_size, color ): void
```

```lua
-- example usage
render.text_shadow( vec2:new( 100, 100 ), "im a text with shadow", 32, color:new( 255, 255, 255 ) )
```

## line

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| start | vec2 | + |
| end | vec2 | + |
| thickness | number | + |
| color | color | + |

```lua
render.line( start, end, thickness, color ): void
```

```lua
-- example usage
render.line( vec2:new( 100, 100 ), vec2:new( 150, 125 ), 1, color:new( 255, 255, 255 ) )
```

## rect

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| start | vec2 | + |
| end | vec2 | + |
| thickness | number | + |
| color | color | + |

```lua
render.rect( start, end, thickness, color ): void
```

```lua
-- example usage
render.rect( vec2:new( 100, 100 ), vec2:new( 200, 150 ), 1, color:new( 255, 255, 255 ) )
```

## filled\_rect

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| start | vec2 | + |
| end | vec2 | + |
| color | color | + |

```lua
render.filled_rect( start, end, color ): void
```

```lua
-- example usage
render.rect_filled( vec2:new( 100, 100 ), vec2:new( 200, 150 ), color:new( 255, 255, 255 ) )
```

## ellipse

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec2 | + |
| radius\_x | number | + |
| radius\_y | number | + |
| thickness | number | + |
| color | color | + |

```lua
render.ellipse( position, radius_x, radius_y, thickness, color ): void
```

```lua
-- example usage
render.ellipse( vec2:new( 100, 100 ), 50, 25, 1, color:new( 255, 255, 255 ) )
```

## circle\_3d

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| position | vec3 | + |
| radius | number | + |
| color | color | + |

```lua
render.circle_3d( position: vec3, radius: number, color: color ): void
```

## get\_resolution

```lua
render.get_resolution( ): vec2
```

