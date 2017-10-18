---
layout: post
title:  "Introducing Unity3D Open Story"
date:   2017-10-15 00:00:00 +0700
categories: Introduction
---
Unity3D Open Story is a [Unity3D][unity3d] tool and framework that helps the game development process by making it easier to create and manage a story system in Unity3D.

Here is the basic story player that is used for playing an example story:

![story player gif]({{ "/assets/introduction/Player.gif" | absolute_url }})

One can easily modify the story player's looks by changing the image inside the UI component, and arrange it however you like.

In order to play a story, you will need to create a story that can be read first. Creating a story is simplified by using the story creator example scene that is included within the project. This scene is used to create and edit stories that can then be played by the player scene. Use the story creator scene to create stories that you want by using every tool that is available.

After you finish creating the story you can try to play it and to check how the story will be shown. If there is some stuff that bothers you, you can easily change it.

After you are done and sure about how the story will look, you can save the story data into the JSON file format. This JSON format will be used in the story player scene to read the playable story that you have created.

The advantage of using the JSON format is that it is easy to understand and plain text, so you can also edit the JSON through your favorite text editor instead of having using the creator scene if you like.

The current view mode of this project is limited to portrait view for mobile device, but users can make their own prefab and attach it to the script when necessary.

[unity3d]: https://unity3d.com/
[project-github]: https://github.com/as3mbus/Dialogue-and-Story-Unity