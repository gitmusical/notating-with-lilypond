# Chords with LilyPond

### Our project right now

Nice job with the time signature! What do you notice about the barlines?

We have created a version of the song in its current form, and [you can listen to it here](https://gitmusical.github.io/notating-twinkle/3-time-sig). 

Right now, the compiled piece would look like this:

![twinkle twinkle initial version](https://gitmusical.github.io/notating-twinkle/3-time-sig.png)

### Chords

You may have noticed so far that our example has many instances of only one note, but there is an example of a chord.

Single notes are notated by letters (or letters combined with numbers or other symbols) that are surrounded by spaces, like:

```ly
  c8\mf c g' b
```

Below, you can see that the notes `G` and `D` are grouped together by the bracket symbols, `<` and `>`:

```ly
  a a <g d>4
```

## Step 4: Create a chord

Let's add another chord to the last note of the piece!

### :keyboard: Activity: Create a chord on the last note with C and the G below it

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Edit the last note to be a chord with the notes `c` and `g`
3. Save and commit your changes to this branch