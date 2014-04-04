# Brown University 2048

Each image is changed to something from Brown and the colors are changed to Brown's colors.
Play it [here](http://lccodes.github.io/2048-AI/).
--------------------------------------------------------------------------------------------------------------------------
"AI for the game [2048](https://github.com/gabrielecirulli/2048).

See it in action [here](http://ov3y.github.io/2048-AI/). (Hit the auto-run button to let the AI attempt to solve it by itself)

The algorithm is iterative deepening depth first alpha-beta search. The evaluation function tries to keep the rows and columns monotonic (either all decreasing or increasing) while aligning same-valued tiles and minimizing the number of tiles on the grid. For more detail on how it works, [check out my answer on stackoverflow](http://stackoverflow.com/a/22389702/1056032).

You can tweak the thinking time via global var `animationDelay`. Higher = more time/deeper search.

~~I think there are still some bugs as it tends to make some weird moves and die during the endgame, but in my testing it almost always gets 1024 and usually gets very close to 2048, achieving scores of roughly 8-10k.~~

The better heuristics now give it a success rate of about 90% in my testing (on a reasonably fast computer)."
