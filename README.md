# Discord Team Bot

An automated team assigning bot for Discord

## Project Abstract

Discord has quickly become an application that people use to communicate with others whether it be with their friends, specific communinity and school. Being a CS major, most classes require group/team work to get assignments done. The project I would like to focus on is a Discord bot that can be called via a typed command (ex: !maketeam). This bot will get members of a Discord Server and automatically assign members randomly to a team. The team sizes will also be able to be specified with the corresponding number following the command while being able to control how big the teams can be. After teams are made, the bot should then be able to assign each team a designated text or voice channel. This bot will be able to help students in a class or friends playing a team based game effortlessly and seamlessly create random groups instantly complely removing wasted time and possible confusion of having team captains pick their teams and manually getting everyone in their own group channels. 

![](JohnLee_DiscordTeamBot.png)

## Relevence

This project will tie in different amounts of topics covered in the course such as implementing Object Oriented Design, Test Driven Development, Version Control and Debugging. While working on the past labs and projects, implementing Object Oriented Design will require extensive testing to make sure that the bot will handle the calls and split teams correctly without any errors no matter what input is made and how many members there are in a server. This project will also be creating and using a UML to model how the classes  and objects will flow and work with one another. 

## Conceptual Design

This is an open source project: ![Switchblade](https://github.com/SwitchbladeBot/switchblade/blob/dev/README.md) which is a server management tool for Discord. As the name suggests, this tool includes many other bots from a music player, a math expression solver all the way to a command that shows the weather forecast for a city. This bot will be able to get members in a lobby channel that is queued for team creation and  of the Discord API. The information will be read and then input into functions that will randomly assign teams by moving members to their specified channel. The created channels will be discarded if all members leave it thus not building up useless channels eveytime a team is created. 

## Required Resources

Python, Discord, Javascript, Git, Laptop/PC
