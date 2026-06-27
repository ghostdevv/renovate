# Renovate Config

A renovate config based on my preferences, inspired by [danielroe/renovate](https://github.com/danielroe/renovate/).

## Base

For public or important projects.

```json
{
	"$schema": "https://docs.renovatebot.com/renovate-schema.json",
	"extends": ["github>ghostdevv/renovate"]
}
```

## Maintenance

For projects that aren't super active and don't need frequent non-security dependency updates.

```json
{
	"$schema": "https://docs.renovatebot.com/renovate-schema.json",
	"extends": ["github>ghostdevv/renovate:maintenance"]
}
```
