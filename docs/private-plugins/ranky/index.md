# Ranky Wiki

This is a custom plugin made for [EnlightenCraft](https://www.planetminecraft.com/server/enlightencraft/). Check it out!

Want this plugin? [Read this page.](\help/private)

## Configuration Files

* [`config.yml`](config)
* [`storage.yml`](storage)

## Usage

Use the placeholder `%ranky%` in PlaceholderAPI in your chat formatter or your DiscordSRV config.

The placeholder returns whatever is set in [config#format](config#format).

You can also use `%ranky_UUID%` (replace UUID with a uuid) to fetch a certain player.

## Errors

### (no player attached)

No player and uuid are attached

**Fix:** Add a UUID to the request (see [#usage](#usage))

### (two players attached)

A player and a uuid are attached

**Fix:** Remove the UUID from the request

## Credits

* AstroSquared: Dev & docs
