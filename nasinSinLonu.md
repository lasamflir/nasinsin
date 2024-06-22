# nasin sin Lonuke

Written in 2024 by ilo Sanli. Idea by jan Wilelen. Suggestions incorporated from jan Awasa and jan Kiwin.

Nasin sin Lonuke is a set of reforms to Toki Pona to resolve existing ambiguities and add nested grammatical structures without creating further ambiguities. It completely removes the need for `e ni:` constructions and makes Toki Pona more expressive and compact. It's named for one of its nimi sin, `lonu`, which encloses nested clauses, and a closing particle that pairs with it, `ke`.

Nasin sin Lonuke is presented in this document "as it is built", with each section only incorporating reforms **above** it. This smoothly and easily introduces each new concept without being overwhelming or confusing.

# Prerequisites

To use nasin sin Lonuke, your existing nasin must do the following:

* Have te/to and allow them to contain an arbitrary number of sentences.
* Have ki
* Use nasin nanpa pona

# Resolving nested pi

The nested `pi` problem is trying to work out the meaning of `A pi B C pi D E`. Does `pi D E` attach to A, or does it attach to B C? If you know your nimi sin, you know the words `te` and `to`, which enclose quotes. The first change that nasin sin Lonuke makes is introducing a new word, `ke`, which is like `to`, except it's used to close off `pi` phrases and more seen later. Here's how it resolves the ambiguity:

* `jan pi kulupu utala pi ma pona` is now unambiguously `jan (pi kulupu utala (pi ma pona))`, meaning a "a soldier of ma pona's army".
* `jan pi kulupu utala ke pi ma pona` is now unambiguously `jan (pi kulupu utala ke) (pi ma pona)`, meaning "a soldier of a ma pona" (not necessarily in ma pona's army, just some army).

Additionally, omitting the second pi has an interesting effect. `jan pi kulupu utala ke ma pona` would mean `(jan (pi kulupu utala ke) ma) pona`, meaning "a good soldier of a land".

Some speakers don't use `to` when it's obvious that a quote is closed. Similarly, `ke` may be dropped when it's impossible that a `pi` phrase is still going. This is most common when it's followed by `li` or `e`, as these cannot nested into pi phrases.

# Reforming ki

## Adding ke

With Toki Pona's ability to include multiple predicate phrases in a sentence, `ki` without `ke` is very difficult to use in complex sentences and will result in miscommunication. For example, in the sentence, `jan ki moku e kili li pona li olin e mi`, where does the `ki` clause end? It obviously ends before `li olin e mi` if it's a complete sentence as opposed to just a noun phrase, but it is ambiguous whether `li pona` is in the `ki` clause or not.

`ki` as it currently exists resolves this ambiguity in writing by extending part of the glyph (much like `pi` does too), but it is more *pona* to resolve it in speech too. Of course, `ke` can be used to close off a `ki` clause, leaving listeners in no doubt as to the structure of sentences.

* `jan ki moku e kili li pona li olin e mi` is now an **interjection without a predicate**. It needs a `ke` somewhere, otherwise each subsequent `li` keeps attaching to the `ki` clause.
* `jan ki moku e kili ke li pona li olin e mi` now means "the person who eats fruit is good and loves me", leaving `li pona` and `li olin e mi` clearly outside of the `ki` clause.
* `jan ki moku e kili li pona ke li olin e mi` now means "the person who eats fruit and who is good loves me", putting `li pona` inside the `ki` clause.

## Resumptive ona

There are plenty of nested clauses where the head of the clause is the object of the nested sentence. The preferred way to do this with `ki` in nasin sin Lonuke is to use resumptive `ona`.

* `kala ki mi moku e ona` simply means "the fish that I ate".

# lonu

## what lonu means

The nimi sin `lonu` introduces a way to embed full sentences into toki pona sentences. It means "event of (sentence)" as a noun and is most useful for replacing standard Toki Pona's `e ni:`, `tan ni:`, `ni li ... :` family of constructions and avoiding the need for a new sentence. For example, `mi wile e ni: mi moku e kili pona` becomes `mi wile e lonu mi moku e kili pona`. As a predicate, `lonu` means "is an event of (sentence)". For example, `tenpo ni li lonu mi moku e kili pona` means "now is an event of me eating good fruit".

* `lonu sina pana e pan tawa mi ke li pini e lonu mi wile moku` means "You giving me bread stops me wanting food".`

## lonu and ke

Just like `ki` and `pi`, every nested sentence started with `lonu` is closed with a `ke`. You might be wondering how these interact. If everything is closed with the same particle, how do you know what's being closed by the `ke` in a phrase like `lonu ona li jan pi kulupu utala ke`? The answer is that `ke` **only closes the innermost construction that is still "open", so to speak**. So in this case, that means that `ke` applies completely unambiguously to `pi`. If this was the subject of your sentence, you'd actually need a second `ke`.

* `lonu ona li jan pi kulupu utala ke ke li pona` means "(the event of them being a soldier) is good".
* `lonu ona li jan pi kulupu utala ke li pona ke` means "the event of them being a soldier and being good" and is an interjection because there's no main predicate. If this was the intended meaning, the first `ke` could be omitted too, as `li` cannot be nested in a `pi` phrase so there's no doubt that the `pi` phrase is closed.

# Separating sentences

If spoken quickly without long pauses to indicate the position of full stops, nasin sin Lonuke as shown so far would still be full of ambiguity. If a `ke` is left off the end of a sentence and the next sentence could appear to "run into" it, then a listener may become confused as to what belongs to the previous sentence and what belongs to the next sentence. One way this could be solved is making all `ke` particles obligatory at the ends of sentences, but this is unworkable because you'd constantly need to remember how deep you are in nested structures.

If `mi wile e lonu sina alasa e kala ki pona tawa jan sona. mi pali.` was spoken quickly, a listener might interpret `mi pali` as belonging to the previous sentence and think that the speaker wants them to fish for fish that are good for *their working* teacher when they mean a teacher generally. Resolving this with the mandatory `ke` approach may only put two `ke`s at the end, but this would just keep getting worse and worse for more deeply nested sentences. What you need is a way out of *everything* in the current sentence and a clear marker that you're starting a new one.

This is where the nimi sin `i` comes in. `i` is mandatory at the start of every sentence and allows for every `ke` in the previous sentence to be dropped.

The phrase with separated sentences and all unnecessary `ke`s removed is now `i mi wile e lonu sina alasa e kala ki pona tawa jan sona. i mi pali.`.

# The letter words

## Introducing the letter words

Standard Toki Pona does not have names for its letters. This is obviously a problem if you need to spell out a word in an exclusively Toki Pona-speaking environment. In order to introduce words for the letters, nasin sin Lonuke introduces the new vowel sound `y`, which is the schwa vowel, a sound made by totally relaxing your mouth while making a voiced sound. This follows every consonant in Toki Pona to make its letter name. For vowels, the suffix `-pu` is added, showing their connection to the official Toki Pona book, and metaphorically literacy as a whole.

* `a` is `apu`
* `e` is `epu`
* `i` is `ipu`
* `j` is `jy`
* `k` is `ky`
* `l` is `ly`
* `m` is `my`
* `n` is `ny`
* `o` is `opu`
* `p` is `py`
* `s` is `sy`
* `t` is `ty`
* `u` is `upu`
* `w` is `wy`
* `y` is `ypu`

Most people's nasins probably don't introduce 15 nimi sin at once, but for such an important purpose, it's definitely worth it.

## Uses of the letter words

To spell out a word, use a `te ... to` quote consisting exclusively of the word's spelling. For example, I'd spell out my name as `te ipu ly opu sy apu ny ly ipu to`.

Outside of quotes, strings of letters or single letters act as pronouns that refer back to the last thing that begins with any of the letters in the same order. For example, `i soweli lili li alasa e kala. i ky li loje.` means "a small animal hunts fish. It is red." but "it" refers clearly to the fish, not the animal. This is not the case with `ona` which makes no distinctions at all between referents. Named entities are refrenced by the spelling of their name rather than their head noun, as many entities share the same head noun. `i jan San en jan Timi li wile e ni. i sy li pali.` means "John and Tim want this. John works." They may also be stacked together to further specify what they can refer to, so `sy opu` may refer to `soweli` but not `suno`.

# Prepositions

## Introducing prepositions

Nasin sin Lonuke still has a huge ambiguity problem. Standard Toki Pona uses the words `kepeken`, `lon`, `sama`, `tan` and `tawa` as both content words and prepositions. This causes problems like in the sentence `i jan li toki e tomo tawa mi`, which might be "a person talks about a house to me" or "a person talks about my car". It would be simpler if these words only ever had their content word meaning, and their prepositional meanings were reassigned onto nimi sin.

## pe, lo, sa, ta and wa

The new prepositions are:

* `pe` for `kepeken`
* `lo` for `lon`
* `sa` for `sama`
* `ta` for `tan`
* `wa` for `tawa`

As described in [sona pona la's page on prepositions](https://sona.pona.la/wiki/Prepositions), these are used in the prepositional senses of these words, with the sense of "transitive verb" or the unlisted intransitive verb senses retaining the use of the original content words. The ambiguous example at the start of this section now becomes:

* `i jan li toki e tomo wa mi` means "a person talks about my car".	
* `i jan li toki e tomo tawa mi` means "a person talks about a house to me".
For easy memorisation and to add an essential missing word to Toki Pona, all five prepositions merge into `pelosatawa`, which means "preposition" as a noun and "is a preposition" as a predicate. The prepositions are not always enough, the word `pijo` may be used to convert the following phrase followed by `e` into a preposition. For example, `waso tawa pijo ante kute e akesi` means "Birds move visually unlike reptiles."

# Reforming multiple-li sentences

## The problem with multiple-li sentences

You might've noticed that in multiple-li sentences containing nested clauses, `ke li` shows up a lot. This is because as many `li` phrases as you like may keep attaching to the current clause unless closed off by li. This rule is bad for creating opportunities to drop `li`, and can be fixed with no loss of compactness by introducing a further nimi sin, `je`.

## je
`je` replaces any `li` **after the first predicate phrase** in a sentence or nested clause. This means that any `li` in a sentence must be within the current nested clause if that clause does not have a predicate phrase yet, or outside of it if it already has one. `je` maintains the current nesting level, but `li` does not if there's already one in the current clause. This makes `ke li` much less often needed, and provides a much more natural way out of nested clauses than needing to think about how many layers deep you are all the time.

* `i jan ki moku e kili li pona li olin e mi` was previously an interjection but has now become **ungrammatical!** This is because `i jan ki moku e kili li pona` now has an implied `ke` after `kili` because clauses or sentences can't have more than one predicate phrase (the first is after `ki`), so that portion has now become a complete sentence. Adding a further `li` phrase is now impossible, because there's nothing it would be closing off.
* `i jan ki moku e kili li pona je olin e mi` now means "the person who eats fruit is good and loves me".
* `i jan ki moku e kili je pona li olin e mi` now means "the person who eats fruit and who is good loves me".

# Clearer names

## The problem with names

You might not actually know which nimi sin belong in a speaker's dialect. You might also not know if a speaker adheres to the rule that name words in Toki Pona are not allowed to clash with Toki Pona's official words. This can be a problem! For example, `ke` is [a Chinese surname](https://en.wikipedia.org/wiki/Ke_(surname)). Mishearing someone's name as the closing particle in nasin sin Lonuke could cause a lot of confusion!

## Unambiguous names

5o fix the clarity problems with names, nasin sin *Lonukes* introduces a new rule: every name must end in a consonant other than n. This makes names never clash with the phonological space of root words, and additionally makes them more flexible to represent names from other languages:

* `Paris` becomes `ma tomo Palis`
* `Samflir` becomes `ilo Sanlil`
* `Ithkuil` becomes `toki Ikuwil`

## Fixing names that now don't work

When a name ends in a vowel, you have two options. You can either add a consonant onto the end that wasn't there before, or clip the last vowel sound off if it results in a final consonant that isn't n. For example:

* `Emily` becomes `jan Emilis` or just `jan Emil`
* `Barry` becomes `jan Palis` or just `jan Pal`

When a name ends in n, you can add -y and then treat it as a name that ends in a vowel, or you can change it to an m if that fits the name better. For example:

* `John` becomes `jan Som` or `jan Sonys`

## Pauses

With any consonant now able to end names, it's important to make it clear when this is happening to prevent mishearing. This is done by inserting pauses around names. The pause at the start ensures that names that start with valid Toki Pona words don't "break off" and are clearly separated from the head noun phrase, as an example `jan Kelis i` might end up sounding like `jan ke li si`, which is no good.

Pauses are written with dots and are given the letter word `awenpu`. With dots enclosing names and their forms completely unable to clash with official words, capitalisation becomes redundant and Toki Pona may be written entirely in lowercase. However, capitalisation may still be optionally used to indicate stress in names, to borrow their stress pattern into Toki Pona. Additionally to avoid conflicts like `sin a` versus `sina` pauses are used before words that begin with a vowel.

`ilo Sanli` is now `.ilo .sanlil.`
