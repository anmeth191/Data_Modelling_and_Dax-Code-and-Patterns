Hello! Thanks for stopping by !

Why am I doing this?

The main reason is to build a DAX toolbox.
During my journey with Power BI—especially DAX—I’ve learned that:
-DAX is powerful but notoriously hard to master.
-Most problems already have solid solutions.
-Without understanding the “bolts and gears,” it’s easy to break models or slow them down.

This repository is my centralized starting point for solving time intelligence challenges.
It combines:
-Patterns from the excellent DAX Patterns book (SQLBI)
-Guidance from ChatGPT
-My own experience and explanations

The problem I’m solving
-Time intelligence in DAX can be tricky—especially if you’ve relied on copy-paste formulas from the internet.
-I used to do that too (Still do it but more careful XD !).
-But when requirements changed, my visuals often broke or slowed down.

The DAX Patterns book was a game-changer, but its examples can be dense. My goal here is to translate those concepts into plain language, with:

-Detailed comments
-Step-by-step explanations
-Practical examples

Who is this for?
Anyone who:
-Works with DAX and time intelligence
-Needs to track performance over time
-Wants reliable, battle-tested code as a starting point
-You can copy a base pattern, adapt it, and confidently meet requirements without reinventing the wheel.

Dependencies
These patterns require a Date Table with the SQLBI structure.

M version (my implementation for Dataflows/reusability)
Date Table in M
https://github.com/anmeth191/myMCode/blob/main/Date_Table_M_Code.SemanticModel/definition/tables/Date_Table.tmdl

DAX version (SQLBI battle-tested code)
https://github.com/anmeth191/Dax-Code-and-Patterns/blob/main/Date%20Table/%20Date%20Table%20SQL.BI%20Battle%20Tested%20Code

Both produce the exact same table.

Folder structure
-Custom Time Intelligence
Recreates built-in functions using continuous numeric keys (e.g., Year Month Number, Year Quarter Number) — works well for fiscal calendars.

-Built-in Time Intelligence
Uses standard DAX functions (DATEADD, DATESINPERIOD, etc.) — best for standard calendar dates.

Final note
This is not “my” intellectual property—I’m building on the incredible public work of SQLBI, combined with my own learning process. My value-add is in documenting, translating, and organizing these patterns for practical, real-world use.

If you find an explanation unclear, please reach out and I’ll update it.
Thanks for reading,

Angel Rivera :)

  
