# Roll a Ball 

## Description

This is a basic game built on Unity3d for practice purposes.

The game was build using the Unity3d Project Tutorial: http://unity3d.com/learn/tutorials/projects/roll-ball-tutorial
To grasp basic understanding of Game Development, Physics Engine, Collision and more.

## Beginner Mistake

In this tutorial video: http://unity3d.com/learn/tutorials/projects/roll-ball-tutorial/collecting-pick-objects?playlist=17141

Many of you will make a mistake by writing functions or variables in camelCases. One such example is that

``` C#
void onTriggerEnter(Collider other) 
```

but since C# doesn't support camelCases, all the functions should start with Caps like:

```C#
void OnTriggerEnter(Collider other) 
```

## Include

This project has an already build version of the game in the Builds folder. Run the .exe file to launch and test the game.
Note: The game can only run on Windows OS.

## Credits

Credits to Unity3d for such a wonderful tutorial.

Unity3d: http://unity3d.com/

Unity3d Tutorials: http://unity3d.com/learn/tutorials

Roll a Ball Game Series Tutorial: http://unity3d.com/learn/tutorials/projects/roll-ball-tutorial
