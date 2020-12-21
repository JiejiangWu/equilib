# cube2equi

Cubemap to equirectangular transformation

## Usage

```Python


```



- `w_out` and `h_out` must be divisible by 8.
- if `w_out, h_out` is large respect to the input cubemap, it may leave some artifacts

## TODO:

- [x] Implement `numpy`
- [x] Implement `torch`
- [x] -Bug on `torch` where there's a bit of artifacts on the left side when output size is large-
    - This only occurs on `torch` grid sample and not `custom`, therefore a problem with grid sample
