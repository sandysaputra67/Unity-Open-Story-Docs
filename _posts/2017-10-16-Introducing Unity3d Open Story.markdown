---
layout: post
title:  "Introducing Unity3D Open Story"
date:   2017-10-15 00:00:00 +0700
categories: Introduction
---
Unity3D Open Story is a project that aim to create tool, framework or anything related, to helps game development process in creating and managing story system in Unity3D. The current state of this project is only limited to portrait view for mobile device, but u can make your own prefab and attach it to the script.
 
Here is the basic story player that used for playing story. 
![story player gif]({{ "/assets/introduction/Player.gif" | absolute_url }})
you can easily modify the story player looks by changing the image inside the UI component, and arrange it however you like.
![story player gif]({{ "/assets/introduction/Player.gif" | absolute_url }})

In order to play a story we will need a story to be read first. Creating a story is simplified by using story creator scene that included within the project. 

This scene is used to create and edit story that can be called by player scene. Use this scene to create story that you want by using every tool that available.

After you finish creating the story you can try to play it to check how the story will be shown and change it, if there are some stuff that bother you in it. 
After you are done and sure about how the story will look, you can save the story data into a json file format. This json format will be used in story player scene to read the playable story that have been created. 
The advantage of using json format you can also edit the json to make small change that can be applied faster through text editor instead of using the creator scene, and also json format is easier to understand.  
[project-github]: https://github.com/as3mbus/Dialogue-and-Story-Unity