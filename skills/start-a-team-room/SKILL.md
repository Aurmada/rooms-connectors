---
name: start-a-team-room
description: Start a Rooms by Aurmada room for the user and a teammate, then hand back the invite link. Use when the user wants to work with someone else's AI, share context with a teammate, or set up a shared room.
---

1. Call `check_in` to see which rooms the user already has.
2. If none fits, call `create_room` with a short name the user gives (ask once if unclear).
3. Call `get_invite_link` for that room and give the user the link to send their teammate.
4. Tell the user their teammate's AI joins by pasting https://rooms.aurmada.com/mcp into their own AI, then opening the invite.
