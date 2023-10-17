# Anki Cards

A collection of my different Anki card templates.
`web`

# Implementation Details

(for nerds)

## On Mules

You might notice I labeled some files as "mules".
This is related to what I call "mule cards".
Just like how you can make an otherwise useless account in a video game for the purpose of holding or carrying your items, you can create a useless Anki card to hold images.
You simply create the card, insert all the media you want it to hold, then suspend it.

The benefit of this is that you can refer to said media by name in other cards (even in Javascript) without having to include the media in each card individually.

## On Mnemonics

I often include an `{{edit:Mnemonic}}` field on my cards templates.
I originally used this to write down any personal mnemonics that helped me memorize things, but by now I just use them for all sorts of personal notes.

To replicate this functionality, I recommend the [Edit Field During Review (Cloze)](https://ankiweb.net/shared/info/385888438) addon.
Without the addon and on mobile, the Mnemonic field shows up as normal.

## On Javascript persistence

Many of my card templates use some form of Javascript.
Whether said Javascript re-runs on a new card during review, and whether variables are carried over is sort of inconsistent between PC and mobile.
This is why you might see some unnatural Javascript code, such as at variable declaration.

## On Mobile Colors

Once again, Anki is inconsistent between PC and mobile in how it handles dark mode and CSS colors.
My cards have a .mobile CSS variants to get around this (to achieve a similar look across devices).