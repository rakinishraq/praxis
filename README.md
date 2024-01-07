# Praxis

**TL;DR:** A repo of ideas and information

**Concept:** Idea and information repository as an Obsidian vault (specifically compatible with GH-flavor markdown) and connections to many automation tools and interfaces (like a Discord server and Google Keep) for utmost ease-of-use, multi-platform compatibility and minimal friction to the second (leveraging existing muscle memories). However, each proprietary and externally-hosted component will be sequentially substituted with self-hosted FOSS solutions.

**Information:** I have tried to adopt Zettelkasten into an Obsidian vault and there were many shortcomings:
- no tag list causes time waste, need for backtracking, redundant tags
- unnecessary title/reference notes/paraphrasing causes friction
- bloated for purpose causes distraction
Some potential solutions:
- KOReader script: Book highlights -> quoted text, "Author - Title (Chapter)" as ref (successful prototype made)
- Godot mobile/desktop app:
	- add tags from 8 most common from same source (video artist/book/author/site in descending order of precedence) with ASDF/HJKL keys in Tags mode, also show full list of tags under those if more than 8
	- list/graph view w/ cards, card editor
- Firefox add-on/userscripts:
	- (+) button -> text input for unquoted text, use site as ref
	- Text highlight, add as quoted text, use site as ref
	- Image -> optional text input, use site as ref
	- YT/video -> open in mpv w/ bookmark script (controller support) ->
		- deviate (zettel mode) -> optional text, export mp3/mp4, use site as ref
	- Other site ref -> tab title as text, remove "- Reddit"..., site as link
- Focus css snippet/userstyles
And some upsides:
- Seemingly bug-free local kanban UI
- Replaces the need for dedicated for markdown or docx (and similar "standard" formats)
- Many website/blog-style output solutions