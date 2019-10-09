# Key Signatures

Nice work! If you'd like to listen before we move on to the next step, here's how:

### Key signatures on LilyPond

Like with the time signature, the key signature is notated with `/key` followed by the signature, like `\key a \minor`. In a file, this would look like:

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