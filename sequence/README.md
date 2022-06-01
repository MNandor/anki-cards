# Sequence

A card type useful for memorizing information that comes in a sequence. Algorithms, poems, chess openings.

The contents of the card is split by the marker `#answer`. Click on the main section to advance to the next step.

The border of the main section is color-coded:
- Red: you have more steps to see
- Yellow: you've seen all steps
- Green: back of the card, showing all steps together


## How to Get

### Importable Deck

1. Go to the [Releases](https://github.com/MNandor/anki-cards/releases) page and find the newest version of Sequence.
2. Save the `.apkg` file
3. In Anki, File/Import and select the file

### Manual

(instructions are for Desktop Anki - but the card type works on AnkiDroid, too)

1. Create a new Note type: Tools / Manage Note Types / Add
2. Give it the required fields: Tools / Manage Note Types / (Select the type you just created) / Fields
3. It needs a `Title` and a `Data` field. You can also add any additional fields you might want to use.
4. Click on Cards... and edit it as follows
  5. Copy `card1_front.html` into Front Template
  6. Copy `card1_back.html` into Back Template
  7. Copy `card1.css` into Styling
8. You're done! You can create cards with this template now!

## Example

The following `Data`:

```text
START
#answer
一 (ichi)
#answer
二 (ni)
#answer
三 (san)
#answer
四 (shi/yon)
#answer
五 (go)
```

Results in this card:

![](example-jap.gif)

## Pictures

You can paste pictures directly into Anki's editor and they will work.

![](example-london.gif)
<!-- ![](example-never.gif) ->>
