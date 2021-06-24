
I created the DysAda font as part of an
ongoing project "to understand if with a new approach I can help
lexical dyslexics to read better on computer or
smartphone or ebook, and by extension to all
readers. Is there a a font that allows to read French, English or any
other Latin language faster, or to learn faster, or to learn it more
easily? Finally, why is the representation of letters is set in stone,
a, b, c?

The questions on dyslexia are difficult questions which touch several
scientific fields more or less hard, biology, neurobiology, behavioral
psychology, linguistics, physics, and many others, but for the moment
rather little the computer science compared to what it could bring.

First of all, there is not one dyslexia, there are many forms and
often they are inseparable from other pathologies like dysphrasia or
dyspraxia. Also, it is important to understand (Point A) that it is
difficult to separate problems due to the relationship between (a)
growth (the organs and parts of the brain do not evolve at the same
speed for all) and (b) the educational system, in particular the age
of learning to read, and (c) the language and its
representation. Whew! The real definition of a dyslexic adult is
roughly an individual on whom all methods of learning to read have not
worked!

But for dyslexic children, whether it is temporary or not, and for
their parents, if they are interested in their children's evolution,
it is really hard to live! I am one of them and that's why I am
interested in the issue, as a computer scientist.

 Dyslexia is an invisible handicap that most often appears only
when the child starts to learn to read. But the appearance of the
problem and therefore its actual detection - because there is no
direct physical diagnosis (yet?) - can be delayed by the mental
capacities of the child, the smarter the child is, the longer his
brain will be able to compensate for the handicap, the later it will
be discovered, and the harder it is for the parents to catch
up/compensate for the problem because the educational system is
advancing more and more rapidly. The risk of dropping out of school is
there, with all the psychological consequences that this entails for
the child and then for the adult. 

 Also, for a parent of a dyslexic, Point A has a direct consequence:
should one compensate the child's handicap in a mechanical way (pens,
lamps, etc), at the risk that he/she cannot do without them, whereas
in many cases it is just a delay in growth? Should one on the contrary
avoid all these mechanical palliatives and rely on speech therapy,
impose high dose reading, at the risk of disgusting the child from
reading, saturating him/her with school, with an uncertain result? The
choice is far from clear.

However, in most cases, life chooses for you and your child: in
France, your child goes to school, at a certain level (cp, ce1, ce2,
cm1...) his reading problem becomes obvious - more or less early as
explained above - the teacher calls you and directs you to a speech
therapist who makes a check-up reimbursed by the social security if
prescribed (in France). Depending on the assessment and the parents'
availability, a long series of 30-minute to one-hour weekly sessions
are planned during the year and the following years, and then it's off
to the races, the parents are busy with their work anyway, and good
luck, my daughter, good luck, my son, you have a chance to get out of
it, we're watching you.

It doesn't matter that in some countries there are very few problems
with dyslexia, that there may be other methods of teaching French,
that most of the communication and written information that we receive
and send is typed on a computer. 

Making progress in this ill-defined field is complicated, especially
since there are many underlying financial interests, mainly from
medicine, or under the guise of medicine. 

Fortunately, my initial problem is simple and will serve as a
guideline: what can I do to help my child read more easily? 

A new approach appeared a few years ago in the form of a stroboscopic
light, with above all an explanation of the origin of a part of
lexical dyslexia: the shape of Maxwell's tasks. According to Albert le
Floch and Guy Ropars, it is the quality of symmetry of these tasks
which would be at the origin of a difficulty to choose between the 2
images built on the two retinas during reading. The stroboscopic light
would allow the brain to erase one of the images. What is important
here is that it would be a symmetry close to perfection that would
cause the reading problems of a large number of lexical dyslexics.

This work is decried in certain scientific branches which deal with
dyslexia, notably in behavioral psychology. However, it would be
sufficient to repeat certain double-blind experiments to know more and
to validate or invalidate this postulate, in a well understood
scientific approach. But setting up an experiment requires large
amounts of funding, an increasingly heavy organization and, above all,
risks showing that Albert le Floch and Mr. Ropars are right, which
does not encourage the branch of psychology that deals with reading to
seriously look into the question. However, le Floch and Ropars have
just won a prize from the Academy of Medicine for their work, so it's
hard to find your way around!

But let's leave these controversies aside. What interests us here is
that the question of symmetry is back on the table, once again! It
seems to be intimately linked to reading, and yet our fonts are most
of the time asymmetrical, but also confusing by overlapping left/right
or top/bottom.

To try something new, I created a symmetrical right-left-top-bottom
font that I named DysAda, affixed on a central line, and that,
potentially, can be read from left to right, right to left, top to
bottom and bottom to top. The result is surprising and amusing, there
are several examples on this page; But this font is currently
completely out of my imagination and out of discussions with dyslexic
colleagues, it will take users to test it!

<img href="https://github.com/mathieuraffinot/dysada-font/blob/main/IMG/dysada-full.png"> dysada font letters </img> 

However, while building it, I realized that part of the solution might
not come from a complete new font: in most cases, the lexical dyslexic
only stumbles on some letters that he confuses, either on the level of
the letter itself or on the level of the associated phoneme. Also his
environment, family or external aids, is very important. Why should we
want to replace all the letters, which will require a longer learning
process for the user but also for his environment, a learning process
that is unpleasant and not very progressive, which will limit the
scope of the method in practice?

Part of the solution comes from a new concept: why not build a
personalized font for each user according to his reading problems? So
we arrive at the notion of a personalized font to facilitate
reading. Also, why limit ourselves to dyslexics? The question then
becomes, is there a personalized font that can accelerate reading?

On the other hand, in order to avoid a too big dispersion of letters
and to allow an understanding between two texts of two different
users, it is important that all the replaced characters, in more or
less number according to the pathology, are extracted from the same
global font. This would be the role of the DysAda font as a reference
replacement font, the rest of the non-replaced characters being taken
from a font that is pleasant to dyslexics or not, it is in fact the
user's choice!

The software to build and use this custom font are not ready yet
(firefox/chrome plugin + Android application), I hope to be able to
provide them within 6 months, unless others want to go faster and
propose them before me in open source. Welcome ! But the reference
font is ready, it can be downloaded on this page.

Question: Why release the font before the software?

Because it seems, as mentioned above, that strong financial appetites
are at work in this field. So I spread the idea of custom fonts and
the generic symmetrical DysAda font before a greedy private company -
I am not against private companies, far from it, but I know of two
dyslexia-related companies that have a policy that I think is quite
ethical.

One of them offers the only original font with hard-to-recognize
characters for dyslexics that I know of, the bilexie font. This font
is not based on symmetry notions but seems to have been tested and
designed with dyslexics - I write "seems" because discussions with this
company have turned sour, although this font is in fact available
digitally on the internet by searching (very) well, from the site of
the association <a href="https://www.puissancedys.org/"> puissance-dys </a>. But the opacity and the secrecy that
reigns over this font - published for some time already in a book - of
the will of its creators raises a serious doubt about its practical
efficiency. In any case, I don't have an answer to this question, and
it's not for not having tried it!

Question: if I want to see the transformation of web pages with the
complete DysAda font, from now on, how do I do it?

While waiting for the above-mentioned software, there are several
plug-ins to load a font and use it directly on all the pages
read. Here is one for example: <a href="https://chrome.google.com/webstore/detail/fontara/dcjdhicepiklefpimapdkbaeoocniemc"> FontAra (Chrome/firefox).</a>
