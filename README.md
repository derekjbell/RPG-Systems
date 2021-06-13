# RPG-Systems
 RPG project made with Unity. Learning how to blend different gameplay systems together.

# Current Progress:

- [x] Movement
- Point-and-click movement using mouse
- Navmesh agent used for logic of where static environment objects restrict movement

- [x] Camera
- Fixed camera on character

- [x] Animation
- Animation blend trees for smooth transitions from standing to walking to running
- Idle / Walking / Running / Attacking / Death animations

- [x] Combat
- Animations for punching
- Keyframes to detect hit on enemy and player
- Health system to allow for death of enemies and player
- Player looks at the enemy it's hitting

- [x] Enemy AI
- Attacks player if they come within attack distance
- Patrol-paths for enemies
- Chase distance established to chase player if inside their vision zone
- Suspicion timer if player runs away after aggroing enemy
