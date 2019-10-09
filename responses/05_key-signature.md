# Key Signatures

### Our project right now

Nice work! We have created a version of the song in its current form, and [you can listen to it here](https://gitmusical.github.io/notating-twinkle/4-chord).

Right now, the compiled piece would look like this:

![twinkle twinkle initial version](https://gitmusical.github.io/notating-twinkle/4-chord.png)

### Key signatures on LilyPond

Like with the time signature, the key signature is notated with `/key` followed by the signature, like `\key c \minor`. In a file, this would look like:

```ly
\relative c' {
  \time 4/4
  \key c \minor
  c8\mf c g' b
  a a <g d>4
  f4 f e e
  d d c2
}
```

## Step 5: Change the key

Let's add some drama and change the key to `c minor`.

### :keyboard: Activity: Change the key signature to C minor

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Add a line after the time signature to specify c minor as the key for this song
3. Save and commit your changes to this branch

I'll respond when I detect a new commit on this branch.