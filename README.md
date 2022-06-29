# Split The Bill

## What

- A single page HTML bill spliter. There's no dynamic server, no other files, no external scripts.
- The URL encodes the entire form, meaning the output is easily shareable as a link.

## How

1. Enter a title, tax, tip
2. Per item fill out:
  - the item
  - the total price
  - how to split
3. Submit
4. Share the link

## Notes

- Splits: one case-insensitive character per "person" you are allocating a cost to. Repeated values are accepted. For example:
  - `XY` splits the price equally between `X` and `Y`
  - `XXYZ` splits 50% to `X`, 25% to `Y`, 25% to `Z`
- Tax and tip are proportionally split
- You can use `<tab>` to switch fields, `<enter>` to submit
