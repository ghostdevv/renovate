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

## Personal

For personal projects, or those with lower volume updates.

```json
{
	"$schema": "https://docs.renovatebot.com/renovate-schema.json",
	"extends": ["github>ghostdevv/renovate:personal"]
}
```
