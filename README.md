### 概要
Unity2018.1.3f1の[VRSample](https://assetstore.unity.com/packages/essentials/tutorial-projects/vr-samples-51519)にOculusGOコントローラーを導入するプロジェクトです。  
Unityのバージョンは2018.1.3f1を使いました。  
[YouTubeに動画を公開しました。](https://youtu.be/QO1EVZvnNMU)

### スクリプトの変更点
- Assets/VRSampleScenes/Scenes/MainMenu.unity
  - [Assets/VRSampleScenes/Scripts/Utils/Reticle.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/6ff10e40da4a37ed92fb5beca7a5334aab272ad3#diff-2ba2b2918b6488304ea0c5f9b0d50cde)
  - [Assets/VRStandardAssets/Scripts/VREyeRaycaster.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/6ff10e40da4a37ed92fb5beca7a5334aab272ad3#diff-7b2a49eb3acda985bd1f7966b4ce5db1)
  
- Assets/VRSampleScenes/Scenes/Flyer.unity
  - [Assets/VRSampleScenes/Scripts/Flyer/FlyerGameController.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/832a038500715b5d96588ad9195215ceee5ac531#diff-f1ccb1ec9f99f6add29b1ff02e705c9e)
  - [Assets/VRSampleScenes/Scripts/Flyer/FlyerMovementController.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/832a038500715b5d96588ad9195215ceee5ac531#diff-d1b8685cd849031c625e705f2a2deafd)
  - [Assets/VRStandardAssets/Scripts/VRDeviceManager.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/832a038500715b5d96588ad9195215ceee5ac531#diff-ef74bbb38842ad9949bf4a3d6ccc7875)
  
- Assets/VRSampleScenes/Scenes/Shooter180.unity
  - [Assets/VRSampleScenes/Scripts/ShootingGallery/ShootingGalleryController.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/ea3d2063b6c5027b9c474a7b1f1fd15bc3512e85#diff-6807d880ffeb4d86345b2fd306bd59eb)
  - [Assets/VRSampleScenes/Scripts/ShootingGallery/ShootingGalleryGun.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/ea3d2063b6c5027b9c474a7b1f1fd15bc3512e85#diff-b903c25a343700f410dfd5a6f9279384)
  
- Backボタンの改良
  - [Assets/VRStandardAssets/Scripts/VRInput.cs](https://github.com/yu1l/UnityVRSampleWithOculusGO/commit/52b8fd66e160240cdacb14e48a5b6441024f7065#diff-9b4cf4dc648ba5122c80432485182f58)

### 参照
[公式ブログ記事](https://developer.oculus.com/blog/adding-gear-vr-controller-support-to-the-unity-vr-samples/)
