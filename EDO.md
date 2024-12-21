# Equal Division of the Octave

TTSS argues that 12-edo works because most of its intervals are consonant.

I wonder whether that's necessary. Suppose it's not. Then what makes Western music comprehensible?

Music should be easily memorable. Moder Western music (jazz or classical influences aside) uses these means:
- diatonic scale (exact tonic isn't always recognizable due to lack of significance of cadential formulas)
- all chords in triads - built on the scale
- only major or minor chords used, a diminished triad isn't used
- four-chord progression as a first default
- a small inventory of very frequent progressions

First question: can we have the same progressions framework reused in other EDOs?

EDOs should be in unique position of having just a few chord types.

# Structures we're searching for

In any N-EDO, define a diatonic scale as any scale that doesn't have two consecutive semitones. I'm not sure we're actually need to restrict ourselves with exactly those scales: I'm not sure which of their properties are cool. Eg. consider minor #4b6 in 12-EDO - I quite like it.

Now, define an _orienting_ scale if it's not of limited transposition.

Too much talking. Let's build something.

A minimally viable object for us is a shuttle: a scale that will allow us having two triads.

I wonder whether we should base all triads on root-fifth relation, that is, whether root-upper interval should be the same for all types of chords we're using.

4-EDO has two different chords: 1-2-3 and 2-3-4. However, 4-EDO is fully intervallically enclosed in 12-EDO, therefore it's not an interesting musical object. It's a plain fully diminished seventh chord. Also, it's not a diatonic scale within a chromatic scale, and it's not orienting.

Why are chords built in triads in 12-EDO? I think the primary thing is the precise blend of root-fifths. 12-EDO is unique in that sense: on almost all scale degrees can you use a fifth. This makes simultaneous chords playable - not just arpeggios.

I don't buy that major or minor thirds do blend as much: given the number of beatings in them in 12-EDO I attribute their niceness to pure repetitiveness of exposure. A typical Western human consumes a magnitude of thousands major third and minor third intervals (simultaneous or arpeggiated) every day.

What does it yield? Either we should specifically work with EDOs having clean perfect fifths, or we might enjoy beating in them, or we might skip playing simultaneous chords in them, or we might drop having all chords an upper third notes. 

That is, a harmony is a root conditioning voice-leadings. But the way it happens in Western 12-EDO is that a root almost always is accompanied by two more notes (third+fifth) which cements the division of scale between "chord tones" and "non-chord tones". 

# Search

 3-EDO, 4-EDO or 6-EDO are already contained within 12-EDO like - which was explored by various romantic and jazz composers.

 Let's look at 10-EDO. We have 120 cents as a basic chromatic interval. Let's call its chromatic scale 0-1-2-3-4-5-6-7-8-9.

 What harmonies can we build?

Drone harmony is acceptable. We better build an orientable scale.

# Observation

In 12-EDO, is any non-chromatic scale with perfect fifth of the tonic is orienting?

Suppose it's not. Let's define X = 1..11 the number of semitones onto which a scale is self-rotatable. X != 7 since then our scale is chromatic (reapply rotation, we yield 0, 7, 2, 9, ..., the entire Z/12Z). By the same argument, X != 1.

If X = 2, then we get 0, 2, 7, 9, 4, 11, 6, 1, 8, 3, 10, 5.

If X = 3, then we get 0, 3, 7, 10, 6, 1, 9, 4 - whole-half scale.

If X = 4, then we get 0, 4, 7, 11, 8, 3 - (1,3) scale. Surprisingly underused in Western music: I don't remember any examples.
