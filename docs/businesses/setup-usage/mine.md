# Mines

This is the page regarding mines. This page will show how to set one up, how to produce material, as well as how to sell products, and find a good price.

*All commands here can also be used as slash commands*

#### Mine Description

- Mines are at the base of the production cycle in Disconomy. They produce the raw ingredients that factories use to make more refined items. For example, a mine produces iron, and a factory buys that iron and converts it into steel. 

#### Production

- Since mines produce the raw materials, there isn't an unlimited amount of things you can produce. At this time, you can produce iron, petroleum, coal, or worms. More things that mines can produce are planned to be added in the future.


## Section 1: Creating a Mine

**To create a mine, you need $40,000**

### Mine Commands

- Commands for mines are under 2 command categories, the `e!mine` command category and the `e!business` or `e!biz` command category.

- The reason for this is that all of the commands in the `e!biz` category are commands for all businesses. We will cover some of them on this page.

#### Create Mine Command

The command to create a mine is `e!mine create {name}`. The name for your mine must be between 3 and 25 characters long.

**Once you create your mine, you CAN NOT change the name!**

#### Setting Mine Production

To set what your mine mines, run the `e!mine mine --mine {mine_name} --to_mine {material to produce}`
The materials you can produce are `iron, petroleum, coal, or worms`

Before deciding what to produce, know your competition and what they are selling their materials for. 


## Section 2: Wages

When setting wages, you can set a wage for a person as well as for each position. You can also set it so that anyone can get a job and you don't have to approve them. 

### Setting Wages

The command to set wages is: `e!business edit-wage <target> <new_wage> <business>`
The target parameter may be one of the positions (laborer, staffmanager, supplymanager, or financer), or a specific user that works at your business. In mines, the skill that determines how much you produce is strength. You can update wages due to high skills, but that is up to you. 

If you want your business to show up in the `e!job list` command, you must set a wage for the laborer position so it is not the default wage

### Buisness Configs

You can use the `e!business edit-config` command to set it so that users automatically get a job if they apply for the laborer position. It is recommended to use this command as a slash command.

Ex. `/business edit-config anyone_can_join true YOUR BUSINESS NAME`

## Section 3: Working

When working in mines, strength is the skill that lets you produce more. 
You will see a grid of 9. Your job is to click the correct emoji of what your mine is producing. If you click right, you get paid and produce more of the material than you would if you clicked wrong.

