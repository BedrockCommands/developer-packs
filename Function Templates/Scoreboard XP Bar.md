### Contributors

- [Zhea Evyline](https://twitter.com/zheaEvyline)

### Table Of Contents

- Description
- Commands
    - Objectives
    - Usage
- Files
    - Editable Files
- Downloads

# Description

This function pack allows you to display players score from a particular objective on their XP bar.

# Commands

## Objectives

- `/function objectives/setup`
    - Add all the objectives to your world required for this pack to function.

## Usage

- `/tag <target> add XPdisplay`
    - XP level of players with this tag will be equal to their score in the objective ` N `
Note; this value cannot exceed `24000`

-  ![repeatingCommandBlock](https://user-images.githubusercontent.com/99989764/234172949-e9c46aa0-ae59-42da-bcc3-0d43cb887f13.png)
`/execute as @a run scoreboard players operation @s N = @s timeLeft`
    - Use this command to apply the scores of your desired objective to the system if you don't want to edit the function file everytime. Here I have used `timeLeft` as an example.

# Files

## Editable Files

- `functions > XPdisplay.mcfunction`
    - If you don't want to use the objective "N", you can edit the name from "N" to any name you want from this file.

# Downloads

- **[Scoreboard XP Bar.mcaddon](https://www.mediafire.com/file/lb0y1tux1pe6dzv/Scoreboard+XP+Bar.mcaddon/file)**
