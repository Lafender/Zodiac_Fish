---
date_created: 2025-12-07
time_created: 10:41
tags:
  - question
  - resource
  - data
  - instructions
share: "true"
dir: documentation/structure
---
Original post in [[Airtable_Questions_001 | Airtable Questions]], started in [[2025_12_02|2025_12_02]].
Continued version in [[Airtable_Questions_001 | Airtable Questions Obsidian Markdown note version 1]] on [[2025_12_05|2025_12_05]]

# CSV loading style
I need to create a set of resources for my game. Until I have created all of the resources and set them up with their individual scenes, I will be getting the data from csv files with all of the resource's data set as columns in the csv. I need to be able to change the csv column orders and names as I go without breaking the app, so functions will get values by "name"[id]= row and then by column header rather than column number so it would be 
## CSV loading code preview

```python
const names_header: new String("names")
var names_column_id: int = 0
for value_header in range(0, headers.length() - 1):
	# return column id of "names" column
	return names_id

var row_id: int = 0
for row in range... etc...

var column_id: int = 0
for value_name in range(0, columns.length() - 1)
etc..

# then get the value

var value
for column...
	for row...
		return value
```


# Resource tables list

## Resource table list

| Table                  | Last Edited |
| ---------------------- | ----------- |
| [[#Race tables| > Race tables]]       | 12:17       |
| [[#Skill tables| > Skill tables]]      | 12:18       |
| [[#Job tables| > Job tables]]        | 12:18       |
| [[#Element tables| > Element tables]]    | 12:18       |
| [[#Quest tables| > Quest tables]]      | 12:19       |
| [[#Chest tables| > Chest tables]]      | 12:19       |
| [[#NPC Dialog tables| > NPC Dialog tables]] | 12:20       |
| [[#Economy tables| > Economy tables]]    | 12:20       |
| [[#Experience tables| > Experience tables]] | 12:20       |


## Resource table template



## Resource tables
### Entity tables
#### Race tables
##### Main Race Table

| header              | header | header          | header           |
| ------------------- | ------ | --------------- | ---------------- |
| name                | icon   | walking sprites | fighting sprites |
| starting statistics | world  | element         | jobs             |


#### Skill tables
#### Enemies tables
#### Items tables
##### Recipes tables
##### Ingredients tables
#### Wish and Rage tables
#### Recruitment tables

### Condition tables
#### Statistic tables
#### Job tables

#### Element tables
##### Damage Multipliers
##### Healing Multipliers
##### *χ* effect multiplier
###### Wish and Rage
###### state effect multiplier
###### "*special*" multipliers
##### Statistic based multiplier tables
#### State tables

### World tables

#### Quest tables
##### Bulletin Board Quests
##### Main Quests
#### Map Tables
##### Chest tables
#### NPC Dialog tables
#### Economy tables
#### Experience tables