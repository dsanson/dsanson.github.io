---
title: The Liar Paradox in the Islamic World
author:
  - name: Ahmed Alwishah
    affiliation: 
      - name: Pitzer College
  - name: David Sanson
    affiliation: 
      - name: Illinois State University
google-scholar: true
format:
  html: default
  typst:
    papersize: us-letter
  # pdf:
  #   author:
  #     - name: Ahmed Alwishah
  #       affiliation: 
  #         - name: Pitzer College
  #     - name: David Sanson
  #       affiliation: 
  #         - name: Illinois State University
  #   pdf-engine: lualatex
  #   font-size: 10pt
  #   papersize: letter
  #   geometry: margin=1in
  #   italicquotes: true
  #   pdfstandard: 
  #     - ua-2
  #     - a-4f
format-links:
  - html
  - format: typst
    text: PDF
    icon: file-pdf
---

**DRAFT**

## Abstract

Although the Liar Paradox was known in antiquity, the surviving textual
record from that period is sparse. By contrast, medieval treatments of
the Liar develop along two relatively well-preserved and parallel lines:
one in the Islamic world, primarily in Arabic, and the other in the
Christian world, primarily in Latin. The Latin tradition has been the
subject of sustained historical scholarship for several decades (Spade
and Read 2021). Scholarly work on the Arabic tradition is a more recent
development.

This article covers the development of the Arabic tradition from the
10th century to the 15th century. In the earliest texts, the Liar occurs
either as a theological counterexample or as a logical sophisim. During
the 13th century, it became a standard example discussed by logicians,
and several distinct solutions were articulated and defended. And at the
end of the 15th century, the Liar had its philosophical moment, as it
became the subject of an extended debate between two rivals, Sadr al-Din
al-Dashtakī (d. 1498) and Jalāl al-Din al-Dawānī (d. 1502), who each
wrote free-standing treatises on the topic.

## 1. General Remarks and Historical Context

In its simplest form, the Liar is a puzzle generated when someone says,
"This is false." If true, this is false, and if false, true. Either way,
leads to contradiction.

Early texts in the tradition instead present the paradox as a puzzle
about someone who says, "I am a liar (*kādhib*)." Or rather---since the
Arabic word '*kādhib*' need not imply any intention to deceive---"I am a
false-teller," that is, someone who says false things. Unfortunately,
this is ambiguous: it could mean that they always say false things; or
it could mean that they sometimes say false things. Careful authors
clarify what it means, or avoid this problem entirely, by instead
presenting the paradox as a puzzle about someone who says, "All my
sayings are false."[^1]

"All my sayings are false" does say of itself that it is false. But in
ordinary circumstances, it is not a paradox. This is because, in
ordinary circumstances, the person who says it will have also said some
other true things. So the claim that all their sayings are false is
simply false. To generate a paradox, we need to stipulate that they
never say anything else that is true, either by stipulating that
everything else they say is false, or by stipulating that this is the
only thing they ever say. Since it is only a paradox in some situations
but not others, "All my sayings are false" is what the contemporary
literature calls a "contingent liar" (Barwise and Etchemendy 1987, 22).

Those stipulations might seem far-fetched: it is hard to imagine a
speaker who has never said anything true. To avoid this, 13th century
authors shift to the example of someone who says, "All my sayings *at
this moment* are false," and this quickly becomes the standard example
used in all discussions of the Liar. It remains the standard example in
the 15th century, but 15th century authors also discuss the simpler
example, "This saying is false," which, over time, becomes the new
standard example (Rezakhany 2018, 185--86, n. 12).

A "liar cycle" is introduced into the discussion in the 14th century:
today, someone says, "All that I say tomorrow is false;" tomorrow, he
says, "All that I say yesterday is true;" these are the only two things
he says today and tomorrow. This generates a paradox, since if what he
says today is true, then what he says tomorrow is false, so what he says
today is false; and likewise, if what he says today is false, what he
says tomorrow is true, so what he says today is true. The unique
today-tomorrow structure of this particular example is due to the fact
that it is built upon an earlier example, of a man who puts himself into
a moral quandary by saying, "I will lie tomorrow," thereby managing (the
argument goes) to do something both bad and good at the same time.

In all of these forms, the Liar puts pressure on the view that truth and
falsehood are contradictories. Perhaps the moral to be drawn is that
they are not, because some sentences are both true and false, or some
sentences are neither true nor false.

Few authors in the tradition are satisfied with that response. But they
do have good systematic reasons to think that truth and falsehood are
not contradictories. Most authors, following Avicenna and Aristotle,
take falsehood to be the metathetic negation of truth (Hodges 2012).
That is, to be false is to be *non-true*, rather than *not true*. This
is understood to have two important consequences. First, truth and
falsehood share a propriety condition: just as a pre-pubescent boy is
neither bearded nor non-bearded, since beards are only proper to adult
men, a question is neither true nor non-true, since truth is only proper
to declaratives. Second, it implies that truth and falsehood share
existential import. This is because "S is true" and "S is non-true" are
both *affirmative* propositions, and the standard view is that
affirmative propositions have existential import, while negative
propositions do not (Parsons and Ciola 2025, sec. 5.3). So, both "S is
true" and "S is non-true" are false when the subject term, "S", is
vacuous. For example, if Zayd says nothing, then the subject term, "What
Zayd says" is vacuous. So both affirmative propositions, "What Zayd says
is true" and "What Zayd says is false," are false, and both
corresponding negative propositions, "What Zayd says is not true" and
"What Zayd says is not false," are true.

These two conditions imply that, strictly speaking, truth and falsehood
are not contradictories, because non-declaratives are neither true nor
false, and non-existent declaratives are neither true nor false. But
when applied to existent declaratives, they remain exclusive and
exhaustive. So this offers no immediate solution to the Liar, which
appears only to involve applying truth and falsity to existent
declaratives.

The Liar is not just a declarative, but a declarative that declares
something about itself. That might sound like a funny way to put it, but
it feeds into a well-entrenched logico-grammatical analysis of
declaratives: each is about one or more thing, and these things---the
things picked out by the subject term---are called its "declared-abouts"
(*mukhbar ʿanhu*). As we will see, several of the solutions make use of
this conceptual distinction, between a declarative and the things it is
about. In some cases, this amounts to a simple restriction on
self-reference: no declarative can declare something about itself. But
other proposals are more subtle than that.

## 2. The Early Period

There are three early historical threads that involve the Liar.

First, Yaḥyā ibn ʿAdī (d. 978) presents the Liar as a difficult sophism.
His solution begins with the observation that the Liar is a declarative
that declares something about itself, and so plays two different roles.
But, he argues, when a declarative becomes the subject of a declarative,
it is no longer a declarative, and so no longer the kind of thing that
can be true or false.

Second, the Liar appears as part of a series of counterexamples to
dualist views of good and evil, all of which involve someone telling the
truth about lying. The series starts with an example from al-Naẓẓām
(d. 845), which is not the Liar, but has sometimes been read as
Liar-like. A later example, due to al-Bāqillānī (d. 1013), is definitely
liar-like, but still not the actual paradox. It is only with al-Baghdādī
(d. 1037) that the Liar proper is used in this context.

The third thread is also begins with examples that are Liar-like but not
the Liar. In his treatment of relativism, Aristotle pointed out that
"Everything is false" is self-falsifying (*Metaphysics* IV 1012b19).
Al-Fārābī (d. 950) and Fakhr al-Dīn al-Rāzī (d. 1209) both treat the
same topic using similar examples. Al-Fārābī does not connect the
examples to the Liar Paradox, but al-Rāzī does.

Of these three threads, only the third shows clear signs of having
influenced later work on the paradox. Al-Kātibī wrote a commentary on
al-Rāzī, and it might be that his efforts to reconstruct al-Rāzī were
what led him to develop his own proposal.

### 2.1 Yaḥyā ibn ʿAdī: When Declaratives Stop Being Declaratives

Yaḥyā ibn ʿAdī was a Syriac Christian in Baghdād. He was a student of
Abū Bishr Mattā (d. 940) and perhaps also al-Fārābī. An important
translator of and commentator upon Greek philosophical works, in his own
time he was held in especially high regard as a logician (Endress 1977).

In a work defending the power of logic over grammar, he illustrates his
claim that logic can solve problems that grammar cannot with four
examples, which he describes as "common problems raised by the
sophists." One of these is the Liar. This places his discussion firmly
into a broadly Hellenistic context, but it is not clear what specific
Hellenistic sources he might have been relying on, if any.

Endress, citing Prantl, says that Ibn ʿAdī's source for the Liar was
Aristotle's *Sophistical Refutations* 25, along with Alexander's
commentary on *Sophistical Refutations* (Prantl 1855, 1.50, n. 83;
Endress 1977, 44). But Alexander's commentary is now thought to be
spurious (Ebbesen 1980, sec. III.4), and the traditional story tracing
medieval Latin treatments of the Liar to *Sophistical Refutations* 25
has been called into question (Spade 1973).

Alexander does discuss the Liar briefly in his commentary on *Topics*
II.7, arguing that "I lie" is not a proposition, because if it were, it
would be both true and false (Alexander 2020, 113, 188:4--189:10). Ibn
ʿAdī says that he consulted Alexander's commentary when writing his own
commentary on *Topics*, but he also says that he was unable to obtain a
copy of Alexander's commentary on *Topics* II. (Endress 1977, 25). He
also says he consulted Ammonius's commentary, which may have also
included discussion of the Liar. Unfortunately, Ammonius's commentary is
lost.

Other sources are possible. It is also possible that, as Ibn ʿAdī says,
in his time the Liar was a well-known "common problem," the sort of
thing that anyone with a logic education would know about, but not by
way of any specific textual sources.

Here is how he presents the paradox:

> Tell us about he who says, "All my sayings are false," if he has not
> spoken before, other than by declaring them all false. Do you judge
> his saying to be false or true? If you insist that it is true, then it
> must be false, and this necessarily entails that his saying is true
> and false together, and it is one saying.

The key to his solution is a curious claim about what happens when a
declarative says something about a declarative:

> If a declarative is posited as a declared-about, it ceases to be a
> declarative. (Ibn ʿAdī 1988, 202)

According to Ibn ʿAdī, this implies that the Liar is false. His
reasoning relies on making a sharp distinction between the evaluation of
the Liar in its role as a declarative and the Liar in its role as the
subject of a declarative, that is, as a "declared-about." In its role as
a "declared-about," the Liar is not a declarative and so neither true
nor false. In its role as a declarative, the Liar claims that its
"declared-about" is false. But that "declared-about," as we just saw, is
neither true nor false. So, in its role as a declarative, the Liar is
false, because what it claims about its "declared-about" is incorrect.

The idea that the Liar can be evaluated in one way as a declarative and
another as the subject of a declarative is puzzling. Does Ibn ʿAdī mean
to suggest that the Liar is really two distinct utterances, not one? Or
does he think that it is really one utterance, playing two distinct
semantic roles? Unfortunately, he fails to say anything to clarify his
position on this point.

What he does do is offer a defense of his claim that declaratives cease
to be declaratives when posited as declared-abouts:

> This is something that can be explained by induction: if you say "Zayd
> is standing" is a declarative, and "ʿAmrū is running" is a
> declarative, and "Bread is beneficial" \[is a declarative\], you are
> not declaring, in all these sayings, that Zayd is standing, or that
> ʿAmrū is running, or that bread is beneficial, and this applies to all
> other declaratives. (Ibn ʿAdī 1988, 202)

As he says, the speaker who utters,

1.  "Zayd is standing" is a declarative,

says "Zayd is standing" but does not declare it. So, assuming that a
saying must be declared to be a declarative, "Zayd is standing" is not,
as it occurs in this utterance, a declarative.

That assumption, that a saying must be declared or asserted to be a
declarative, along with the further assumption that a saying must be a
declarative to have a truth value, is the standard Aristotelian doctrine
about assertion. The doctrine is best known to contemporary philosophy
because of Frege's argument against it. As Frege points out, the
doctrine implies that the antecedent and consequent of a conditional,
since they are not asserted, have no truth values (Geach 1965).

If the doctrine is granted, Ibn ʿAdī's examples suggest a narrowly
tailored principle, only covering cases in which a saying that has the
grammar of a declarative is verbally displayed as the subject of another
declarative without actually being declared. A Liar-adjacent example
that is like this is,

2.  "All my sayings are false" is false.

In this case, the speaker says but does not declare "All my sayings are
false." Granting the Aristotelian doctrine about assertion, Ibn ʿAdī's
analysis applies brilliantly to this case: "All my sayings are false" is
not declared and so not a declarative, so neither true nor false, so
(2), which says it is false, is incorrect, and so false.

The analysis applies less brilliantly to the actual case under
discussion:

3.  All my sayings are false.

The speaker who says (3) also declares (3). And the "declared-about" of
(3) is (3) itself. So in this case, the "declared-about" is both
declared *and* verbally displayed, and it is hard to see why, in its
role as a "declared-about," the fact that it is declared should be
somehow cancelled or ignored.

Ibn ʿAdī's text is the earliest known treatment of the Liar in the
Islamic world. Although Ibn ʿAdī's Hellenistic sources are obscure, and
nothing like his solution appears in surviving Hellenistic texts, he
presents it as a well-known sophism, suggesting that it was part of the
inherited Hellenistic logical tradition he was working within. His
appeal to a distinction between the Liar as a declarative and as a
"declared-about" is a recurring theme throughout the Arabic tradition,
though later authors in the tradition show no sign of being aware of Ibn
ʿAdī's text or his specific proposal. Structurally, this distinction is
similar to the distinction made in the Latin tradition by the
"distinguentes," between the speaker's "exercised act" and "signified
act" (Spade and Read 2021, sec. 2.3) It is possible that this
distinction is also part of the inherited Hellenistic tradition.

### 2.2 Al-Naẓẓām, al-Bāqillānī, al-Baghdādī: Good, Evil, and the Liar

Ibrāhīm al-Naẓẓām (d. 845) is an important Muʿtazilī theologian, working
in Baghdād roughly a century prior to Ibn ʿAdī. His role in the history
of the Liar is minor, involving an argument against Manichaen and
Bardaisan dualists.

The dualists hold that there are two opposing cosmic principles, the
Light and the Dark. As al-Naẓẓām interprets them, they also hold that
each created agent is either a creature of the Light, who does only
good, or a creature of the Dark, who does only evil. So there can be no
"mixed" agents---agents who do both good and evil. He asks the dualist,

> What would you say about the man who says his saying is false? Who is
> the liar? (al-Khayyāṭ 1957, 28)

"The man who says his saying is false" suggests the Liar Paradox. Van
Ess comments that "the argument is structured following the model of the
sophism of the lying Cretan, but it does not need to be expressed quite
so pointedly (van Ess 2018, 3:426)." Miller says that al-Naẓẓām uses the
paradox to refute the dualists (Miller 1989, 173).

But al-Naẓẓām's ensuing discussion makes it clear that what he has in
mind is a man who tells a lie and then confesses, saying that his
earlier saying is false. There is no paradox here, just a "mixed" agent:
someone who first does something evil (lying) and then does something
good (telling the truth about his earlier lie); or someone who first
does something good (telling the truth) and then does something evil
(lying about his earlier truth-telling) his earlier truth-telling).

Following al-Nazaam, this sort of argument against dualism became a
popular trope.

The first variant of the trope to move things in the direction of the
paradox is due to al-Bāqillānī (d. 1013), an Ashʿarī theologian and
logician, working in Baghdād more than 100 years after al-Naẓẓām. He
asks the dualist,

> Tell us of someone who says, "I am dark." Does this person belong to
> the individuals of the Light or the individuals of the Dark?
> (al-Bāqillānī 1957, 67)

As al-Bāqillānī points out, someone who says "I am dark" cannot be a
creature of the dark---because then they would have told the truth, and
creatures of the dark cannot tell the truth---and also cannot be a
creature of the light---because then they would have lied, and creatures
of the light cannot lie. Structurally, this is not the Liar, but a
"Knights and Knaves" puzzle (Goodman 1973; Smullyan 1978, 20ff).

Like al-Naẓẓām and al-Bāqillānī, Abū Manṣūr al-Baghdādī (d. 1037)---who,
despite his eponym, spent most of his career working not in Baghdad but
in Nishapur---offers a counterexample to dualism that involves telling
the truth about lying. But his example is Liar paradox:

> There is no declarative that is both true and false together, except
> one: namely, the declaration by he who has not lied at all, about
> himself, that he is a liar. And this declarative, from him, is false.
> And a liar who declares about himself that he is a liar is truthful,
> and this single declarative is true and false, and the speaker is one.
> And this is a demonstration of the invalidity of the saying of the
> dualists, that the truth-teller cannot tell a lie. (al-Baghdādī 2002,
> 28)

His reasoning is not as clear as it could be, and may involve some
equivocation on what is meant by "I am a liar." He stipulates that the
speaker has "not lied at all." If "I am a liar" means "All my sayings
are false," then, as he says, a speaker who has not lied at all and says
"I am a liar" thereby says something false. But on this interpretation
of "I am a liar," this does not establish that the speaker is a liar, as
it only establishes that they something lie, not that they always lie.
So the claim that "a liar who declares about himself that he is a liar
is truthful," while correct, does not apply to this case.

Logical details aside, the most striking feature of al-Baghdādī's
treatment is his attitude toward the paradox itself. He simply accepts
the conclusion that it is both true and false. He offers no reason to
think that this is not a contradiction. His objection to dualism appears
to be that they are unable to accommodate true contradictions.

Al-Baghdādī connects this point to a point about the definition of the
declarative: no declarative is true or false together, except this one.
Writing much later, Sayf al-Dīn al-Āmidī (d. 1233), reports on debates
among the Muʿtazilī about the definition of the declarative. He mentions
the Liar alongside another problematic example,

> Muḥammad and Musaylima are truthful in declaring the prophecy
> (al-Āmidī 2004, 2:2:245)

The putative trouble here is that Muḥammad is a true prophet but
Musaylima is a false prophet, and if you say this is true, then you say
both are true prophets, but if you say it is false, you say both are
false prophets.

Al-Āmidī provides a detailed report of a wide range of responses to this
example, and these responses can be found in earlier texts from al-Qādī
ʿAbd al-Jabbār (d. 1024) and Abī ʿAbd Allāh al-Basṛī (d. 980). He
reports no responses to the Liar, and no discussion of the Liar can be
found in those earlier texts.

### 2.3 Al-Fārābī and al-Rāzī: From self-falsification to paradox?

Some positions are self-refuting. Famously, Plato argues that the
opinion that every opinion is true is self-refuting, since, in his own
opinion, it is false, so if every opinion is true, then his opinion is
true, so it is false that every opinion is true (*Theaetetus*
170d-171c). Aristotle extends this point, giving several additional
examples of self-refuting claims. One of his examples is the claim,
"Everything is false." This cannot be true, he argues, since if it were,
it would be false (*Metaphysics* IV 1012b14-19).

It is possible to generate the Liar Paradox from this sort of example,
by stipulating that "Every saying is false" is the only thing anyone
ever says, so that the claim is both self-refuting and self-verifying.
But neither Aristotle nor his Hellenistic commentators do this. The
example is and remains an example of self-refutation or
self-falsification, not an example of paradox.

Al-Fārābī's treatment of the example follows this pattern. But in one
place, the example he uses is not "Everything is false" or "Every saying
is false," but "the saying of he who says that all he says is incorrect
(*bāṭil*)" (al-Fārābī 1987--1989, 348). This is the same example seen in
his contemporary Ibn ʿAdī, "All my sayings are false," without the
paradox-inducing stipulation that it is the only thing the speaker ever
says.

Fakhr al-Dīn al-Rāzī's (d. 1209) treatment of the topic make the
connection to the Liar explicit. Giving an example of a declarative that
can be known to be false because it is self-refuting, he says,

> Within this type is the saying of he who never lied at all, \[and\]
> says, "I am a liar." This declarative is false. This is because he is
> saying the declared-abouts are false. These are either earlier
> declaratives, or this declarative. The first is incorrect (*bāṭil*),
> because these declaratives were not false, so his declaring of himself
> that he is lying in them is false. The second is incorrect, because
> the declarative about something is later in order than the
> declared-about. So if the declarative were made the same as the
> declared-about, that would entail that the thing is later in order
> than itself, and that is impossible. (al-Rāzī 2011, 4:291)

Notice that the initial example, "I am a liar", is the same as
al-Baghdādī's, as is the stipulation that the speaker "never lied at
all" prior to saying this.

Al-Rāzī says that there are two possible interpretations of "I am a
liar." On the first, it means "All my earlier declaratives are false,"
and this is false, given the stipulation. On the second, it means "This
declarative is false." But this is also incorrect, he says, because the
declarative must be "later in order" than the declared-about, so they
cannot be the same.

Al-Rāzī's use of 'incorrect (*bāṭil*)' leaves open room for two
different interpretations. The most obvious way for a declarative to be
incorrect is for it to be false, and that is exactly what happens on the
first reading of "I am a liar": it is incorrect because it is false. But
what about the second reading? Is "This declarative is false" *false*,
given that the declarative must be distinct from the declared-about, or
is it defective in some other way?

Al-Rāzī's topic---declaratives that are known to be *false*, not
declaratives that are known to be *false or otherwise defective*--favors
the first interpretation. Perhaps the idea is that, since a declarative
cannot declare something about itself, "This declarative is false" has a
vacuous subject, and so, being an affirmative with a vacuous subject, is
false.

In another text on the same topic, al-Rāzī alters the example and takes
it in a different direction:

> \[A declarative is known to be false\] if it contradicts itself, as
> when one says, "All my sayings are false." For on the assumption that
> it can be said that all his sayings at prior times were false, he was
> truthful in declaring that he was false. And on the assumption that he
> was saying this saying is false, he was truthful in some priors
> (al-Rāzī 1994, 138; see also Ibn Kammūna and al-Kātibī 2007, 245).

Here, the unambiguous "All my sayings are false" replaces the ambiguous
"I am a liar." And the stipulation, that all the prior sayings are
false, is the proper stipulation needed to generate a paradox. But
otherwise, the logic of the passage is difficult to parse.

On one interpretation, al-Rāzī offers a solution to the Liar based on
the idea that it is false because it contradicts itself. This is how
al-Kātibī reads the passage, and so, historically, this reading is the
most influential (Ibn Kammūna and al-Kātibī 2007, 245). On another
interpretation, despite appearances, al-Rāzī is just making the old
Aristotelian point, that "All my sayings are false" is self-refuting,
and the passage is not actually about the Liar paradox at all (Alwishah
and Sanson forthcoming).

## 3. The 13th and 14th Centuries: A Conjunction of Two Contradictories

Prior to the 13th century, treatment of the Liar is spotty and isolated.
In the 13th century, it becomes a standard example of an especially
difficult fallacy, often referred to generically as "the problem of the
conjunction of two contradictories." Several authors take the problem
up, offering competing solutions and expressing disagreement or
agreement with each other.

This continues into the 14th century, which also sees a second
development, as al-Taftāzānī draws a connection between the Liar and
theological arguments against the view that good and evil can be judged
by reason. As part of this, he introduces a Liar cycle, based upon an
older theological example of a man who gets himself into a moral pickle
by saying, "I will lie tomorrow." As he points out, with just a few
tweaks, the man lands himself in a logical pickle as well. Also, he
gives the paradox a somewhat puzzling new name, widely adopted by the
later tradition, calling it "the paradox of the irrational root."

### 3.1 Al-Abharī and al-Kātibī: Self-contradiction

13th century engagement with the Liar beings with Najm al-Dīn al-Kātibī
(d. 1276) and Athīr al-Dīn al-Abharī (d. 1258/1265). Al-Kātibī was
al-Abharī's student, though there is some evidence that they had a
falling out. Across several texts, each presents and defends the same
solution, neither ever mentioning the other (al-Abharī 1998, 217ff;
2018, 382ff; 2020, 183; al-Kātibī 2022, 683; 2019, 130; Ibn Kammūna and
al-Kātibī 2007, 245). Al-Ṭūsī, their contemporary and associate,
criticizes al-Abharī's solution without mentioning al-Kātibī. Al-Dawānī
and al-Dashtakī criticize al-Kātibī's solution without mentioning
al-Abharī.

The basic idea, perhaps echoing al-Rāzī, is that the Liar is false
because its truth implies a contradiction. By itself, this is not a
solution. The Liar presents two competing arguments, one showing that
its truth implies a contradiction, and the other showing that its
falsehood does too. Solving the paradox is not a matter of picking
sides, and deciding to accept the first and so reject to the second, or
vice versa. (For this objection, see al-Dashtakī 2007, 31.)

But that is not what al-Abharī and al-Kātibī do. Instead, they try to
leverage the first argument, using it to identify a fallacy in the
second. They argue that, since the truth of the Liar *is* the
conjunction of its truth and falsehood, its falsehood is the
non-conjunction of its truth and falsehood. Here is al-Kātibī, from his
commentary on al-Rāzī:

> \[The Liar's\] falsehood is determined after the affirmation of what
> its utterance signifies. And what its utterance signifies is that this
> saying is true and false. So its falsehood is the non-affirmation of
> this conjunction. (Ibn Kammūna and al-Kātibī 2007, 245)

They then use this to identify a fallacy in the second argument---the
argument that the falsehood of the Liar implies that it is both true and
false. This argument, they say, requires a fallacious inference from the
negation of a conjunction to the negation of one of its conjuncts. So,
something like this:

1.  The Liar is false. (Assumption)
2.  If so, it is not both true and false. (By the principle defended
    above)
3.  If so, it is not false (The fallacious inference)
4.  If so, it is true.
5.  If so, it is both true and false.

There are at least two problems with this analysis.

First, despite the formal fallacy, it is not clear that the argument is
invalid. When "*p*" and "*q*" are logically equivalent, "not *p*" and
"not *q*" both follow from "not (*p* and *q*)." Arguably, that is the
case here, as the truth of the Liar implies its falsehood, and its
falsehood implies its truth, so the two conjuncts are logically
equivalent.

Second, the analysis does nothing to prove that every argument from
false to true must proceed in this formally fallacious way. Here, for
example, is another argument from false to true:

1.  The Liar is false. (Assumption)
2.  If so, things are as it says. (Because the Liar says it is false)
3.  If so, it is true. (By the general principle that a declarative is
    true when things are as it says)

Unfortunately, neither al-Abharī nor al-Kātibī ever directly address
this objection.

Contemporary interpreters suggest reading al-Abharī and al-Kātibī
through the lens of a cluster of 14th century Latin proposals defended
by Thomas Bradwardine (d. 1349), John Buridan (d. 1358), and Albert of
Saxony (d. 1390) (Alwishah and Sanson 2009, forthcoming; Zarepour 2021;
Spade and Read 2021, sec. 3.1). On this reading, it is not just that the
truth of the Liar *implies* that it is both true and false; it is that
this is what the Liar *says* or *signifies*.

On its face, the Liar, "All my sayings at this moment are false," says
that it is false. The claim that it *also* says or signifies that it is
true, and so says or signifies that it is both true and false, requires
some further non-obvious principle about what sayings say or signify.
One such principle is the principle that every saying signifies that it
is true, in addition to whatever it says on its face. Another is the
principle that, in addition to what it says on its face, every saying
signifies everything that logically follows from that.

Neither al-Abharī nor al-Kātibī explicitly endorse any such principles.
But they do say not just that the truth of the Liar *is* its truth and
falsity, not just that it *implies* its truth and falsity. And, in one
place, as quoted above, al-Kātibī says that the utterance of the Liar
*signifies* that it is both true and false. Endorsing some such
principle would allow them to reject the claim that, since the Liar is
false, things are as it says, so it is true. From the fact that the Liar
is false, all that follows is that things are partly how it says, which
is not enough to establish that it is true.

### 3.2 Al-Ṭūsī: Truth, Correspondence, and Distinctness

Nasīr al-Dīn al-Ṭūsī (d. 1274) was a contemporary of al-Abharī and
al-Kātibī, and the founding director of the Maragha observatory, where
al-Kātibī also worked later in his career.

Al-Ṭūsī argues that the Liar has no truth value. He grants that it is a
declarative, and so is the kind of saying that is apt to be true or
false, but he argues that it cannot be true or false because it is
self-referential. Truth, he says, requires a correspondence relation
between a declarative and the things it is about, its "declared-abouts".
And falsehood requires a non-correspondence relation. But both
relations, correspondence and non-correspondence, require distinct
relata. So self-referential declaratives, like the Liar, cannot be true
or false.

Others in the tradition argue that self-reference is impossible (see
[Section 2.3](#al-fārābī-and-al-rāzī-from-self-falsification-to-paradox),
[Section 3.3](#al-samarqandī-dual-evaluations), and
[Section 3.5](#al-jurjānī-self-reference-and-speaker-intention)). But
al-Ṭūsī's point is not that self-reference is impossible. Instead, he
argues that when self-reference occurs, truth and falsity are
impossible.

The claim that self-referential declaratives are neither true nor false
conflicts with the standard definition of declaratives, as sayings that
are either true or false. Saʿad Ibn Mansūr Ibn Kammūna (d. 1284), a
Jewish philosopher working in Baghdād, offers two responses to this
objection on al-Ṭūsī's behalf, though he never mentions al-Ṭūsī by name.
In a fragment of his correspondence with al-Kātibī, he suggests that the
mark of a declarative is not that it is true or false, but that it can
be *judged* to be true or false (al-Dawānī 2007, 119). Elsewhere, he
suggests that falsehood is the simple negation of truth rather than its
metathetic negation, so, while truth requires correspondence (and so
distinct relata), falsehood does not require non-correspondence, and so
does not require distinct relata. Instead, the absence of correspondence
is enough to make the Liar false (Ibn Kammūna 2008, 74--75).

Ibn al-Muṭahhar al-Ḥillī (d. 1325) endorses al-Ṭūsī's solution (and,
unlike Ibn Kammūna, attributes it to al-Ṭūsī). His only disagreement
concerns the identification of the fallacy. Al-Ṭūsī says that the Liar
involves a fallacy of "the misuse of the predicate." Although later
authors in the tradition lose track of this, and so find this confusing,
this is Avicenna's name for fallacies *secundum quid* (See Avicenna
1958, 21)). Al-Ḥillī says that this is wrong, and it is instead the
fallacy of accident, "taking what is an accident in place of what is an
essence" (al-Ḥillī 2000, 233). Both fallacies involve a failure to
recognize exceptions to a general rule---in this case, presumably, the
general rule that a declarative must be either true or false. It is not
clear why al-Ḥillī thinks this case is better described as a fallacy of
accident than a fallacy *secundum quid*.

Al-Dawānī and al-Dashtakī raise the obvious objection, that not all
self-referential declaratives are paradoxical, and many are clearly
either true or false. For example, "This saying is composed" (that is,
composed of words) is true, and "This saying is not composed" is false.

Al-Ṭūsī does not simply assert that correspondence and
non-correspondence require distinct relata. He suggests that distinct
relata are required to sustain the structure of opposition found between
a declarative and its negation:

> Upon investigation, truth and falsity apply to every declarative that
> is distinct from its declared-about, so that it is conceived that this
> declarative and a declarative opposite to it are standing on contrary
> sides, such that, if one of them corresponds to the declared-about,
> the other does not correspond to it, so that one of them is true and
> the other of them is false. \[...\] However, if the declarative is the
> same as the declared-about, then truth and falsity are not conceived
> from it, for correspondence is not conceived except between two
> things, and the contrary \[to correspondence\] is not conceived
> \[except between two things\]. For if one thing is affirmed, then
> nothing is denied, and if one thing is denied, then nothing left to be
> affirmed is conceived. (al-Ṭūsī 1974, 237)

One might be tempted to claim, contrary to al-Ṭūsī, that correspondence
does not require distinct relata, and that, in fact, everything
corresponds to itself. But notice that this entails that all
self-referential declaratives are true: "This saying is composed"
corresponds to itself, and so is true; but also, "This saying is not
composed" corresponds to itself, and so also is true. This example is
not quite the same as what al-Ṭūsī has in mind above, since the second
declarative is not the negation of the first, since "this saying" refers
to different sayings in each case. Still, it is an example of the way
that the structure of opposition between affirmation and negation, and
truth and falsehood, threatens to break down in cases of
self-correspondence.

Al-Ṭūsī raises a related concern about self-correspondence, truth, and
falsehood in the case of mathematical judgment. According to Avicenna,
mathematical objects exist in the mind. Al-Ṭūsī argues that, if this
were correct, then the truth of a mathematical judgment, like the
judgment that 1 is half of 2, would consist in a correspondence between
a mental relation and itself. That is because there would be no
distinction between the mental relation that is the judgment, and the
mental relation between 1 and 2 as they are in themselves. But this
would imply, al-Ṭūsī argues, that all mathematical judgments are true,
including the judgment that 2 is half of 1 (See Zarepour 2022; Erdt
2024; Spiker 2021; Ahmed 2022).

Al-Ṭūsī does not connect this argument with his solution to the Liar,
but the connection is clear (See Qarāmaleki 2016; Motavalli and
Qarāmaleki 2021; Alwishah and Sanson forthcoming). In both cases, the
worry is that allowing self-correspondence as truth would obliterate the
opposition between truth and falsehood, by making everything true. In
the mathematical case, al-Ṭūsī avoids the problem by insisting on
distinct relata, rejecting Avicenna's claim that mathematical objects
exist as they are in themselves in the mind. Instead, they exist as they
are in themselves outside the mind, in the universal active intellect.
So the truth of mathematical judgment involves a correspondence relation
between two distinct things: the judgment in the mind, and the thing
itself outside the mind, in the universal active intellect. In the case
of the Liar, self-reference cannot be avoided, so he concludes that it
cannot be true or false.

None of this is to suggest that al-Ṭūsī's solution to the Liar succeeds.
But it does suggest that his solution is not an *ad hoc* restriction on
self-referential truth introduced to avoid paradox, but is instead
grounded in systematic worries about the role correspondence and
non-correspondence play in the theory of truth.

### 3.3 Al-Samarqandī: Dual Evaluations

Little is known about the life of the logician, theologian, and
mathematician, Shams al-Dīn al-Samarqandī (d. 1322).

Like al-Rāzī, he points out that the Liar can be given a non-paradoxical
reading. Specifically, when someone says, "All my sayings in this moment
are false," their intention determines exactly which sayings they are
talking about. So if they only intend to include that all their *other*
sayings at the moment, there is no paradox. Moreover, since this is the
only thing they say at that moment, there are no other sayings, so "All
my sayings" is vacuous, and "All my sayings at this moment are false,"
is therefore false.

The paradox occurs when the speaker intends to include the Liar as one
of the sayings they are talking about. In this case, al-Samarqandī says,
"it is as if he spoke this saying, and then said again, 'This saying is
false.'" And so, "in this saying, he has conjoined two declaratives,
each attached to the other," one declaring the other to be false
(al-Samarqandī 2020, 646).

Granting this analysis, the paradox once again dissolves. When one
declarative declares another to be false, if the first, the
"declared-about," is true, then the second, the "declarative," is false,
and if the first is false, the second is true. Either way, there is no
contradiction, since truth and falsity are being applied to two
different declaratives.

But, of course, even if, in the case of the Liar, it is in some sense
"as if" the speaker uttered two declaratives, one declaring the other
false, in fact he only uttered one. His shorter treatment, in his book,
*al-Qisṭās*, al-Samarqandī has no response to this objection. But in his
longer autocommentary, *Sharḥ al-Qisṭās*, he argues that, since there is
only one declarative, in effect the first declarative fails to exist,
leaving just one declarative, saying of a non-existent declarative that
it is false. In that case, the declarative is false, since it is an
affirmative with a vacuous subject (al-Samarqandī 2023).

One might further object that the Liar says that it itself is false. It
does not say that some *other* (existent or non-existent) declarative is
false. This brings things back to al-Samarqandī's "as if" claim. While
he says that it is "as if" the speaker who utters the Liar utters two
declaratives, his actual view appears to be that the speaker really does
utter two declaratives, not one. The predicate "false", he says, plays
two roles. In one role, it is part of a declarative that declares
something. In the other role, it is part of a declarative that something
is declared about. At this point, he asserts, without further argument
or explanation, that this entails that the speaker "has conjoined two
declaratives, each attached to the other." But since he later admits
that one of these two declaratives might not exist, it might be better
to say that the speaker has done something that in some sense *requires*
two declaratives, each attached to the other. Unfortunately, he does not
explain why the two roles must have distinct occupants.

The resemblance Ibn ʿAdī's solution and the Latin *distinguentes* was
mentioned above. The resemblance here is even more striking, especially
with respect to al-Samarqandī's simplest proposal.

### 3.4 Al-Taftāzānī: Voluntarism, Liar Cycles, and Irrational Roots

Saʿd al-Dīn al-Taftāzānī (d. 1392), is a prominent 14th century scholar,
known for his work in linguistics, grammar, logic, and jurisprudence.
His treatment of the Liar is something of an anomaly, occurring not in a
work on logic, but in a work on theology, and his proposed "solution"
hardly qualifies as a solution.

He is responsible for giving the Liar an odd name, calling it, without
further explanation, "the paradox of the irrational root (*jadhr
al-aṣamm*)." The label proved popular, and shows up in the titles of
many later works, including al-Dawānī's treatise on the Liar. Writing a
century and a half after al-Taftāzānī, ʿIṣmat Allāh b. Kamāl al-Dīn
al-Bukhārī (d. 1540) has no idea why it is called this, and offers three
speculations: first, that it is a reference to the idea that irrational
roots, like the square root of 2, are unknowable; second, that it
second, that, since '*aṣamm*' can mean 'backbone' instead of
'irrational', and 'root (*jadhr*)' can also mean "pull up from the
roots," the Liar is so-called because it pulls the backbone of logic,
the principle of non-contradiction, up from its roots; third, that,
since '*aṣamm*' can mean 'mute', and '*jadhr*' can mean 'source', the
Liar is so-called because the person who came up with the puzzle was
deaf. Al-Bukhārī confidently adds that this last explanation cannot be
correct, because the man who first came up with the puzzle, Ibn Kammūna,
was not deaf (al-Bukhārī 2007, 315--16).

Sanson and Alwishah (2017) and Alwishah and Sanson (forthcoming) offer
some further speculations. Perhaps the most plausible, which they
attribute to Henry Mendell, is that the name is a reference to one of
the standard examples of an argument by *reductio*, the ancient proof
that the diagonal of a square is incommensurable with its sides (See
Aristotle 2009, 41a22--37; Alexander 2014, 41a26--37). That proof
assumes that the diagonal is commensurable to a unit side, and shows
that, if so, it would be both odd and even, just as, in the case of the
Liar, we assume it is true or false, and show that, if so, it would be
both true and false. And if we think of truth and falsehood as relations
or ratios between a declarative and what it is about, we might describe
the Liar as a declarative for which no such ratio exists, and so a
declarative that is neither true nor false, just as the diagonal is
neither odd nor even.

His solution appeals to the distinction between truth and falsity
occurring as the content of a judgment, and truth and falsity occuring
as properties or states of a judgment:

> Truth and falsity, in the same way they are states for judgment, as
> affirmative and negative relations, required of all propositions, can
> \[also\] be a judgment. That is, what is judged is predicated of
> something indirectly, as when we say, this is true and that is false.
> And they are not contradictory to each other unless we consider them
> as two states for one judgment, or two judgments for one subject, as
> opposed to if we consider one of them as a state for judgment and the
> other as a judgment. (al-Taftāzānī 1998, 4:287)

This distinction applies to any predicate that applies to judgments: a
judgment can be rash or measured, and it can also be judged to be rash
or measured. In the first instance, rashness and being measured are
"states of a judgment"; in the second, they "are judgments" made about a
judgment.

Suppose Zayd's judgment is measured, and you judge it to be rash. As
al-Taftāzānī says, there is no contradiction here. There is only a
contradiction when the two contradictory properties occur both as states
of the same judgment, or both as judgments on the same state. In the
first case, there is a contradiction in the world---Zayd's judgment is
both rash and measured; in the second, there is a contradiction in your
judgment---you judge Zayd's judgment both to be rash and to be measured.

Described in these terms, the Liar is a judgment that has two possible
states---truth and falsehood---and it is also a judgment that judges
itself to have one of these two states, falsehood. This is not yet a
contradiction: truth occurs as one of two possible states; falsehood
occurs as a judgment. But a contradiction follows: if the Liar is true,
the judgment that it is false is false, and so the Liar is false. And
this is now a contradiction: the same judgment has both the state of
truth and the state of falsehood. Likewise, if it is false, then the
judgment that it is false is true, and so the Liar is true. Again, we
have a contradiction: one judgment in contradictory states.

But al-Taftāzānī does not think this is what happens. As he sees it,
when we attempt to generate our contradiction, we start from an
assumption about a state of the "original judgment", then introduce a
*new* judgment about that original judgment, and conclude that the *new*
judgment has a contradictory state. For example, if we assume that the
state of the Liar---the "original judgment"---is that it is false, we
can then introduce a *new* judgment judging it to be false, and infer
that this new judgment is true. In this case, both truth and falsity
occur as states of *different* judgments, so there is no contradiction.

This is al-Samarqandī's first solution re-described. The Liar is not one
but two judgments/declaratives, one judging/declaring the other to be
false. So, if the first is true the second is false, and if the first is
false the second is true, neither of which is a contradiction.

To his credit, al-Taftāzānī did not appear to think to highly of his own
proposal. He says,

> However, the correct judgment regarding this proposition is to give up
> on a solution and admit that we are unable to solve the paradox.

This is where things get interesting.

As mentioned above, al-Taftāzānī discusses the Liar in theological
rather than logical context, and his immediate concern is good and evil,
not truth and falsehood. Specifically, he is arguing against the
Muʿtazilī view that good and evil are "intrinsic" and can be judged by
reason, and in favor of the Ashʿarī view that good and evil are instead
grounded in divine command.

He rehearses several arguments for this position, and many involve the
ethics of lying. For example, reason judges that lying is always wrong,
but it also judges that one must lie to the murderer at the door. This
shows that reason cannot be used to judge good and evil, without falling
into confusion and contradiction (al-Taftāzānī 1998, 4:285).

Another argument involves the example of a man who says, "I will lie
tomorrow":

> If goodness and badness are intrinsic, then this entails the
> conjunction of two contradictories, as in the case of the one who
> says, "I will lie tomorrow." For either he is truthful, so his truth
> entails his goodness, and entailing the lie tomorrow, his badness; or
> he is a liar, so his lie entails his badness and entailing the truth
> tomorrow \[entails\] his goodness. And thus, it is possible to
> establish that there is a conjunction of two contradictories in the
> declarative, "I will lie tomorrow." (al-Taftāzānī 1998, 4:286)

Once again, attempting to use reason to judge good and bad leads to
contradiction. In this case, the contradiction is that someone who says
"I will lie tomorrow" has done something that is both good and bad.

There are obvious objections to this argument. For present purposes, its
interest lies in the fact that al-Taftāzānī connects the example to the
Liar:

> And this fallacy can be set up in such a way that truth and falsehood
> are conjoined in one saying, and thus goodness and badness are
> conjoined. For if we consider a proposition whose purport is to
> declare itself not to be true, then truth and falsehood are entailed
> in it, as when you say that the saying I now speak is not true, for
> its truth entails the absence of its truth and vice versa.
> (al-Taftāzānī 1998, 4:286--87)

Having done this, he then goes a step further, using the temporal
structure of the original example to generate Liar cycle:

> And this can be expressed in the form of "tomorrow" and "yesterday"
> sayings. For if one says that the saying I speak tomorrow is not true,
> or that nothing I say tomorrow is extrinsically true, and then
> tomorrow his only saying is, "The saying I spoke yesterday is true,"
> then the truth of either the "tomorrow" saying or the "yesterday"
> saying entails the absence of the truth in both cases, and vice versa.
> (al-Taftāzānī 1998, 4:287)

This is the first Liar cycle introduced into the tradition. It causes
trouble for most of the prior solutions, including al-Taftāzānī's own.
But al-Taftāzānī does not seem to notice this.

### 3.5 Al-Jurjānī: Self-reference and Speaker Intention

Al-Sharīf al-Jurjānī (d. 1413) was a celebrated grammarian and logician,
working in Shiraz. His views about the Liar survive in the form two
conflicting reports, one from al-Dashtakī and the other from al-Dawānī,
both students of students al-Jurjānī, who treat him as a respected
authority (Pourjavady 2011, 4, 9). It is quite possible that their
conflicting reports have little to do with anything al-Jurjānī actually
said, and simply reflect their attempts to position themselves in
relation to his authority.

According to the first report, from al-Dashtakī, al-Jurjānī held that
self-reference is impossible. So, when someone says, "All my sayings in
this moment are false", that very saying cannot be among the sayings
they refer to. The report does not include any further information about
what is taken to follow from this. Perhaps the upshot is that the "All
my sayings in this moment" is vacuous, and so "All my sayings in this
moment are false" is false.

According to al-Dawānī, self-reference is impossible in the case of
demonstrative pronouns. When someone says, "Those men are walking," for
example, they must *specifically intend* each man referred to by "those
men." This requires a *prior perceptual connection* to each of those
men, and so implies that each of those men must exist prior to becoming
a referent. Likewise, then, someone who says, "Those declaratives are
false," cannot include that very declarative as one of the referents of
the demonstrative pronoun, "those declaratives." And, by the same token,
someone who says, "This declarative is false," cannot include that very
declarative as the referent of "this declarative," assuming "this
declarative here functions as a demonstrative pronoun.

Although al-Dawānī accepts this view of how demonstrative pronouns work,
he does not accept it a view about how all reference works.
Specifically, he rejects the idea that each referent of a universal
terms like "All men" or "All my sayings at this moment", must be
specifically intended by the speaker.

The second report, from al-Dawānī, is second-hand, but, he thinks, more
plausible and therefore more likely to reflect what al-Jurjānī actually
said:

> A declarative is a reference (*ishāra*) to the state of the thing it
> is about, and the reference to a thing cannot be a reference to this
> reference itself. Thus, the declarative itself cannot enter into the
> judgment that contains the declarative, hence the judgment does not
> include it, as if it were excluded. And it is not the point of this
> that it is not one things the declarative is about, nor that it is not
> one of its subjects, but rather that the reference is unable to
> include itself. (al-Dawānī 2007, 118--19)

This is strikingly similar to al-Dawānī's own view, though expressed in
different terms.

## 4. The 15th Century

In the late fifteenth century, two scholars, Ṣadr al-Dīn al-Dashtakī
(d. 1498) and Jalāl al-Dīn al-Dawānī (d. 1502), both working in Shiraz,
engaged in extended debate over several interrelated topics, one of
which was the Liar. This debate began in correspondence, continued in
their competing glosses on al-Qūshjī's commentary on al-Ṭūsī's *Tajrīd*,
and culminated in two freestanding treatises on the topic. At around the
same time, or perhaps a bit earlier, an Ottoman scholar of uncertain
identity defended his own solution to the Liar, responding primarily to
al-Taftāzānī.

### 4.1 Ḫaṭībzāde (?): States, Judgments, and Self-Contradiction

A late 15th century work, attributed to both Ḫocazāde Muṣliḥuddīn Efendī
(d. 1488) and Ḫaṭībzāde Muḥyiddīn Efendī (d. 1496), takes al-Taftāzānī
as its jumping off point for a discussion of the Liar (Dasdemir 2023;
Daşdemir 2023; Aydin 2014). As with al-Taftāzānī, the context is once
again theological rather than logical, focused on arguments against the
view that good and evil and are not intrinsic.

Following al-Taftāzānī, the author emphasizes the distinction between
truth and falsehood as *judgments* versus truth and falsehood as
*states* of judgments. He rejects al-Taftāzānī's solution, and offers
three different solutions of his own, all based on the idea that the
Liar is not a declarative because it fails to have proper truth
conditions.

First, he argues that no judgment can judge itself to be true or false.
His argument depends on two key claims. One is the claim that the state
of being true or false is "essentially distinct" from the judgment that
has it:

> \[...\] This state (truth or falsehood) is distinct from the judgment,
> essentially distinct, since its meaning is (in the case of truth) the
> correspondence of the judgment to reality, or (in the case of
> falsehood) its absence. (Ḫaṭībzāde \[?\] 2023, 227)

The other is the claim that, when a state is essentially distinct from a
judgment, that judgment that something has that state is essentially
distinct from the thing that has that state:

> The judgment of a state of the thing that is essentially distinct from
> it is also essentially distinct from that thing, and this is clear.
> (Ḫaṭībzāde \[?\] 2023, 227)

Together, these entail that no judgment can judge itself to be true or
false.

On the basis of this argument, Dasdemir attributes to the author a
blanket restriction on self-reference---no judgment can judge anything
about itself---similar to restriction attributed to al-Jurjānī by
al-Dashtakī (2023, 245ff). But the first claim only establishes that the
states of *truth* and *falsehood* are essentially distinct from the
judgments that have them, so the argument only rules out a judgment that
judges itself true or false. There is nothing here to suggest that a
judgment cannot judges itself to be composed of subject and predicate,
or judge itself to be rash, or hasty. The argument narrowly targets
self-referential judgments of truth and falsity.

As for the Liar, the author concludes that, because it attempts to judge
(or declare) itself to be true or false, and that is impossible, it not
a judgment (or declarative) at all.

This solution shares a great deal with al-Ṭūsī. Al-Ṭūsī holds that a
declarative can declare itself false, but such a declarative cannot be
true or false, because truth and falsehood require correspondence and
non-correspondence, which require distinct relata. This author holds
that a declarative cannot declare itself false, because if it did, it
could not be true or false, because truth and falsehood require
correspondence and non-correspondence, which (he appears to assume
without saying) require distinct relata.

The author's second solution is presented as a solution to
al-Taftāzānī's Liar Cycle. Here, the author relies on the claim that a
declarative must be able to be actualized "with each of truth and
falsity, one in lieu of the other (Ḫaṭībzāde \[?\] 2023, 228)." That is,
to be a declarative, a saying must be able to be true without also being
false, and vice versa. When our speaker says today, "My saying tomorrow
is false," and then says tomorrow, "My saying yesterday is true," his
saying today is true if false and false if true. That is, it cannot be
true without also being false, and it cannot be false without also being
true. So it is not a declarative.

On an alternate reading, the author instead holds that, to be a
declarative, a saying must be able to be true *and then* false (Daşdemir
2023, 253). This has the radical implication that all declaratives are
temporally contingent "tensed" declaratives, like "It is raining," which
can be true today but false tomorrow.

The author's third solution is appeals to the claim that no declarative
can signify both an affirmative and a negative judgment about the same
relation at the same time:

> \[These\] two significations, namely, the signification of the
> affirmative judgment and the signification of the negative judgment,
> cannot be conjoined in one saying. (Ḫaṭībzāde \[?\] 2023, 229)

For example, "Zayd is standing" signifies an affirmative judgment about
the relation between Zayd and *standing*, while "Zayd is not standing"
signifies a negative judgment about that same relation. But a
declarative that somehow does both at the same time---like "Zayd is
standing and Zayd is not standing"?---is impossible.

But this is what the Liar does, because it signifies both the
affirmative judgment that it false, and the negative judgment that it is
not false, because

> the declarative that any proposition is false \[...\] includes a
> declarative that the affirmative relation between the predicate and
> the subject of that proposition does not obtain. (Ḫaṭībzāde \[?\]
> 2023, 229)

This is similar to the solution defended by al-Abharī and al-Kātibī, who
also hold that the Liar signifies a contradiction. But they conclude
from this that the Liar is false, while this author concludes that it
fails to be a declarative.

### 4.2 Al-Dashtakī: Something Missing

According to al-Dashtakī, the Liar is one declarative that predicates
falsehood twice. But, he argues, a declarative that predicates a truth
value twice requires the existence of two declaratives. Since the Liar
is just one declarative, not two, it fails to meet this requirement.

His argument that a declarative that predicates two truth predicates
requires the existence of two declaratives begins with the point,
familiar from Ibn ʿAdī, that a declarative that predicates truth or
falsity of another declarative requires the existence of that other
declarative:

> Truth and falsehood require the actualization of the declarative to
> which they are attributed. If this declarative is actualized, then the
> attribution of one of them is correct, otherwise it is not. But if the
> declarative they are attributed to is missing, then it is not correct
> to attribute truth or falsehood to it.

For example, if Zayd has not declared anything, and someone says,
"Zayd's declarative is false," their declarative is not correct, because
Zayd's declarative does not exist.

Al-Dashtakī says that a declarative that violates this condition is
"incorrect (*bāṭil*)". As with al-Rāzī, this leaves open room for two
different interpretations. He could mean that such declaratives are
false (Alwishah and Sanson forthcoming), or he could mean that they are
semantically defective in some way. Along these lines, Zarepour suggests
a proto-Frege interpretation: since the subject has no referent, the
sentence as a whole has no truth-evaluable semantic content. (2023,
12--13). On the first interpretation, al-Dashtakī's position fits with
the orthodox Aristotelian view that affirmatives with vacuous subjects
are false. On the second, al-Dashtakī radically breaks from that
tradition.

Either way, al-Dashtakī infers from this that a declarative that
"considers truth or falsity twice" requires two declaratives:

> This is if one considered truth and falsity once. However, if one
> considered them twice, then this requires two declaratives, as when
> you say "'Zayd's declarative is true' is true" or "'Zayd's declarative
> is false' is false." So it is not sufficient for it to be correct that
> we have one declarative, rather it requires two declaratives to be
> actualized, one of them a declaring about something, and the second a
> judgment on this declarative, namely that it is true or false.

He works through several of the relevant possibilities. For example,
suppose Zayd declares something, but nobody declares "Zayd's declarative
is true." In this case, regardless of what Zayd declared, it would be
incorrect to attribute truth or falsehood to "Zayd's declarative is
true," because it does not exist. So, both "'Zayd's declarative is true'
is true" and "'Zayd's declarative is true' is false" are incorrect.

He does not explicitly consider the opposite case, where Zayd does not
declare anything, but somebody declares "Zayd's declarative is true" and
somebody else declares "Zayd's declarative is false." In this case, the
orthodox Aristotelian should infer that "Zayd's declarative is true" is
false, on the grounds that it has a vacuous subject. So "'Zayd's
declarative is true' is false" is *correct*, contrary to what
al-Dashtakī claims. Likewise, "Zayd's declarative is false" is also
false, for the same reason. So "'Zayd's declarative is false' is false"
is also *correct*.

Zarepour's proto-Fregean reading saves al-Dashtakī from this
embarassment. On that reading, since Zayd did not declare anything, both
"Zayd's declarative is true" and "Zayd's declarative is false" lack
truth-evaluable content, so both "'Zayd's declarative is true' is false"
and "'Zayd's declarative is false' is false" lack truth-evaluable
content as well.

El-Rouayheb offers a third interpretation (2019b, 11; 2019a, 101). As he
understands al-Dashtakī, a declarative that considers truth or falsehood
twice is structurally defective. In the non-defective case, Zayd
declares something, someone declares "Zayd's declarative is true," and
someone declares "'Zayd's declarative is true" is false." In the
defective case, that second step is skipped. Instead, Zayd declares
something, and someone attempts to apply both predicates, "is true" and
"is false," all at once: "Zayd's declarative *is true is false*." The
result is a structurally defective declarative, composed of a single
subject and two predicates.

Finally, there is al-Dashtakī's claim that the Liar "considers falsity
twice." In support of this, al-Dashtakī argues that when someone's only
saying in a given day is, "My sayings today are false," the subject, "My
sayings today," picks out the saying, "My sayings today are false," so
the predicate, "is false", is applied to "My sayings today are false."
In other words, it is "as if" the speaker said, "'My sayings are false'
is false," a declarative that considers falsehood twice (al-Dashtakī
2007, 56; al-Dawānī 2007, 125).

This recalls al-Samarqandī's position, that the person who speaks the
Liar "has conjoined two declaratives, each attached to the other," but,
in doing so, has only produced a single declarative, so one of the two
conjoined declaratives fails to exist, rendering the other false.

### 4.3 Al-Dawānī: Fruitless Self-Imitation

Al-Dawānī argues that the Liar is not a declarative, and is not a
truth-apt saying, because it fails to be an imitation (*ḥikāya*) of a
relation in reality (*nisba wāqiʿiyya*).

He connects this proposal to a long-standing debate about the
distinction between declarative and non-declarative sayings. By
al-Dawānī's time, this distinction was understood as a distinction
between a declarative (*khabar*) and an *inshāʾ* (Firanescu 2006;
Larcher 1990, 198ff). The word "*inshāʾ*" is often translated using
Austin's now-familiar neologism, "performative" (Austin 1961, 235ff).
But the root of "*inshāʾ*" is not about performance; it is about
creation or construction. This is an important part of the theory: a
declarative *reports on* a fact; an *inshāʾ* *constructs* or *creates* a
fact. So a more apt Austin-style neologism, translating "*inshāʾ*", is
"constructative."

The debate has to do with sayings that are grammatically declarative,
but are used in non-declarative ways. For example, "I sold (*biʿtu*)"
is, grammatically, a simple past tense declarative. And it can be used
this way, to report on a past sale. But it is also used as a
constructative, as when an auctioneer says "Sold (*biʿtu*)!" In this
case, it is used to create or execute a sale in the present, rather than
to report on a sale in the past.

Al-Astarābādī (d. 1287) offers an explanation of how this works:

> With respect to the constructative, "Sold!" there is no external that
> is intended to correspond to it; rather, the sale occurs in the
> present by this utterance, and this utterance brings it into
> existence. For this reason it is said that a constructative saying is
> not possibly true or false. And this is because the meaning of truth
> is the correspondence of the saying to the external, and falsehood the
> non-correspondence to it. For, if there is no external, how could
> there be correspondence or non-correspondence? (al-Astarābādī 1996,
> 4:11--12; Also see Larcher 1990, 199).

Al-Astarābādī explains the distinction by appeal to speaker intention:
"there is no external that is intended to correspond to it." Al-Dawānī
rejects this, and explains the distinction by appeal to imitation. When
the seller says, "Sold!", he does not imitate a relation in reality; he
instead creates a relation in reality. By contrast, the declarative, "I
sold," imitates a relation in reality, and it is true when it
corresponds to the relation it imitates, false when it does not.

To support his claims about imitation, al-Dawānī likes to appeal to
examples involving paintings. A declarative is like a portrait, a
painting painted in imitation of someone. Just as a good portrait
resembles the person it imitates and a bad portrait fails to resemble
the person it imitates, a true declarative corresponds to the fact it
imitates, while a false declarative fails to correspond to the fact it
imitates.

A constructative is not an imitation of any fact. It is like a painting
that is not a portrait---an image that the artist makes up, not in
imitation of anyone or anything. In both cases, any similarity to actual
persons (or things), living or dead, is purely coincidental.

Extending the analogy, al-Dawānī suggests that self-imitation is
impossible:

> An aspect of this imitation is that the imitated is determined in
> reality without regard to the imitation. For if you say to a painter,
> "Paint an image that imitates this image itself," your sentence is
> fruitless. For if the thing is not determined first, the imitation of
> it would not be established, and this is necessary. (al-Dawānī 2007,
> 134)

And this, he says, is like what happens in the case of both the Liar and
the Truthteller ("This saying is true"):

> Perhaps you understand from this discussion that if one says, "My
> saying is true," referring to this same saying, this is not a
> declarative at all, even if it is in a form of a declarative, because
> of the lack of imitation, which requires the distinctness of the
> imitation and the imitated. (al-Dawānī 2014, 173--74)

From this, it would appear to follow that he thinks that all
self-imitation is impossible. But, when objecting to al-Ṭūsī, he clearly
insists that some self-referential declaratives are non-paradoxically
true or false, like "This saying is composed" and "This saying is not
composed." Al-Dashtakī accuses al-Dawānī of inconsistency here. Dasdemir
agrees, arguing that, for the sake of consistency, al-Dawānī ought to
have held that no self-referential declarative is truth-apt (Daşdemir
2023, 258).

But why think that self-imitation is impossible?

On interpretation focuses the attention of the argument on what it is to
be a "relation in reality (*nisba wāqiʿiyya*)." On this interpretation,
a "relation in reality" is a independent fact, and the problem with
cases of self-imitation is that there is no properly independent fact to
be imitated. (Rezakhany 2018; El-Rouayheb 2019b; 2019a, 104).

Rezakhany (2018, 190--95) offers the most detailed development and
defense of this reading. While he initially suggests that a relation in
reality must be mind-independent, the criteria that he ultimately
appeals to is utterance-independence. When someone says, "This saying is
false," there is no prior relation between that saying and falsehood, so
no utterance-independent fact to be imitated. Since there is no
utterance-independent fact to be imitated, the saying cannot be true or
false. This dovetails nicely with al-Astarābādī, who, in the case of
"Sold!", connects the utterance-dependence of the sale with the claim
that there is "no external" to correspond to it.

This interpretation is also supported by what al-Dawānī himself says in
response to al-Dashtakī, about the difference between "This saying is
false" and "This saying is composed":

> The difference is clear, as we drew your attention to \[earlier\]. For
> the intellect finds it self-evident that there is a relation in
> reality between this saying and composition, in contrast with this
> saying and truth and falsehood.(2007, 145)

Here he clearly states that in the one case, there is a relation in
reality, while in the other, there is not.

He also says that this difference is self-evident, but it is not. A
saying does not exist unless and until it is uttered, and it is composed
of the words that are uttered as it is uttered. So it is hard to see how
the relation between the saying and its composition is
utterance-independent. Rezkahany suggests that al-Dawānī might instead
have in mind the conceptual or definitional relation between being a
saying and being composed, a relation that does plausibly hold
independent of any specific utterance (Rezakhany 2018, 202). But it is
not clear that such a relation is enough to make "This saying is
composed" true. And it is not clear how to extend this suggestion to
other examples, like "This saying is composed of seven words," or "This
saying is uttered by a philosopher."

An alternative interpretation focuses attention on imitation itself,
rather than the imitated relation. On this interpretation, the
problematic cases of self-imitation are cases where what is being
imitated is the imitation itself (Alwishah and Sanson forthcoming).
There are many ways that a painting can imitate itself. For example, a
painting can depict itself set on an easel, in a studio, being painted
by an artist. An artist can paint such a painting by placing herself and
her canvas in front a mirror, and painting what she sees in the mirror.
The kind of trouble al-Dawānī describes---the fruitless attempt at
self-imitation---only arises when the question of what to paint cannot
be settled by what she sees in the mirror. In that situation, the artist
can continue to paint, but at that point, she is making it up, and it is
no longer an imitation.

Plausibly, a non-semantic predicate like "is composed" attributes a
feature that a saying has independent of its attempt to imitate
anything, and so independent of its attempt to imitate itself. By
contrast, a predicate like "is true" or "is false" attribute features
that not only depend upon, but intrinsically involve, imitation.

Al-Dawānī extends his solution to cover al-Taftāzānī's Liar Cycles.
There, he argues that, even if each declarative in the cycle imitates a
relation that is independent of itself, the chain of imitation relations
is fruitless and empty, because it never reaches an independent ground.
On a reading the centers the utterance-independence of relations in
reality, the thought is that, while each declarative in the cycle
corresponds to a relation that is independent of its own utterance,
collectively, their truth conditions fail to reach any relations in
reality that are independent of their collective utterance. On a reading
that emphasizes the limits of self-imitation, the idea is that the chain
of imitation relations never reaches an imitation-independent ground.

## 5. Conclusion

Research into work on the Liar after al-Dawānī is on-going.

The generation of scholars who came immediately after al-Dashtakī and
al-Dawānī continued to discuss the topic. Al-Dashtakī's son, Ghiyath
al-Din Dashtakī (d. 1542) wrote his own treatise on the Liar (Qarāmaleki
2007; El-Rouayheb 2019a, 106), as did Shams al-Dīn Muḥammad al-Khafrī
(d. 1535-6), a student of both al-Dawānī and the elder al-Dashtakī
(Qarāmaleki 2013). El-Rouayheb (2019a) reports treatments of the Liar
from Mir Fakhr al-Din al-Astarābādī (d. 1577), al-Shustari (d. 1610),
Mir Damad (d. 1631), Khwansari (d. 1687) (See also Qarāmaleki 1997,
77--89), Bihari (d. 1707), Ilahabadi (circa 1700), Gūpāmawī (d. 1749),
Lakhnawi (d. 1784), and al-Shuwayhi (early 1800s), and reports more
generally the Liar was widely discussed within the Indo-Muslim
tradition, and to a lesser degree within the Ottoman tradition.
Rezakhany (2018) contains useful discussion of the Liar in Mīr Zāhid
al-Harawī (d. 1689), Qāḍī Mubārak (d. 1748), and Mullā Mubīn (d. 1810).

The conceptual similarity between Ibn ʿAdī and al-Samarqandī and the
Latin distinguentes tradition has already been noted, as has the
similarity between al-Abharī and al-Kātibī, and Bradwardine and his
followers. Other comparisons have been suggested. Qarāmaleki (2014) sees
in al-Dashtakī's use of iterated truth predicates an echo of Tarski's
theory of truth. Alwishah and Sanson (forthcoming) see in al-Dawānī's
solution to the Liar connections to contemporary "grounding" solutions,
as defended and articulated by Herzberger (1970) and Kripke (1975).

## References

### Translations

Most of the works discussed in this article are only just becoming
available in translation, and most of those translations are scattered
throughout the secondary literature. Alwishah and Sanson (2009) includes
useful translations of al-Āmidī and al-Ṭūsī as an appendix; Zarepour
(2023) includes useful translations of al-Ṭūsī, Ibn Kammūna,
al-Samarqandī, al-Ḥillī, al-Dawānī, and al-Dashtakī. Sanson and Alwishah
(2017) includes a complete translation of the relevant fragment from
al-Taftāzānī. Dasdemir (2023) includes both an edition and translation
of the Ottoman text, along with arguments in favor of attributing it to
Ḫaṭībzāde. Alwishah and Sanson (forthcoming) includes a complete
translation of al-Dawānī's *Final Word*, along with many other texts,
including Ibn ʿAdī, al-Rāzī, al-Abharī, al-Kātibī, al-Ṭūsī, al-Ḥillī,
al-Samarqandī, and al-Taftāzānī.

### Primary Texts

al-Abharī, Athīr al-Dīn 1998. *Kashf al-Ḥaqāʾiq fi taḥrīr al-daqāʾiq*.
Edited by Hüseyin Sarıoğlu. Istanbul: n.p.

---------. 2018. *Khilāṣat al-afkār wa naqāwat al-asrār*. Edited by
Nahdi Azimi and Hashem Qorbani. Iranian Institute of Philosophy.

---------. 2020. *Tanzīl al-afkār fī taʿdīl al-asrār*. Edited by
Muḥammad ʿAbd al-Ḥammīd. Masters Thesis. Egypt: University of Minia.

al-Āmidī, Sayf al-Dīn 2004. *Abkār al-afkār fī usūl al-dīn*. Edited by A
Mahdī. Vol. 2. Cairo: Dār al-kutub,.

al-Astarābādī, Raḍī al-Dīn 1996. *Sharḥ al-Raḍī ʿalā kāfiyya*. Edited by
Yūsuf Ḥasan ʿUmar,. Vol. 4. Benghazi: Manshurāt Jāmiʿat Qāryūnis.

Avicenna. 1958. *al-Shifāʾ: al-Safsaṭa*. Edited by Ibrāhīm Madkūr.
Cairo: al-Maṭbaʿa al-Amīriyya.

al-Baghdādī, ʿAbd al-Qāhir 2002. *Uṣūl al-dīn*. Edited by Ahmed Shams
al-Dīn. Beirut: Dār al-Kutb al-ʿilmiyya.

al-Bāqillānī, Abū Bakr 1957. *Al-Tamhīd*. Edited by Richard al-Yasūʿī.
Beirut: al-Maktaba al-Sharqiyya.

al-Bukhārī, 2007. "Al-Muntakhab min sharḥ risālat al-mughālaṭāt." In *12
Treatises on the Liar Paradox in Shirāz School*, edited by Aḥad
Qarāmaliki. Tehran: Iranian Institute of Philosophy.

al-Dashtakī, Ṣadr al-Dīn 2007. "Risāla fī ḥall shubhat jadhr aṣamm." In
*12 Treatises on the Liar Paradox in Shirāz School*, edited by Aḥad
Qarāmaliki. Tehran: Iranian Institute of Philosophy.

---------. 2015. "Treatise on the Problem of the Liar's Paradox." In
*Anthology of Philosophy in Persia: From the School of Shiraz to the
Twentieth Century*, edited by Seyyed Hossein Nasr and Mehdi Aminrazavi,
translated by Majid Fakhry. Vol. 5. London: I.B. Tauris Publishers.

al-Dawānī, Jalāl al-Dīn 2007. "Nihāyat al-kalām fī ḥall shubhat jadhr
al-aṣamm." In *12 Treatises on the Liar Paradox in Shirāz School*,
edited by Aḥad Qarāmaliki, 101\--155. Tehran: Iranian Institute of
Philosophy.

---------. 2014. "Sharḥ Tahdhīb al-manṭiq." In *Sharḥā al-muḥaqiq
al-Dawānī wa al-Mullā ʿAbd Allāh al-Yazdī ʿalā Tahdhīb al-manṭq*, edited
by ʿAbd al-Naṣīr al- Milyabārī. Kuwiat: Dār al-Ḍiyāʾ.

al-Fārābī, Abū Naṣr 1987--1989. "Sharḥ al-Qiyās." In *Al-Manṭiqiyāt*,
edited by Muḥammad Taqī Dānishpazuh. Vol. 2. Qum: Manshurāt al-Marʿashī,
al-Najafī.

Ḫaṭībzāde \[?\]. 2023. "Ḥall Al-Maghlaṭa Al-Musammāt Bi-l-Jadhr
Al-Aṣamm." Translated and edited by Yusuf Dasdemir. In *Theories of
Paradox in the Middle Ages*, edited by Stephen Read, and Barbara
Bartocci, 224--34. Cambridge: College Publications.

al-Ḥillī, Ibn al-Muṭahhar 2000. *Asrār al-khafiya fī al-ʿulūm
al-ʿaqliyya*. Qom: Markaz al-Abḥāth wa-al-Dirāsāt al-Islāmīyah.

Ibn ʿAdī, Yaḥyā. 1988. *Maqālāt Yaḥyā Ibn ʿAdī al-falsafiya*. Edited by
S. Khalīfāt. ʿAman: Jordan University.

---------. 2017. "Maqāla fī tabyīn faḍl sịnāʿat al-mantịq bi-waṣf̣ baʿḍ
mā yufīduhū ahlahā min al-quwā al-muʿjiza li-sāʾir al-ṣināʿāt
al-kalāmīyya siwāhā." In *A Safavid Anthology of Classical Arabic
Philosophy. Facsimile Edition of MS Madrasah-i Marvī 19*, edited by
Robert Wisnovsky, ms. 5--6. Tehran and Montreal: Markaz-i Dāʾirat
al-maʿārif-I buzurg-i islāmī---Intishārāt-I kitab-i rayzān and McGill
Institute of Islamic Studies.

Ibn Kammūna, Saʿd ibn Manṣūr. 2008. *al-Kāshif (al-Jadīd fī al-ḥikma)*.
Edited by Ḥāmid Aṣfahānī. Tehran: mu'ssa pashuhashti hikmat wa falsafat.

Ibn Kammūna, Saʿd ibn Manṣūr, and Najm al-Dīn al- Kātibī. 2007.
*Critical Remarks by Najm Al-Dīn Al-Kātibī on the Al-Maʿālim by Fakhr
Al-Dīn Al-Rāzī, Together with the Commentaries by ʿIzz Al-Dawla Ibn
Kammūna*. Edited by Sabine Schmidtke and Reza Pourjavady. Series on
Islamic Philosophy and Theology. Texts and Studies 6. Tehran: Iranian
Institute of Philosophy & Institute of Islamic Studies, Free University
of Berlin.

al-Kātibī, Najm al-Dīn 2019. *Sharḥ Kāshif al-asrār ʿan ghāwāmiḍ
al-afkār*. Edited by Anwar Shāhīn.

---------. 2022. *Jāmiʿ al-daqāʾiq fī kashf al-ḥaqāʾiq*. Edited by
Selman Sucu, Sacide Ataş, Ömer Odabaş, and Afife Şeyma Taç. Istanbul:
Türkiye Yazma Eserler Kurumu Başkanlığı.

al-Khayyāṭ, Abū al-Husayn 1957. *Kitāb al intiṣār: le livre du triomphe
et de la réfutation d'ibn al Rawandi l'hérétique*. Translated by Albert
N. Nader. Beirut: Éditions Les Lettres Orientales.

Qarāmaleki, Aḥad. 2007. *12 Treatises on the Liar Paradox in Shirāz
School*. Tehran: Iranian Institute of Philosophy.

al-Rāzī, Fakhr al-Dīn 1994. *Al-Maʿālim fī ʾuṣūl al-fiqh*. Edited by
ʿĀdil ʿAbd al-Mawjūd and ʿAlī Muʿawaḍ. Cairo: Mukhtār lil-Nashr wa
Tawzīʿ al-Kitāb.

---------. 2011. *Al-Maḥṣūl fī ʿlm uṣūl al-fiqh*. Edited by Ṭā-hā
al-ʿAlwānī. Vol. 4. Cairo: Dār al-Salām.

al-Samarqandī, Shams al-Dīn 2020. *Qisṭās al-afkār fī al-manṭiq*. Edited
by A. Falāḥī. Muassasah-i Pizhūhishī-i Ḥikmat va Falsafah-i Īrān.

---------. 2023. *Sharḥ al-Qisṭās*. Edited by Ḥasan Bīkkā. Tehran:
Intishārāt Mawlā.

al-Taftāzānī, Saʿd al-Dīn 1998. *Sharḥ al-Maqāṣid*. Edited by Umayra
ʿAbd al-Raḥmān. 2nd ed. Vol. 4. Beirut: ʿĀlam al-Kitāb.

al-Ṭūsī, Naṣīr al-Dīn 1974. "Taʿdīl al-miʿyār fī naqd tanzīl al-afkār."
In *Collected Texts and Papers on Logic and Language*, edited by Mehdi
Mohaghegh and Toshihiko Izutsu, 139--248. Tehran: Institute of Islamic
Studies.

### Other References

Ahmed, Asad Q. 2022. *Palimpsests of themselves: logic and commentary in
postclassical Muslim South Asia*. 5. Oakland: University of California
Press.

Alexander. 2014. *On Aristotle Prior analytics 1.23-31*. Translated by
Ian Mueller. Ancient Commentators on Aristotle. London: Bloomsbury.

Alexander. 2020. *On Aristotle, Topics 2*. Translated by Laura Maria
Castelli. Ancient Commentators on Aristotle. London: Bloomsbury
Academic.

Alwishah, Ahmed, and David Sanson. forthcoming. *The Final Word:
Al-Dawānī and the Liar Paradox in the Islamic World*. Oxford: Oxford
University Press.

---------. 2009. "The Early Arabic Liar: The Liar Paradox in the Islamic
World from the Mid-Ninth to the Mid-Thirteenth Centuries CE." *Vivarium*
47 (1): 97--127. <https://doi.org/10.1163/156853408X345909>.

Aristotle. 2009. *Prior analytics. Book 1*. Translated by Gisela
Striker. Clarendon Aristotle series. Oxford: Oxford University Press.

Austin, J. L. 1961. "Performative Utterances." In *Philosophical
Papers*, edited by J. O. Urmson and G. J. Warnock. Oxford: Oxford
University Press.

Aydin, Mehmet. 2014. "The liar paradox in the Islamic thought and the
treatise called 'Hallu Maglatat'l-Musammati Bi'l-Cazri'l-asamm' of
Hadjazada Bursawi." *İlahiyatt Fakultesi Dergisi* 40 (2): 167--213.

Barnes, Jonathan. 2007. *Truth, Etc: Six Lectures on Ancient Logic*.
Oxford: Clarendon Press.

Barwise, Jon, and John Etchemendy. 1987. *The Liar: An Essay on Truth
and Circularity*. New York: Oxford University Press.

Dasdemir, Yusuf. 2023. "A Fifteenth-Century Ottoman Treatise on the Liar
Paradox: A Case for Ḫaṭībzāde's Authorship." In *Theories of Paradox in
the Middle Ages*, edited by Stephen Read and Barbara Bartocci, 204--328.
Cambridge: College Publications.

Daşdemir, Yusuf. 2023. "A Fifteenth-Century Ottoman Solution to the Liar
Paradox by Ḫaṭībzāde Muḥyiddīn." *Arabic Sciences and Philosophy* 33
(2): 237--63. <https://doi.org/10.1017/S0957423923000048>.

Ebbesen, Sten. 1980. *Commentators and Commentaries on Aristotle's
Sophistici Elenchi: A Study of Post-Aristotelian Ancient and Medieval
Writings on Fallacies*. Leiden: Brill.

El-Rouayheb, Khaled. 2019a. *The Development of Arabic Logic
(1200-1800)*. Medieval and Early Modern Philosophy 2. Basel: Schwabe
Verlag.

---------. 2019b. "The Liar Paradox in Fifteenth-Century Shiraz: The
Exchange Between Ṣadr Al-Dīn Al-Dashtakī and Jalāl Al-Dīn Al-Dawānī."
*British Journal for the History of Philosophy*, July, 1--25.
<https://doi.org/10.1080/09608788.2019.1616156>.

Endress, Gerhard. 1977. *The Works of Yaḥyā Ibn ʿAdī: An Analytical
Inventory*. Weisbaden, Germany: Ludwig Reichert Verlag.

Erdt, Agnieszka. 2024. "A Third Realm Ontology? Naṣīr Al-Dīn Ṭūsī and
the Nafs Al-Amr." *British Journal for the History of Philosophy* 33
(3): 435--59. <https://doi.org/10.1080/09608788.2024.2369136>.

Ess, Josef van. 2018. *Theology And Society In The Second And Third
Centuries Of The Hijra: A History of Religious Thought in Early Islam*.
Translated by Gwendolin Goldbloom. Vol. 3. 4 vols. 116/3. Leiden: Brill.

Firanescu, Daniela Rodica. 2006. "Speech Acts." In *Encyclopedia of
Arabic Language and Linguistics*, edited by Kees Versteegh. Leiden:
Brill.

Geach, Peter T. 1965. "Assertion." *The Philosophical Review* 74
(October): 449--65. <https://doi.org/10.2307/2183123>.

Goodman, Nelson. 1973. "The Truth-Tellers and the Liars." In *Problems
and Projects*, 449--51. Indianapolis: Bobbs-Merrill.

Herzberger, Hans G. 1970. "Paradoxes of Grounding in Semantics." *The
Journal of Philosophy* 67 (6): 145--67.
<https://doi.org/10.2307/2023885>.

Hodges, Wilfrid. 2012. "Affirmative and Negative in Ibn Sīnā." In
*Insolubles and Consequences, Essays in Honour of Stephen Read*, edited
by C. Dutilh Novaes and Ole Hjortland Thomassen, 119--34. London: Milton
Keynes.

Kripke, Saul. 1975. "Outline of a Theory of Truth." *The Journal of
Philosophy* 72 (19): 690--716. <https://doi.org/10.2307/2024634>.

Larcher, Pierre. 1990. "Eléments Pragmatiques Dans La Théorie
Grammaticale Arabe Post-Classique." In *Studies in the History of the
Language Sciences*, edited by Kees Versteegh and Michael G. Carter,
56:195. Amsterdam: John Benjamins Publishing Company.
<https://doi.org/10.1075/sihols.56.16lar>.

Miller, Larry. 1989. "A Brief History of the Liar Paradox." In *Of
Scholars, Savants, and Their Texts: Studies in Philosophy and Religious
Thought - Essays in Honor of Arthur Hyman*, edited by Ruth
Link-Salinger, 173\--182. New York: Peter Lang.

Motavalli, Morteza, and Aḥad Qarāmaleki. 2021. "Nasīr Al-Dīn Al-Tūsī's
Theory of Truth: The Analysis." *Quarterly of Religious Thought* 21 (1).

Parsons, Terence, and Graziana Ciola. 2025. "The Traditional Square of
Opposition." In *The Stanford Encyclopedia of Philosophy*, edited by
Edward N. Zalta and Uri Nodelman, Summer 2025. Metaphysics Research Lab,
Stanford University.
<https://plato.stanford.edu/archives/sum2025/entries/square/>.

Pourjavady, Reza. 2011. *Philosophy in Early Safavid Iran: Najm Al-Dīn
Maḥmūd Al-Nayrīzī and His Writings*. Leiden: Brill.

Prantl, Carl. 1855. *Geschichte der Logik im Abendlande*. Leipzig:
Verlag von S. Hirzel.

Qarāmaleki, Aḥad. 1997. "Āqā Ḥusayn Khwānsārī Va Muʿammā-Yi Jadhr-i
Aṣamm." *Khirādnāme-Yi Ṣadrā* 10: 77--89.

---------. 2013. "The Liar's Paradox and Shamsuddin Mohammad Khofari's
Solution." *Religious Thought* 11.

---------. 2014. "The Liar Paradox in the Shiraz Philosophical School."
*Ishraq* 5: 41--52.

---------. 2016. "Argument of the Facts of Nafs Al-Amri and the Mystery
of the Root of Asm." *Articles and Reviews* 62.

Rezakhany, Hassan John. 2018. "Jalāl Ad-Dīn Ad-Dawānī's Solution to the
Liar Paradox and Its Reception in Qāḍī Mubārak and Mullā Mubīn."
*Journal of South Asian Intellectual History* 1 (2): 183--220.
<https://doi.org/10.1163/25425552-12340007>.

Sanson, David, and Ahmed Alwishah. 2017. "Al-Taftazani on the Liar
Paradox." *Oxford Studies in Medieval Philosophy* 4: 100--124.
<https://doi.org/10.1093/acprof:oso/9780198786368.003.0005>.

Smullyan, Raymond M. 1978. *What is the name of this book?* Englewood
Cliffs, N.J.: Prentice-Hall.

Spade, Paul Vincent. 1973. "The Origins of the Insolubilia Literature."
*Franciscan Studies* 33: 292--309.

Spade, Paul Vincent, and Stephen Read. 2021. "Insolubles." In *The
Stanford Encyclopedia of Philosophy*, edited by Edward N. Zalta, Winter
2021. Metaphysics Research Lab, Stanford University.
<https://plato.stanford.edu/archives/win2021/entries/insolubles/>.

Spiker, Hasan. 2021. *Things as They are: Nafs al-Amr and the
Metaphysical Foundations of Objective Truth*. Abu Dhabi: Tabah Research.

Zarepour, Mohammad Saleh. 2021. "Abharī's Solution to the Liar Paradox:
A Logical Analysis." *History and Philosophy of Logic* 42 (1): 1--16.
<https://doi.org/10.1080/01445340.2020.1793291>.

---------. 2022. "Arabic and Islamic Philosophy of Mathematics." In *The
Stanford Encyclopedia of Philosophy*, edited by Edward N. Zalta, Summer
2022. Metaphysics Research Lab, Stanford University.
<https://plato.stanford.edu/archives/sum2022/entries/arabic-islamic-phil-math/>.

---------. 2023. "Dashtakī's Solution to the Liar Paradox: A Synthesis
of the Earlier Solutions Proposed by Ṭūsī and Samarqandī." *History and
Philosophy of Logic* 0 (0): 1--27.
<https://doi.org/10.1080/01445340.2023.2210918>.




[^1]: 'Saying' is the best of several bad options for translating the
    Arabic words '*qawl*' and '*kalām*' into English. Both are used
    interchangeably to pick out the grammatical category of
    "complete"---that is, sentence-length--- utterances. Compare to
    Barnes (2007, 2 n. 3) on the Greek word '*logos*' as used in
    grammar.
