# Welcome to Notating with LilyPond!

LilyPond is an open source music notation technology. With LilyPond, music can be notated in non-binary files with numbers and symbols, just like code.

In this course, we're going to practice some of the fundamental ways to notate music with LilyPond, like:

- Pitches
- Rhythms
- Time signature
- Key signature
- Accidentals
- Dynamic markings

Before you start this course, you may want to be familiar with a few concepts, like melody and rhythm notation in traditional western music. This course is _not_ about how music is notated - it's about how to notate music with LilyPond.

### Notating pitch with LilyPond

LilyPond uses the alphabetical note names to determine pitch. In this pull request, we see:

```ly
  c8\mf c g' b
  a a <g d>4
  f4 f e e
  d d c2
```

Some of these letters, numbers, and symbols represent things related to the notes, and some represent pitches. The letters that represent pitches are:

```ly
  c c g b
  a a <g d>
  f f e e
  d d c
```

We'll talk about some of the other symbols later on.

### Our project right now

We have created a version of the song in its current form, and [you can listen to it here](https://gitmusical.github.io/notating-twinkle/0-default).

Right now, the compiled piece would look like this:

![twinkle twinkle initial version](https://gitmusical.github.io/notating-twinkle/0-default.png)

You can also see and play the file on [LilyBin](http://lilybin.com/3ojky1/1).

## Step 1: Fix a note

This pull request introduces a file called `twinkle-twinkle.ly`. This file is the notation of the melody from "Twinkle Twinkle Little Star". But, a few things are wrong. You'll notice that a note is wrong, and a rhythm is wrong - we'll fix the rhythm later. First, correct the note so it matches the traditional melody.

### :keyboard: Activity: Fix a note

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Identify and correct the note in the pattern
3. Save and commit your changes to this branch

I'll respond when I detect a new commit on this branch.
