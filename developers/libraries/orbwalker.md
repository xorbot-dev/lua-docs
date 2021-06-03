# orbwalker

{% hint style="info" %}
Orbwalker functions can only be called from`features`and`pre_orbwalker`[callbacks](../../#available-callbacks) ****unless stated differently.
{% endhint %}

## ignore\_target

Ignores a target for 1 cheat tick.

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| target\_index | number | + |

```lua
orbwalker.ignore_target( target_index: number ): void
```

## force\_target

Forces a target for 1 cheat tick.

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| target\_index | number | + |

```lua
orbwalker.force_target( target_index: number ): void
```

## get\_target

Can be called from all callbacks.

```lua
orbwalker.get_target( ): number | nil
```

## is\_active

Can be called from all callbacks.

```lua
orbwalker.is_active( ): bool
```

## can\_reset\_aa

Can be called from all callbacks.

```lua
orbwalker.can_reset_aa( ): bool
```

## reset\_aa

```lua
orbwalker.reset_aa( ): void
```

## get\_last\_attack\_time

Can be called from all callbacks.

```lua
orbwalker.get_last_attack_time( ): number
```

## get\_windup\_duration

Can be called from all callbacks.

```lua
orbwalker.get_windup_duration( ): number
```

## get\_next\_attack\_time

Can be called from all callbacks.

```lua
orbwalker.get_next_attack_time( ): number
```

## set\_should\_attack

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| should\_attack | bool | + |

```lua
orbwalker.set_should_attack( should_attack: bool ): void
```

## get\_ignored\_targets

```lua
orbwalker.get_ignored_targets( ): table<number>
```

## get\_forced\_target

```lua
orbwalker.get_forced_target( ): number | nil
```

## is\_targeting\_champion

```lua
orbwalker.is_targeting_champion( ): bool
```

