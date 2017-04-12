Sublime Text 'Smart' VHDL Package
==================================


General
-----------

The goal of this plugin is to provide IDE-like features for VHDL (similar to my other plugin for SystemVerilog) :


Compare to the basic VHDL plugin it already proposes:

 - a proper symbol definition for easy code navigation
 - Some basic indentation definition
 - A complete set of snippets written by https://github.com/ccornish
 - Tooltip to get signal definition on mouse hover
 - Generate a design hierarchy (list of every sub-block) (available in the command panel)

Future features includes code completion (for record, enum, ...), code alignement, block instantiation, ...


Description
-----------

####Syntax Highlighting:
Syntax highlighting is based on the VHDL bundle for Textmate, with a rework of scope to be aligned with the SystemVerilog plugin and some support of VHDL2008 features

Note: the default color scheme (Monokai) is missing a lot of scope, and might not give the best results.
You can try my personal variation of Sunburst : https://bitbucket.org/Clams/sublimesystemverilog/downloads/Sunburst2.tmTheme


####Code Navigation:

 * Show signal declaration in tooltip or status bar
 * Show hierarchy of a block (all its sub-block and their sub-block)