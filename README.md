## Disable-Locals

A lightweight FiveM thread that blocks all AI peds and vehicles from spawning.

This resource disables population spawning for the default routing bucket (`0`), preventing any ambient AI peds or vehicles from appearing in the server. The behavior is applied automatically when the resource starts and does not require any configuration just a simple drag and drop file.

### How It Works

* Runs a thread when the resource starts
* Disables population spawning for routing bucket `0`
* Prevents all AI peds and vehicles from spawning

### Installation

1. Download or clone this repository
2. Place the folder into your server’s `resources` directory

   * Example: `/resources/disable-locals`
3. (Optional) Rename the folder to something like `populationoff` or `disableai`
4. Add the resource to your `server.cfg`:

```
ensure disable-locals
```

5. Start your server

### Notes

* Affects **AI population only**
* Players are not affected
* Stopping the resource will allow AI to spawn again

### License

MIT
