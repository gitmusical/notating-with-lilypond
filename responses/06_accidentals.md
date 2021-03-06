# Accidentals

### Our project right now

We have created a version of the song in its current form, and [you can listen to it here](https://gitmusical.github.io/notating-twinkle/5-key-sig).

Right now, the compiled piece would look like this:

![twinkle twinkle initial version](https://gitmusical.github.io/notating-twinkle/5-key-sig.png)

You can also see and play the file on [LilyBin](http://lilybin.com/pxpm7v/1).

### Accidentals on LilyPond

If you chose to visualize the changes as music notation after you changed the key signature, you may have noticed that the notes affected were automatically notated as naturals.

To change how these notes are visualized, we will add the notation for flats by the notes that we want to actually be flat.

**Flats** are notated with `es` after a note, like `ces` for c♭.

**Sharps** are notated with `is` after a note, like `cis` for c♯.

Naturals (♮) are always assumed.

## Step 6: Add an accidental

Let's make the _second_ `a` in the piece a _flat_.

### :keyboard: Activity: Change the key signature to C minor

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Edit the second occurrence of the pitch `a` to be a flat
3. Save and commit your changes to this branch

I'll respond when I detect a new commit on this branch.
