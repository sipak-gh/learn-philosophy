# Chapter 2 — Logic and Argument

Philosophers have no laboratories. Their instrument is the argument, and logic is the study of what makes an argument good. This chapter gives you the working toolkit you will use in every later chapter: how to spot an argument and write it in standard form; the difference between deduction and induction, validity and soundness; the argument forms worth memorizing; the classic fallacies, including the dirty tricks Schopenhauer catalogued with a straight face; the principle of charity; the Socratic method of question and counterexample; and the thought experiment, philosophy's substitute for the lab. Along the way you will meet two of the deepest puzzles in the subject: Mill's worry that deduction can never teach anything new, and Hume's argument that induction has no rational foundation at all.

Previous: [Chapter 1 — What Is Philosophy?](01-what-is-philosophy.md). Next: [Chapter 3 — The Presocratics](03-the-presocratics.md).

## Required reading

- Arthur Schopenhauer, *The Art of Controversy* (tr. T. Bailey Saunders), the whole essay: [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Fschopenhauer-art-of-controversy-pg10731.epub) [File](readings/schopenhauer-art-of-controversy-pg10731.epub).
- David Hume, *An Enquiry Concerning Human Understanding*, Section IV "Sceptical Doubts Concerning the Operations of the Understanding": [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Fhume-enquiry-concerning-human-understanding-pg9662.epub) [File](readings/hume-enquiry-concerning-human-understanding-pg9662.epub).
- Bertrand Russell, *The Problems of Philosophy*, Chapter VI "On Induction": [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Frussell-problems-of-philosophy-pg5827.epub) [File](readings/russell-problems-of-philosophy-pg5827.epub).
- Plato, *Theaetetus* 148e–151d, Socrates the midwife (tr. Benjamin Jowett): [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Fplato-theaetetus-pg1726.epub) [File](readings/plato-theaetetus-pg1726.epub).
- Anthony Weston, *A Rulebook for Arguments*, 5th ed. (Hackett, 2017), the whole book (under 100 pages). **(procure yourself)**

Further reading:

- John Stuart Mill, *A System of Logic* (8th ed., 1872), Book II Ch. III, Book III Ch. VIII, Book V Ch. I: [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Fmill-system-of-logic-pg27942.epub) [File](readings/mill-system-of-logic-pg27942.epub).
- A. E. Taylor, *Aristotle* (1919), the chapter on logic: [Read](https://sipak-gh.github.io/webreader/?source=https%3A%2F%2Fraw.githubusercontent.com%2Fsipak-gh%2Flearn-philosophy%2Fmaster%2Freadings%2Ftaylor-aristotle-pg48002.epub) [File](readings/taylor-aristotle-pg48002.epub).
- Graham Priest, *Logic: A Very Short Introduction*, 2nd ed. (Oxford University Press, 2017). **(procure yourself)**
- Daniel C. Dennett, *Intuition Pumps and Other Tools for Thinking* (W. W. Norton, 2013). **(procure yourself)**

## What an argument is

In ordinary speech an "argument" is a quarrel. In logic it is something calmer: a set of statements, the **premises**, offered as reasons for another statement, the **conclusion**. The word comes from the Latin *arguere*, "to make clear." An argument tries to make a conclusion clear by showing what supports it.

Three things that look like arguments are not:

- **An assertion**, however loud, is just a claim. "Abortion is murder" and "Abortion is a right" are conclusions in search of premises.
- **An explanation** tells you *why* something you already accept is true ("The bridge collapsed because the bolts corroded"). An argument tries to convince you *that* something is true ("The bolts must have corroded, since the bridge collapsed and there was no overload"). The same "because" can do either job, so ask: is the speaker trying to prove the claim, or to account for it?
- **A story or illustration** can make a view vivid without supporting it. Plato's myths often work this way, and he usually marks them as myths.

To analyze an argument, put it in **standard form**: number the premises, draw a line, write the conclusion. Indicator words help. *Since, because, for, given that* usually introduce premises; *therefore, so, hence, thus, it follows that* introduce conclusions. Real arguments leave premises unstated (such an argument is traditionally called an *enthymeme*, borrowing Aristotle's term for a rhetorical argument), and part of your job is to supply the missing ones, charitably. You did this with Socrates' argument about death in [Chapter 1](01-what-is-philosophy.md).

## Deduction: validity and soundness

The first great division is between deductive and inductive arguments. A **deductive** argument aims to make its conclusion *necessary* given its premises. Aristotle, whose treatises later grouped as the *Organon* ("tool") are the first systematic treatment of formal logic that survives (fourth century BCE), defined the deductive argument, the *sullogismos*, like this:

> "Syllogism is a discourse wherein certain things (viz. the premisses) being admitted, something else, different from what has been admitted, follows of necessity because the admissions are what they are."
>
> — Aristotle, *Prior Analytics* 1.1, 24b18–20, as translated in A. E. Taylor, *Aristotle* (1919)

Every phrase counts. "Something else" means the conclusion is not just a premise repeated. "Follows of necessity" is the heart of deduction. "Because the admissions are what they are" means the necessity comes from the premises themselves, not from outside facts.

From this come the two most important terms in this course:

- An argument is **valid** if and only if it is *impossible* for all the premises to be true and the conclusion false. Validity is about the connection, not the truth of the parts.
- An argument is **sound** if and only if it is valid *and* all its premises are true. A sound argument has a true conclusion, guaranteed.

Validity does not require true premises, and true premises plus a true conclusion do not guarantee validity. Study these four cases until they are obvious:

| | Premises | Conclusion | Valid? | Sound? |
|---|----------|-----------|--------|--------|
| A | All fish fly. Socrates is a fish. | So Socrates flies. | yes | no |
| B | All humans are mortal. Socrates is human. | So Socrates is mortal. | yes | yes |
| C | All humans are mortal. Socrates is mortal. | So Socrates is human. | **no** | no |
| D | If it rains, the street is wet. The street is wet. | So it rained. | **no** | no |

Argument A is absurd but valid: *if* its premises were true, its conclusion would have to be. Argument C has true premises and a true conclusion, but it is invalid: Socrates's dog is also mortal, and that does not make the dog human. The method you just used is the **method of counterexample**: to show an argument form invalid, find an argument with *the same form* whose premises are plainly true and whose conclusion is plainly false. It is the single most useful tool in philosophy.

So when you criticize a deductive argument there are exactly two strategies. You can attack the **form** (the conclusion does not follow) or attack a **premise** (it is false or unsupported). Saying "I just don't like the conclusion" is not a third strategy. If an argument is valid and you reject the conclusion, logic forces you to reject at least one premise. Philosophers say: one person's *modus ponens* is another's *modus tollens*. If you are more confident the conclusion is false than that the premises are true, run the argument backwards.

### Argument forms worth memorizing

Validity depends on **form**: the pattern that remains when you replace the specific content with letters. The ancient Stoics, especially Chrysippus (third century BCE), worked out the logic of sentences joined by "if," "or," and "and," and listed five "indemonstrable" forms from which they derived the rest. (The [Stoicism course, Chapter 5](../learn-stoicism/05-logic-and-knowledge.md) treats Stoic logic in detail.) The modern names are Latin and medieval:

| Name | Form | Example |
|------|------|---------|
| *Modus ponens* (affirming the antecedent) | If P then Q. P. So Q. | If she is in Athens, she is in Greece. She is in Athens. So she is in Greece. |
| *Modus tollens* (denying the consequent) | If P then Q. Not Q. So not P. | If he were guilty, his prints would be on the knife. They are not. So he is not guilty. |
| Hypothetical syllogism | If P then Q. If Q then R. So if P then R. | |
| Disjunctive syllogism | P or Q. Not P. So Q. | Either the butler or the maid did it. Not the butler. So the maid. |
| Constructive dilemma | P or Q. If P then R. If Q then S. So R or S. | (Socrates on death, Chapter 1, with R = S = "death is a gain") |
| *Reductio ad absurdum* | Assume P. Derive a contradiction. So not P. | Zeno's paradoxes ([Chapter 3](03-the-presocratics.md)) |

And two **invalid** forms that look valid and fool people every day:

| Fallacy | Form | Why it fails |
|---------|------|-------------|
| Affirming the consequent | If P then Q. Q. So P. | Case D above: the street can be wet because of a hose. |
| Denying the antecedent | If P then Q. Not P. So not Q. | "If you study you will pass. You did not study. So you will fail." You might be lucky. |

Aristotle's own system is different: it concerns sentences of four types ("All A are B," "No A are B," "Some A are B," "Some A are not B") linked by a shared "middle term." The most famous valid pattern was later nicknamed *Barbara* (the three vowels mark three universal affirmatives): All B are C; all A are B; so all A are C. Aristotle's syllogistic was the core of logic for two thousand years, until Gottlob Frege (1879) created modern predicate logic, which handles "all," "some," relations and nested quantifiers that Aristotle's system could not ([Chapter 18](18-the-analytic-turn.md)). Kant thought logic had not taken a single step forward since Aristotle; within a century of his death, that had become false.

### The law of non-contradiction

Underneath all valid forms is a principle Aristotle called "the firmest of all" (*Metaphysics* Γ 3, 1005b19–20): the same attribute cannot at the same time belong and not belong to the same thing in the same respect. Without it, you could not reject any premise, because rejecting a claim would not exclude accepting it. Aristotle admits the principle cannot be proved (any proof would presuppose it) but argues that anyone who denies it refutes himself the moment he says anything definite. A. E. Taylor, in his little 1919 book, thought Aristotle's defense begged the question. Modern *dialetheists* such as Graham Priest go further and argue that a few contradictions (the liar sentence "This sentence is false" is the usual candidate) are true. You do not have to follow them, but you should know that even the firmest principle has living critics.

### Is deduction useless? Mill's challenge

Here is a puzzle that should bother you. If a valid argument's conclusion is already "contained in" its premises, how can deduction ever teach you anything? John Stuart Mill pressed this in his *System of Logic* (1843) with the textbook syllogism:

> All men are mortal,  
> The Duke of Wellington is a man,  
> therefore  
> The Duke of Wellington is mortal.
>
> — John Stuart Mill, *A System of Logic*, Book II, Ch. III, §2

How do you know the first premise? Only if you already know that every man, Wellington included, is mortal. So the syllogism seems to assume what it proves. Mill states the dilemma sharply: either the conclusion is already asserted in the premises (so the argument is circular) or it is not (so the argument is invalid). His solution is that the real inference is *inductive*, from particular past deaths to this particular case, and the general premise is only a memorandum:

> The error committed is, I conceive, that of overlooking the distinction between two parts of the process of philosophizing, the inferring part, and the registering part; and ascribing to the latter the functions of the former.
>
> — John Stuart Mill, *A System of Logic*, Book II, Ch. III, §3

The standard modern reply distinguishes **logical** novelty from **psychological** novelty. A deduction adds no information in the logical sense (the conclusion is true in every possible situation where the premises are), but it can be news to *you*, because you did not know what your premises implied. All of mathematics is deduction from axioms, and Fermat's Last Theorem was news to everyone in 1994. Philosophers call the residue of Mill's worry the "scandal of deduction" (Jaakko Hintikka's phrase), and it is still discussed in work on logical omniscience and the information content of proofs.

## Induction: probable reasoning and Hume's problem

An **inductive** argument aims to make its conclusion *probable* rather than certain. It is not invalid deduction; it is a different enterprise, judged on a different scale. Inductive arguments are **strong** or **weak**, and a strong one with true premises is called **cogent**. Common types:

- **Enumerative induction**: every observed raven has been black, so all ravens are black (or: the next raven will be black).
- **Statistical syllogism**: 95 percent of patients with these symptoms have flu; this patient has these symptoms; so this patient (probably) has flu.
- **Argument from analogy**: a mouse's liver resembles a human liver in relevant ways; this drug damaged mouse livers; so it will probably damage human livers.
- **Inference to the best explanation** (what C. S. Peirce called *abduction*): the floor is wet, the window is open, and it rained last night; the best explanation is that rain came through the window. Detective stories and most of science run on it.

Mill gave the most famous rules for finding causes inductively, his "methods of experimental inquiry." Two of them carry most of the weight:

> If two or more instances of the phenomenon under investigation have only one circumstance in common, the circumstance in which alone all the instances agree, is the cause (or effect) of the given phenomenon.
>
> — John Stuart Mill, *A System of Logic*, Book III, Ch. VIII, §1 (the Method of Agreement)

> If an instance in which the phenomenon under investigation occurs, and an instance in which it does not occur, have every circumstance in common save one, that one occurring only in the former; the circumstance in which alone the two instances differ, is the effect, or the cause, or an indispensable part of the cause, of the phenomenon.
>
> — John Stuart Mill, *A System of Logic*, Book III, Ch. VIII, §2 (the Method of Difference)

The Method of Difference is the logic of the controlled experiment: two groups alike in everything except the treatment. Mill's own example is grim and clear: a man shot through the heart was "in the fullness of life immediately before, all circumstances being the same, except the wound."

### Hume's problem

Now the bombshell. Every inductive inference assumes that the future will resemble the past, or more generally that unobserved cases resemble observed ones. Can we justify that assumption? David Hume argued in 1748 that we cannot, without going in a circle.

> If there be any suspicion that the course of nature may change, and that the past may be no rule for the future, all experience becomes useless, and can give rise to no inference or conclusion. It is impossible, therefore, that any arguments from experience can prove this resemblance of the past to the future; since all these arguments are founded on the supposition of that resemblance.
>
> — David Hume, *An Enquiry Concerning Human Understanding*, Section IV, Part II

Reconstructed:

1. Any justification of the principle that the future resembles the past (call it the Uniformity Principle, UP) must be either demonstrative (deductive, *a priori*) or probable (based on experience).
2. It cannot be demonstrative, because the denial of UP involves no contradiction: we can clearly conceive snow that tastes of salt, or trees that bloom in December.
3. It cannot be probable, because every probable argument already assumes UP; using it to justify UP is circular.
4. So UP cannot be justified.
5. So inductive inferences have no rational justification.

Hume's conclusion is not that you should stop expecting the sun to rise. It is that the expectation comes from **custom** or habit, not from reason: "All inferences from experience, therefore, are effects of custom, not of reasoning." Russell put it unforgettably:

> The man who has fed the chicken every day throughout its life at last wrings its neck instead, showing that more refined views as to the uniformity of nature would have been useful to the chicken.
>
> — Bertrand Russell, *The Problems of Philosophy*, Ch. VI

The main responses, each of which you will meet again in [Chapter 21](21-knowledge-and-science.md):

- **Inductive justification of induction.** Induction has worked in the past, so it will work in the future. This is exactly the circle Hume pointed out, though some (Max Black, Braithwaite) argued that "rule-circularity" is not vicious.
- **Analytic dissolution** (P. F. Strawson, 1952): asking whether induction is reasonable is like asking whether the law is legal. Being reasonable, in empirical matters, *means* proportioning belief to inductive evidence.
- **Pragmatic vindication** (Hans Reichenbach, 1938): if any method can find regularities in nature, induction will; so using it is the best bet, even if we cannot show it will succeed.
- **Abandonment** (Karl Popper): science does not use induction at all; it proposes bold conjectures and tries to refute them deductively, by *modus tollens*.
- **Bayesianism**: rational belief is degree of belief updated by Bayes' theorem; this regulates induction without solving Hume's problem at the root, since the prior probabilities still need justification.

Nelson Goodman made matters worse in 1955 with the "new riddle of induction." Define an object as *grue* if it is green and observed before 2050, or blue and not so observed. Every emerald observed so far is green, and also grue. Why does our evidence support "all emeralds are green" rather than "all emeralds are grue," which predicts blue emeralds after 2050? Something about which predicates are "projectible" is doing the work, and no one agrees on what.

## Fallacies

A **fallacy** is a pattern of reasoning that is bad but tends to look good. Mill introduced his treatment of them with an old scholastic maxim:

> It is a maxim of the school-men, that "contrariorum eadem est scientia:" we never really know what a thing is, unless we are also able to give a sufficient account of its opposite.
>
> — John Stuart Mill, *A System of Logic*, Book V, Ch. I, §1

**Formal** fallacies are invalid forms, like affirming the consequent. **Informal** fallacies depend on content, context or language. The classical list goes back to Aristotle's *Sophistical Refutations*, and every generation adds names. Here are the ones you will meet most, with honest caveats.

- **Equivocation.** Using a word in two senses within one argument. "The end of a thing is its perfection; death is the end of life; so death is the perfection of life." *End* means "goal" in premise one and "termination" in premise two. Schopenhauer calls the controversial version "Homonymy": "to extend a proposition to something which has little or nothing in common with the matter in question but the similarity of the word; then to refute it triumphantly."
- **Straw man.** Refuting a weaker version of the opponent's view than the one held. Schopenhauer's first stratagem, the "Extension," is the art of doing it deliberately (quoted below).
- **Begging the question** (*petitio principii*). Assuming what is to be proved. Mill takes over Archbishop Whately's definition: the fallacy "in which the premise either appears manifestly to be the same as the conclusion, or is actually proved from the conclusion, or is such as would naturally and properly so be proved." (In everyday English, "begs the question" has drifted to mean "raises the question"; philosophers keep the old sense.)
- **Ad hominem.** Attacking the arguer rather than the argument. Caveat: when the issue is someone's *testimony* or *expertise*, their reliability is relevant. And there is an older, respectable sense, discussed below.
- **Tu quoque** ("you too"). "You say smoking is bad, but you smoke." The hypocrisy is real; the argument against smoking is untouched.
- **False dilemma.** Presenting two options as the only ones. Socrates' "nothingness or migration" in the *Apology* may be one.
- **Slippery slope.** Claiming that a first step will inevitably lead to a terrible last one. Caveat: some slopes really are slippery; the fallacy is to *assert* the slide without evidence for each step.
- **Appeal to authority.** Citing someone as an authority outside their field, or citing a disputed authority as if settled. Appeals to genuine expert consensus within the expert's field are reasonable inductive arguments.
- **Post hoc ergo propter hoc** ("after this, therefore because of this"). Inferring causation from sequence. Mill's methods are the cure.
- **Composition and division.** Inferring that a whole has a property because its parts do, or the reverse. Every brick is light; the wall is not.
- **Genetic fallacy.** Judging a belief by its origin rather than its grounds. Caveat: in "debunking arguments" (Nietzsche's genealogy, evolutionary debunking of moral realism in the [nihilism course, Chapter 12](../learn-nihilism/12-moral-nihilism-and-error-theory.md)), origins can matter, because they can show that a belief would have been held whether or not it was true.

Indian logicians of the Nyāya school developed a parallel theory of *hetvābhāsa*, "pseudo-reasons" that look like good evidence but are not, such as a reason that is "inconclusive" because it occurs where the conclusion fails, or "contradictory" because it supports the opposite. Their standard example of a good inference ("the hill has fire, because it has smoke, as in a kitchen") carries its own illustrative case, an analogy built into the form. [Chapter 8](08-classical-india-and-china.md) returns to Indian epistemology.

A warning about fallacy lists. Naming a fallacy is not refuting an argument. Many arguments that superficially fit a fallacy's pattern are fine (appeals to real experts, slippery slopes with evidence for each step, relevant attacks on a witness's reliability). And the "fallacy fallacy" is the inference that because an argument for a conclusion is fallacious, the conclusion is false. Bad arguments are given for true conclusions every day.

### Schopenhauer's catalogue of dirty tricks

Schopenhauer's *The Art of Controversy* (written in the 1830s, published after his death) is the funniest book on logic ever written, and one of the most cynical. He defines his subject with brutal honesty:

> Controversial Dialectic is the art of disputing, and of disputing in such a way as to hold one's own, whether one is in the right or the wrong—*per fas et nefas*.
>
> — Arthur Schopenhauer, *The Art of Controversy* (tr. T. Bailey Saunders)

He then lists thirty-eight stratagems, so that you can recognize them when they are used on you. The first is the straw man by exaggeration:

> The *Extension*.—This consists in carrying your opponent's proposition beyond its natural limits; in giving it as general a signification and as wide a sense as possible, so as to exaggerate it; and, on the other hand, in giving your own proposition as restricted a sense and as narrow limits as you can, because the more general a statement becomes, the more numerous are the objections to which it is open.
>
> — Arthur Schopenhauer, *The Art of Controversy*, Stratagem I

The defense, he notes, "consists in an accurate statement of the point or essential question at issue." The last stratagem is the one everybody knows:

> A last trick is to become personal, insulting, rude, as soon as you perceive that your opponent has the upper hand, and that you are going to come off worst. It consists in passing from the subject of dispute, as from a lost game, to the disputant himself, and in some way attacking his person. It may be called the *argumentum ad personam*, to distinguish it from the *argumentum ad hominem*, which passes from the objective discussion of the subject pure and simple to the statements or admissions which your opponent has made in regard to it.
>
> — Arthur Schopenhauer, *The Art of Controversy*, Stratagem XXXVIII

Note his distinction. For Schopenhauer (and for older logicians, including Locke), *ad hominem* meant arguing from the opponent's own admissions (*ex concessis*): "By your own principles, you must accept this." That is a legitimate way to show inconsistency, and Socrates used it constantly. The insulting kind he calls *ad personam*. Modern textbooks have merged the two under "ad hominem," which loses a useful distinction.

## The principle of charity

The opposite of Schopenhauer's art is the **principle of charity**: interpret others so that what they say comes out as true and as reasonable as possible, consistent with the evidence of what they actually said. The phrase comes from N. L. Wilson (1959), and Donald Davidson made it a principle of all interpretation: you cannot even identify what someone *means* without assuming most of their beliefs are true. In debate culture it survives as "steelmanning," building the strongest version of the opposing view before you criticize it.

Charity is not politeness. It is a method of getting at the truth, for two reasons. First, if you refute a weak version, the strong version is still standing and you have learned nothing. Second, the strongest version of a view you reject often contains the part of the truth you were missing. Schopenhauer, after thirty-eight tricks, ends with surprisingly Socratic advice, citing Aristotle's *Topics*:

> The only safe rule, therefore, is that which Aristotle mentions in the last chapter of his *Topica*: not to dispute with the first person you meet, but only with those of your acquaintance of whom you know that they possess sufficient intelligence and self-respect not to advance absurdities; to appeal to reason and not to authority, and to listen to reason and yield to it; and, finally, to cherish truth, to be willing to accept reason even from an opponent, and to be just enough to bear being proved to be in the wrong, should truth lie with him.
>
> — Arthur Schopenhauer, *The Art of Controversy* (tr. T. Bailey Saunders)

He follows this with the cynical calculation that "scarcely one man in a hundred is worth your disputing with him." You do not have to accept the arithmetic to accept the rule.

### Misology: the hatred of argument

There is an opposite danger to being fooled by bad arguments: giving up on argument altogether. Plato puts the warning in Socrates' mouth on the day of his death, just after his friends' objections have shaken their confidence in his proofs of immortality:

> Lest we become misologists, he replied, no worse thing can happen to a man than this. For as there are misanthropists or haters of men, there are also misologists or haters of ideas, and both spring from the same cause, which is ignorance of the world.
>
> — Plato, *Phaedo* 89d (tr. Benjamin Jowett)

The misanthrope trusted people naively, was let down several times, and concluded that everyone is rotten. The misologist trusted arguments naively, was refuted several times, and concluded that no argument is sound. Socrates' diagnosis: blame your own lack of skill, not reason itself. That is good advice for the reader of this course, who will meet brilliant arguments for flatly incompatible conclusions. The response is better logic, not cynicism.

## The Socratic method

Socrates' characteristic method is the *elenchus* (Greek, "examination," "test," "refutation"). Gregory Vlastos, in an influential 1983 paper "The Socratic Elenchus," described the "standard elenchus" this way:

1. The interlocutor asserts a thesis *p*, usually a definition ("Courage is endurance of the soul"). Socrates says he does not know whether it is true.
2. Socrates obtains agreement to further premises *q* and *r*, typically ones the interlocutor finds obvious.
3. Socrates shows that *q* and *r* entail not-*p*.
4. Socrates claims that *p* has been shown false.

Logically, step 4 is too quick. The argument shows only that *p*, *q* and *r* are inconsistent; the interlocutor could give up *q* or *r* instead. Vlastos called this "the problem of the elenchus": how can Socrates claim to have refuted *p* rather than merely exposed an inconsistency? Vlastos's answer was that Socrates assumes anyone with false moral beliefs also holds true beliefs that entail their negation. Other scholars (Richard Kraut, Hugh Benson) argue that Socrates only ever claims to show inconsistency, and that this is enough: it shows you do not *know*.

The most famous early example is the first counterexample in the *Republic*. The old businessman Cephalus has suggested that justice is telling the truth and paying back what you owe:

> Well said, Cephalus, I replied; but as concerning justice, what is it?—to speak the truth and to pay your debts—no more than this? And even to this are there not exceptions? Suppose that a friend when in his right mind has deposited arms with me and he asks for them when he is not in his right mind, ought I to give them back to him?
>
> — Plato, *Republic* 1, 331c (tr. Benjamin Jowett)

The form is the template for a thousand later philosophical moves. A proposed definition says: *X is just if and only if X is a case of truth-telling or debt-repaying*. A counterexample shows a case of debt-repaying that is not just. So the condition is not **sufficient**. Learn the vocabulary:

- A condition C is **necessary** for X if nothing can be X without being C (being a closed figure is necessary for being a triangle).
- C is **sufficient** for X if anything that is C is thereby X (being an equilateral triangle is sufficient for being a triangle).
- A good definition gives conditions that are **jointly necessary and sufficient**. Counterexamples can attack either direction: an X that lacks C (C is not necessary), or a C that is not X (C is not sufficient).

The *elenchus* often ends in *aporia* (literally "no way through," puzzlement). That sounds like failure. Socrates presents it as the beginning of real inquiry, and in the *Theaetetus* he describes his role with a metaphor from his mother's profession:

> Well, my art of midwifery is in most respects like theirs; but differs, in that I attend men and not women; and look after their souls when they are in labour, and not after their bodies: and the triumph of my art is in thoroughly examining whether the thought which the mind of the young man brings forth is a false idol or a noble and true birth.
>
> — Plato, *Theaetetus* 150b–c (tr. Benjamin Jowett)

The midwife does not supply the baby; she helps deliver it and tests whether it is viable. The questioner does not supply the answer; the answerer must produce it, and the questioner tests it. [Chapter 4](04-socrates-and-the-sophists.md) watches the method at work in the *Euthyphro* and discusses Socratic irony. The dialogues at the end of every chapter in this course are built on it.

## Thought experiments

Philosophy's experiments are imaginary. A **thought experiment** describes a possible scenario and asks what we would say about it, in order to test a principle, separate variables that are always mixed in reality, or reveal a hidden commitment. Some of the most famous are older than science.

**Lucretius' spear.** Is the universe bounded? The Roman poet Lucretius (first century BCE), defending Epicurean physics, imagines a traveler at the supposed edge:

> If some one farthest traveller runs forth  
> Unto the extreme coasts and throws ahead  
> A flying spear, is't then thy wish to think  
> It goes, hurled off amain, to where 'twas sent  
> And shoots afar, or that some object there  
> Can thwart and stop it? For the one or other  
> Thou must admit and take.
>
> — Lucretius, *On the Nature of Things* 1.968–975 (tr. William Ellery Leonard)

If the spear flies on, there is space beyond the "edge." If something stops it, there is something beyond the edge. Either way, the edge is not an edge. (The argument, which goes back to the Pythagorean Archytas, is a constructive dilemma; modern cosmology escapes it with a universe that is finite but unbounded, like the surface of a sphere, which neither horn anticipated.)

**The ring of Gyges.** In the *Republic*, Glaucon tells of a shepherd who finds a ring that makes him invisible, and uses it to seduce the queen, kill the king and take the throne. Then he generalizes:

> Suppose now that there were two such magic rings, and the just put on one of them and the unjust the other; no man can be imagined to be of such an iron nature that he would stand fast in justice.
>
> — Plato, *Republic* 2, 360b (tr. Benjamin Jowett)

The experiment isolates a variable: remove all consequences of injustice, and see whether anyone still has reason to be just. The [Ethics course, Chapter 1](../learn-ethics/01-what-is-ethics.md) builds on it.

**Galileo's falling stones.** Aristotle held that heavier bodies fall faster. Galileo (in *Two New Sciences*, 1638) asked: tie a heavy stone to a light one. The light one should slow the heavy one, so the pair falls slower than the heavy stone alone. But the pair is heavier than the heavy stone, so it should fall faster. Contradiction: so speed of fall does not depend on weight. A *reductio* without a laboratory.

Later chapters bring Descartes' evil demon ([Chapter 11](11-descartes-and-the-rationalists.md)), the trolley problem ([Ethics, Chapter 2](../learn-ethics/02-moral-reasoning.md)), Mary the color scientist and the zombie ([Chapter 20](20-philosophy-of-mind.md)), the brain in a vat and Gettier cases ([Chapter 21](21-knowledge-and-science.md)), and Rawls's veil of ignorance ([Chapter 22](22-political-philosophy.md)).

### How do thought experiments work, and do they?

There are two main philosophical accounts. John Norton argues that thought experiments are just **arguments** in picturesque dress: anything you learn from one, you could learn from an explicit argument with premises you already accepted. James Robert Brown, a Platonist, argues that some (Galileo's above all) give us a kind of direct **insight** into laws of nature that goes beyond any premises. A third, practical view says they are tools for consulting our **intuitions**, our considered judgments about cases, which then serve as evidence about concepts or principles.

The skeptics have strong points. Kathleen Wilkes (*Real People*, 1988) argued that thought experiments about personal identity describe scenarios so remote from reality (duplication, teleportation) that our judgments about them are worthless. Daniel Dennett calls many famous thought experiments "intuition pumps" and urges you to "turn the knobs": change a detail that should be irrelevant and see whether the intuition changes. If it does, the experiment was steering you. And since the 2000s, **experimental philosophy** has surveyed ordinary people and found that some intuitions vary with culture, wording or order of presentation, which raises the question whose intuitions count. Defenders reply that philosophers' intuitions are trained judgments like those of expert chess players, and that the variation is smaller than first reported. The debate is live; the [Ethics course, Chapter 18](../learn-ethics/18-moral-psychology-and-responsibility.md) covers its moral side.

## Living it

Logic is a skill, and skills come from practice. For one week:

1. **Put one argument a day into standard form.** Take it from a newspaper editorial, a podcast or a family argument. Number the premises, supply the missing ones charitably, and write the conclusion under a line. Then ask the two questions separately: *Is it valid (or inductively strong)? Are the premises true?*
2. **Steelman before you strike.** Choose a view you strongly reject. Write its best argument in a form that a thoughtful defender would sign. Only then write your objection, aimed at a specific premise. This is the principle of charity and Schopenhauer's "safe rule" made into a habit.
3. **Watch your own stratagems.** In your next disagreement, notice when you reach for Schopenhauer's tricks: exaggerating the other side's claim (Extension), switching the sense of a word (Homonymy), getting personal when you are losing. Schopenhauer wrote his catalogue as satire; the honest use of it is as a mirror.
4. **Practise the counterexample.** When someone states a universal rule ("You should always tell the truth," "Success is earned"), look, as Socrates did with Cephalus, for a case where the condition holds but the conclusion fails. Then try to amend the rule so it survives. That second step is where you learn something.

Remember the *Phaedo*. The point of all this is not to win, and not to become someone who believes nothing because every argument can be attacked. It is to become someone whose beliefs are worth having.

## Summary

- An argument is premises offered in support of a conclusion; put it in standard form and supply missing premises charitably.
- A **valid** deductive argument cannot have true premises and a false conclusion; a **sound** argument is valid with true premises. Validity depends on form; test it by counterexample.
- Key valid forms: *modus ponens*, *modus tollens*, hypothetical and disjunctive syllogism, constructive dilemma, *reductio*. Key invalid forms: affirming the consequent, denying the antecedent.
- Mill argued that the syllogism begs the question; the standard reply separates logical from psychological novelty.
- Inductive arguments are strong or weak, not valid or invalid. Mill's methods of agreement and difference formalize causal reasoning. Hume argued that induction cannot be justified without circularity; responses include Strawson, Reichenbach, Popper and Bayesianism, and Goodman's "grue" deepened the problem.
- Fallacies are tempting bad patterns; naming one is not refuting an argument, and a bad argument can have a true conclusion. Schopenhauer distinguished *ad hominem* (from the opponent's admissions) from *ad personam* (insult).
- The principle of charity and Socrates' warning against misology are complementary: interpret generously, and do not give up on reason when arguments fail.
- The Socratic *elenchus* tests definitions by counterexample, aiming at necessary and sufficient conditions; it often ends in productive *aporia*.
- Thought experiments (Lucretius' spear, Gyges' ring, Galileo's stones) test principles by imagined cases; whether they are disguised arguments, intuition probes or sources of insight is debated.

## Dialogues

These dialogues are imagined, in the tradition of Plato's. Answer before you open each continuation.

### Dialogue 1 — On whether a good argument needs true premises

**Socrates:** Here is an argument. "All philosophers are poor. You are a philosopher. Therefore you are poor." Is it a good argument?

**You:** …

*Your turn: answer Socrates in three or four sentences before opening the continuation. Then ask yourself what he will ask next.*

<details><summary>Continue the dialogue</summary>

**You:** No. Not all philosophers are poor. Some are professors with good salaries.

**Socrates:** So the first premise is false. But suppose it were true. And suppose you were a philosopher. Would you then have to be poor?

**You:** Yes. If both premises were true, the conclusion would have to be.

**Socrates:** Then in one way the argument is in good order and in another way it is not. What shall we call these two ways?

**You:** The logicians would say it is valid but not sound. The connection is fine; a premise is false.

**Socrates:** Now another. "If a man is a philosopher, he loves wisdom. Socrates loves wisdom. Therefore Socrates is a philosopher." Good or bad?

**You:** It sounds good. Both premises are true and so is the conclusion.

**Socrates:** Then let me give you one of the same shape. "If a man is a horse, he has a heart. Socrates has a heart. Therefore Socrates is a horse."

**You:** That is absurd. Oh. It is the same form: if P then Q; Q; therefore P. Affirming the consequent. The first one only *looked* good because the conclusion happened to be true.

**Socrates:** So a true conclusion does not show an argument is good, and a false premise does not show the reasoning is bad. Which is worse in an argument, a false premise or a bad connection?

**You:** I want to say a bad connection, because then the argument is worthless even if everything in it is true.

**Mill:** I should put in a word for the premises. Every connection you call valid is only as useful as the general premise it starts from, and that premise was learned from experience. Most of the errors that ruin people are not invalid inferences but false generalizations, held without evidence.

**You:** Then both matter, but differently. Logic can check the connection by itself, by looking for a counterexample with the same form. Checking the premises needs experience, or further argument.

**Socrates:** And if someone hands you a valid argument whose conclusion you are sure is false?

**You:** Then at least one premise is false, and I owe it to him to say which. I cannot just reject the conclusion and keep all the premises.

**Socrates:** You have learned in ten minutes what took the Athenians a lifetime not to learn.

*What we learned:* validity and soundness are distinct; true premises and conclusion do not make an argument valid; a valid argument with a false conclusion forces you to reject a premise. Mill's point about the source of general premises reappears in his challenge to the syllogism (Book II, Ch. III).

</details>

### Dialogue 2 — On why you expect the sun to rise

**Hume:** Will the sun rise tomorrow?

**You:** …

*Your turn: answer Hume in three or four sentences before opening the continuation. Then ask yourself what he will ask next.*

<details><summary>Continue the dialogue</summary>

**You:** Of course it will. It has risen every day for billions of years.

**Hume:** I do not doubt that you believe it, nor do I. I ask what *reason* you have. You say it has always risen. How does that bear on tomorrow?

**You:** Because nature follows laws. The earth rotates, and nothing will stop it overnight.

**Hume:** And how do you know nature follows laws tomorrow, as it did yesterday?

**You:** Because it always has.

**Hume:** Observe what you have done. You argue that the future will resemble the past because, in the past, the future resembled the past. Is that not to assume the very thing in question?

**You:** It is circular, I admit. But can I not prove it another way, by pure reasoning?

**Hume:** Try. Is there any contradiction in supposing that the sun will not rise tomorrow?

**You:** No contradiction, just an incredible physical catastrophe. I can imagine it.

**Hume:** Then no demonstration can rule it out, since whatever we can clearly conceive is not contradictory. Neither reason nor experience justifies the inference. Custom produces it.

**Russell:** Remember my chicken. It too had excellent inductive evidence that the farmer brings food.

**You:** But the chicken lacked knowledge of farmers. We know physics, and physics explains *why* the sun rises. Isn't an explanation better than a mere regularity?

**Hume:** Your physics is itself a generalization from past observations. You have made the regularity more elaborate, not escaped it.

**You:** Then I will try Strawson's reply. Asking whether induction is "reasonable" is like asking whether the law is legal. Being reasonable about the future just *is* basing belief on past evidence in this way. There is no deeper standard to appeal to.

**Hume:** Ingenious. But it seems to me you have only changed the word. I ask why we should expect the inference to lead to truth, and you tell me it is what we call reasonable. The chicken was reasonable too.

**You:** Then I accept your point and keep my belief. I cannot justify induction without circularity, but I cannot live without it either. "Be a philosopher; but, amidst all your philosophy, be still a man."

**Hume:** You have quoted me against myself, which is the only kind of *argumentum ad hominem* I respect.

*What we learned:* Hume's argument shows that inductive inference cannot be justified by deduction or, non-circularly, by induction; the main replies (Strawson, Reichenbach, Popper, Bayes) each pay a price. See *Enquiry* Section IV and [Chapter 21](21-knowledge-and-science.md).

</details>

### Dialogue 3 — On whether it is fair to win an argument by tricks

**Schopenhauer:** Last night at dinner your brother-in-law insisted that philosophy is useless. You knew you were right. Did you win?

**You:** …

*Your turn: answer Schopenhauer in three or four sentences before opening the continuation. Then ask yourself what he will ask next.*

<details><summary>Continue the dialogue</summary>

**You:** Not really. He kept changing the subject and in the end he said I was "just an academic," and everyone laughed.

**Schopenhauer:** Stratagem thirty-eight: the last trick, *ad personam*. He saw he was losing. You should take it as a compliment. Did you use any tricks yourself?

**You:** I said that he obviously thought nothing was worth knowing unless it made money.

**Schopenhauer:** Stratagem one, the Extension. He said philosophy is useless; you widened it to "nothing is worth knowing unless profitable," which is easier to refute. Well done. Did it work?

**You:** It got a laugh. But I am not proud of it. He did not say that.

**Schopenhauer:** Pride has nothing to do with it. Men argue to win, not to find the truth. Vanity is stronger than the love of truth in almost everyone. That is why I wrote my little book: to arm the honest against the dishonest.

**Socrates:** May I ask the gentleman from Danzig a question? When you win by a trick, what have you won?

**Schopenhauer:** The appearance of being right, before the bystanders.

**Socrates:** And is the appearance of being right the same as being right?

**Schopenhauer:** Obviously not. I said as much: one can be objectively right and come off worst.

**Socrates:** Then if our young friend wants to know whether philosophy is useless, will tricks help him find out?

**You:** No. They help me look clever, but if my brother-in-law had a good point I would never hear it.

**Socrates:** Did he have a good point?

**You:** Maybe. He said that most philosophy is never applied to anything. That might be true. I could have asked him whether it matters, whether anything worth doing must be applied.

**Schopenhauer:** You are assuming he would have answered honestly. Scarcely one man in a hundred is worth disputing with.

**You:** Then your own "safe rule" says I should either argue with him honestly, as someone who might be right, or not argue at all. It does not say I should use your tricks on him.

**Schopenhauer:** Correct. The tricks are to be recognized, not used. I confess I enjoyed writing them more than I should.

**You:** So my position is: know the stratagems in order to defuse them ("That has no bearing on the point in dispute"), steelman the other side, and if the other person will not reason, stop arguing. Winning by tricks is losing the only thing an argument is for.

*What we learned:* Schopenhauer separates being right from appearing right; his catalogue is diagnostic. Socrates' question, what have you won?, connects argumentative ethics to the aim of inquiry. Compare the *Gorgias* on rhetoric versus dialectic in [Chapter 4](04-socrates-and-the-sophists.md).

</details>

Sources for this chapter: [REFERENCES.md](REFERENCES.md#chapter-2--logic-and-argument)
