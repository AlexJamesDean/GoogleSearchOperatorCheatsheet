
# Google Search Operator Cheatsheet 🔍

## Basic Operators
| Operator | Description | Example |
|----------|-------------|---------|
| `""` | Exact match | `"how to center a div"` |
| `OR` | Either term | `python OR javascript` |
| `-` | Exclude term | `javascript -jquery` |
| `*` | Wildcard | `how to * in python` |
| `()` | Group terms | `(javascript OR python) tutorial` |

## Advanced Operators
| Operator | Description | Example |
|----------|-------------|---------|
| `site:` | Search specific website | `site:github.com react hooks` |
| `filetype:` | Search for file types | `filetype:pdf javascript guide` |
| `intitle:` | Term in page title | `intitle:react tutorial` |
| `inurl:` | Term in URL | `inurl:react` |
| `related:` | Related websites | `related:microsoft.com` |
| `cache:` | Cached version | `cache:website.com` |

## Time-Based Search
| Operator | Description | Example |
|----------|-------------|---------|
| `before:` | Before date | `javascript before:2023` |
| `after:` | After date | `react after:2022` |
| `..` | Number range | `phone $100..$500` |

## Code-Specific Search
| Operator | Description | Example |
|----------|-------------|---------|
| `language:` | Programming language | `language:javascript promise` |
| `repo:` | GitHub repository | `repo:facebook/react hooks` |
| `error:` | Error messages | `error:"npm ERR!"` |

## Social Media Search
| Operator | Description | Example |
|----------|-------------|---------|
| `@` | Social tags | `@username twitter` |
| `#` | Hashtags | `#javascript` |

## Combinations for Developers

### Finding Code Solutions
Search: `site:stackoverflow.com OR site:github.com "specific error message"`

### Finding Documentation
Search: `site:docs.microsoft.com OR site:developer.mozilla.org javascript`

### Finding Recent Tutorials
Search: `intitle:tutorial react after:2023`

### Finding Code Examples
Search: `site:github.com filetype:js "function example"`

### Finding API Documentation
Search: `site:docs.* api reference "endpoint"`

## Pro Tips 💡

### Use Multiple Operators
Search: `site:github.com "react hooks" filetype:md after:2023`

### Exclude Multiple Terms
Search: `javascript -jquery -wordpress -php`

### Find Similar Sites
Search: `related:netflix.com streaming service`

### Find Specific Versions
Search: `"react tutorial" "version 18" OR "v18"`

### Find Source Code
Search: `site:github.com filetype:js "function name"`

## Common Development Searches

### Error Messages
Search: `"error message" site:stackoverflow.com OR site:github.com`

### Library Usage
Search: `site:github.com "import library" filename:js`

### Best Practices
Search: `intitle:"best practices" javascript after:2023 -wordpress`

### Security Issues
Search: `site:cve.mitre.org OR site:nvd.nist.gov vulnerability library`

### Performance Tips
Search: `site:web.dev OR site:developers.google.com performance optimization`

## Remember 🤔
- Google search is not case-sensitive
- Order matters - put important terms first
- Use fewer, more specific terms
- Update date ranges for current information
- Check multiple pages of results
- Verify information from multiple sources

## Additional Resources 📚
- **Google Advanced Search**
https://www.google.com/advanced_search
- **Google Search Console**
https://search.google.com/search-console
- **Google Developers Search**
https://developers.google.com/search/

## Expert Tips 🎯

### Finding Specific File Types
- PDFs: `filetype:pdf subject`
- PowerPoints: `filetype:ppt subject`
- Excel files: `filetype:xlsx OR filetype:xls subject`
- Word docs: `filetype:doc OR filetype:docx subject`

### Academic Research
- Search: `site:.edu OR site:.gov subject`
- Search: `filetype:pdf site:.edu research paper subject`

### Technical Documentation
- Search: `site:readthedocs.io OR site:docs.* subject`
- Search: `inurl:docs OR inurl:documentation subject`

### Forum Discussions
- Search: `site:reddit.com OR site:stackoverflow.com subject`
- Search: `inurl:forum OR inurl:discussion subject`

### Price Comparisons
- Search: `price OR cost $50..$100 product`
- Search: `compare OR vs product1 product2`

## Troubleshooting Tips 🔧

### Too Many Results?
- Add more specific terms
- Use exact phrases in quotes
- Add `site:` operator
- Specify date ranges

### Too Few Results?
- Remove some terms
- Try synonyms
- Remove quotes
- Broaden date range

### Wrong Context?
- Add context terms
- Use `-term` to exclude irrelevant results
- Specify industry/field

### Outdated Results?
- Use `after:` operator
- Sort by date
- Add year to search
- Include "current" or "latest"

I fix the bugs other devs gaslight you about.
A I tools, Five M systems, automation pipelines.
Build it, break it, resurrect it: 👉 https://AJThe.Dev
