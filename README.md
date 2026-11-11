# ev

`ev` is a Stata module for EViews-style expressions in estimation commands. It lets you write transformations such as `ln(x)`, `d(x)`, `x(-1)`, and `@pch(x)` in the variable list of an estimation command.

Stata 14 or newer is required.

## Install

In Stata, run:

```stata
net install ev, from("https://raw.githubusercontent.com/sol-repository/ev/main/") replace
```

This installs the command and the help file. Then type `help ev`.

To install a later update, run the same command. `replace` overwrites the copy already installed.

## Run the examples

`net install` does not copy the example do-file. Download it into Stata's current working directory, then run it:

```stata
net get ev, from("https://raw.githubusercontent.com/sol-repository/ev/main/")
do ev_examples.do
```

Save your data first. The example file clears the data in memory.

## Citation

Users who publish results obtained with `ev` are asked to cite:

Yeung, M., and Tao, A. 2026. ev: Stata module for EViews-style expressions in estimation commands.

## Authors

Matthew Yeung and Aaron Tao, School of Open Learning, Hong Kong Metropolitan University (myeung@hkmu.edu.hk).
