# Beboki Katowice — Gra Terenowa AR

Location-based outdoor game in Katowice. Players walk to real-world quest locations and unlock Beboki in AR.

## MVP
- GPS-based locations
- Map / quest list
- Proximity unlocks
- Camera AR view
- Bebok character anchored to a real-world location
- Designed for mobile browser, no app install

## AR stack
The first prototype uses AR.js + A-Frame because AR.js supports location-based AR in the browser. LocAR.js is kept as a possible next step for more advanced Three.js positioning.

## Assets
Existing Bebok artwork comes from the project's `beboki-katowice-mis` repository. Initial characters: Hanys, Fachura, Hopla, Podciep.

## Roadmap
1. GPS quest loop
2. Real Bebok 3D GLB assets
3. Better compass/sensor fusion
4. Quest dialogue and minigames
5. Player progress and collection
6. Admin panel for adding locations
7. PWA install + offline cache

## License
Game code: MIT. Character artwork/model rights must be handled separately.
