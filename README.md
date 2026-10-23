# MG4
## Devlog
The function of the FloatAnimation script is to make the fish food float up and down continuously. The Start() method sets the initial state required for the animation, including timing-related content, at the beginning of the game. The variable _up is used to determine whether the fish food should move upwards or downwards at the moment. If _up is true, the fish food moves upwards; if it is false, it moves downwards. The Update() method runs in each frame, so the position of the fish food is constantly updated. At the same time, _timer changes over time. When the timing reaches a certain duration, the script will change the state of _up, changing the fish food from moving upwards to moving downwards, or from moving downwards to moving upwards. This process is repeated continuously, creating the effect of the fish food floating up and down.
https://qingw7.itch.io/minigame4
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
