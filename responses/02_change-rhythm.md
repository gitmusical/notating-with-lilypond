# Rhythm with LilyPond

In LilyPond, rhythm is dictated through symbols. As stated in [LilyPond's documentation](http://lilypond.org/doc/v2.18/Documentation/notation/writing-rhythms),

> **Durations** are designated by numbers and dots, and entered as their reciprocal values. For example, a quarter note is entered using a 4 (since it is a 1/4 note), and a half note is entered using a 2 (since it is a 1/2 note). For notes longer than a whole you must use the \longa (a double breve) and \breve commands. Durations as short as 128th notes may be specified. Shorter values are possible, but only as beamed notes.

### Rhythm in Twinkle Twinkle 

The duration of each note is defined with a **number** in the **same block with the pitches**. For twinkle twinkle little star, the long version would look like:

```ly
{
  c8\mf c8 g'8 b8
  a8 a8 <g d>4
  f4 f4 e4 e4
  d4 d4 c2
}
```

If a pitch doesn't have a specific number (duration), it assumes the duration of the pitch before it. You may notice that there isn't a number after every letter (pitch)! In our example, we see:

```ly
{
  c8\mf c g' b
  a a <g d>4
  f4 f e e
  d d c2
}
```

## Step 2: Correct the rhythm

If you sing, play, or read this music as it currently is, you will notice that the harmonic rhythm changes in the second bar (the song slows down to half speed). Edit the rhythm to continue the notation pattern from the first measure.

### :keyboard: Activity: Fix a rhythm

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Identify and correct the rhythm in the pattern
3. Save and commit your changes to this branch