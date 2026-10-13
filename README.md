# minigame 2
## Devlog
### 1
#### While I writing my code and preparing the WebGL build, I encountered a compiler error: CS0234: The type or namespace name 'GraphView' does not exist in the namespace 'UnityEditor.Experimental'. This occurred because my ColorChange.cs script included using UnityEditor.Experimental.GraphView; at the top. Since UnityEditor namespace elements are editor-only and cannot be included in player builds, Unity stopped the build process.   To resolve this issue, I opened ColorChange.cs and deleted the unused using UnityEditor.Experimental.GraphView; line. Once saved, I cleared the error logs in the Unity Console, and the WebGL build completed successfully without any further errors. 
### 2
#### The period (.): I think the period is used to access a specific property or component inside an object. In this case, I am accessing the color property inside the _spriteRenderer component.
#### The word new: I think the word new is used to create or initialize a brand new instance of an object or data structure—here, I am creating a new Color value with the RGB parameters

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
