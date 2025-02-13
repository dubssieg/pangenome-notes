---
title: Build a pangenome graph
---
## Specification

The reference GFA format specification can be [found here](http://gfa-spec.github.io/GFA-spec/).

## Conversions

You can use `vg convert -gfW` to convert from GFA 1.1 to 1.0 and `vg convert -gf` to convert from 1.0 to 1.1.

## Tools

It exists many tools to build pangenome graphs.
+ [[minigraph-cactus]] 
+ [[pggb]]
+ minigraph
+ vg
+ pangraph

Each tool uses it's own formats, data structures, and inputs. You may find a flow data-chart here (in construction) to help you find commands and how everything works together.

![[building_flowchart.png]]