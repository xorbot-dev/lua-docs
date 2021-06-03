# object

## constructors

* `object:new( index )`

## get\_health

```lua
object:get_health( ): number
```

## get\_index

```lua
object:get_index( ): number
```

## get\_position

```lua
object:get_position( ): vec3
```

## is\_alive

```lua
object:is_alive( ): bool
```

## is\_valid

```lua
object:is_valid( ): bool
```

## is\_local

```lua
object:is_local( ): bool
```

## get\_attack\_damage

```lua
object:get_attack_damage( ): number
```

## get\_screen\_position

```lua
object:get_screen_position( ): vec2 | nil
```

## is\_enemy

```lua
object:is_enemy( ): bool
```

## get\_spell\_book

```lua
object:get_spell_book( ): spell_book
```

## get\_predicted\_position

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| projectile\_speed | number | + |
| projectile\_range | number | + |
| projectile\_width | number | + |
| cast\_time | number | + |

```text
object:get_predicted_position( projectile_speed, projectile_range, projectile_width, cast_time ): vec3
```

## get\_name

```lua
object:get_name( ): string
```

## get\_current\_gold

```lua
object:get_current_gold( ): number
```

## get\_max\_health

```lua
object:get_max_health( ): number
```

## is\_teammate

```lua
object:is_teammate( ): bool
```

## get\_armor

```lua
object:get_armor( ): number
```

## get\_bonus\_armor

```lua
object:get_bonus_armor( ): number
```

## get\_crit\_chance

```lua
object:get_crit_chance( ): number
```

## get\_level

```lua
object:get_level( ): number
```

## get\_level\_points

```lua
object:get_level_points( ): number
```

## get\_attack\_speed

```lua
object:get_attack_speed( ): number
```

## get\_attack\_range

```lua
object:get_attack_range( ): number
```

## get\_health\_regen

```lua
object:get_health_regen( ): number
```

## get\_movement\_speed

```lua
object:get_movement_speed( ): number
```

## get\_max\_gold

```lua
object:get_max_gold( ): number
```

## is\_recalling

```lua
object:is_recalling( ): bool
```

## get\_buff\_manager

```lua
object:get_buff_manager( ): buff_manager
```

## get\_champ\_name

```lua
object:get_champ_name( ): string
```

## get\_mana

```lua
object:get_mana( ): number
```

## get\_max\_mana

```lua
object:get_max_mana( ): number
```

## get\_ability\_power

```lua
object:get_ability_power( ): number
```

## get\_bonus\_attack\_damage

```lua
object:get_bonus_attack_damage( ): number
```

## get\_base\_attack\_damage

```lua
object:get_base_attack_damage( ): number
```

## get\_magic\_resist

```lua
object:get_magic_resist( ): number
```

