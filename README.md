# Whatsit Swap

A trading table for weird, random, one-of-a-kind things. Built for Aria.

Live: https://rasjammin.github.io/whatsit-swap/

Two traders, one phone laid flat between them. Tap a thing in your stash to put
it on the table, tap it again to take it back. The two sets of buttons sit at
the outside edges of the table and the stuff being traded goes between them.

Each trader gets three round buttons:

- **Blue circle, plus - Keep playing** - not enough yet, the other trader should
  put more stuff down.
- **Green circle, check - Yes, finish** - I'm happy. When *both* traders tap
  green, the stuff swaps.
- **Red circle, X - Cancel trade** - call the whole thing off, everybody gets
  their stuff back.

## Finding stuff

There is no generic "find stuff" button. There are six **bins**, and you tap the
one you want to dig through:

Cursed - Squishy - Shiny - Gross - Ancient - Boxes

Each bin shows six things to choose from, and every thing is drawn as a little
picture: a cursed teapot has squiggly lines coming off it, shiny things sparkle,
squishy things wobble, gross things drip, ancient things are sepia and cobwebbed.

## Boxes are a scam

Every box - iPhone Box, Treasure Chest, Pizza Box - advertises five stars on the
outside. Tap the **+** badge on a box in your stash to hide any item inside it,
and it seals shut. Nothing about the sealed box reveals what is in there: not the
card, not the table, not the page source.

Trade the box away, and whoever ends up with it taps the **unlock** badge to open
it - and finds out whether they just got a legendary crystal or a one-star
Terrible Tooth. The box empties out and can be re-used for the next scam.

## Playing the robot

Tap the people button in the top bar to swap the other trader for **Robo**. Robo
runs entirely in the browser - no server, no account, no second device.

Robo values a pile by counting stars, always brings something of its own to a
trade, tops up when it is getting the better end, pushes back when it is not,
and walks away after being pushed three times. Tapping the blue **+** at it is a
real ask - it will add another thing, or tell you it has given you plenty.

**Robo believes what a box says on the outside.** The first time, a sealed box is
worth the five stars printed on it, so it will happily overpay. Get burned once
and it starts discounting boxes; by the third time it values them at half a star
and stops overpaying entirely. It says so out loud when it opens one: *"Robo will
remember this."*

Robo also pulls the box trick itself, so watch what it hands over.

Against Robo you cannot see its cards - its side of the screen collapses to a row
of face-down backs, and that reclaimed space goes to your own stash and the
trading line. You only find out what it is holding when it puts it on the table.

## Fits one phone screen

The whole game is locked to a single screen: the page itself never scrolls, only
the two stashes (vertically) and the table shelves (horizontally). Verified at
iPhone SE, 14/15, and Pro Max sizes.

Single file, no dependencies: `index.html`.
