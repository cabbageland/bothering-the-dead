# Bothering the Dead, Daily Essay Instructions

This repo publishes one new essay every day for the *bothering-the-dead* project.

## Schedule

- Run every day at 12:00 AM America/Los_Angeles.

## Daily task

For the current date, write a new essay in this repo.

### Subject selection policy

The pool of dead subjects should stay broad, strange, and interesting. Do not over-index on politicians.

Current standing thematic preference:

- Celebrate physics.
- Talk to dead physicists by default until Tracy changes the theme.
- Prefer physicists over other subject classes when choosing the day's subject, unless a different dead figure has a clearly stronger fit for the day's exact question.
- Within the physics lane, favor breadth rather than the same canonical men forever: vary era, geography, subfield, fame level, and moral register.
- Good lanes include theoretical physics, experimental physics, astrophysics, geophysics, climate and atmospheric physics, statistical mechanics, thermodynamics, electromagnetism, quantum theory, relativity, condensed matter, nuclear physics, instrumentation, and overlooked physics-adjacent lives where the essay still genuinely talks to physics.

Preferred subject classes:

- philosophers
- artists
- scientists
- writers
- scholars
- doctors
- musicians
- religious figures
- activists
- ordinary or obscure dead people with poignant, peculiar, or revealing stories
- children or accidental deaths, when handled with real tenderness and seriousness rather than shock-value
- dead animals
- dead plants
- abandoned toys or other lost objects treated as quasi-dead cultural beings, when the essay premise supports it

Deprioritized subject classes:

- politicians, heads of state, party operators, ministers, senators, presidents, kings, and similar state-power figures

Selection rules:

- Under the current physics-celebration mode, a dead physicist should be the default subject.
- If you choose someone other than a physicist while this mode is active, the essay should make the reason obvious.
- Politicians should be rare, not the default.
- In any rolling 14-day span, a clear majority of essays should be about non-politicians.
- If a politician is chosen, there should be a strong reason they uniquely fit the day’s intellectual question, and that reason should be visible in the essay.
- When choosing between an easy famous politician and a more unusual philosopher, artist, scientist, animal, child, plant, toy, or obscure dead person, prefer the latter.
- Favor variety of type, era, geography, and emotional register.
- The overall vibe should be less parliament and more haunted museum drawer.

Opening template:

- `today is ______.`

Prompt:

- Describe how you found a grave, a tomb, or a dead body of any sort or kind.
- Creatively, effortlessly, and determinedly wake the dead body up and bring it back to life for only one purpose: to talk to them.
- The dead figure can be a famous person, scientist, artist, scholar, philosopher, doctor, musician, a random person, an animal, a plant, an abandoned toy, or anything else.
- Imagine a conversation or debate with the revived dead figure on a controversial topic.
- Challenge each other and make the exchange intellectually stimulating.
- Entertain Tracy with the self-play energy of the argument.
- Document both the resurrection story and the conversation as a beautifully orchestrated, philosophical, logical essay.

## Style

- This is a serious, fully committed conversation, not a winky gimmick.
- Be concrete about the topic, the stakes, and the actual arguments.
- Make it readable as an essay, not a transcript dump.
- It is fine for the voice to be sharp, funny, unsettling, lyrical, or argumentative, as long as it stays coherent.
- The conversation should contain real tension, not fake agreement.
- Both you and the dead figure should reason seriously and specifically.

## Citations

- Properly cite the sources used for reasoning, philosophical questioning, arguments, and factual claims.
- Keep this citation standard for both sides of the conversation.
- Cite inline, not only at the end.
- Embed the actual source links directly in the inline citations.
- Prefer primary sources when possible, and otherwise use strong secondary sources.
- Do not fake citations. If a claim is imaginative rather than sourced, make that clear in the prose.

## File naming

- Use the local date in Los Angeles time.
- Name files like: `MM-DD bothering NAME.md`
- Example: `04-24 bothering Mary Shelley.md`

## Git workflow

1. Pull latest changes from `main`.
2. Add the new daily essay file.
3. Commit with a clear message.
4. Push to `origin main` the same day.

## Important

- Do not overwrite previous essays.
- Write exactly one new essay per scheduled run unless explicitly asked otherwise.
- If the best title subject becomes clear only after writing, choose the filename accordingly.
- For local file inspection and cleanup checks, use ordinary shell/file tools such as `ls`, `find`, `sed -n`, `grep`, `git`, and small bounded reads.
- Do not use abstract helper actions like `search ...` or `print lines ...` against local files in cron runs; they are flaky and count as avoidable failures.
- If you want to check for non-ASCII characters or similar file-level issues, use a normal shell command such as `LC_ALL=C grep -n "[^ -~]" "MM-DD bothering NAME.md"` instead of an abstract search helper.
