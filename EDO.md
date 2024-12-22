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

Drone harmony is acceptable. We better build an orienting scale.

# Observation

In 12-EDO, is any non-chromatic scale with perfect fifth of the tonic is orienting?

Suppose it's not. Let's define X = 1..11 the number of semitones onto which a scale is self-rotatable. X != 7 since then our scale is chromatic (reapply rotation, we yield 0, 7, 2, 9, ..., the entire Z/12Z). By the same argument, X != 1.

If X = 2, then we get 0, 2, 7, 9, 4, 11, 6, 1, 8, 3, 10, 5.

If X = 3, then we get 0, 3, 7, 10, 6, 1, 9, 4 - whole-half scale.

If X = 4, then we get 0, 4, 7, 11, 8, 3 - (1,3) scale. Surprisingly underused in Western music: I don't remember any examples.

If X = 5, then we get 0, 5, 7, 2, 10 - a tetratonic scale.

# 8-EDO

150 cents. Perfect half-flats. C, Dhb, Eb, Fhb, F#, Gh#, A, Bhb.

# 10-EDO

Funny enough, the fifth will be 720 cents. So there will be beating, but it may actually be fun.

Which chord qualities we have?

360 + 360 - neutral chord.

240 + 480 - sus2 chord.

480 + 240 - sus4 chord.

Let's first try to build a scale with neutral chords - much like a major scale in 12-EDO which has I, IV and V.

A neutral chord on 0 is 0-3-6 (0n).

Suppose I also take a 6-9-2 chord (6n) - with a leading tone. Then I have a proto-scale 0-2-3-6-9. 

I suppose that for smoothness of melodies I want another note between 3 and 6 and between 6 and 9. 

I think that for lesser chromaticism around the scale start I take 5: 0-2-3-5-6-9. Then if I take 8, let's see which chord qualities I have in 0-2-3-5-6-8-9:
- 0n 0-3-6
- 2n 2-5-8
- 3n 3-6-9
- 5no 5-8-0
- 6n 6-9-2
- 8?

So, I have 0n, 2n, 3n, 6n. I don't have a chord quality opposition between major and minor - no solid sus chords that can act for this opposition. 3n7 can act as a dom chord - however, I can build the same structure on 0, so no dom-maj7 opposition either. 

I probably don't have cool applieds. What are applieds? Applieds are degrees on which I have a chord quality different from a standard dominant in there.

Let's think again.

The basis is a neutral chord. Can we build a system to contrast it with some other chord quality that is frequently present on a scale?

0-3-6 is 0n. Let's avoid it, let's start a scale as 0-2-4-6, therefore omitting 3. Therefore we'll aim to have 6n 6-9-2 as a dominant chord - which dominance manifests in its quality, much like V in minor.

0-2-6 is 0t (two-chord) - a tonic chord.

## Tritone dominant approach.

Tritone is 0-5. We have a percect tritone (I don't know what that means). Can we use it to have a good dominanth via a lower leading tone? Maybe by having a 4-9 chord?

0-3-6 - a 0n tonic neutral chord. 4-6-9 is a dominant chord (lower diminished). 4-7-0 is a pre-dominant 4n chord. A scale so far is 0-3-4-6-7-9 - we have a gap between 0 and 3. If we take 1 (phrygian vibe), we'll have 1n chord in the scale. Unfortunately, 0-1-3-4-6-7-9-0 is not orienting. I think we need a seven-tone scale.

How about 2?

Can we avoid chromaticism (two consecutive semitones) in an orienting scale in 10-EDO?

The only way is to have 0-2-4 somewhere in the scale. By continuing from both ends we'll get 7-9-0-2-4-5 - which shows us that these two whole tones should be in some other part of the scale (maybe around 6) - since we want a tonic neutral chord.

Again, this is a colonial 12-EDO optics - why even aim for triads with good properties?

6-8-0? 6-8-0-1-3-5-6 -> 0-1-3-5-6-8. Six-tone scale again. Chords?
- 0n: 0-3-6
- 1? - don't have fifth
- 3? - don't have fifth
- 5n 5-8-1
- 6?
- 8?

## Fresh look

Since we only have one third (a neutral third, 360 cents), the main opposition we gonna have (if possible) is between 720 chords and 600 chords. We have two types of diminished chords: 240+360 and 360+240 (l and u). Ideally, we only have one of those types for dominant (same as V7 uniqueness), so that it would be orienting and applied-usable. 

Can we have a neutral chord a tonic and a dim chord a dominant?

### Lower leading tone

Capture 9 via dim dominant. So, options are 4-6-9, 4-7-9; 6-9-1, 7-9-2; 9-1-4, 9-2-4.

0n: 0-3-6

#### Try 6-9-1 u

- 0n: 0-3-6
- 1l: 1-3-6 
- 3n: 3-6-9
- 4l: 4-6-9
- 6u: 6-9-1
- 9l: 9-1-4


Scale: 0-1-3-4-6-9, orienting, neutral scale.

Should have an opposing scale as 0l tonic chord: 0-2-5 with dominant 6-9-1, 0-1-2-5-6-9. Heavily chromaticized, unstable.

### Aug chords?

An alternative is probably a scale where two main opposing chords are neutral and augmented.

0-3-6 neutral, its upper structure augmented is 3-6-0 (same chord) - can't work.

### Try 7-9-2 l

0n: 0-3-6
2
3
4
6n: 6-9-2
7l: 7-9-2
9u: 9-2-4


# 15-EDO

80 cents.

A perfect fifth is the same as in 10-EDO: 720 cents. Which probably allows us to strangely blend two EDOs somewhere.

Which thirds we have? 320 (minor third) and 400 (major third).


