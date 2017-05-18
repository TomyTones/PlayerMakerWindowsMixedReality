# [Mixed Reality Add-ons for PlayMaker](http://johnsietsma.com/PlayerMakerWindowsMixedReality/)


Create HoloLens applications without coding. These add-ons for PlayMaker provide actions you can use in your PlayMaker state machines that control and interact with the HoloLens (and other Mixed Reality headsets) from within Unity.

[PlayMaker]("https://www.assetstore.unity3d.com/en/#!/content/368") is required and must be purchased seperately.


## Actions

 * **AttachOrLoadWorldAnchor**: Loads a [WorldAnchor](https://docs.unity3d.com/ScriptReference/VR.WSA.WorldAnchor.html) from the [WorldAnchorStore](https://docs.unity3d.com/ScriptReference/VR.WSA.Persistence.WorldAnchorStore.html) or attaches and saves a new WorldAnchor.
 * **RemoveWorldAnchor**: Removes a [WorldAnchor](https://docs.unity3d.com/ScriptReference/VR.WSA.WorldAnchor.html) from the [WorldAnchorStore](https://docs.unity3d.com/ScriptReference/VR.WSA.Persistence.WorldAnchorStore.html).
 * **CheckForHoloLensGesture**: This state waits till it detects a gesture from the [GestureRecognizer](https://docs.unity3d.com/ScriptReference/VR.WSA.Input.GestureRecognizer.html) and then fires a PlayMaker event to respond to the event.
 * **CheckForHoloLensVoiceCommand**: This state waits till it detects a voice command from the [KeywordRecognizer](https://docs.unity3d.com/ScriptReference/Windows.Speech.KeywordRecognizer.html) and then fires a PlayMaker event to respond to the event.
 * **GazeSelection**: Casts a ray from the headset into the world. Sends enter, exit and stay events for the GameObjects being gazed on.
 * **ShowSpatialMappingRenderer**: Controls the [SpatialMappingRenderer](https://docs.unity3d.com/ScriptReference/VR.WSA.SpatialMappingRenderer.html).



 ## Examples
 
You can find example scenes in the PlayMaker Windows Mixed Reality Examples" folder. Either run in the emulator on the on the device.

  * **AirTap**: Demonstrates how to respond to an AirTap. This exmaple adds a RigidBody to any GameObject being gazed at while air-tapping.
  * **GazeCursor**: Demonstrates how to implement a cursor that follows the gaze.
  * **SpatialRendering**: Demonstrates how to hide and show the spatial renderer. Use an air-tap to toggle visibility.
  * **VoiceCommands**: Demonstrates how to implement voice commands. Say "Make Physical" make all GameObject props non-kinematic and "Reset World" to reset their positions and make them kinematic again.
  
