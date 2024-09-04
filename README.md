```mermaid
classDiagram
    MonoBehaviour <|-- Component
    MonoBehaviour <|-- Behaviour
    Behaviour <|-- Renderer
    Behaviour <|-- Collider
    Behaviour <|-- Animator
    Behaviour <|-- AudioBehaviour
    Behaviour <|-- Camera
    Behaviour <|-- Light  
    Component <|-- Transform
    Component <|-- Rigidbody
    Component <|-- AudioSource
    Component <|-- MeshFilter
    Component <|-- MeshRenderer
    Component <|-- ParticleSystem
    Component <|-- TextMesh
    GameObject *-- Component
    GameObject *-- Transform
    GameObject *-- Layer
    GameObject *-- Tag
    ScriptableObject <|-- AssetBundle
    ScriptableObject <|-- AudioMixer
    ScriptableObject <|-- ShaderVariantCollection
    Object <|-- Component
    Object <|-- GameObject    
    Object <|-- Material
    Object <|-- Shader
    Object <|-- Mesh
    Object <|-- ScriptableObject
    Object <|-- Sprite
    Object <|-- Texture
    Object <|-- AssetImporter
    AssetImporter <|-- ModelImporter
    AssetImporter <|-- TextureImporter
    AssetImporter <|-- AudioImporter
    AssetPostprocessor <|-- ModelImporterAssetPostprocessor
    AssetPostprocessor <|-- TextureImporterAssetPostprocessor
    Editor <|-- AssetImporterEditor
    Editor <|-- EditorWindow
    ScriptableObject <|-- AssetPostprocessor
    ScriptableObject <|-- Editor
    Component --|> UnityEngine
    GameObject --|> UnityEngine
    Object --|> UnityEngine
    Scene --|> SceneManagement
    Application --|> UnityEngine
    Physics --|> UnityEngine
    Time --|> UnityEngine
    Input --|> UnityEngine
    Resources --|> UnityEngine
    Mathf --|> UnityEngine
    Quaternion --|> UnityEngine
    Vector2 --|> UnityEngine
    Vector3 --|> UnityEngine
    AssetPostprocessor --|> UnityEditor
    Editor --|> UnityEditor
    UnityEngine <|-- SceneManagement
    UnityEngine <|-- Animations
    UnityEngine <|-- Audio
    UnityEngine <|-- Physics
    UnityEngine <|-- UI

    click MonoBehaviour href "https://docs.unity3d.com/ScriptReference/MonoBehaviour.html"
    click Behaviour href "https://docs.unity3d.com/ScriptReference/Behaviour.html"
    click Renderer href "https://docs.unity3d.com/ScriptReference/Renderer.html"
    click Collider href "https://docs.unity3d.com/ScriptReference/Collider.html"
    click Animator href "https://docs.unity3d.com/ScriptReference/Animator.html"
    click AudioBehaviour href "https://docs.unity3d.com/ScriptReference/AudioBehaviour.html"
    click Camera href "https://docs.unity3d.com/ScriptReference/Camera.html"
    click Light href "https://docs.unity3d.com/ScriptReference/Light.html"
    click Transform href "https://docs.unity3d.com/ScriptReference/Transform.html"
    click Rigidbody href "https://docs.unity3d.com/ScriptReference/Rigidbody.html"
    click AudioSource href "https://docs.unity3d.com/ScriptReference/AudioSource.html"
    click MeshFilter href "https://docs.unity3d.com/ScriptReference/MeshFilter.html"
    click MeshRenderer href "https://docs.unity3d.com/ScriptReference/MeshRenderer.html"
    click ParticleSystem href "https://docs.unity3d.com/ScriptReference/ParticleSystem.html"
    click TextMesh href "https://docs.unity3d.com/ScriptReference/TextMesh.html"
    click Component href "https://docs.unity3d.com/ScriptReference/Component.html"    
    click GameObject href "https://docs.unity3d.com/ScriptReference/GameObject.html"
    click Layer href "https://docs.unity3d.com/ScriptReference/LayerMask.html"  
    click Tag href "https://docs.unity3d.com/ScriptReference/Tag.html"
    click Material href "https://docs.unity3d.com/ScriptReference/Material.html"
    click Shader href "https://docs.unity3d.com/ScriptReference/Shader.html"  
    click Mesh href "https://docs.unity3d.com/ScriptReference/Mesh.html"
    click ScriptableObject href "https://docs.unity3d.com/ScriptReference/ScriptableObject.html"
    click Sprite href "https://docs.unity3d.com/ScriptReference/Sprite.html"
    click Texture href "https://docs.unity3d.com/ScriptReference/Texture.html"
    click Application href "https://docs.unity3d.com/ScriptReference/Application.html"
    click Time href "https://docs.unity3d.com/ScriptReference/Time.html"
    click Resources href "https://docs.unity3d.com/ScriptReference/Resources.html"
    click Mathf href "https://docs.unity3d.com/ScriptReference/Mathf.html"
    click Quaternion href "https://docs.unity3d.com/ScriptReference/Quaternion.html"
    click Vector2 href "https://docs.unity3d.com/ScriptReference/Vector2.html"
    click Vector3 href "https://docs.unity3d.com/ScriptReference/Vector3.html"
    click AssetImporter href "https://docs.unity3d.com/ScriptReference/AssetImporter.html"
    click ModelImporter href "https://docs.unity3d.com/ScriptReference/ModelImporter.html"
    click TextureImporter href "https://docs.unity3d.com/ScriptReference/TextureImporter.html"
    click AudioImporter href "https://docs.unity3d.com/ScriptReference/AudioImporter.html"
    click AssetBundle href "https://docs.unity3d.com/ScriptReference/AssetBundle.html"
    click AudioMixer href "https://docs.unity3d.com/ScriptReference/Audio.AudioMixer.html"
    click ShaderVariantCollection href "https://docs.unity3d.com/ScriptReference/ShaderVariantCollection.html"
    click AssetPostprocessor href "https://docs.unity3d.com/ScriptReference/AssetPostprocessor.html"
    click ModelImporterAssetPostprocessor href "https://docs.unity3d.com/ScriptReference/ModelImporterAssetPostprocessor.html"
    click TextureImporterAssetPostprocessor href "https://docs.unity3d.com/ScriptReference/TextureImporterAssetPostprocessor.html"
    click Editor href "https://docs.unity3d.com/ScriptReference/Editor.html"
    click EditorWindow href "https://docs.unity3d.com/ScriptReference/EditorWindow.html"
    click AssetImporterEditor href "https://docs.unity3d.com/ScriptReference/AssetImporterEditor.html"
    click UnityEditor href "https://docs.unity3d.com/ScriptReference/UnityEditor.html"    
    click Physics href "https://docs.unity3d.com/ScriptReference/Physics.html"
    click SceneManagement href "https://docs.unity3d.com/ScriptReference/SceneManagement.html"
    click Scene href "https://docs.unity3d.com/ScriptReference/SceneManagement.Scene.html"
    click Animations href "https://docs.unity3d.com/ScriptReference/Animations.html"
    click Audio href "https://docs.unity3d.com/ScriptReference/Audio.html"
    click UI href "https://docs.unity3d.com/ScriptReference/UI.html"
```mermaid
