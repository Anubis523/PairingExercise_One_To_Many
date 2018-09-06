
# Poke`mon Trainer Exercise
***INTRO:*** Hello there! Welcome to the world of pokémon! My name is Oak! People call me the pokémon Prof! This world is inhabited by creatures called pokémon! For some people, pokémon are pets. Others use them for fights. Myself...I study pokémon as a profession.
### Objectives
#### Models/Tables
1. Construct 2 models with a has_many relationship
2. These 2 models should be **Trainer** and **Pokemon** respectively.
3. The Trainer **has_many** Pokemon and Pokemon **belongs_to** a Trainer
4. The Trainer must have the following attributes:
* **name:string**, **league:string**
5. The Pokemon must have these attributes:
* **name:string**, **type:string**, **level:integer**, **trainer_id:integer**

#### Routes/Controllers
1. Pokemon
* **new/edit** form and accompanying routes
* **index** needs to print links to the Trainer's show page with their **name** as the text for the link tag
* **index** needs a link to the pokemon's show page with its **name** as the visible link on the page
* **show** page should include a link to the **index**, the pokemon's **name, type, level, and trainer's name**, the trainer name needs to act as a **link** to the trainer's **show** page
2. Trainer
* **index** should include links to the trainer's individual **show** page w/ the trainer **name** as the link text
* **show** page should include an unordered list with the pokemon's **name** and **type**, the name should serve as a **link** to the pokemon's **show** page

#### Validations
1. Pokemon
* pokemon **type** can only be **%w(Water Fire Earth Ground Fighting Flying Psychic Bug Poison Electric Normal Ghost Grass)**
* pokemon **level** should be between 1 and 100 and should not exceed the max or be below the minimum

2. Trainer
* **name** can't be **empty** and the name should be **unique**
* **league** can't be **empty** either
* each trainer should have at least one starter **pokemon**

## Good Luck!!


