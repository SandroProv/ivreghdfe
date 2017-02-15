
Note: for now, reghdfe requires Stata 13 or up (until I add David Roodman's code)


## Installation steps

Ensure ivreg2 is installed:

```
ssc install ivreg2
```

Install ivreg2hdfe (fake name so it doesn't clash)

```
cap ado uninstall ivreg2hdfe
net install ivreg2hdfe, from(https://github.com/sergiocorreia/ivreg2_demo/raw/master/)
```


### Install locally:


```
cap ado uninstall ivreg2hdfe
net install ivreg2hdfe, from(c:\git\ivreg2_demo)
```