# Dynamics

### Our project right now

We have created a version of the song in its current form, and [you can listen to it here](https://gitmusical.github.io/notating-twinkle/6-accidental).

Right now, the compiled piece would look like this:

![twinkle twinkle initial version](https://gitmusical.github.io/notating-twinkle/6-accidental.png)

### Dynamics on LilyPond

As you may have noticed, musical notation is typically associated with the pitch. Dynamics are included directly after a pitch. You can see this already in our song.

```ly
  c8\mf c g' b
```

As seen on [LilyPond's documentation](http://lilypond.org/doc/v2.18/Documentation/notation/expressive-marks-attached-to-notes), the available dynamic marks are \ppppp, \pppp, \ppp, \pp, \p, \mp, \mf, \f, \ff, \fff, \ffff, \fffff, \fp, \sf, \sff, \sp, \spp, \sfz, and \rfz.

## Step 6: Change the dynamics

### :keyboard: Activity: Change the dynamic marking from `mf` to `p`

1. [Edit the `twinkle-twinkle.ly` file on this branch]({{ editUrl }})
2. Edit the dynamic marking, changing it from mezzo-forte (`mf`) to piano (`p`)
3. Save and commit your changes to this branch
