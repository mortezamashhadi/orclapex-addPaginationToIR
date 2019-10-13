# orclapex-Add Pagination To IR
A Dynamic Action  plug-in for Oracle APEX.  
This Plug-in adds a pagination with "First page,Last Page,Previous Page,Next Page"  links to Interactive Reports.
This  plug-in is inspired by a JavaScript code of  Foad Olyaee https://www.linkedin.com/in/foad-ao/ .

![](https://raw.githubusercontent.com/mortezamashhadi/orclapex-kpi-gauge/master/preview.gif)

## Demo
https://apex.oracle.com/pls/apex/f?p=15676:10

## How to install
1- Download this repository and import the plug-in into your application from this location:

`plugin/dynamic_action_plugin_ir_pagination.sql`

## How to use

1.Set your Interactive Report pagination to **"Row Ranges X to Y of Z"**.
2.a Create a Dynamic Action, on **"page load"**.
2.b Add a true action, and set the action attribute to **"Add pagination to IR"**. 
3.Enjoy it...
