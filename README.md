# LegRaycasters Patch
------------------

This is a utility mod which patches the erroneous `LegRaycasters.FixedUpdate` method in the base game code.

Previously, if players were too small (for instance, if they stacked several Glass Cannon cards) the collision physics for hitting the ground would break. This caused players to accelerate infinitely towards the ground even when they were touching it. This patch fixes that bug.
