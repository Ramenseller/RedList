[![GitHub license](https://img.shields.io/badge/licence-MIT-blue.svg
)](https://github.com/Ramenseller/RedList/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/Ramenseller/RedList.svg?branch=master)](https://travis-ci.org/Ramenseller/RedList)

* This is README file for B-4

# RedList
A simple schedule managing program made with python

## Getting Started
### Installation
```
pip3 install redlist
```

### Tutorial
1. Want to add your schedule? Press 'a'
   - What? : enter a name of schedule
   - Due? : enter a due date of your schedule. Please enter with correct form (ex 2018-05-29 23:59:59)
   - Importance? : enter a importance of your schedule
   - Category? : enter a category of your schedule

2. Want to see your schedule list? Press 'l'
   - '*due*' will show you the list in less time left order.
   - '*what*' will show you the list in alphabetical order.
   - '*importance*' will show you more important thing first.
   - '*category*' will show you the lists that have a category you choose.

3. Want to modify your schedule? Press 'm'
   - Enter 'what' you want to change.
   - same with 'add to do'.

4. Want to delete your schedule? Press 'd'
   - Enter 'what' you want to delete

5. Want to know what category is in list? Press 'c'

### Using args
Usage :
```
redlist [options]
```

Options :
```
--version
```
show program's version number and exit
```
-h
--help
```
show this help message and exit
```
-a [what] [due(yyyy-mm-dd hh:mm:ss)]
```
add a new todo
```
-l what || due || importance || category [category]
```
list todos by option
```
-m [org_what] [what] [due(yyyy-mm-dd hh:mm:ss)] [importance(0~5)] [category] [finishied(y/n)]
```
modify the todo
```
-d [what]
```
delete the todo
```
-c
```
show categories



## Bulit With
- Python


## Contributors
| Participant    | Role      |
|----------------|-----------|
| Moon SeongIn   | PM        |
| Yun SungHo     | Designer  |
| Lee Hayung     | Presenter |
| Nam YunJae     | Developer |
| Lee Gukgon     | Secretary |

## License
