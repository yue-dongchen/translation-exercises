# Translation Exercises
<!-- TODO: section on rationale — e.g. explanation for others on what this is, remarks on the output hypothesis, etc. -->
**Notes on organisation:**
* Top-level organisation in this repo is by language pairs: e.g. the *en-fr* directory means “translations from English into French”.
## Workflow
1. Assemble the material to be translated into a file with the name *[article name (& possible info such as publication/source].[language code].md*.
2. Create an empty file called *[article name].[target language].md*
3. Translate (either the whole thing with the below process being performed once overall, or subpassages with the below process being repeated)
	1. Translate the passage, minimally consulting external resources. If I cannot produce a translation close in meaning in the target language, try nonetheless to express similar meaning — e.g. with more rudimentary expressions that could suffice to convey the basic meaning.<p>
	If I still can't come close, leave the knowledge-deficient bits in the original language, formatted in <span style="color:#EB1800;">#EB1800</span> [(contrasts sufficiently with both white and black backgrounds.)](https://web.archive.org/web/20160214165231/trace.wisc.edu/contrast-ratio-examples/PassingMidColorSamples_4-5to1.htm). The HTML is `<span style="color:#EB1800;">whatever text</span>`.<p>
	Make a Git commit — e.g. *[unaided pass]* in commit message.
	2. **Vocabulary amendment stage:** Revise the translation by consulting dictionaries (including possibly newer hybrid lexicon-translator resources such as Reverso Context or Linguee). Then, there should still be remaining bits where I lack adequate grammatical knowledge to confidently translate. They should be marked also in <span style="color:#EB1800;">#EB1800</span>.<p>
	Make a Git commit — e.g. *[amend vocabulary]* in commit message.
	3. **Grammar amendment stage:** Revise the inadequate grammatical aspects by consulting external resources. Machine translations may help; but do not copy machine-produced target-language output without thoroughly understanding the semantic implications. Keep this in mind especially when machine-translating longer expressions.<p>
	Make a Git commit — e.g. *[amend grammar]* in commit message.
	4. Make some final mixed amendments. At this stage I don't think it's feasible to clearly separate vocabulary and grammar amendments into different commits.
	5. Give the piece for feedback — e.g. through LangCorrect.
	
---
This README shall have the [Creative Commons Attribution-ShareAlike 4.0 International copyright licence](https://creativecommons.org/licenses/by-sa/4.0/) applied.