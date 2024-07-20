# UnityURPGI
## Dynamic GI
Dynamic is simple in Unity, open 1DynamicGI scene. The following settings are included in this scene

**- 1DynamicGI.lighting**: This light setting opened Realtime Global Illumination, unchecked Baked Global Illumination

**- Reflection Probe in the Scene**: This is a real-time Reflection Prob, all objects opened in a fully metallic setting can receive the reflection.

**- Adaptive Probe Volume in the Scene**: APV can't be used when Global Illumination is opened, because APV bakes baked GI and Direct Light

Only static objects can use Dynamic GI. The light information is baked into a real-time light map, GI will use the map to generate GI in real-time, dynamic objects can only receive Direct Light, and the scene demonstrates how the dynamic objects and static objects looks in the Dynamic GI.