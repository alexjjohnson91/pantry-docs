# Storing Items

In order to keep track of the different items in the pantry, 
we are going to convert everything to consistent units based on the type of item.

``` Java
Enum ItemUnitType {
    MASS,
    VOLUME,
    QUANTITY
}
```

The idea is to accept any unit on the front-end, but be able to convert into a consistent unit on the backend.

