# orbwalker

## ignore\_target

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| target\_index | number | + |

```lua
orbwalker.ignore_target( target_index: number ): void
```

Needs to be called from `features` callback. Ignores a target for 1 cheat tick.

## force\_target

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| target\_index | number | + |

```lua
orbwalker.force_target( target_index: number ): void
```

Needs to be called from `features` callback. Forces a target for 1 cheat tick.

## get\_target

```lua
orbwalker.get_target( ): number | nil
```

## is\_active

```lua
orbwalker.is_active( ): bool
```

## can\_reset\_aa

```lua
orbwalker.can_reset_aa( ): bool
```

## reset\_aa

```lua
orbwalker.reset_aa( ): void
```

## get\_last\_attack\_time

```lua
orbwalker.get_last_attack_time( ): number
```

## get\_windup\_duration

```lua
orbwalker.get_windup_duration( ): number
```

## get\_next\_attack\_time

```lua
orbwalker.get_next_attack_time( ): number
```

## set\_should\_attack

Parameter:

| Name | Type | Required |
| :--- | :--- | :--- |
| should\_attack | bool | + |

```lua
orbwalker.set_should_attack( should_attack: bool ): void
```

