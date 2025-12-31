# KickForce
Roblox kickball game with server-authoritative rules, UI feedback, and physics-based ball play.

## Features (Current)
- Auto-rolling pitch when kicker is ready
- 6 innings, 3 outs per inning (teams swap)
- Outs: catch, tag, hit below shoulders
- Runs tracked + announcements + status UI

## Controls
- Left Click: Kick (when up) / Throw (when holding ball)
- E: Pick up ball (fielders near ball)

## How to run
1. Open `place/KickForce.rbxl` in Roblox Studio
2. Press Play (Start Server + 1 Player recommended)

## Remotes required
ReplicatedStorage/Remotes:
- KickRequest (RemoteEvent)
- PickupBall (RemoteEvent)
- ThrowBall (RemoteEvent)
- GameStatus (RemoteEvent)

## Roadmap
- Kick meter + aiming arrow
- Multi-runner support
- Force outs at bases
- Foul/out-of-bounds rules with field boundary
- SFX/VFX polish
