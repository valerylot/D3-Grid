# Grid Notes

## display: grid
- `display: grid` goes on the parent. Direct children become grid items.
- `grid-template-columns: 1fr 1fr 1fr;` = three equal columns.
- `fr` = fraction, a share of the space that's left.
- Mix units: `200px 1fr 1fr` = one fixed column, two that share the rest.

## repeat()
- `repeat(3, 1fr)` = `1fr 1fr 1fr`.
- First number = how many, second number = what to repeat.

## Row Heights
- `grid-template-row: 150px 150px` = sets two rows height to 150px.
- Rows I didn't list are just as tall as their content
- `grid-auto-row: 150px;` = every row, even the ones grid makes on its own gets set to 150px.

## Spanning
- `grid-columns: span 2;` = take up two columns.
- `grid-row: span 2;` = take up two rows.
- In a grid, we say how many columns or rows, not how many pixels.

## Grid lines
- Grid lines are numbered starting at 1. Three columns = four lines (end column + 1).
- `grid-column: 1 / 3;` = start at line 1, end at line 3.
