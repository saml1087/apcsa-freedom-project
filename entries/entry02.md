# Entry 2
##### 12/20/21

Throughout the previous weeks, I've been making progress in my Freedom Project. Just to reiterate what my project is about, I'm using **Unity** to create a **Paperball Physics Game**. In terms of what I've been doing, I've been really repeating three steps that's benefiting my progress with Unity.

1. Watch a Unity Game Tutorial
2. Taking Notes on Syntax
3. Using Notes to Create Game

To further elaborate on these steps, I'll be explaining these steps in detail. First, when I watch a Unity game tutorial on YouTube, it's no longer than 30 minutes. For example, I watched ["Learn C# Scripting for Unity in 15 Minutes (2020)"](https://www.youtube.com/watch?v=9tMvzrqBUP8&t=615s). This leads me to my second step. I'm actively taking notes. Obviously learning a new scripting language will take a lot of absorbing new information. By taking notes, I'm keeping track of things that could _potentially_ be used in my personal game. This transitions me to the third step, which is putting these basic syntax to use in my game. I'm trying to incorporate what I've learned into the game. Obviously, I'm not going to be using every line of code that the video addresses, but I do take note of it so that when I do have to use it, I'll know how to use it.

To demonstrate some of my learning, I'll briefly explained some lines of code that I've learned and how I have implemented them in my game.

```c#
Input.GetKeyDown(KeyCode.Space))
```
The line of code above is just the game detecting whether the user is pressing the space key. It's a basic useful syntax because in my game, when I want to listen for an input for any key, I can simply call that line of code and change the **_KeyCode_** to the necessary key.

```c#
private void OnCollisionEnter(Collision collision) //collision is the object that hits the gameObject
{
	collision.gameObject.tag == “string”
	collision.gameObject  // the collided object
}
```
The block of code above is a more general method that's useful for my game in particular. It's basically a built in method in Unity that listens for any **_collision_** on an item. Because my game deals with shooting a paperball into a bucket, it's quite useful for me to detect a collision from inside the bucket from the paperball. With that method, I can add a point system that increments whenever that condition is met.

```c#
SceneManager.LoadScene(“name”);
```
Lastly, the line of code above deals with the **_Scene Manager_** of Unity. It's a simple yet useful code that helps transition the current camera to another stage or scene. If I wanted multiple levels of my game, (currently I have two as the most viable product) I can call this line of code and transition to the necessary scene.

These were just a few lines of code that I used in my project, but I believe that they were very powerful and useful for my personal game.

In the **Engineering Design Process**, I'm currently **creating a prototype**. I'm not near finishing my game, but I am making progression in learning to create a very basic template where everything works. I have basic physics involved in the game and simple forces that are being generated. Obviously, it doesn't look appealing to the eye yet, but in terms of functionality, it is going well.

Two important skills I've learned is learning **how to learn** and being **organized**. As mentioned earlier, I've found my way of learning using the three step strategy listed above. I feel like I'm making progress with the way I'm learning by both taking notes and trying it hands on. However, with my notes, I feel like I'm also being more organized. Being organized makes it so much easier to efficiently incorporate code into my game. I've been consistently organizing my code in a google doc where I have my code explained which makes it easier for me to process new code.


[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)