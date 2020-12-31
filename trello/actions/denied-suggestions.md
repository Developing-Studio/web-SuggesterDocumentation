# Trello Integration Configuration: When a new suggestion is denied (action)

### What is it for?
This subsetting allows you to define if denied suggestions will be removed from the board

### Usage
Use `.config trello actions deny [delete/none]` in any channel the bot can read & send messages in 

### Arguments
You may only choose one:
`delete`: Choosing this element will enable deletion when the suggestion is denied
`none`: Chossing this element will disable it

!> As mentionned [here](https://help.trello.com/article/795-archiving-and-deleting-cards), deleted cards cannot be restored!