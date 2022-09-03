# Module Events

Each module has several events where you can execute code.

`onEnable`

This is called whenever the module is enabled.

`onDisable`

This is called whenever the module is disabled.

`onUpdate`

This is called whenever the player is updated.

`onRender2D`

This is called when the in-game overlay is rendered.

`onPacket`

This is called when a packet is sent or received.



We can utilise these events in the following way:

```lua
onUpdate = function()
    -- Your code here
end
```

A full implementation of this would look like:

```lua
manager:registerModule('test', 'sex', newModule ({
        onUpdate = function()

        end
    })
)
```

This is done the same way for all events.
