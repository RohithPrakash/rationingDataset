# Rationing Dataset
Food item rationing dataset, follows metric measurement system.
A dataset to help reduce hoarding perishable and non perishable food items during the pandemic.
Dataset is in JSON.

Used in [Ration Calculator](https://rationcalculator.com/ "Ration Calculator")

**Brain Child** of [SkywalkerZ](https://github.com/SkywalkerZ "aka Abraar Nawaz Shaikh")

## Overview

Dataset contains the following food item categories

* vegetables
* fruits
* grains
* meat
* bread
* dairy
* snacks
* beverages
* oil
* spices

## Data Format

```javascript
{
    "name": // name of the food item,
    "quantity": // quantity of the food item(with respect to the measuring unit),
    "unit": // measuring unit,
    "serving": // individuals the quantity of food can be served to
}
```

* Metric measurement system is followed
  * 'Grams' for solid measurements
  * 'Litres' for liquid measurement

* For measurements that do not comply with the above, one could use whatever makes sense for the corresponding fooditem, like
  * 'Slices' for bread
  * 'Whole' for fruits/vegetables that are consumed whole rather by weight
  
## How to Contribute

Feel free to fork it, add categories of food items that you feel should be part of the dataset, add new food items to the dataset and modify already existing data, if you feel it's not accurate.
