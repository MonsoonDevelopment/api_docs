# Player Util

### `sendMessage(String message)`

Sends a message to the server.

#### Parameters

Message - The message to be sent







### `getSpeed()`

`Returns double`

Gets the current speed of the player





### `getBaseSpeed()`

`Returns double`

Gets the base move speed of the player







### `setSpeed(double speed)`

Sets the player's speed

#### Parameters

speed - The player's speed factor.





### `jump()`

Makes the player jump





### `isOnGround()`

`Returns boolean`

Checks if the player is on the ground.





### `isCollidedHorizontally()`

`Returns boolean`

Checks if the player is collided horizontally.





### `isCollidedVertically()`

`Returns boolean`

Checks if the player is collided vertically.





### `getYaw()`

`Returns float`

Gets the player's yaw







### `getPitch()`

`Returns float`

Gets the player's pitch





### `getMotionX()`

`Returns double`

Gets the player's motion X





### `setMotionX(double motion)`

Sets the player's motion X

#### Parameters

motion - The motion X amount





### `getMotionY()`

`Returns double`

Gets the player's motion Y





### `setMotionY(double motion)`

Sets the player's motion Y

#### Parameters

motion - The motion Y amount





### `getMotionZ()`

`Returns double`

Gets the player's motion Z





### `setMotionZ(double motion)`

Sets the player's motion Z

#### Parameters

motion - The motion Y amount



### `getPosX()`

`Returns double`

Gets the player's X





### `getPosY()`

`Returns double`

Gets the player's Y







### `getPosZ()`

`Returns double`

Gets the player's Z







### `setPosition(double x, double y, double z)`

Sets the player's position

#### Parameters

x - The X position

y - The Y position

z - The Z position





### `isFlying()`

`Returns boolean`

Checks whether the player is flying or not



### `setFlying(boolean flying)`

Sets whether the player is flying or not

#### Parameters

flying - Whether the player is flying or not





### `attack(Entity entity)`

Attacks an entity

#### Parameters

entity - The entity to attack





### `getDistanceToEntity(Entity entity)`

`Returns double`

Gets the distance to an entity





### `sendPacket(Packet packet)`

Sends a packet to the server

#### Parameters

packet - The packet to send





### `sendPacketNoEvent(Packet packet)`

Sends a packet to the server without firing PacketEvent

#### Parameters

packet - The packet to send





### `getFallDistance()`

`Returns double`

Gets how far the player has fallen





### `setFallDistance(float distance)`

Sets how far the player has fallen

#### Parameters

distance - How far the player has fallen





### `isMoving()`

`Returns boolean`

Checks whether the player is moving or not
