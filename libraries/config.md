# config

## dump\_vars

Logs the list of all config vars of the script.

```lua
-- prints all config vars to lua debug console
config.dump_vars( ): void
```

## get\_value

```lua
config.get_value( name: string ): number | bool | color | nil
```

## set\_value

```lua
config.set_value( name: string, value: number | bool | color ): bool
```

