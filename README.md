# RPG Systems
 RPG project made with Unity. Learning how to blend different gameplay systems together.
 
### All models and animations from Synty Studios: 

https://assetstore.unity.com/publishers/5217/?orderBy=1&page=3&pageSize=24&plusPro=false&price=0-4000&rating=0&released=0
 
## Youtube Demo:

https://www.youtube.com/watch?v=dVkArio9CF8



# Current Progress:

- [x] Movement
- Point-and-click movement using mouse
- Navmesh agent used for logic of where static environment objects restrict movement

- [x] Camera
- Utilizing Cinemachine library to initiate follow camera on player
- Multiple virtual cameras added to scene to create intro cinematic
- Cameras are blended and moved between using an animator timeline

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
