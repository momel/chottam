# **D&D console game**
## Table of Contents
**[Goal of project](#goal-of-project)**

**[Git Workflow](#git-workflow)**

## **Goal of project**
The main goal of application it's provide for players and Dungeon Master's (DM's) of Dungeon and Dragon (DnD) tool for creating characters, Non Played Characters (NPC's) quests etc. 
Application consist from two parts: **server** and **client**.

## *Server*
The server it's part of application for connecting and collaboration of cliens against each other.
Server should work by _http_ protocol and get requests by REST standart, it is mean that you shoul use next http methods:
|   Method	    |  Action 	| 
|---	        |---	    |
|   **GET**	    |  Get data of some object 	    |
|   **POST**	|  Add new data into system	    |
|   **PUT**	    |  Update exists data from the system 	    |
|   **DELETE**	|  Delete data from the system 	    |

## *Client*
Client have 4 modules: *Login*, *Player client*, *DM client*, *Batlefield*.

#### Login
This module need for connecting users to server, login users into system.

#### Player client
This module provide possibilities for users with *Player role*, it is mean that user have possibilities like:
- Creating new character;
- Edit his own characters;
- Delete his own characters;
- Save characters on server;
- Roll dices;
- Get quest.
 
#### DM client
This module provide possibilities for users with *DM role*, it is mean that user have possibilities like:
- Creating new NPC;
- Edit his own NPC;
- Delete his own NPC;
- Save NPC on server;
- Roll dices;
- Create new story (list of quests);
- Create Terraine;
- Create Board for story.

## **Technologies**
  - C++ 11
  - MySQL Server
  - Boost

## **Git Workflow**
![Image of gitflow](https://confluence.atlassian.com/download/attachments/337772794/git-workflow-release-cycle-3release.png?version=2&modificationDate=1382587326800&api=v2)

### **Version**
*0.0.1-a*

