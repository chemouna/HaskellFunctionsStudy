# HaskellFunctionsStudy

## Table of Contents

### Higher order functions
* [`foldl`](#foldl)
* [`scanl`](#scanl)

[⬆ back to top](#table-of-contents)
## Higher order functions

#### foldl

#### scanl

#### ConcatMap 

#### iterate 
iterate f x returns an infinite list of repeated applications of f to x

##### Examples 

1. Pascal Triangle
```haskell
pascal = iterate (\row -> zipWith (+) ([0] ++ row) (row ++ [0])) [1]
```
  
## IO 

### mapM


