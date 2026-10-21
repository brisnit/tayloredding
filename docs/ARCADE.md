# Taylor edding arcade

Eight original games inspired by familiar arcade genres. No licensed game art or ROMs are used.

| Cabinet | Game | Rules |
|---|---|---|
| 01 | Lost Frequencies | Space formations, diving enemies, waves, lives, shields. Hunt unlocks prism shots. |
| 02 | Midnight Maze | Procedurally generated connected maze, collectible notes, three shadows, temporary power notes. |
| 03 | Rooftop Radio | Five roofs, alternating ladders, jumping, descending barrels, antenna goal. |
| 04 | Signal Snake | Grid movement, growing tail, notes, accelerating speed, wall/self collisions. |
| 05 | Prism Break | Paddle/ball physics, five rows of colored bricks, three lives, clear-board victory. |
| 06 | Echo Pairs | Sixteen cards, eight pairs, turn count, mismatch delay, completion bonus. |
| 07 | Off the Grid | Eight-tile sliding puzzle. Shuffled through legal moves, guaranteeing solvability. Move-count score. |
| 08 | Quiet Signals | 8x8 minefield with ten mines, safe first reveal and neighbors, flood reveal, flags, 54-safe-cell victory. |

The single Bandcamp console remains mounted when switching games. Game changes stop the previous game loop. Games pause when scrolled away, when the tab is hidden, or when the hunt is opened. Scores save independently by game in localStorage, with a fallback if storage is unavailable. Touch direction controls supplement keyboard input. Puzzles use native buttons and retain keyboard focus after moves.

Local-audio analysis is shared with action-game visuals. Lost Frequencies additionally uses bass energy for shot power and shield charging. Bandcamp uses clearly labeled designed rhythms, not actual beat detection.

Validation: JS syntax; eight unique selections; unique DOM IDs; browser start/switch/pause checks for all four new action games; memory two-card turn; sliding legal move and full 18-move solution/win; minefield safe first reveal and flag placement. Physical-phone interaction and real-song local audio still require device testing.
