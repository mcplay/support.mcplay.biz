# Getting Started
You can protect your buildings from other players by "claiming" your survival server's land.
Claimed lands refuse to be blocked, destroyed, animals killed, chests opened, etc. by other players.

Claiming a land requires several items. A wooden shovel and a stick. You can make these items yourself. The shovel is used to make and modify the claim and the stick is used to display the claim information.

A tutorial video is available. You can also check it out here.

[How to Claim Land with the Grief Prevention Minecraft Server Plugin - YouTube](https://youtu.be/VDsjXB-BaE0)

# Create a claim
To see if someone else's claim exists on the land you want to claim, hold a wooden stick in your hand and right-click on it towards the block. `Shift+right-click` to view all the claims in the vicinity.

Once you have verified that there are no claims by others, you will need to take the wooden shovel in your hand and right-click on the diagonal of the land you want to protect.

# Resizing Claim
With a wooden shovel, you can change the size of the claim. This is similar to creating a claim.

Initially, use a wooden stick to locate the claim. At this point, you will see the border of the claim and you will know where the corners are.

When you want to resize the claim, `right-click` on the corner you want to move it to. Then `right-click` on the new corner.

# Subdividing Claims
By subdividing claims, you can give players access to only a portion of the claim.

The idea of subdivision is simple. You can create smaller claims within the main claim and give the player permissions within that claim. Once a subdivision claim has been created, it can be granted to a player. The player can be granted privileges in a subdivision claim by using the trust command in the subdivision claim.

To create a subdivision claim, you need to be in subdivision mode. To enter this mode, use the command `/subdivideclaims`. When you are in this mode, you can create a subdivision claim in the same way that you create a claim. Subdivision claims are marked with a white border. To return to normal mode, use the `/basicclaims` command.

# Trusting
You can give various levels of claim authority to other players. Replace `<player>` with `all` to trust all players on the server.
- To give someone access to all of your claims (break, place, access chest, etc): `/trust <player>`
- To give someone access to the chest (Canot build): `/containertrust <player>`
- To gain access to a lever or door (open a door, press a button, etc): `/accessstrust <player>`
- To allow someone to manage a claim (can trust other players): `/permissiontrust <player>`

# Useful Commands
- `/unclaim` - Remove a protection​
- `/claimslist` - List all of your protections
- `/containertrust <player>` - Give someone access to chests in your claim
- `/permissiontrust <player>` - Give someone the ability to trust and untrust others in your claim
- `/accesstrust <player>` -Give someone access to doors and trapdoors in your claim
- `/subdivide` - Create claims within your main claim that you can trust people to
- `/restrictsubclaim` - Sets subclaim NOT to inherit perms from the parent claim
- `/trust <player>` - Allow someone to build and use chests within your claim​
- `/trustlist` - See who is trusted in your claim
- `/untrust <player>` - Remove a player from your protection