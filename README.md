- This code-along is heavily inspired by my previous more thorough (2d) unity code-along. If you miss some more basic explanations, maybe look there: https://github.com/Powersource/unity-ld-demo
- So yes I'm going to progress a little bit faster than last time, both since many of you were there then and because I have less time now. But a beginner should be able to follow. Please ask if anything is unclear.

- Create a new unity project, make sure it's a 3d project.
- You can move around by right clicking and using wasd/e/q/shift.
- Before we add anything, go to `Edit->Preferences->Colors` and change the Playmode tint. Since unity discards anything we do in playmode, we want to be warned not to make important changes then.

- Move the .blend file into the Assets folder. If you're lucky Unity creates an .fbx file for you, otherwise you have to manually export the model as one.
- Drag the finished model into the scene. Make sure that it doesn't contain unnecessary cameras and lights.

- Create some terrain to run around on, `GameObject->3d Object->Terrain`
- Drag it away a bit to not fall of too easily (don't worry, you can still do that).
- Click on the terrain and click on the fourth button in the inspector under the terrain title, `Paint Texture`. Click `Edit textures->Add texture`, click select in the left box and pick any image, then `Add` in the lower right corner.
- From this menu you can also raise and modify the terrain in many ways. If raising terrain, remember to increase brush size and opacity.

- Unpack the zip file into the Assets folder. You can also get these files and many more if you search for "Standard Assets" in the asset store, but we're on eduroam and that download is very large.