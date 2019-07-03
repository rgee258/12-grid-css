# 12 Grid CSS

In this repository is a small CSS framework for creating a **1200px** wide grid of **12** columns that are **100px** each to contain the contents of a webpage. Included are several default fonts for basic text elements as well.

Setting up this stylesheet was done using guidance from the [960 Grid System](https://960.gs/).

The CSS reset used is provided by [Eric Meyer](https://meyerweb.com/eric/tools/css/reset/).

## Usage

Add this stylesheet to a project and put the content that you would like to use the grid with in a div and add the **container** class.

Each row will contain tags with column classes that total up to 12, using of the **col-#** classes.

When starting a new row make sure to add an empty div with the **empty** class to clear the floats from the previous columns.