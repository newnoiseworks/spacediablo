# Approach Notes

#### General high level ideals, tenets, hopes, and dreams.

## Reduce, Reuse, Recycle
- Promote as much replayability and reuse of existing content, e.g.:
  - Incentivize players to replay certain areas for leveling new characters / weapons etc e.g. Warframe
    - Should never have to feel like they're "starting over" as much as "leveling something else up"
    - Building an "x team" of sorts as a play through as opposed to focusing on a single build is an idea here as well
  - DRY code approaches
  - Systems that require fewer character model changes / code changes e.g.:
    - NO ARMOR - no items whose existence would require entire character model updates to accomodate for visuals of armor etc etc
      - not only to reduce having to re-create models for the sake of items, but also to later sell models
      - presents a challenge with the loot reward system
  - This is an incomplete list

## Play how you want
- Keyboard, mouse, controller support from the get go - diablo style + w0w WASD style
  - Need to ensure high level method wrappers etc etc so no skills / game code touch inputs directly
- Hardcore style level grinding / looting, or lazy style dungeon crawling, whatevs
  - Different servers, good mixing of players
- Modding
  - Sanction safe ways to do this
    - Unity probably has stuff for the client (see Skylines, uses Steam store for distro too)
    - Spatial kind of implies server stuff is totally cool?
- Offline / Online
  - Characters / run throughs would likely have to be completely separate
    - Reconciliation makes any kind of economy tough
  - Needs to have codebase written to universal actions / behaviors, largely (hopefully) a programming architecture problem

## Just the fun parts
- Tight game loops, solid reptitions
  - establish a solid time pattern / goal to achieve a solid rhtyhm to gameplay (missions, combat, leveling, etc)
    - use a tool to track stuff like this for data
    - later use a tool to track stuff in the game (the one we're making)
      - unity analytics
    - some timing patterns for reference:
      - w0w opening pattern: 60-90 seconds, 5 minute, 10 minute mission times
        - move this elsewhere into a general record of game timing loops
  - always be shoving that dopamine
    - loot
    - mission completions
    - achievements
    - components to build loot
    - maybe funny one liners like in comic books but thematically matching the act / area
    - see timing

