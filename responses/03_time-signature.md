# Time signatures

### Our project right now

Great job! So far, you've edited pitches and rhythms.

We have created a version of the song in its current form, and [you can listen to it here](https://gitmusical.github.io/notating-twinkle/2-rhythm).

Right now, the compiled piece would look like this:

![twinkle twinkle initial version](https://gitmusical.github.io/notating-twinkle/2-rhythm.png)

### Time Signatures

Time signatures can be specified before a group of notes by `\time` followed by the time signature. (Ex: `\time 2/4 `).

The main block of notes in our piece currently look like:

```ly
\relative c' {
  c8\mf c g' b
  a a <g d>4
  f4 f e e
  d d c2
}
```

If we were to specify 2/4 time, we would add a line before the notes, but within the block, like this:

```ly
\relative c' {
  \time 2/4
  c8\mf c g' b
  a a <g d>4
  f4 f e e
  d d c2
}
```

See the difference?

## Step 3: Change the time signature

Right now, the time signature of this piece is not specified. Let's try out a change and edit it to specify a time signature of 2/4 time. _What do you think will happen to the bar lines?_ 🧐

### :keyboard: Activity: Change the time signature to 2/4 time

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Insert a line before the pitches start to declare a 2/4 time signature
3. Save and commit your changes to this branch

I'll respond when I detect a new commit on this branch.