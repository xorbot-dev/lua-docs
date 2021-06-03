# config

## dump\_vars

Logs all config variables to the lua debug console.

```lua
-- prints all config vars to lua debug console
config.dump_vars( ): void
```

## get\_value

Get the value of a given config variable.

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| name | string | + |

```lua
config.get_value( name: string ): number | bool | color | nil
```

## set\_value

Set the value for a given config variable.

### Parameters:

| Name | Type | Required |
| :--- | :--- | :--- |
| name | string | + |
| value | number \| bool \| color | + |

```lua
config.set_value( name: string, value: number | bool | color ): bool
```

