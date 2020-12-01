# Pokemon 
Kita akan membuat CRUD (Create Read Update Delete) terhadap `pokemons.json` dengan menggunakan MVC, argv & OOP!
```
    ==============
    COMMAND LIST : 
    ==============
    node index.js read-all
    node index.js create <name> <level>
    node index.js update <id> <newName> <newLevel>
    node index.js delete <id>
```

<br><br><br> 

## READ 
> node index.js read-all
```js
===============
Pokemon List : 
===============
┌─────────┬────┬───────────┬───────┬──────────────────────────┐
│ (index) │ id │   name    │ level │        ownedDate         │
├─────────┼────┼───────────┼───────┼──────────────────────────┤
│    0    │ 1  │ 'Pikachu' │  12   │ 2020-11-29T15:01:13.942Z │
│    1    │ 2  │ 'Raichu'  │  37   │ 2020-11-29T15:01:13.942Z │
│    2    │ 3  │  'Minun'  │  10   │ 2020-11-29T15:01:13.942Z │
│    3    │ 4  │ 'Plusle'  │  11   │ 2020-11-29T15:01:13.942Z │
└─────────┴────┴───────────┴───────┴──────────────────────────┘
```  
<br><br> 

## CREATE
> node index.js create Lucario 50
```
==============
SUCCESS CREATE
==============
Pokemon "Lucario" has been added with ID 5
```
<br><br>  

## UPDATE
> node index.js update 1 Pikachu 13
```js
SUCCESS UPDATE ID 1
=====================
Pokemon {
  id: 1,
  name: 'Pikachu',
  level: 13,
  ownedDate: 2020-11-29T15:01:13.942Z
}
```  
<br><br>  

## DELETE 
> node index.js delete 5
```
========================================
SUCCESS DELETE 5 (Lucario)
========================================
Total data : 4
```
