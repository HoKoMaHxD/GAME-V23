# Verification — v2.5.14

701 automated tests passed with Node 24.19.0.

- Slash and text quest aliases send a public launcher with an owner-bound استعراض المهام button and no quest details.
- Button clicks respond ephemerally in the same channel; another member cannot open the owner’s card.
- Private refresh stays private. No DM is sent.
- Saved mute/deafen and minimum people preferences survive attendance-rate migration and restarts.
- Live settings changes exclude/include subsequent voice time in quests, attendance and activity without resetting prior progress.
- Attendance still reaches exactly 4,000 after 7 eligible hours within one Saudi day.

Tests use local fixtures; no live Discord or production MongoDB validation was performed.
