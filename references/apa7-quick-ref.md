# APA 7 Quick Reference Guide

Quick reference for common citation formats in APA 7th edition.

## Journal Articles

### Standard Journal Article
```
Author, A. A., & Author, B. B. (Year). Title of article. Journal Name, Volume(Issue), pages. https://doi.org/xxxxx
```

**Example:**
```
🟢 Smith, J. D., & Jones, M. L. (2023). Cognitive load theory in digital learning environments. Educational Psychology Review, 35(2), 123-145. https://doi.org/10.1037/edu0000123
```

### Article with 3+ Authors
Use all authors (APA 7 removed "et al." in reference lists):
```
🟢 Martinez, R., Chen, L., Williams, S., & Brown, K. (2024). Meta-analysis of working memory interventions. Psychological Bulletin, 149(1), 45-78. https://doi.org/10.1037/bul0000456
```

### Article with 21+ Authors
List first 19, ellipsis, then final author:
```
🟢 Thompson, A., Smith, B., ... & Zhang, Y. (2023). Large-scale study title. Journal Name, 40(3), 200-225. https://doi.org/xxxxx
```

### No DOI Available
```
🟢 Anderson, P. (2022). Title without DOI. Journal of Research, 28(4), 567-589.
```

### Online-Only Journal
```
🟢 Roberts, K. (2024). Digital-only publication. Cyberpsychology, 18, Article 5. https://doi.org/10.5817/CP2024-1-5
```

## Books

### Standard Book
```
Author, A. A. (Year). Book title (Edition ed.). Publisher. https://doi.org/xxxxx
```

**Example:**
```
🟢 Kahneman, D. (2011). Thinking, fast and slow. Farrar, Straus and Giroux.
```

### Edited Book
```
🟢 Anderson, R., & Smith, T. (Eds.). (2023). Handbook of cognitive psychology (3rd ed.). Wiley. https://doi.org/10.1002/9781118133880
```

### Chapter in Edited Book
```
🟢 Lee, S. (2022). Attention and perception. In J. Brown & K. White (Eds.), Cognitive processes (pp. 45-67). Cambridge University Press.
```

### E-Book
```
🟢 Miller, G. (2023). Memory systems. Oxford University Press. https://doi.org/10.1093/xxxxx
```

## Conference Papers

### Published Conference Proceedings
```
Author, A. A. (Year). Paper title. In Editor (Ed.), Conference name (pp. xx-xx). Publisher.
```

**Example:**
```
🟡 Chen, L. (2024). Neural networks in education. In M. Brown (Ed.), Proceedings of the International Conference on AI in Education (pp. 150-165). IEEE.
```

### Conference Presentation (Not Published)
```
🟡 Garcia, M. (2023, June 15-17). Presentation title [Conference presentation]. Conference Name, City, Country.
```

## Preprints & Working Papers

### Preprint
```
Author, A. A. (Year). Preprint title. Preprint Server. https://doi.org/xxxxx
```

**Examples:**
```
🔴 Johnson, R., & Lee, S. (2024). Emerging theory in development. PsyArXiv. https://doi.org/10.31234/osf.io/abc123

🔴 Martinez, A. (2024). Machine learning approaches. arXiv. https://arxiv.org/abs/2401.12345
```

## Online Sources

### Webpage
```
Author/Organization. (Year, Month Day). Title. Website Name. URL
```

**Example:**
```
🟡 American Psychological Association. (2023, November 15). Understanding anxiety disorders. https://www.apa.org/topics/anxiety
```

### Webpage with No Date
```
🟡 National Institute of Mental Health. (n.d.). Depression basics. https://www.nimh.nih.gov/health/topics/depression
```

### Online Report
```
🟢 World Health Organization. (2023). Mental health report 2023. https://www.who.int/publications/i/item/9789240049338
```

## Datasets & Software

### Dataset
```
🟡 Author, A. A. (Year). Dataset title (Version X.X) [Data set]. Repository. https://doi.org/xxxxx
```

### Software
```
🟡 Developer, A. (Year). Software name (Version X.X) [Computer software]. Company/Repository. URL
```

## Special Cases

### Government Report
```
🟢 U.S. Department of Education. (2023). Education statistics 2023 (NCES 2023-144). National Center for Education Statistics. https://nces.ed.gov/pubsearch/pubsinfo.asp?pubid=2023144
```

### Dissertation/Thesis
```
🟡 Brown, K. M. (2022). Dissertation title [Doctoral dissertation, University Name]. Repository. https://repository.url/item/123456
```

### Newspaper Article
```
🟡 Smith, J. (2024, January 15). Article headline. The New York Times. https://www.nytimes.com/article-url
```

### Magazine Article
```
🟡 Jones, A. (2023, December). Feature article title. Scientific American, 329(6), 40-45.
```

## Quality Indicators

Add these at the start of each citation:

- 🟢 **High-impact**: Peer-reviewed, high citation count, reputable journal/publisher
- 🟡 **Moderate**: Conference papers, newer publications, specialized sources
- 🔴 **Limited**: Preprints, non-peer-reviewed, low citations, grey literature

## Common Formatting Rules

### Author Names
- Last name, First initial., Middle initial.
- Use "&" before final author
- If 21+ authors: First 19, ..., final author

### Titles
- Sentence case for articles, chapters, webpages
- Title Case for journals, books, conferences
- Italicize journal names and book titles

### DOIs and URLs
- Prefer DOI over URL when available
- Format: https://doi.org/xxxxx (no "DOI:" prefix)
- No period after DOI/URL
- No retrieval date unless source changes (e.g., Wikipedia)

### Dates
- Year for books and most sources
- Year, Month Day for newspapers, blogs, specific dated content
- (n.d.) for no date

### Volume and Issue
- Volume in italics: *35*
- Issue in parentheses: (2)
- No space between: *35*(2)

## Non-English Sources

### Provide Translation
```
🟢 Schmidt, K., & Müller, H. (2023). Kognitive Belastung [Cognitive load]. Zeitschrift für Psychologie, 231(3), 145-167. https://doi.org/xxxxx
```

### Turkish Example
```
🟢 Yılmaz, A., & Demir, S. (2024). Bilişsel yük kuramı [Cognitive load theory]. Türk Psikoloji Dergisi, 39(1), 23-45.
```

## In-Text Citations

### One Author
- (Smith, 2023)
- Smith (2023) found that...

### Two Authors
- (Smith & Jones, 2023)
- Smith and Jones (2023) argued...

### Three or More Authors
- First citation: (Smith, Jones, & Brown, 2023)
- Subsequent: (Smith et al., 2023)

### Multiple Sources
- (Smith, 2023; Jones, 2024; Brown, 2022)
- Alphabetical by first author

### Direct Quote
- (Smith, 2023, p. 45)
- (Smith, 2023, pp. 45-46)

## Tools & Resources

For automated formatting, use:
```bash
python scripts/format_citations.py --interactive
```

Official APA Style resources:
- https://apastyle.apa.org/
- APA Publication Manual (7th ed.)
