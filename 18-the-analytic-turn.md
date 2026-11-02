# Chapter 18 — The Analytic Turn

Around 1900 a handful of philosophers in Jena, Cambridge and Vienna decided that the old questions about being, knowledge and value had been asked badly, and that the way to ask them well was to look hard at logic and language. Gottlob Frege built a new logic and with it a theory of meaning. Bertrand Russell and G. E. Moore rebelled against the idealism that dominated British universities. Ludwig Wittgenstein wrote a seventy-page book that claimed to solve all the problems of philosophy, then spent the second half of his life taking it apart. The Vienna Circle tried to sweep metaphysics away as literal nonsense; W. V. O. Quine knocked out the distinction their program depended on; and a group at Oxford argued that ordinary speech already contains more philosophy than the philosophers had noticed. The result, "analytic philosophy," is the dominant style in English-speaking universities today. This chapter tells its story through its best arguments, so that you can read a modern journal article and know where its moves come from. Previous: [Chapter 17 — Pragmatism](17-pragmatism.md). Next: [Chapter 19 — Phenomenology and Existentialism](19-phenomenology-and-existentialism.md).

## Required reading

- Bertrand Russell, *The Problems of Philosophy* (1912), Chapter V "Knowledge by Acquaintance and Knowledge by Description": [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Frussell-problems-of-philosophy-pg5827.epub) [File](readings/russell-problems-of-philosophy-pg5827.epub).
- Bertrand Russell, *Our Knowledge of the External World* (1914), Lecture II "Logic as the Essence of Philosophy": [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Frussell-our-knowledge-of-the-external-world-pg37090.epub) [File](readings/russell-our-knowledge-of-the-external-world-pg37090.epub).
- Ludwig Wittgenstein, *Tractatus Logico-Philosophicus* (tr. C. K. Ogden, with Frank Ramsey, 1922), the Preface, propositions 1–2.063, 4–4.116 and 6.4–7, and Russell's Introduction: [readings/wittgenstein-tractatus-logico-philosophicus-pg5740.pdf](readings/wittgenstein-tractatus-logico-philosophicus-pg5740.pdf) (Gutenberg offers it only as a PDF). The Pears and McGuinness translation (Routledge Classics, 2001; first published 1961) is the recommended modern alternative.
- Gottlob Frege, "On Sense and Reference" ("Über Sinn und Bedeutung," 1892), tr. Max Black, in Michael Beaney, ed., *The Frege Reader* (Blackwell, 1997) **(procure yourself)**.
- Bertrand Russell, "On Denoting," *Mind* 14 (1905) **(procure yourself)**: public domain, but not on Project Gutenberg; widely reprinted.
- W. V. O. Quine, "Two Dogmas of Empiricism" (1951), in *From a Logical Point of View* (Harvard University Press, 1953) **(procure yourself)**.
- Ludwig Wittgenstein, *Philosophical Investigations*, tr. G. E. M. Anscombe, P. M. S. Hacker and Joachim Schulte, 4th edition (Wiley-Blackwell, 2009), §§1–43, 65–71, 185–202 and 243–315 **(procure yourself)**.

Further reading: G. E. Moore, *Principia Ethica* (1903), Preface and §§1–15: [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Fmoore-principia-ethica-pg53430.epub) [File](readings/moore-principia-ethica-pg53430.epub); Moore, "The Refutation of Idealism" (1903), in *Philosophical Studies*: [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Fmoore-philosophical-studies-pg50141.epub) [File](readings/moore-philosophical-studies-pg50141.epub); Russell, *Introduction to Mathematical Philosophy* (1919), chapter 16 "Descriptions": [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Frussell-introduction-to-mathematical-philosophy-pg41654.epub) [File](readings/russell-introduction-to-mathematical-philosophy-pg41654.epub); Russell, *Mysticism and Logic* (1918), "Mathematics and the Metaphysicians": [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Frussell-mysticism-and-logic-pg25447.epub) [File](readings/russell-mysticism-and-logic-pg25447.epub); A. J. Ayer, *Language, Truth and Logic* (1936), chapter 1; J. L. Austin, *How to Do Things with Words* (1962), lectures I–II; Saul Kripke, *Naming and Necessity* (1980), lecture I; Ray Monk, *Ludwig Wittgenstein: The Duty of Genius* (1990); Scott Soames, *Philosophical Analysis in the Twentieth Century*, 2 vols. (Princeton University Press, 2003) — all **(procure yourself)**.

## What "analysis" meant

The word "analytic" names a method more than a doctrine. To *analyze* a concept or a sentence is to break it into its parts and show how they fit, the way a chemist breaks a compound into elements. The early analysts thought that many philosophical puzzles came from the surface form of language hiding the real logical form of what we say. Fix the form and the puzzle goes away, or turns into a precise question that can be answered.

Moore put the motivating complaint in the first lines of *Principia Ethica* (1903):

> It appears to me that in Ethics, as in all other philosophical studies, the difficulties and disagreements, of which its history is full, are mainly due to a very simple cause: namely to the attempt to answer questions, without first discovering precisely *what* question it is which you desire to answer.
>
> — G. E. Moore, *Principia Ethica*, Preface

Russell, eleven years later, went further:

> ...every philosophical problem, when it is subjected to the necessary analysis and purification, is found either to be not really philosophical at all, or else to be, in the sense in which we are using the word, logical.
>
> — Bertrand Russell, *Our Knowledge of the External World*, Lecture II

That is the analytic turn in one sentence. But "logic" here means something new. It is not Aristotle's syllogistic, which had barely changed in two thousand years (see [Chapter 6 — Aristotle](06-aristotle.md)), but the logic invented by a mathematics professor in Jena whom almost nobody read.

## Frege: a new logic and the puzzle of identity

Gottlob Frege (1848–1925) spent his career at the University of Jena trying to show that arithmetic is a branch of logic, a program called **logicism**. To do it he needed a logic far stronger than the syllogism. In a short book called *Begriffsschrift* ("concept-script," 1879) he provided one: the first modern formal system, with **quantifiers** ("for all *x*," "there is an *x*") and variables. With quantifiers you can represent sentences like "Every student read some book," which mean two different things depending on which quantifier comes first and which the syllogism could not handle. Almost all of modern logic, and through it computer science, descends from this book. It sold almost no copies.

Frege's *Foundations of Arithmetic* (1884) states three methodological principles. The most influential is the **context principle**: never ask for the meaning of a word in isolation, but only in the context of a sentence. Ask "what is the number 2?" in isolation and you will imagine a ghostly object or a mental image; ask what "the number of moons of Mars is 2" says, and you will see that number words do logical work in sentences.

### Sense and reference

In "On Sense and Reference" (1892) Frege started with a puzzle about identity. Compare:

1. The Morning Star is the Morning Star.
2. The Morning Star is the Evening Star.

Both are true, and both are about the same object, the planet Venus. Yet (1) is trivial and known *a priori*, while (2) was an astronomical discovery made by the Babylonians. If the meaning of a name were simply the object it names, the two sentences would mean the same thing. They do not. So, Frege argued, an expression has two semantic properties: its **reference** (*Bedeutung*), the object it picks out, and its **sense** (*Sinn*), the "mode of presentation" of that object, the route by which the mind reaches it. "Morning Star" and "Evening Star" share a reference and differ in sense.

The distinction does a great deal of work. Sentences have senses too (Frege calls them *thoughts*, mind-independent contents that different people can grasp) and references (their truth-values). It explains why you can believe that the Morning Star is bright without believing the Evening Star is: belief contexts are sensitive to sense. And it explains how "Odysseus was set ashore at Ithaca" can be meaningful even though "Odysseus" refers to nothing: it has a sense without a reference.

### The letter

Frege's life's work was *Basic Laws of Arithmetic* (*Grundgesetze der Arithmetik*), volume 1 of which appeared in 1893. In June 1902, as volume 2 was in press, he received a polite letter from a young Englishman named Bertrand Russell. Russell had found a contradiction in Frege's Basic Law V, which allowed you to form the set of all things satisfying any condition.

Consider the set of all sets that are not members of themselves. Is it a member of itself? If it is, then it is not; if it is not, then it is. Frege's system could prove both. In a hastily written appendix, Frege acknowledged that nothing worse can befall a scientific writer than to have a foundation of his building collapse just as the work is completed. Russell later wrote that he knew of nothing to equal Frege's dedication to truth in that moment. **Russell's paradox** forced a generation of logicians to rebuild set theory (Zermelo's axioms, Russell's own theory of types), and it led indirectly to Gödel's incompleteness theorems in 1931.

Frege died in obscurity. A diary from his last year, published in 1994, contains ugly antisemitic remarks that shocked Michael Dummett, his greatest interpreter. Both facts about the founder belong in the story.

## Russell: descriptions and the revolt against idealism

Bertrand Russell (1872–1970) was an aristocrat, the godson of John Stuart Mill, a mathematician, a pacifist jailed in 1918 for an anti-war article (he wrote *Introduction to Mathematical Philosophy* in Brixton prison), a campaigner against nuclear weapons arrested again at age 89, and a Nobel laureate in literature. He wrote with a clarity that remains the model for the analytic style.

In 1898 Russell and his friend G. E. Moore broke with the British Idealists, followers of Hegel (see [Chapter 14 — Hegel, Marx and Their Critics](14-hegel-marx-and-their-critics.md)) such as F. H. Bradley, who taught that reality is a single spiritual Absolute and that ordinary objects and relations are mere appearance. Russell later described the revolt as an escape from a prison: suddenly he could believe again that grass is green and that the stars would exist if no one were aware of them.

### "On Denoting"

Russell's most celebrated contribution is the **theory of descriptions** in "On Denoting" (1905). Consider the sentence "The present King of France is bald." There is no present King of France (France has been a republic since 1870). Is the sentence true? No: there is no bald King of France. Is it false? Then by the law of excluded middle, "The present King of France is not bald" should be true, which seems wrong too. The Austrian philosopher Alexius Meinong had concluded that "the present King of France" must refer to a non-existent object that has some kind of being. Russell found this ontology intolerable; logic, he wrote in *Introduction to Mathematical Philosophy* (1919), must keep "a robust sense of reality."

His solution is that "the present King of France" is not a name at all, despite its grammatical form. A sentence of the form "The F is G" says three things:

1. There is at least one F.
2. There is at most one F.
3. Whatever is F is G.

In logical notation: ∃*x*(K*x* ∧ ∀*y*(K*y* → *y* = *x*) ∧ B*x*). Since clause 1 is false, the whole sentence is false. And "The present King of France is not bald" turns out to be ambiguous: it can mean "There is exactly one King of France and he is not bald" (false), or "It is not the case that there is exactly one King of France who is bald" (true). The negation can take wide or narrow **scope**, and the puzzle came from failing to see that. Surface grammar disguised logical form. Frank Ramsey called the theory a paradigm of philosophy.

### Acquaintance and description

In *The Problems of Philosophy* (1912) Russell built the theory of descriptions into a theory of knowledge. We are **acquainted** with things we are directly aware of without inference: sense-data, our own thoughts, perhaps ourselves, and universals. Everything else we know only **by description**: Bismarck, the center of mass of the solar system, your great-grandmother.

> The fundamental principle in the analysis of propositions containing descriptions is this: *Every proposition which we can understand must be composed wholly of constituents with which we are acquainted*.
>
> — Bertrand Russell, *The Problems of Philosophy*, Chapter V

The principle has a startling consequence: most proper names are disguised descriptions. When you say "Bismarck was an astute diplomat," the thought you actually have is something like "the first Chancellor of the German Empire was an astute diplomat," with a description built from things you are acquainted with. Hold on to this: in 1970 Saul Kripke would argue that it is completely wrong.

Russell went on to develop **logical atomism**, the view that the world consists of atomic facts that a perfect logical language would mirror. He credited the idea partly to his former student, whom it is time to meet. But his prose was never solemn. In a 1901 essay he explained that pure mathematics deduces what follows from hypotheses about *anything at all*:

> Thus mathematics may be defined as the subject in which we never know what we are talking about, nor whether what we are saying is true.
>
> — Bertrand Russell, "Mathematics and the Metaphysicians," in *Mysticism and Logic*

He added that people puzzled by the beginnings of mathematics would find comfort in this definition, and "will probably agree that it is accurate."

## Moore: common sense and the open question

G. E. Moore (1873–1958) was Russell's opposite: slow, gentle, and famous for the astonished incredulity with which he met a careless claim. Keynes and the Bloomsbury Group took *Principia Ethica* as their bible.

"The Refutation of Idealism" (1903) attacks the Berkeleyan principle *esse est percipi*, "to be is to be perceived" (see [Chapter 12 — The Empiricists](12-the-empiricists.md)):

> The trivial proposition which I propose to dispute is this: that *esse* is *percipi*. This is a very ambiguous proposition, but, in some sense or other, it has been very widely held.
>
> — G. E. Moore, "The Refutation of Idealism," in *Philosophical Studies*

Moore's key move is to distinguish, in every experience, the act of awareness from its object: the sensation of blue and the blue are two things, which idealists run together. Later, in "Proof of an External World" (1939), he raised his hands before the British Academy and argued, roughly: here is one hand, here is another; so at least two external objects exist; so there is an external world. The proof is valid and, Moore insisted, its premises are known. Most listeners thought he had missed the skeptic's point. Whether a premise can be more certain than any philosophical argument against it is still debated (see [Chapter 21 — Knowledge and Science](21-knowledge-and-science.md)); Wittgenstein's last notebooks, *On Certainty* (1969), are a long meditation on Moore's hands.

In ethics, *Principia Ethica* argued that "good" names a simple, indefinable, non-natural property:

> If I am asked 'What is good?' my answer is that good is good, and that is the end of the matter.
>
> — G. E. Moore, *Principia Ethica* §6

His **open question argument**: for any proposed definition of good as some natural property N (pleasure, what we desire to desire), it remains an open, meaningful question whether N is good. If "good" just meant "pleasant," then "Is pleasure good?" would be as empty as "Is pleasure pleasant?" It is not empty, so the definition fails; the attempt to define good naturalistically commits the **naturalistic fallacy**. The argument launched modern metaethics; it is examined in detail in [the Ethics course, Chapter 17](../learn-ethics/17-metaethics.md). Moore also left a puzzle, **Moore's paradox**: "It is raining, but I don't believe it is raining" could be true, yet no one can sensibly assert it.

## Early Wittgenstein: the *Tractatus*

Ludwig Wittgenstein (1889–1951) was the youngest son of one of the richest families in Europe; Brahms played in the family's Vienna palace, and three of his brothers died by suicide. He studied engineering, became obsessed with the foundations of mathematics, and in 1911 turned up unannounced in Russell's rooms in Cambridge. Within a year Russell believed the young Austrian would solve the problems he himself could not. In the war Wittgenstein volunteered for the most dangerous postings and wrote a book in his notebooks at the front; the manuscript reached Russell from an Italian prisoner-of-war camp.

The book, published in German in 1921 and in English in 1922 as *Tractatus Logico-Philosophicus* (the title was Moore's suggestion, echoing Spinoza), is a sequence of numbered propositions. Proposition 1.1 comments on 1, 1.11 on 1.1, and so on. It opens:

> The world is everything that is the case.
>
> — Wittgenstein, *Tractatus* 1 (tr. C. K. Ogden)

> The world is the totality of facts, not of things.
>
> — Wittgenstein, *Tractatus* 1.1 (tr. C. K. Ogden)

The Preface promises a great deal:

> The book deals with the problems of philosophy and shows, as I believe, that the method of formulating these problems rests on the misunderstanding of the logic of our language. Its whole meaning could be summed up somewhat as follows: What can be said at all can be said clearly; and whereof one cannot speak thereof one must be silent.
>
> — Wittgenstein, *Tractatus*, Preface (tr. C. K. Ogden)

And at the end of the Preface, with a straight face, Wittgenstein says that the truth of its thoughts seems "unassailable and definitive," and that the problems of philosophy have "in essentials been finally solved."

### The picture theory

How can a sentence be about the world at all? The *Tractatus* answers with the **picture theory of meaning**, which Wittgenstein reportedly conceived on reading about a Paris court case in which a traffic accident was reconstructed with toy cars and dolls.

> We make to ourselves pictures of facts.
>
> — Wittgenstein, *Tractatus* 2.1 (tr. C. K. Ogden)

A proposition is a picture of a possible state of affairs. Its elements (names) stand for objects, and the way the names are arranged in the proposition shows how the objects are arranged if the proposition is true. A proposition is true if things are as it pictures them, false otherwise. What a picture cannot do is picture its own **logical form**, the structure it shares with reality. That can only be *shown*, not *said*. The distinction between saying and showing is the hinge of the book.

From this follows a strict theory of meaningful language. Only propositions that picture possible states of affairs, ultimately the propositions of natural science, say anything. The propositions of logic are **tautologies**: they say nothing, though they show the logical structure of the world. And the propositions of philosophy, ethics, aesthetics and religion try to say what can only be shown. They are not false but *nonsensical* (*unsinnig*).

> All philosophy is "Critique of language" (but not at all in Mauthner's sense). Russell's merit is to have shown that the apparent logical form of the proposition need not be its real form.
>
> — Wittgenstein, *Tractatus* 4.0031 (tr. C. K. Ogden)

> Philosophy is not a theory but an activity.
>
> — Wittgenstein, *Tractatus* 4.112 (tr. C. K. Ogden)

### The mystical and the ladder

The last pages of the *Tractatus* turn, abruptly, to death, ethics and the meaning of life.

> The sense of the world must lie outside the world.
>
> — Wittgenstein, *Tractatus* 6.41 (tr. C. K. Ogden)

> Death is not an event of life. Death is not lived through.
>
> — Wittgenstein, *Tractatus* 6.4311 (tr. C. K. Ogden)

> We feel that even if all possible scientific questions be answered, the problems of life have still not been touched at all. Of course there is then no question left, and just this is the answer.
>
> — Wittgenstein, *Tractatus* 6.52 (tr. C. K. Ogden)

> The solution of the problem of life is seen in the vanishing of this problem.
>
> — Wittgenstein, *Tractatus* 6.521 (tr. C. K. Ogden)

He adds, at 6.44: "Not how the world is, is the mystical, but that it is." And then he turns on his own book:

> My propositions are elucidatory in this way: he who understands me finally recognizes them as senseless, when he has climbed out through them, on them, over them. (He must so to speak throw away the ladder, after he has climbed up on it.)
>
> — Wittgenstein, *Tractatus* 6.54 (tr. C. K. Ogden)

The final proposition, 7, stands alone: "Whereof one cannot speak, thereof one must be silent."

Russell, in his Introduction, spotted the obvious problem:

> What causes hesitation is the fact that, after all, Mr Wittgenstein manages to say a good deal about what cannot be said, thus suggesting to the sceptical reader that possibly there may be some loophole through a hierarchy of languages, or by some other exit.
>
> — Bertrand Russell, Introduction to the *Tractatus*

Frank Ramsey, the Cambridge prodigy who did much of the translating at eighteen, was blunter:

> What we can't say we can't say, and we can't whistle it either.
>
> — Frank Ramsey, "General Propositions and Causality" (1929), in *The Foundations of Mathematics* (1931)

### Two readings

How should you read a book that declares itself nonsense? Scholars divide sharply.

- **The traditional or "ineffabilist" reading** (Elizabeth Anscombe, P. M. S. Hacker, Peter Geach in places) holds that the *Tractatus* tries to convey deep truths about logic, the world and value that cannot be stated but can be shown. The nonsense is "illuminating nonsense," gesturing at what lies beyond language.
- **The "resolute" or "New Wittgenstein" reading** (Cora Diamond, "Throwing Away the Ladder," 1988; James Conant; collected in Crary and Read, eds., *The New Wittgenstein*, 2000) holds that this is a cheat: nonsense is just nonsense, with no ineffable content. The book is a therapeutic trap. You are meant to be drawn into its metaphysics, feel its pull, and then recognize that it says nothing, and be cured of the urge to say it. The "frame" (Preface and 6.54) tells you how to read the rest.

In a letter to the publisher Ludwig von Ficker, Wittgenstein said that the book's point was ethical: it had two parts, the one he had written and everything he had not, and the second was the important one. Whatever that means, the *Tractatus* is not the positivist manifesto its first admirers took it for. Having solved philosophy, Wittgenstein gave away his inheritance and became a village schoolteacher in Lower Austria. Philosophy, meanwhile, had found his book.

## The Vienna Circle and logical positivism

From 1924 a discussion group met on Thursday evenings around Moritz Schlick, professor of the philosophy of inductive sciences at the University of Vienna. Its members included the logician Rudolf Carnap, the sociologist and economist Otto Neurath, the mathematician Hans Hahn, Herbert Feigl, Friedrich Waismann, and, as a silent visitor, the young Kurt Gödel. They read the *Tractatus* line by line, twice. In 1929 they published a manifesto, *The Scientific Conception of the World: The Vienna Circle*. Their program was called **logical positivism** (or logical empiricism).

### The verification principle

The central idea combined Hume's fork (see [Chapter 12 — The Empiricists](12-the-empiricists.md)) with Frege's and Russell's logic. Every meaningful statement is either:

1. **Analytic**: true or false by virtue of meaning and logic alone (the truths of logic and mathematics), and saying nothing about the world; or
2. **Empirically verifiable**: its truth or falsity makes some possible difference to experience.

Anything else is literally meaningless: not false, but empty, however much feeling it expresses. This is the **verification principle**. The young English philosopher A. J. Ayer, who had sat in on the Circle's meetings, brought it to the English-speaking world in *Language, Truth and Logic* (1936), a short book written at twenty-five that became a bestseller. By its lights, statements about God, the Absolute, the soul and objective value fail the test. In ethics, Ayer drew the consequence of **emotivism**: "Stealing is wrong" expresses disapproval, as if you said "Stealing!" in a shocked tone, and states nothing true or false (see [the Ethics course, Chapter 17](../learn-ethics/17-metaethics.md), and for the nihilist consequences, [the Nihilism course, Chapter 12](../learn-nihilism/12-moral-nihilism-and-error-theory.md)).

### Carnap against Heidegger

The most notorious application came in Carnap's 1932 essay "The Elimination of Metaphysics through Logical Analysis of Language." Carnap took sentences from Martin Heidegger's 1929 lecture "What Is Metaphysics?", including the famous *Das Nichts selbst nichtet* (roughly, the nothing itself does the "nothing-ing"), and argued that they arise from a grammatical illusion: treating "nothing," which is a logical operator (a negated existential quantifier), as if it were a name for something that could act. Metaphysicians, Carnap concluded, are like musicians without musical ability, expressing an attitude toward life in the wrong medium. The encounter is often taken as the founding scene of the split between "analytic" and "continental" philosophy. For Heidegger's side, see [Chapter 19 — Phenomenology and Existentialism](19-phenomenology-and-existentialism.md) and [the Nihilism course, Chapter 9](../learn-nihilism/09-heidegger-and-the-nothing.md). Michael Friedman's *A Parting of the Ways* (2000) shows that the two sides understood each other better than the legend suggests.

### Why the principle failed

The verification principle collapsed under its own weight, and the story of its collapse is a lesson in rigor.

1. **Universal laws.** "All copper conducts electricity" can never be conclusively verified, since you cannot test all copper. A strong principle excludes science itself.
2. **The weakening problem.** Ayer retreated to "weak" verifiability: a statement is meaningful if some observation is relevant to it. Every version he proposed turned out, on logical inspection, to let in any sentence at all. Alonzo Church showed in 1949 that the formula of Ayer's second edition (1946) admitted any statement or its negation.
3. **Self-application.** Is the verification principle itself analytic or verifiable? It does not seem to be either. So by its own lights it is meaningless. Defenders replied that it is a proposal, a recommendation about how to use the word "meaningful." But then a metaphysician can decline the proposal.
4. **Holism.** Statements do not meet experience one by one, as the next section explains.

Carl Hempel's 1950 survey, "Problems and Changes in the Empiricist Criterion of Meaning," wrote the obituary. Karl Popper had already proposed replacing the criterion of *meaning* with a criterion for *science*, falsifiability (see [Chapter 21 — Knowledge and Science](21-knowledge-and-science.md)).

Politics destroyed the Circle before logic finished it. In 1936 a former student shot Schlick dead on the university steps, and Nazi-sympathizing papers celebrated. Most members, Jewish, socialist or both, scattered to Britain and the United States, where they reshaped philosophy departments. Logical positivism died as a doctrine and triumphed as a style: precise, argumentative, allied to science and logic.

## Quine: no dogmas, no first philosophy

Willard Van Orman Quine (1908–2000) visited the Vienna Circle as a young man and came home to Harvard as Carnap's most admiring and most dangerous critic. Two of his papers changed the field.

### What there is

"On What There Is" (1948) asks how we can say, truly, that Pegasus does not exist, without seeming to refer to Pegasus. Using Russell's theory of descriptions, he shows that we can deny existence without naming anything. He then proposes a criterion for what a theory says exists, its **ontological commitment**: the things a theory must quantify over, the values its bound variables must take, for it to be true.

> To be is to be the value of a variable.
>
> — W. V. O. Quine, "On What There Is" (1948), in *From a Logical Point of View* (1953)

The slogan made ontology respectable again. To find out whether you believe in numbers, sets or possible worlds, regiment your best scientific theory in logic and see what you need to quantify over.

### "Two Dogmas of Empiricism"

The more famous paper, published in 1951, attacks two assumptions of logical positivism.

**The first dogma** is the analytic/synthetic distinction itself. Try to define "analytic." It means true by virtue of meaning. A sentence like "No bachelor is married" is analytic because "bachelor" is synonymous with "unmarried man." What is synonymy? Interchangeability in all contexts without change of truth-value? That works only in a language already containing a notion like "necessarily," which itself must be explained by analyticity. Definitions? They record prior synonymies. Carnap's "semantic rules"? They tell you which sentences are called analytic in an artificial language, not what analyticity is. Quine concludes that every attempt moves in a small circle, and that no principled line divides analytic from synthetic truths.

**The second dogma** is **reductionism**: the idea that each meaningful statement can be translated into, or confirmed by, its own set of possible experiences. Quine, following the physicist Pierre Duhem, argues that statements face the tribunal of experience not individually but as a corporate body. A failed prediction tells you that *something* in your web of beliefs is wrong, not which belief. You can always keep a cherished belief by adjusting others elsewhere; equally, any belief, even a law of logic, could in principle be given up if that made the whole system work better. Beliefs near the "periphery" (observation reports) are easily revised; beliefs at the "center" (logic, mathematics) are revised rarely, because so much depends on them. The difference is one of degree.

This picture, **confirmation holism**, has a radical consequence: there is no first philosophy, no armchair discipline standing outside science to justify it. Philosophy is continuous with science. Quine later called for **naturalized epistemology** (1969): study how human beings actually get from sensory stimulation to theory, as a chapter of psychology. And he ends "Two Dogmas" by calling his own position a more thorough pragmatism, linking analytic philosophy back to [Chapter 17](17-pragmatism.md).

H. P. Grice and P. F. Strawson replied in "In Defense of a Dogma" (1956) that a distinction people apply with wide agreement is not empty just because it resists non-circular definition; many basic concepts do. Quine pushed on regardless. In *Word and Object* (1960) he argued for the **indeterminacy of translation**: a linguist hearing a native say "Gavagai!" as a rabbit runs past can never settle, from all possible behavioral evidence, whether the word means "rabbit," "undetached rabbit part" or "temporal stage of a rabbit."

## Later Wittgenstein: meaning as use

Wittgenstein returned to Cambridge in 1929, persuaded partly by Ramsey that the *Tractatus* had serious mistakes. He submitted it as his doctoral thesis; at the end of the oral examination, the story goes, he clapped his examiners, Russell and Moore, on the shoulder and told them not to worry, they would never understand it.

Over the next twenty years he developed a new philosophy, published after his death as *Philosophical Investigations* (1953). Its opening attacks a picture of language he had shared, the "Augustinian" picture from Augustine's *Confessions*, in which every word names an object and a child learns language by having things pointed out.

### Language-games and family resemblance

Instead, Wittgenstein asks you to look at how words are actually used. In §2 he describes a language of builders: A calls out "Block!", "Pillar!", "Slab!", "Beam!", and B brings the stone. This is a complete language for that activity; the words are not labels but moves. Wittgenstein calls such practices **language-games** and lists many: giving orders, describing an object, reporting an event, making up a story, play-acting, telling a joke, asking, thanking, cursing, greeting, praying (§23). The point is that language is part of a **form of life** (*Lebensform*), woven into human activities. The slogan that summarizes the shift:

> For a *large* class of cases—though not for all—in which we employ the word "meaning" it can be defined thus: the meaning of a word is its use in the language.
>
> — Wittgenstein, *Philosophical Investigations* §43 (tr. G. E. M. Anscombe)

Next he attacks the assumption that a general word must name something common to all its instances. What do all games have in common? Board games, card games, ball games, Olympic games, ring-around-the-rosy? Some involve winning, some do not; some need skill, some luck. Wittgenstein's instruction is to stop theorizing and look at the cases (§66). You find a network of overlapping, criss-crossing similarities, which he calls **family resemblances** (§67), like the shared nose of one cousin and the shared gait of another. Many concepts philosophers have tried to define by necessary and sufficient conditions ("knowledge," "art," "religion," "game") may have no essence at all.

### Rules and private language

Two arguments in the *Investigations* have generated vast literatures.

**Rule-following** (§§138–242). A pupil is taught to continue the series "add 2." Up to 1000 he does it correctly; then he writes 1004, 1008, 1012, and insists he is going on in the same way. Nothing in the finite examples, or in any formula or mental image he might have had, logically excludes his interpretation. The paradox (§201) is that any course of action can be made out to accord with a rule under some interpretation, so no rule seems to determine anything. His resolution is that following a rule is not interpreting it but a practice, a custom, mastered in a community. Saul Kripke's *Wittgenstein on Rules and Private Language* (1982) turned this into a skeptical argument (how do you know you meant *plus* and not *quus*, a function that agrees with plus for small numbers and gives 5 above 57?) with a "skeptical solution": meaning facts consist in community assertion conditions. Critics, especially John McDowell and G. P. Baker and P. M. S. Hacker, argue that "Kripkenstein" misreads Wittgenstein, who meant to dissolve the paradox, not accept it.

**The private language argument** (§§243–315). Could there be a language whose words refer to the speaker's private sensations, which only the speaker could understand? Suppose you decide to write "S" in a diary whenever you have a certain sensation. What makes it correct to write "S" next time? Only that it seems to you the same sensation. But if whatever seems right is right, Wittgenstein replies, the word "right" has lost its grip (§258). Without a public criterion of correctness, there is no rule, and so no meaning. In §293 he offers the parable of the **beetle in a box**: everyone has a box with something in it called a "beetle," no one can look into anyone else's box, and everyone says he knows what a beetle is by looking at *his* beetle. The thing in the box, Wittgenstein says, has no place in the language-game at all. The argument is aimed at a picture of the mind that runs from Descartes to the sense-data of Russell, and it reappears in [Chapter 20 — Philosophy of Mind](20-philosophy-of-mind.md).

### Philosophy as therapy

The later Wittgenstein regards philosophical problems as confusions that arise when words are lifted out of the practices that give them sense, when language idles instead of working (§38). Philosophy is a struggle against being bewitched by our own forms of expression (§109); in the image of §309, its aim is to show a trapped fly the way out of the bottle. Note how close this is to Dewey's "we do not solve them: we get over them" ([Chapter 17](17-pragmatism.md)), and to the *Tractatus*' own "vanishing" of the problem of life. The continuity between early and late Wittgenstein is itself a scholarly controversy.

## Ordinary language philosophy

At Oxford after 1945 a loosely allied group took a related line without Wittgenstein's intensity. **Gilbert Ryle**'s *The Concept of Mind* (1949) attacked Descartes' picture of a mind inside a body, the *ghost in the machine*, as a **category mistake**: like a visitor shown the colleges, libraries and laboratories of Oxford who then asks where the University is, as if it were one more building. Talk of minds, Ryle argued, is talk of how people behave and are disposed to behave (see [Chapter 20](20-philosophy-of-mind.md)).

**J. L. Austin**, in *How to Do Things with Words* (1962), noticed **performatives**: "I do" at a wedding, "I name this ship the *Queen Elizabeth*," "I bet you sixpence it will rain." These are not true or false descriptions; they *do* things, and they can misfire. His **speech-act theory** distinguishes what you say (the locutionary act), what you do in saying it (the illocutionary act: warning, promising), and what you bring about by saying it (the perlocutionary act: alarming, persuading). Ordinary language, he held, is not the last word in philosophy, but it is the first.

**P. F. Strawson**'s "On Referring" (1950) argued that someone who says "The present King of France is bald" does not assert but *presupposes* that there is a King of France (Dialogue 1 stages the quarrel with Russell). **Paul Grice**'s theory of **conversational implicature** ("Logic and Conversation," 1967) explained how we communicate more than we literally say. His example is a reference letter for a philosophy job candidate that says only that the candidate's English is excellent and his attendance at tutorials regular. Nothing false is said; a great deal is meant.

## Where the analytic tradition went

By the 1970s the "linguistic turn" had run its course, and analytic philosophy returned to metaphysics with new tools. The decisive event was a set of three lectures given without notes by Saul Kripke at Princeton in 1970, published as *Naming and Necessity* (1980). Kripke argued that Russell's descriptivism about names is false: if "Gödel" meant "the man who proved the incompleteness theorem," then if it turned out that someone named Schmidt had really proved it, "Gödel" would refer to Schmidt, which it plainly would not. Names are **rigid designators**, picking out the same object in every possible world. And Kripke separated three distinctions that Hume and the positivists had run together: *a priori*/*a posteriori* (epistemology), necessary/contingent (metaphysics), and analytic/synthetic (semantics). "Hesperus is Phosphorus" and "water is H₂O" are, he argued, necessary yet known only *a posteriori*. With that, essentialism, possible worlds and old-fashioned metaphysics returned, and David Lewis's modal realism, the view that all possible worlds are as real as ours, became a serious position.

Histories long told this as a story of men; recent scholarship has corrected it. Susan Stebbing became Britain's first woman professor of philosophy in 1933 and wrote *Thinking to Some Purpose* (1939), a critical-thinking manual aimed at the propaganda of the day. Ruth Barcan Marcus published the first quantified modal logic in 1946–47, anticipating Kripke on the necessity of identity. At wartime Oxford, Elizabeth Anscombe, Philippa Foot, Iris Murdoch and Mary Midgley challenged Ayer's emotivism and revived virtue ethics (see [the Ethics course, Chapter 13](../learn-ethics/13-the-virtue-ethics-revival.md)); their story is told in Benjamin Lipscomb's *The Women Are Up to Something* (2021) and Clare Mac Cumhaill and Rachael Wiseman's *Metaphysical Animals* (2022).

Today "analytic philosophy" names a style (explicit arguments, clear definitions, engagement with logic and the sciences, the journal article as the main unit of work) more than any doctrine. Its practitioners include realists and anti-realists, physicalists and dualists, Kantians and utilitarians. What they share is the conviction Moore stated in 1903: find out exactly what the question is before you try to answer it.

## Living it

The analytic tradition gives you a set of habits you can practice on anything you read or say.

1. **Moore's question first.** Take a question you have been stuck on ("Am I a good person?", "Is my job meaningful?", "Should I forgive her?"). Before answering, write down at least three different questions it could be. "Am I a good person?" might mean "Do I usually act rightly?", "Are my motives decent?", or "Would the people who know me best approve of me?" Moore's claim is that many disagreements, including disagreements with yourself, dissolve or sharpen at this step.
2. **Russell's scope test.** When a headline or a speech uses a definite description ("the will of the people," "the real reason," "the science"), unpack it Russell's way: Is there such a thing? Is there exactly one? Does the predicate hold of it? Many rhetorical tricks live in a description that presupposes existence and uniqueness without arguing for either.
3. **Wittgenstein's "don't think, but look."** Pick a value-word that matters to you, such as "fair," "success" or "love." Instead of defining it, collect ten real cases where you or others used it, and lay out the overlapping similarities. Ask whether you have been assuming a single essence that is not there.
4. **Austin's performatives.** For one day, notice what you *do* with words: promising, apologizing, blaming. Which acts misfired, and why?

## Summary

- The analytic turn treated philosophical problems as problems of logic and language; Moore demanded that we discover what a question asks before answering it.
- Frege invented modern quantificational logic, the context principle, and the sense/reference distinction (Morning Star/Evening Star). Russell's paradox wrecked his logicist system.
- Russell's theory of descriptions analyzes "The F is G" as an existential claim with uniqueness, dissolving the puzzle of non-existent referents and showing that grammatical form can mislead. His acquaintance/description distinction made names into disguised descriptions.
- Moore attacked idealism (*esse est percipi*), defended common sense ("here is one hand"), and launched metaethics with the open question argument.
- The *Tractatus*: the world is the totality of facts; propositions picture facts; logical form is shown, not said; ethics and the meaning of life lie beyond what can be said; the book is a ladder to be thrown away. Readings divide into ineffabilist and resolute.
- The Vienna Circle's verification principle declared metaphysics meaningless; it failed on universal laws, on attempts to weaken it, and on its own status.
- Quine rejected the analytic/synthetic distinction and reductionism in favor of holism and naturalism; "to be is to be the value of a variable."
- Later Wittgenstein: meaning as use, language-games, family resemblance, rule-following, the private language argument, philosophy as therapy.
- Ordinary language philosophy (Ryle, Austin, Strawson, Grice) studied speech acts, presupposition and implicature. Kripke's *Naming and Necessity* restored metaphysics; recent histories have restored Stebbing, Barcan Marcus and the Oxford quartet.

## Dialogues

### Dialogue 1 — On the King of France

**Russell:** I have a simple question for you. Is the present King of France bald?

**You:** …

*Your turn: answer Russell in three or four sentences before opening the continuation. Then ask yourself what he will ask next.*

<details><summary>Continue the dialogue</summary>

**You:** No. There is no King of France, so he can't be bald.

**Russell:** Then "The present King of France is bald" is false?

**You:** I suppose so.

**Russell:** And so its negation, "The present King of France is not bald," is true?

**You:** No, that's no better. It also talks about a king who doesn't exist.

**Russell:** Then you have a sentence that is neither true nor false, or a sentence whose negation is also false. Either way, the law of excluded middle is in trouble. Shall we give it up?

**You:** I'd rather not. Maybe the phrase refers to some non-existent king, the way "Sherlock Holmes" refers to a fictional detective?

**Russell:** That is Meinong's view, and it fills the universe with golden mountains and round squares. One should preserve a robust sense of reality. Try this instead: when you say "The present King of France is bald," what are you claiming about the world?

**You:** That there is a King of France, that there's only one, and that he's bald.

**Russell:** Precisely. Then the sentence is simply false, because its first clause is false. Now the negation. Does "not" apply to the whole claim, or only to "bald"?

**You:** I see. If it applies to the whole thing, then "it's not the case that there is exactly one King of France who is bald" is true. If only to "bald," then "there is exactly one King of France and he is not bald" is false.

**Russell:** And excluded middle survives, because the two "negations" were different propositions all along. Grammar deceived you.

**Strawson:** May I object? Nobody who says "The King of France is bald" is *asserting* that there is a King of France. He is presupposing it. If I said it to you, you would not reply "That's false!" You would say, "But there is no King of France." The question of truth does not arise.

**You:** That does match how I'd actually respond.

**Russell:** Mr. Strawson is describing what people ordinarily say. I am describing what the proposition is. Ordinary usage is a poor guide to logic.

**Strawson:** And you are inventing a proposition that no one ever uttered.

**You:** So the disagreement is about what the theory is for. If it is a theory of the logical content of propositions, for use in mathematics and science, Russell's analysis is clean and preserves classical logic. If it is a theory of what speakers do when they talk, Strawson's notion of presupposition fits better. Both learned something real: grammatical subjects don't always name things.

**Russell:** That is a respectable conclusion, though I maintain that mine is the more important one.

</details>

### Dialogue 2 — On whether "fair" needs a definition

**Wittgenstein:** You have told me that your company's new promotion policy is unfair. What does "fair" mean?

**You:** …

*Your turn: answer Wittgenstein in three or four sentences before opening the continuation. Then ask yourself what he will ask next.*

<details><summary>Continue the dialogue</summary>

**You:** Fair means treating people equally.

**Wittgenstein:** Is it fair to give the same exam to a blind student as to a sighted one?

**You:** No. So fair means treating people according to their needs.

**Wittgenstein:** Is it fair to give the prize to the runner who most needs the money, rather than to the one who crossed the line first?

**You:** No. Then fair means giving people what they deserve.

**Wittgenstein:** Is a lottery fair? No one deserves to win.

**You:** Yes, a lottery is fair if everyone has the same chance. I keep finding exceptions. Maybe I just don't know what fairness is.

**Wittgenstein:** Or you are looking for something that is not there. You assume that because we call all these things "fair," there must be one thing common to them. Stop theorizing and look at the cases. What do you see?

**You:** Equal treatment in some cases, need in others, desert in others, equal chances in others. They overlap. A fair exam is fair partly because everyone faces the same questions and partly because accommodations remove irrelevant obstacles.

**Wittgenstein:** Like the resemblances in a family. Now, does your inability to define "fair" mean you cannot say whether the policy is unfair?

**You:** No. I can point to which strand of fairness it violates. It promotes people based on who socializes with the director, which has nothing to do with desert, need or equal chance.

**Wittgenstein:** Then you understood "fair" all along. You understood it as one understands a game: by being able to go on, to recognize cases, to argue about borderline ones.

**Socrates:** Forgive me, but in my day we thought a man who could not say what justice is did not know it.

**Wittgenstein:** And your friends left your conversations in *aporia*, unable to define what they could perfectly well recognize. Perhaps the demand for a definition was the confusion.

**Socrates:** Or perhaps the search for a definition, even when it fails, teaches us which strands matter and why. You yourself have just made our friend sort them.

**You:** Then maybe both are right. I don't need a definition to use the word correctly or to criticize the policy. But trying to define it, and failing in instructive ways, showed me the different considerations that go into fairness and made my criticism sharper.

</details>

### Dialogue 3 — On whether "life has meaning" means anything

**Ayer:** You said yesterday that you believe life has meaning. What observation would count for or against that statement?

**You:** …

*Your turn: answer Ayer in three or four sentences before opening the continuation. Then ask yourself what he will ask next.*

<details><summary>Continue the dialogue</summary>

**You:** I'm not sure any observation would. It isn't that kind of claim.

**Ayer:** Then it is not analytic, since its denial is not a contradiction, and it is not empirically verifiable. By the principle of verification it is literally meaningless. It expresses a feeling, perhaps an admirable one, but it says nothing.

**You:** Is the principle of verification itself analytic or verifiable?

**Ayer:** It is a definition of "literal meaning," a proposal I offer for your acceptance.

**You:** Then I can decline the proposal. Why should I accept a definition of "meaning" on which my most important beliefs come out meaningless?

**Ayer:** Because it is the definition that makes sense of science and mathematics, where we actually know things.

**You:** Science also contains universal laws that can't be conclusively verified, and you had to weaken the principle until, I've read, it let in everything.

**Ayer:** I concede that I never found a satisfactory formulation. The spirit remains: be suspicious of statements that make no difference to anything.

**Wittgenstein:** Allow me to defend our friend from a different direction. I also said that the meaning of life cannot be stated as a fact. "The sense of the world must lie outside the world." Even if all scientific questions were answered, the problems of life would not have been touched.

**You:** So you agree with Ayer that it can't be said?

**Wittgenstein:** I said it cannot be said. I did not say it is nothing. Those to whom, after long doubting, the sense of life became clear could not say wherein it consisted. It shows itself in how they live.

**Ayer:** That is mysticism. I prefer to call it emotion.

**You:** Here's where I've come out. Ayer is right that "life has meaning" is not a factual claim like "water boils at 100°C," and that I should be suspicious if I think it describes some hidden cosmic fact. But Wittgenstein suggests that its sense might lie in a way of living rather than in a proposition. If so, the right test is not "what observation would verify it?" but "what difference does it make to how I live?", which is close to the pragmatists' question.

**Ayer:** You have turned a metaphysical statement into a description of an attitude. I can accept that, provided you don't then claim it is true in the way science is true.

**Wittgenstein:** And I would add only: be careful not to chatter about it.

</details>

Sources for this chapter: [REFERENCES.md](REFERENCES.md#chapter-18--the-analytic-turn)
