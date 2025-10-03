---
description: Write a newsletter article for Vibe Coding Academy using 3 newsletter agents that will help with the 3 main sections of the newsletter content
argument-hint: [links to the linkedin posts] [what happened at vibe coding academy during the last 2 weeks] [newsletter topic]
---

/agents use newsletter-vibe-coding-academy-news-curator to write-up the section "Vibe Coding Academy’s news"

/agents use newsletter-linkedin-curator to write-up the section "Bi-weekly Digest"

/agents use newsletter-content-writer to write-up the remain section (the name of the section will depend on the topic of the article)

Write a newsletter article for Vibe Coding Academy based on the following 3 arguments:
- the links towards the three Linkedin post to write-up the section "Bi-weekly Digest": $1 (requires the use of the following /agents use newsletter-linkedin-curator to write-up the section "Bi-weekly Digest")
- the section called "Vibe Coding Academy’s news": $2 (requires the use of the following /agents use newsletter-vibe-coding-academy-news-curator to write-up the section "Vibe Coding Academy’s news")
- another section about the main topic of the newsletter article whose title you will have to find: $3 (requires the use of the following /agents use newsletter-content-writer to write-up this section)

You should add the newsletter article to the following folder `../Obsidian/newsletters`