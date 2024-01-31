# Simple-CTI

## Features
Create incidents, news articles, group, tactics, techniques and correlate them.

## Installation

Add the theme as a hugo module and enable the custom taxonomies to take full advantage of the theme.

```toml
[module]
[[module.imports]]
path = "github.com/CTI-Sweden/Simple-CTI"

[taxonomies]
category = "categories"
tag = "tags"
sector = "sectors"
group = "groups"
tactic = "tactics"
technique = "techniques"
```

## Configuration
Comming soon

## Edit locally

To edit the theme and see the changes locally in realtime you can add an replacement to go.mod

```
replace(
    github.com/CTI-Sweden/Simple-CTI => ../Simple-CTI
)
```
