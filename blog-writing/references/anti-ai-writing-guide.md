# Anti-AI Writing Guide

## Contents

1. Core Model
2. Sentence Structure and Formatting Tells
3. Vocabulary and Consensus-Middle Drift
4. Phrasing and Tone Tells
5. Voice and Posture
6. Prompting Workflow
7. Headings
8. Concessions, Pronouns, and Specificity
9. Ruthless Human-Edit Checklist
10. Execution Order

## Core Model

Large language models work as prediction tools. They generate text token by token based on statistical safety, which pulls prose toward the consensus middle: safe, boring, predictable language that avoids risk and therefore avoids character.

To sound human, prompt around those defaults, add controlled wonkiness, and edit hard for structural, vocabulary, and tonal tells. The goal is not random weirdness. The goal is specificity, rhythm, texture, and a point of view that feels lived rather than averaged.

Do not moralize individuals. Target structures, incentives, and outcomes. Ask whether the guardrails are strong enough to survive your own objections.

## Sentence Structure and Formatting Tells

### Negation Structure

The contrastive reframe is one of the clearest AI tells:

- `It's not just X, it's Y`
- `X isn't just evolving, it's accelerating`
- `AI doesn't eliminate labor; it redistributes it`

Readers feel the pattern quickly. It reads as synthetic sophistication.

Prefer specific affirmative statements:

- AI-like: `AI doesn't eliminate labor; it redistributes it.`
- Better: `AI will become your research assistant and free up time for strategic messaging.`

Use this prevention prompt when drafting:

- `Avoid sentence structures that set up and then negate or expand beyond expectations, such as "X isn't just about Y." Use direct affirmative statements instead.`

Keep at most one deliberate negation structure in a piece if it genuinely lands harder. Audit stealth forms too: `cannot`, `doesn't`, `isn't`, `won't`, `wouldn't`.

### Sentence Stacking and Uniform Rhythm

AI prose often reads like a list without bullets. Every sentence stands alone. Or the opposite happens: the draft settles into a uniform 20 to 27-word march that creates a dull drone.

AI-like:

`Improv is a type of unscripted theater. It requires performers to make up scenes in the moment. Many exercises focus on listening and reacting.`

Better:

`Improv is a form of unscripted theater where performers build scenes in real time. It sharpens listening, encourages quick thinking, and builds the kind of trust that teams can feel on and off stage.`

Use natural bridges such as `so`, `because`, `which means`, `for example`, or `as a result`. Avoid empty transitions that merely announce importance.

Vary length deliberately:

- long sentence
- short sentence
- medium sentence
- occasional fragment for emphasis

Fragments are emphasis tools, not the baseline rhythm. One complete sentence is usually better than three chopped beats pretending to be urgency.

Severe sentence stacking often appears when a draft is built from too much source material plus a tight word-count constraint, especially with large RAG inputs. Narrow the scope before drafting.

Use this fix prompt:

- `Make sure the writing uses natural transitions and reads smoothly. Avoid stacking short, factual sentences. Connect ideas in a way that guides the reader.`

Use this rework prompt for bullet conversion:

- `Turn these bullets into a cohesive paragraph with voice and varied rhythm. Use transitions to guide the reader.`

Memorize the shorthand:

`Prompt for flow -> Prioritize -> Use transitions -> Vary rhythm -> Add voice`

### Colons and Em Dashes

AI leans on colons because they connect ideas cheaply. It also overuses em dashes. Audit both.

Watch for:

- colons in three consecutive paragraphs
- a colon in a paragraph followed by another colon in a bulleted lead-in
- a colon in every header
- em dashes where a comma, period, or parenthetical would sound more human

Do not hard-prompt `use fewer colons`, which narrows the model too much. Generate first, then rewrite the offending section without the colon. Replace em dashes manually or restructure the sentence.

Do not use em dashes if they can be avoided.

The bonus-point tell is negation plus em dash:

- `Not performative updates - but real transparency.`

Also watch for the same negation pattern stretched across two consecutive sentences.

### Bullet Points and Bold Titles

AI jumps to lists too quickly, even when the material wants prose.

Common tell:

- `**Scalability:** The system is designed to scale easily across different use cases.`

The sentence adds no new value beyond the bold term. If you use bullets, make them intentional and make the follow-on sentence earn its keep.

## Vocabulary and Consensus-Middle Drift

### The Consensus Middle and Crazy-Town Detour

Do not ask the model for second- or third-choice wording. That pushes it from bland corporate average into clunky faux-original language.

- Consensus-middle version: `The company transformed its operations to stay competitive in a changing market.`
- Bad rewrite: `The company morphed its internal systems to remain nimble in an evolving landscape.`

Use specific, concrete language instead of thesaurus substitutions. If the first-choice word feels boring, the sentence probably needs more specificity, not a fancier synonym.

High-entropy language should be surgical. One idiomatic phrase per paragraph is enough.

### Red-Flag Vocabulary

Search for these and cut aggressively when they cluster:

- hype words: `unlock`, `transform`, `revolutionize`, `future-proof`, `game-changer`, `supercharge`, `harness`, `leverage`, `unleash`, `unprecedented`, `cutting-edge`, `next-generation`, `seamless`, `dynamic`
- business framing: `robust`, `empower`, `strategic`, `elevate`, `align`, `proactive`, `nuanced`, `intersection`
- fake transitions: `moreover`, `furthermore`, `however`, `the goal`, `the result`, `the bottom line`, `fundamentally`, `thrilled`, `delve`, `foster`
- superficial analysis endings: `ensuring`, `highlighting`, `emphasizing`, `reflecting`
- other common AI gloss: `vibrant`, `resilient`, `genuinely`, `honestly`, `straightforward`

### Hedging and Weasel Wording

AI hedges because it is risk-averse. Cut weak qualifiers:

- `typically`
- `might be`
- `more often than not`
- `don't always`
- `some degree of`
- `certain`

Cut vague attribution:

- `Industry reports`
- `Observers have cited`
- `Some critics argue`

Name the source or take the position directly.

### Exact Phrase Blacklist

These highly structured phrases show up constantly in AI drafts:

- `Delving into the intricacies of...`
- `Navigating the complexities of...`
- `Based on the information provided...`
- `It goes without saying...`
- `If you have ever wondered...`

## Phrasing and Tone Tells

### Vague-Change Intros

Because a model writes sequentially, it often begins with vague framing before it knows where the piece is going:

- `As [broad trend] continues to [vague verb], [industry] must [generic goal].`
- `In today's fast-paced business landscape...`
- `As the digital landscape continues to evolve...`
- `Now more than ever...`

Write the introduction last. Open with a real example, stat, contradiction, or sharp observation that reflects the core message.

Use this intro prompt:

- `Rewrite the intro now that the piece is complete. Open with a real example, stat, or sharp observation that reflects the core message, and cut any generic framing.`

### Wikipedia and Tourism Tone

AI often treats factual subjects with inflated reverence or brochure language:

- `rich cultural heritage`
- `breathtaking`
- `must-visit`
- `stunning natural beauty`
- `stands as a testament`
- `underscores its importance`
- `watershed moment`
- `solidifies`
- `It's important to note`
- `No discussion would be complete without`

Cut editorializing and reverential inflation.

### Faux Conversation and Blogging Cliches

Cut:

- `Let's face it`
- `Let's dive in`
- `Here's the uncomfortable truth`
- `Everyone wants to`
- `Without further ado`

### Inconsistency Between Posts

Human writers have mannerisms. They lean toward empathy, irritation, humor, precision, or outrage in repeatable ways. AI lacks that continuity. It changes voice from one post to the next and often speaks at the reader rather than to them.

If the audience knows the writer, they will notice this drift immediately. Preserve recurring mannerisms across drafts.

### Land of the Obvious

Most AI writing stays fluffy and obvious because it is trained on predictable language and avoids concrete claims that could be wrong. It produces a vanilla, hollowed-out vibe.

To sound human, go into the deep waters:

- personify objects
- use similes
- be funny when the material allows it
- use names, numbers, and lived details
- describe sights, smells, and sounds

Use wonkiness sparingly. The point is texture, not performance.

## Voice and Posture

Keep the posture calm, systems-brained, slightly incredulous, and low-drama. The subtext is `this is obviously strange once you see it`, not `they're out to get you`.

The argument should carry a `why are we accepting this?` energy without tipping into conspiracy or ranting. Diagnose rather than perform outrage. Moral language should be sparse but sharp.

It is fine to sound like you are speaking. Spoken rhythm, conversational phrasing, and the occasional informal turn are all good if they make the prose easier to follow. What to avoid is preachiness, self-importance, grandstanding, and any tone that sounds like a lecture or keynote.

Take a position. This is a blog post, not a textbook or neutral explainer. Let the position feel inevitable by the time you state it.

Mechanism-first persuasion matters. Do not start with `this is wrong`. Start with `here is what is happening`, then let the wrongness become self-evident.

Stay implementation-agnostic when the point is institutional design, incentive design, or system plumbing. Explain first.

Do not dunk on individuals. Do not lead with ideology labels. Keep the public-interest frame without utopian vibes. Try to keep readers on both left and right onboard.

Explain things the way you would to a smart friend over coffee. If it sounds like a keynote, a sermon, or a performance of seriousness, pull it back. If it sounds like a textbook, warm it up.

## Prompting Workflow

Do not rely on rigid prohibitions such as `never use colons`. That often flattens the draft. Use soft constraints, references, and post-generation rewrites instead.

### Step 1: Pre-Generation Prompts

- `From this source, choose 3 to 5 topics that would matter most to [audience]. Go deeper on those, and don't try to cover everything.`
- `Avoid overused phrases like "in today's world" or "the bottom line." Use specific, natural language and varied sentence rhythm. Surprise me with at least one turn of phrase.`
- `List 20 words or phrases ChatGPT is most likely to use when writing about [TOPIC].`
- `Write the draft, but be mindful of common buzzwords like [Insert List], and vary language so they are not overused.`

### Step 2: Reference-Based Prompting

Feed the model 2 or 3 examples of human writing:

- `Use the attached examples as a reference. Match the tone, structure, and level of specificity.`

### Step 3: Post-Generation Prompts

- `Highlight any phrases that sound formulaic, overused, or like AI-generated filler. Focus on intros, transitions, and overly polished marketing language.`
- `Rewrite this in a confident, human voice. Be specific. Be interesting. Cut phrases that feel generic. Let the rhythm feel a little more conversational.`

### Expert-Persona Trap

Avoid prompts like:

- `You're an expert with 20 years of experience. Write a short, actionable summary of how improv helps with communication in under 120 words.`

Why they fail:

- `expert with 20 years` pushes the tone toward formal authority
- `actionable` encourages dry, stepwise copy
- `under 120 words` compresses the draft into robotic sentence stacking

## Headings

Headings do polemical work. They can be a little sharper and more provocative than the body, but they still need to be cashed out within the next 2 or 3 paragraphs.

No blame targets in titles. Point at systems, not people.

Better:

- `The Haka Without the Maori`
- `Every City Becoming the Same City`
- `The Land as a Private Wealth Machine`

Worse:

- `The Substitution Problem`
- `The Direction of Travel`
- `What We're Actually Losing`

The body should earn the headline by walking through the plumbing.

## Signposting, Polish, and Voice Preservation

When an LLM drafts a blog post from source notes, two failure modes dominate. The first is signposting — the model leaves breadcrumbs to itself about what to say next, and those breadcrumbs survive into the final draft as bridge sentences and meta-announcements. The second is polish — the model upgrades the raw notes into something more measured, balanced, and aphoristic than the author would have written. Polish is a tell. It smooths out heat, rough edges, repeated phrases, and comma-piled thoughts, and replaces them with sentences that read like anyone wrote them.

Fight both by auditing for specific patterns and by preserving verbatim phrases from the source notes.

### The Signposting Trap

Because LLMs generate sequentially, they leave themselves directions. These show up in the final draft as sentences whose only job is to announce what the next section is about to do:

- `The interesting question is what happens when...`
- `There are two obvious responses and both of them fail, but they fail in different ways that are worth separating.`
- `The answer is becoming visible.`
- `So the idiom comes back, and it means something heavier than it did at the start.`
- `This is true across most skilled work.`

Every one of these is the model talking to itself. Cut them. If the structure is sound, the reader feels the turn without being told it is happening. If the structure is not sound, no signpost will save it.

Audit for:

- Bridge sentences that announce the next section's topic before the section header does
- Sentences that summarize what just happened
- `The question is`, `The answer is`, `The result is` openings
- `Two things`, `Both of them`, `Which means that`, and similar meta-narration
- Any sentence that could be cut without the argument losing a beat

### The Aphoristic Polish Trap

LLMs love to close paragraphs on short, balanced, aphoristic sentences. They feel satisfying to generate because they read as conclusive:

- `Profit was the alibi.`
- `The craft was the life.`
- `True in aggregate and brutal in particular.`

Each of these is a tidy closer. None of them sound like how a person actually talks. They sound like something written for the closer position.

Most paragraphs should end on a plain sentence. Reserve the aphoristic snap for once or twice in the piece, where it earns the weight. If a draft has aphoristic closers in three consecutive paragraphs, two of them should be flattened back into normal prose.

AI-like:

> They did not notice because the expression was profitable, so nobody had to examine it. Profit was the alibi.

Better (loosened):

> They just didn't notice, because the expression was profitable, and profit covered for it.

Same meaning, less performance.

### The Tidiness Audit

Run after the main editing pass:

1. Look for paired constructions like `X in aggregate, Y in particular` or `It is humane. It will not survive.` These are parallel for parallel's sake. Break one of them into a longer sentence or rephrase.
2. Count consecutive short paragraphs. If three in a row are one or two sentences each, one of them is probably performing tightness rather than earning it.
3. Look at section closers. If every section ends on a punchy fragment or aphorism, the piece reads as a string of TED-talk beats rather than a continuous argument.
4. Scan for matched sentence lengths. Two sentences of roughly the same length and rhythm sitting next to each other should usually get broken up.

The goal is not to avoid tight prose. Tight prose is good when it carries weight. The goal is to make sure the tightness is load-bearing rather than decorative.

### Voice Preservation From Source Notes

Before drafting, read the raw notes and pull out the specific markers that make the author's voice recognizable. Typical candidates:

- Comma-piled clauses where a cleaner writer would use periods
- Visceral verbs or phrases with heat (`spilled from the AI giants`, not `generated by AI providers`)
- Questions the author asks and then answers
- Recurring phrases or idioms, especially ones used more than once
- Hedges like `idk`, `maybe`, `really`, `just`
- Sentence openings with `Like`, `And`, `But`
- First-person confessionals (`almost no one I know`)
- Contractions used in specific spots (authors use contractions where the rhythm wants them, not everywhere)

Keep at least two or three of these phrases intact in the draft, verbatim. If the notes say `spilled from the AI giants`, the draft says `spilled from the AI giants`. Do not translate it into neutral equivalents. The verbatim phrase is a load-bearing voice marker, and the moment it gets replaced, the piece starts sounding like an LLM wrote it.

### Drafting Prompt

When drafting from notes:

> Draft this as a blog post using the source notes. Preserve the author's voice markers: comma-piled clauses, visceral phrases from the notes (quote them verbatim where possible), hedges, and conversational rhythm. Avoid aphoristic closers on more than one or two paragraphs. Do not add signposting sentences that announce what the next section will do. Let structure carry the argument instead of narrating it.

### Editing Pass Additions

Add to the ruthless edit pass:

- Signposting hunt: search for `the interesting question`, `the answer is`, `the result is`, `two things`, `both of them`, `which means that`, and similar meta-announcements.
- Aphoristic closer audit: for each paragraph ending, ask whether the final sentence is doing work or performing closure. If it is performing, flatten it.
- Verbatim preservation check: compare the draft against the source notes and confirm that at least two or three of the author's specific phrases survived intact.
- Tidy pair break: find sentence pairs with matching length and rhythm and break at least one pair per piece.


## Concessions, Pronouns, and Specificity

### Concessions and Objections

Concede what is real. Prebut objections like a serious person. Take the best counterargument and answer it with constraints, precedent, and tradeoffs.

One real concession is better than four disclaimer sentences.

### Pronouns and Heat Management

Use `you` to make abstraction tactile:

- `when you buy a share...`
- `your rent goes up`
- `moving costs explode`

Make `you` the person affected, never the villain. Use `they` or `someone` for neutral beneficiaries in system descriptions.

Switch voices naturally across first, second, and third person when the piece benefits from it.

### Specificity

Specificity is the biggest differentiator between AI writing and human writing. If the prose stays abstract for more than two paragraphs, add a named person, place, event, example, number, or before-and-after.

One named example often does more than three paragraphs of general argument.

## Ruthless Human-Edit Checklist

Run this before publishing:

1. The `just` test. Search for `just` and catch stealth `not just X, it's Y` phrasing.
2. The first-sentence test. If the opening mentions `landscape`, `evolving`, or `today's environment`, delete it and replace it with a hard example or story.
3. The colon and em-dash audit. Remove repeated colons. Replace em dashes where a comma works.
4. The consistency test. If the piece stays rigidly in third person, add lived voice through first or second person where appropriate.
5. The vocabulary sweep. Search for `delve`, `unlock`, `robust`, `leverage`, `seamless`, `tapestry`, `testament`.
6. The flow test. Read aloud. If the sentences all sound the same length, break them up. Add one short sentence. Add a useful bridge such as `for example` or `as a result`.
7. The hedging hunt. Cut `some critics argue`, `typically`, and other weak qualifiers unless they are truly necessary.
8. The reader-care check. Make sure the prose flows easily and does not induce cognitive overload.
9. The fragment audit. If more than a quarter of paragraphs end on a punchy fragment, convert some back to full sentences.
10. The throat-clearing hunt. Cut lines whose only job is to say the next sentence matters.
11. The performed-sincerity hunt. Cut lines that announce honesty or thoughtfulness.
12. The capping-phrase audit. If the last line of a section is decorative rather than substantive, cut it.

## Execution Order

1. Write the body first.
2. Add concrete examples and specificity.
3. Write the intro last around the strongest material.
4. Run the editing checklist.
5. Read the whole piece aloud and pull back anything that sounds like a speech.
