# Rulealize.RuleSet.Minesweeper

Minesweeper on a 9 × 9 board with ten mines, laid after the first cell is opened and never next to it. A [Rulealize](https://github.com/reny-develop/Rulealize) rule set.

| | |
| --- | --- |
| Rule set id | `Rulealize.RuleSet.Minesweeper` |
| Package | [`Rulealize.RuleSet.Minesweeper`](https://www.nuget.org/packages/Rulealize.RuleSet.Minesweeper) |
| Inputs | `tap`, `flags`, `digs` |
| Holds | nothing |
| Draws on | TypeSchema, State, Sequence, Comparison, Logic, Arithmetic, Branch, Binding, Definition, Grid, Graph, Chance |

The document is written by [`tool/minesweeper.mjs`](tool/minesweeper.mjs): its cell list, the graph of which cell touches which and the scrambled order are too long to keep by hand. Edit the script and run it, not the document.

## Opening it

[Rulpane](https://github.com/reny-develop/Rulpane) opens it from the
[Rulealize Registry](https://github.com/reny-develop/Rulealize.Registry) by its identifier and
version: `#r=Rulealize.RuleSet.Minesweeper@1.0.0`.

## License

[Apache-2.0](LICENSE).
