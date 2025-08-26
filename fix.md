1. merge comment

merge continuous `//`, `///`, `///|` three kinds comment,
using `///` as the unified documentation comment,
and then run `moon fmt` shell command;

2. fix type documentation comment

replace all '//' regular comments with '///' documentation comments,
and then run `moon fmt` shell command;


2. extract function definition into other files.

MoonBit all files in the same directory would treat as in the same package.
all symbol is visable each other. like golang package.

MoonBit module contains packages, unlike OCaml package contains modules.