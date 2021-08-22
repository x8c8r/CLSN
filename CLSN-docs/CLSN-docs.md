# Documentation for `CLSN` 
## Info:

- Uses 1 groups
- Uses 0 colors
- Uses 0 block IDs
- Uses 1 item IDs

- Adds 0 objects
# Exports:
 **Value:** 
```spwn
{init: (length: @number = 0, invis: @group = 1g, lock: @group = 2g, hide: @bool = true, lock: @bool = true) { /* code omitted */ },setup_kill: (spikeGroup: @group, controls: @bool = true) { /* code omitted */ },kill: (spikeGroup: @group) { /* code omitted */ }}
``` 
**Type:** `@dictionary` 

## **init**:

> **Value:** 
>```spwn
>(length: @number = 0, invis: @group = 1g, lock: @group = 2g, hide: @bool = true, lock: @bool = true) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `length` | @number | `0` | The length of the level in seconds |
>| 2 | `invis` | @group | `1g` | The group for invisible objects |
>| 3 | `lock` | @group | `2g` | The group to lock objects to the player |
>| 4 | `hide` | @bool | `true` | Whether to hide the player on level start or not |
>| 5 | `lock` | @bool | `true` | Whether to lock objects to the player or not |
>

## **setup\_kill**:

> **Value:** 
>```spwn
>(spikeGroup: @group, controls: @bool = true) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`spikeGroup`** | @group | | The group of the spike that kills the player |
>| 2 | `controls` | @bool | `true` | Whether you are using 2 player controls or not |
>

## **kill**:

> **Value:** 
>```spwn
>(spikeGroup: @group) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`spikeGroup`** | @group | | The same spike group as setup_kill |
>
