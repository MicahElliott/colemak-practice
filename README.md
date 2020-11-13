# Colemak Practice Words

Home-row typing is really great, _almost all of the time_.

This is a collection of hard-to-type same-finger bigram (and some
trigram) words.

These are your primary enemies:

	hj hk hl hm hn jk jl jm jn kl km kn lm ln mn

The goal is to never use the same finger twice in succession … ’cuz
that makes you slow (and uncomfortable!). And if you ever wanna beat
[Sean Wrona](https://forum.colemak.com/topic/1309-typing-tips-from-the-fastest-typist-sean-wrona/),
in a typing contest and tell him to his face that COLEMAK RULEZ!, you gotta get that
[1.52%](https://colemakmods.github.io/mod-dh/compare.html#compare-results)
down to 0%! (among other unlikely things)

This even covers “shifting” as you might do on a piano. Eg, try typing
some of these: _helm, acknowledge, wrinkly_. Not great, huh?
Well, it turns out there are a lot of nasty colemak words like these.
But the good news is that it’s not _that_ many! And you can train them
all into your hands in probably a couple weeks until the patterns
become automatic. And bam, you’re wearing the world-champion co-Wrona!

There are some particularly nasty words like _ploying_ and _unkempt_
that just take a lot of practice of the shifts.

But a lot of the words are pretty easy and are natural “scrunches”,
like _scriptwriter_, featuring three! scrunches in a single word: `sc
pt wr`. _(Can you figure out how to scrunch them??)_ Although
“slide-downs” sound nice in theory, I don’t find them possible, so I
think we should stick to vertical scrunching.

The words in this file collection can be loaded into typing practice
tools, like https://www.keybr.com

Some discussion:
https://forum.colemak.com/topic/2642-practice-with-altfloatingsamefinger-bigram-combos/

## Source

The words in these practice lists are taken from the OED (I think, but
source really doesn’t matter).

## Files

All same-finger permutations with more than ~10 semi-common words are
in files of the respective names. Others like _hk_ and _jk_ are
basically non-existent. You can get away with skipping tiny files like
_ln.lst_.

There is also a *programming* file of oddball names like `mkfs` that
are tricksy.

The best file for training is _best.lst_, containting ~100 words that
have multiple odd patterns in a single word, like _deutschmark_
(they’re mostly English :P).

## Tricks

``` shell
❯ echo `shuf tb.lst`
hatbox eastbound outbuilding ratbag paintbox …
```

That randomizes the list and puts them on a single line. Now you can
load them into your favorite typing tutor.

## Convention

Since fingerstyle guitar already has a
[convention](https://en.wikipedia.org/wiki/Fingerstyle_guitar#Notation)
for referring to index, middle, ring, and pinky, let’s stick with it: “I M
A X”.

## Shifty Patterns

``` text
ken
kel
kne
key
unk
ulm
uln
ulken
unl
unmi
uen
quen
fsc
mne
helm
enj
inj
enli
inme
dbr
onke
like
lunk
keu
lke
lumny
```

## Optimizations Described (with examples)

### like

It’s not obvious that _like_ is a bad word. However, l and k are so
awkward/slow for your index that you can improve it with your first
full shift by typing: `l(M) i(X) k(I) e(A)`

_helm_ becomes: `h(I) e(A) l(M) m(I)`

_key_ becomes: `k(I) e(A) y(X)`

## This is ridiculous

What’s that, this is a total waste? You might be right. Most people
probably don’t care about tuning an already amazing layout. But no
layout can be perfect. Without some hacks. And that’s what these are,
but they should actually speed you up if you really wanna up your game
(after you down it yet again).

But seriously, these are cool, and I don’t see any harm in using them.
They don’t make otherwise normal words worse. They actually make your
fingers more comfortable and spry for a little more learning effort.
Imagine a pianist never leaving C-position. That’s what you’ve been …
till now.
