# PRAO of Roza

- When: Wednesday November 26th 2025 9:00-16:00 (see [schedule](schedule.md))
- What to bring: a laptop, (optional) food (there are microwaves)
- Where in Uppsala: Biomedical Center, Husargatan:
  see [location](location.md) how to get there
- Where in BMC: [office B9:430b](https://use.mazemap.com/#v=1&zlevel=4&center=17.635980,59.841862&zoom=19.9&campusid=49&desttype=poi&dest=386656):
  see [office](office.md) how to get there
- [Schedule](schedule.md): see [schedule](schedule.md)
- [Report](report.md): see [report](report.md)
- [Reflection](reflection.md): see [reflection](reflection.md)
- [Reflection from supervisor](reflection_from_supervisor.md): see [Reflection from supervisor](reflection_from_supervisor.md)
- [Link to PRAO schedule](https://docs.google.com/spreadsheets/d/1BkG-ni6lGVyfSBe_FIRclETSmP8F_uuYG6bkS8pue_4/edit?gid=0#gid=0)

## Files used by continuous integration scripts

Filename                                  |Descriptions
------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------
[mlc_config.json](mlc_config.json)        |Configuration of the link checker, use `markdown-link-check --config mlc_config.json --quiet docs/**/*.md` to do link checking locally
[.spellcheck.yml](.spellcheck.yml)        |Configuration of the spell checker, use `pyspelling -c .spellcheck.yml` to do spellcheck locally
[.wordlist.txt](.wordlist.txt)            |Whitelisted words for the spell checker, use `pyspelling -c .spellcheck.yml` to do spellcheck locally
[.markdownlint.jsonc](.markdownlint.jsonc)|Configuration of the markdown linter, use `markdownlint "**/*.md"` to do markdown linting locally. The name of this file is a default name.
[.markdownlintignore](.markdownlintignore)|Files ignored by the markdown linter, use `markdownlint "**/*.md"` to do markdown linting locally. The name of this file is a default name.
