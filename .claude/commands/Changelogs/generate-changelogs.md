---
description: Generate a changelog entry from a feature description using the changelog-writer agent
args:
  - name: feature_description
    description: Description of the feature, update, or improvement to document
    required: true
---

/agents use changelog-writer

I need you to create a changelog entry for the following feature:

{{feature_description}}

Please use the changelog-writer agent to transform this raw description into a polished, compelling changelog entry that matches the style and format of existing changelogs in the Obsidian/changelogs/ directory.
