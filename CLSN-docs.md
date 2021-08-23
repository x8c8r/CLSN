# Documentation for `CLSN` 
_Generated using `spwn doc [file name]`_
## Info:

- Uses 8 groups
- Uses 2 groups
- Uses 0 colors
- Uses 4 block IDs
- Uses 1 item IDs

- Adds 24 objects
# Exports:
 **Type:** `@dictionary` 

## Macros:

## **init**:

> **Value:** 
>```spwn
>(length: @number, hide: @bool = true, BG_RGB: @array = [0,0,0], GROUND_RGB: @array = [0,0,0], GROUND2_RGB: @array = [0,0,0], LINE_RGB: @array = [0,0,0]) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`length`** | @number | | |
>| 2 | `hide` | @bool | `true` | |
>| 3 | `BG_RGB` | @array | `[0,0,0]` | |
>| 4 | `GROUND_RGB` | @array | `[0,0,0]` | |
>| 5 | `GROUND2_RGB` | @array | `[0,0,0]` | |
>| 6 | `LINE_RGB` | @array | `[0,0,0]` | |
>

## **setup\_kill**:

> **Value:** 
>```spwn
>() { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>

## **kill**:

> **Value:** 
>```spwn
>() { /* code omitted */ }
>``` 
>**Type:** `@macro`
>
## Other values:

## **create**:

> **Type:** `@dictionary` 
>
>## **platformer**:
>
>> **Value:** 
>>```spwn
>>(x_grid: @number, y_grid: @number, color: @array = [255,255,255]) { /* code omitted */ }
>>``` 
>>**Type:** `@macro` 
>>## Arguments:
>>
>>| # | name | type | default value | description |
>>| - | ---- | ---- | ------------- | ----------- |
>>| 1 | **`x_grid`** | @number | | |
>>| 2 | **`y_grid`** | @number | | |
>>| 3 | `color` | @array | `[255,255,255]` | |
>>
>
>## **topdown**:
>
>> **Value:** 
>>```spwn
>>(x_grid: @number, y_grid: @number, continuousMovement: @bool = true, usePlayerCol: @bool = true, color: @array = [255,255,255]) { /* code omitted */ }
>>``` 
>>**Type:** `@macro` 
>>## Arguments:
>>
>>| # | name | type | default value | description |
>>| - | ---- | ---- | ------------- | ----------- |
>>| 1 | **`x_grid`** | @number | | |
>>| 2 | **`y_grid`** | @number | | |
>>| 3 | `continuousMovement` | @bool | `true` | |
>>| 4 | `usePlayerCol` | @bool | `true` | |
>>| 5 | `color` | @array | `[255,255,255]` | |
>>
>
>## **topdown360**:
>
>> **Value:** 
>>```spwn
>>(x_grid: @number, y_grid: @number, color: @array = [255,255,255]) { /* code omitted */ }
>>``` 
>>**Type:** `@macro` 
>>## Arguments:
>>
>>| # | name | type | default value | description |
>>| - | ---- | ---- | ------------- | ----------- |
>>| 1 | **`x_grid`** | @number | | |
>>| 2 | **`y_grid`** | @number | | |
>>| 3 | `color` | @array | `[255,255,255]` | |
>>
>

>`setup_kill needs to be called before kill`
>
## Other values:

## **sprite**:

> **Value:** 
>```spwn
>{circle: (x_grid: @number, y_grid: @number, color: @array = [255,255,255], useGroup: @bool = true) { /* code omitted */ },square: (x_grid: @number, y_grid: @number, Objcol: @array = [255,255,255], useGroup: @bool = true) { /* code omitted */ }}
>``` 
>**Type:** `@dictionary` 
>
>## **circle**:
>
>> **Value:** 
>>```spwn
>>(x_grid: @number, y_grid: @number, color: @array = [255,255,255], useGroup: @bool = true) { /* code omitted */ }
>>``` 
>>**Type:** `@macro` 
>>## Arguments:
>>
>>| # | name | type | default value | description |
>>| - | ---- | ---- | ------------- | ----------- |
>>| 1 | **`x_grid`** | @number | | |
>>| 2 | **`y_grid`** | @number | | |
>>| 3 | `color` | @array | `[255,255,255]` | |
>>| 4 | `useGroup` | @bool | `true` | |
>>
>
>{square: (x_grid: @number, y_grid: @number, Objcol: @array = [0,0,0]) { /* code omitted */ }}
>``` 
>**Type:** `@dictionary` 
>
>## **square**:
>
>> **Value:** 
>>```spwn
>>(x_grid: @number, y_grid: @number, Objcol: @array = [255,255,255], useGroup: @bool = true) { /* code omitted */ }
>>(x_grid: @number, y_grid: @number, Objcol: @array = [0,0,0]) { /* code omitted */ }
>>``` 
>>**Type:** `@macro` 
>>## Arguments:
>>
>>| # | name | type | default value | description |
>>| - | ---- | ---- | ------------- | ----------- |
>>| 1 | **`x_grid`** | @number | | |
>>| 2 | **`y_grid`** | @number | | |
>>| 3 | `Objcol` | @array | `[255,255,255]` | |
>>| 4 | `useGroup` | @bool | `true` | |
>>| 3 | `Objcol` | @array | `[0,0,0]` | |
>>
>
