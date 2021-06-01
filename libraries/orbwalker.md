### ignore_target

```lua
orbwalker.ignore_target( index: number ): void
```

Needs to be called from `features` callback. Ignores a target for 1 cheat tick.

### force_target

```lua
orbwalker.force_target( index: number ): void
```

Needs to be called from `features` callback. Forces a target for 1 cheat tick.

### get_target

```lua
orbwalker.get_target( ): number | nil
```

### is_active

```lua
orbwalker.is_active( ): bool
```

### can_reset_aa

```lua
orbwalker.can_reset_aa( ): bool
```

### reset_aa

```lua
orbwalker.reset_aa( ): void
```

### get_last_attack_time

```lua
orbwalker.get_last_attack_time( ): number
```

### get_windup_duration

```lua
orbwalker.get_windup_duration( ): number
```

### get_next_attack_time

```lua
orbwalker.get_next_attack_time( ): number
```