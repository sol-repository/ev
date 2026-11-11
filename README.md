# ev

`ev` is a Stata module for EViews-style expressions in estimation commands. It lets you write transformations such as `ln(x)`, `d(x)`, `x(-1)`, and `@pch(x)` in the variable list of an estimation command.

Stata 14 or newer is required.

## Install

In Stata, run:

```stata
net install ev, from("https://raw.githubusercontent.com/sol-repository/ev/main/") replace
```

Then type `help ev`.

To install a later update, run the same command. `replace` overwrites the copy already installed.

## Citation

Users who publish results obtained with `ev` are asked to cite:

Yeung, M., and Tao, A. 2026. ev: Stata module for EViews-style expressions in estimation commands.

## Authors

Matthew Yeung and Aaron Tao, School of Open Learning, Hong Kong Metropolitan University (myeung@hkmu.edu.hk).
