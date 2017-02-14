# Mars Mission: Xamarin

## Mission Brief
Your crew on Mars has lost contact with Earth and as a result is lacking some essential functions for the mission. Your team has some satellite phones running Android, but the communcation tablets are running Windows.

Your crew has just found an alien bot on Mars that understands English, but we need an interface to interact with the bot. As we need a tool that works across all the team's devices, we will be building an application in Xamarin.

After establishing a connection, We also need to create a tool that can patch our camera feeds into the Computer Vision API, in order to identify unknown objects.

## Prerequisites
Go through this [install document](https://github.com/jamesleeht/MarsXamarin2/blob/master/INSTALL.md).

## Introduction
Xamarin allows you to write your code base once in C#/.NET and have it deployed across the 3 popular mobile platforms, iOS, Android and Windows Phone.

In this Mars Mission guide, we will learn to build a Xamarin Forms app:

1. [Publishing a bot and getting direct line](https://github.com/jamesleeht/MarsXamarin2/blob/master/MISSION1.md)
2. [Connecting to a bot](https://github.com/jamesleeht/MarsXamarin2/blob/master/MISSION2.md)
3. [Making an interface to interact with the bot](https://github.com/jamesleeht/MarsXamarin2/blob/master/MISSION3.md)

If you've finished the missions, there are some challenges for you to complete to and win some prizes.

1. [Challenge 1: Quality Control](https://github.com/jamesleeht/MarsXamarin2/blob/master/CHALLENGE1.md)
2. [Challenge 2: Identifying Objects](https://github.com/jamesleeht/MarsXamarin2/blob/master/CHALLENGE2.md)

## Starting Point
In this repository there is a blank Xamarin.Forms shared project that has been pre-configured with the right nugets for you.

The main nugets installed in this project are:
- [Bot Connector DirectLine](https://www.nuget.org/packages/Microsoft.Bot.Connector.DirectLine/3.0.0)
- [Rest Client Runtime](https://www.nuget.org/packages/Microsoft.Rest.ClientRuntime/)

These nugets allow us to communicate with the bot using pre-defined methods and classes, without the need for manually writing HTTP calls.

Click on the `MarsBuddyBlank` submodule in this repository to download the starting project. 