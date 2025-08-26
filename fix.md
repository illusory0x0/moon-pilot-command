1. merge comment

merge continuous `//`, `///`, `///|` three kinds comment,
using `///` as the unified documentation comment,
and then run `moon fmt` shell command;

2. fix type documentation comment

replace all '//' regular comments with '///' documentation comments,
and then run `moon fmt` shell command;