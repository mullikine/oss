# oss

This repo is for staging generated contributor guides of OSS projects. The folder structure is:

<owner>/
	<project>/
		README.md
		template.md
		generated.md
		codelingo.yaml

The README.md should have a link to the original contributor docs. generated.md is generated from this command: `lingo run docs --template template.md --output generated.md`. The contents of generated should match that of the original as closely as possible.

The directory template/ can be copied when setting up a new project.