# Dungeon-Gameplay-Prototype
This project was built as part of a structured Unreal Engine C++ curriculum to explore interaction systems, lighting, and first-person gameplay mechanics. I focused on implementing object pickup, trigger-based events, and player targeting while debugging and extending base systems provided by the engine.

## Project Focus
Rather than building a content-complete game, this prototype intentionally concentrates on core gameplay systems, including:
- First-person player movement and camera control
- Object targeting and interaction
- Pickup and placement mechanics
- Trigger-based events and state changes
- Environmental lighting used as player feedback

## Gameplay Overview
The player navigates a dungeon environment, identifies an interactive object, and places it in a specific location to trigger environmental changes. Successful placement reveals a hidden room containing a special item.

## Key Systems Implemented
- **Interaction System:** Raycasting-based targeting to detect and interact with objects
- **Pickup & Placement:** Object attachment, detachment, and state validation
- **Trigger Events:** Volume-based triggers to drive environmental changes
- **Lighting Feedback:** Dynamic lighting used to guide player behavior and signal progression
- **Game State Logic:** Simple condition checks to control progression and reveal content

## What I Learned
- How to structure gameplay logic in C++ within Unreal Engine
- Debugging interaction edge cases and collision issues
- Using lighting and environment changes as implicit player feedback
- Scoping projects intentionally to focus on specific systems

## Future Improvements
- Add UI feedback for interaction prompts
- Expand game state handling for additional puzzle steps
- Introduce audio cues to reinforce player feedback
