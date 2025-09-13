# Planning Document Template

**Student Name:** [Olivia Denton]  
**Date Completed:** [09/12/2025]  
**AI Tool Used:** [Google Gemini]

## My chosen poem

**Poem:** "[Ozymandias]" by [Percy Bysshe Shelley]

**Public domain verification:**
``` text
[Confirm this is public domain - author died 70+ years ago or explicitly public domain. Include death year if known.]
```died July 8. 1822

**Why I chose this poem:**
``` text
[2-3 sentences explaining why this poem appeals to you and why it will work well for a website project. Consider both personal connection and practical factors like structure, length, and visual potential.]
```It’s not usually the kind of poem I would pick. I wanted to try something more realistic that also matches todays world feelings. It channels bigger emotional awareness that seems relatable.

**Brief description for design purposes:**
``` text
[1-2 sentences about the poem's mood, themes, or imagery that will influence your design choices.]
```The mood is dreary the opposite of life. Things are unexpected and one’s perspective can change depending on the stage in life they are at.

## HTML guidelines

Based on my AI conversations, here are my simple guidelines for structuring this poem:

**Document structure:**
- [ ] Main heading: [What will be your h1]
- [ ] Poem container: [article, section, or div - which and why]
- [ ] Stanza handling: [How you'll mark up stanzas]
- [ ] Line breaks: [br tags, separate p elements, or other approach]
- [ ] Author attribution: [Where and how you'll credit the author]
<head>: contains meta-information
<body>: visible content appears here
<main>: main content 
<h1>: Ozymandias
<p>: Percy Bysshe Shelley
<blockquote> used for a block of quoted text
“I met a traveller from an antique land, Who said—"Two vast and trunkless legs of stone Stand in the desert. . . . Near them, on the sand, Half sunk a shattered visage lies, whose frown, And wrinkled lip, and sneer of cold command, Tell that its sculptor well those passions read Which yet survive, stamped on these lifeless things, The hand that mocked them, and the heart that fed; And on the pedestal, these words appear: My name is Ozymandias, King of Kings; Look on my Works, ye Mighty, and despair! Nothing beside remains. Round the decay Of that colossal Wreck, boundless and bare The lone and level sands stretch far away."
<br> is a line break 

**Semantic elements to use:**
- [ ] Header: [What goes here]
- [ ] Main: [What goes here] 
- [ ] Footer: [What goes here]
- [ ] [Any other specific elements your poem needs]
Semantic elements to use:
<article> or <section>: contains entire poem
<h1>: poem title
<p>: author credentials
<blockquote>: wrap entire poems text
<br>: line breaks
<footer>: holds publication year

**Accessibility considerations:**
- [ ] Heading hierarchy: [Your planned h1, h2, etc.]
- [ ] [Any other accessibility notes from your AI discussion]
Headings- <h1>, <h2>
Paragraphs- <p>
Blockquotes- <blockquote>
Use <br>. Avoid <div>
Clear and concise text- it’s about presentation
Avoid justified text- use left-aligned text
Font and contrast- Ensure your text has a high contrast ratio with the background color. Avoid overly stylized or "fancy" fonts that are difficult to read. A simple, legible font is always best.
Page title- <title> make sure its descriptive ex: title of poem by author of poem
Language attribute- <html> tag should specify what language is being used

## CSS guidelines

Based on my AI conversations, here are my simple design guidelines:

**Colors:**
- Background: [Color name + hex code if known]
- Text: [Color name + hex code if known]
- Accent color: [If needed - color name + hex code]
- Why these colors: [Brief reason connecting to poem's mood]
Background- navy blue (for now)
Text- white (for now)
Accent color- black (for now)
Why these colors- 

**Typography:**
- Heading font: [Font name] - Why: [Brief reason]
- Body/poem font: [Font name] - Why: [Brief reason]
- Font sizes: [Planned approach - specific sizes or relative approach]
Font-size- 14px (will adjust as needed)
Font-family- Verdana for now

**Layout and spacing:**
- Content width: [How wide your content area will be]
- Stanza spacing: [How much space between stanzas]
- Overall feel: [Clean/cozy/spacious/intimate - whatever matches your poem]
Line-height- 1.5 adds vertical space can help people with dyslexia or low vision
Text-alignment- align to the left
Centering the poem- margin-auto;
Padding- create white space
Overall feel- hurt, wreckage, bare, far, lonely

**Simple responsive plan:**
- Mobile: [1-2 key adjustments for small screens]
- Desktop: [How it will look on larger screens]

## Key AI conversations and discoveries

### What worked well
**Best prompt and response:**
``` text
[Your most effective prompt]
```

**Why this worked:**
``` text
[1-2 sentences on what made this effective]
```

### What surprised you
**An AI limitation you discovered:**
``` text
[Example: It became repetitive when asked different questions]
[Example: Gave me titles of poems but not actual poems]
[Example: ]
[Example: ]
```

**How you worked around it:**
``` asked more detailed questions
[What you did to get better results]
```changed my way of thinking

## Ready to build?

**Do you feel prepared to start coding your poetry website?** [Yes/No]
I feel kind of ready a little anxious

**What are you most confident about?**
``` I’m most confident about nothing as of right now lol.
[What aspect of the plan feels solid to you?]
```The solid part of the plan is planning out the html and CSS guidelines

**What might you need to figure out as you go?**
``` I would need to figure out the overall look I’m going for
[What aspects still feel uncertain or might need adjustment during implementation?]
```The design part of CSS will need plenty of adjustments during implementation. I can get peculiar about how I want things to look.

**Next step:** Start building your poetry website using these guidelines as your reference!