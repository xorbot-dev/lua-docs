Render functions can only be called from `draw` callback

### circle

```lua
render.circle( position, radius, color ): void
```

```lua
-- example usage
render.circle( vec2:new( 100, 100 ), 50, color:new( 255, 255, 255 ) )
```

### filled_circle

```lua
render.filled_circle( position, radius, color ): void
```

```lua
-- example usage
render.filled_circle( vec2:new( 100, 100 ), 50, color:new( 255, 255, 255 ) )
```

### text

```lua
render.text( position, text, font_size, color ): void
```

```lua
-- example usage
render.text( vec2:new( 100, 100 ), "im a text", 32, color:new( 255, 255, 255 ) )
```

### text_shadow

```lua
render.text_shadow( position, text, font_size, color ): void
```

```lua
-- example usage
render.text_shadow( vec2:new( 100, 100 ), "im a text with shadow", 32, color:new( 255, 255, 255 ) )
```

### line

```lua
render.line( start, end, thickness, color ): void
```

```lua
-- example usage
render.line( vec2:new( 100, 100 ), vec2:new( 150, 125 ), 1, color:new( 255, 255, 255 ) )
```

### rect

```lua
render.rect( start, end, thickness, color ): void
```

```lua
-- example usage
render.rect( vec2:new( 100, 100 ), vec2:new( 200, 150 ), 1, color:new( 255, 255, 255 ) )
```

### filled_rect

```lua
render.filled_rect( start, end, color ): void
```

```lua
-- example usage
render.rect_filled( vec2:new( 100, 100 ), vec2:new( 200, 150 ), color:new( 255, 255, 255 ) )
```

### ellipse

```lua
render.ellipse( position, radius_x, radius_y, thickness, color ): void
```

```lua
-- example usage
render.ellipse( vec2:new( 100, 100 ), 50, 25, 1, color:new( 255, 255, 255 ) )
```

### get_resolution

```lua
render.get_resolution( ): vec2
```

### circle_3d
```lua
render.circle_3d( position: vec3, radius: number, color: color )
```