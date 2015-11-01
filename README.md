# UnityCheetSheet 

# Sound

## Play

```
AudioSource audio = GetComponent<AudioSource>();
audio.play();
```

## Mixer

TODO

# Animations

- [GoKit](http://qiita.com/kamayuki_fs/items/928823800a38a9dbb601)

# Resource

Load image of "Resources/Sprites/background.png".

```
GetComponent<SpriteRenderer>().sprite = Resources.Load<Sprite>("Sprites/background");
```

Instantiate prefab of "Resources/Prefabs/Person.prefab".

```
Instantiate(Resources.Load("Prefabs/Person"), Vector3.zero, Quaternion.identity);
```

