# Translate Skill (英译中翻译助手)

An expert English-to-Chinese translation assistant and English language teacher for Claude Code.

## Overview

The translate skill provides comprehensive English-to-Chinese translation with detailed linguistic analysis, making it perfect for language learners who want to understand not just what English text means, but *how* it works.

## Features

### 🌍 Translation
- Accurate, natural Chinese translations
- Maintains original meaning and tone
- Uses idiomatic Chinese expressions (not word-for-word translation)

### 📚 Grammar Analysis
- Identifies and explains key grammar points
- Highlights sentence structures (simple, compound, complex)
- Explains verb tenses, voice (active/passive), mood
- Points out special grammatical constructions

### 💡 Vocabulary Explanation
- Explains difficult or key vocabulary words
- Provides word types (noun, verb, adjective, etc.)
- Includes example sentences
- Mentions idioms, phrasal verbs, and collocations

### 🔍 Sentence Structure Analysis
- Breaks down complex sentences into components
- Identifies main clauses and subordinate clauses
- Explains how different parts connect

### 📌 Language Points
- Cultural context where relevant
- Register (formal/informal)
- Alternative translations or phrasings
- Common mistakes Chinese learners might make

## Installation

1. Create a ZIP file of the `translateSkill` folder
   - Ensure the ZIP contains the folder as its root: `translateSkill.zip → translateSkill/ → skill.md`
2. Install the ZIP file in Claude Code via the skills management interface
3. The skill will be available as `/translate`

**Packaging:**
```
translateSkill.zip
  └── translateSkill/
      ├── skill.md
      └── README.md
```

## Usage

Invoke the skill in Claude Code:

```
/translate
```

Then provide English text to translate and analyze. For example:

```
The book that I bought yesterday was incredibly interesting.
```

## Output Format

The skill generates a beautifully styled HTML page with:

- **📝 Original Text** - The English text in a styled box
- **✅ Translation** - Natural Chinese translation
- **📚 Grammar Points** - Key grammatical structures explained
- **💡 Vocabulary List** - Important words with definitions and examples
- **🔍 Sentence Structure** - Detailed breakdown of sentence components
- **📌 Additional Notes** - Cultural context, common mistakes, alternatives

## Example

**Input:**
```
The book that I bought yesterday was incredibly interesting.
```

**Output includes:**
- Translation: 我昨天买的那本书非常有趣。
- Grammar analysis of the relative clause structure
- Vocabulary breakdown of "incredibly" and "interesting"
- Sentence structure showing main clause and subordinate clause
- Notes about alternatives like using "which" instead of "that"

## Best Practices

- Works best with complete sentences or paragraphs
- For very long texts, the skill focuses on the most important points
- Ideal for language learners at intermediate to advanced levels
- Can be used for literary texts, articles, or everyday English

## Technical Details

**Skill Name:** `translate`

**File Structure:**
```
translateSkill/
├── skill.md      # Skill definition and prompt
└── README.md     # This documentation
```

**Output:** HTML file with embedded CSS styling, optimized for readability with Chinese and English text.

## Customization

To customize the skill behavior, edit `skill.md` and modify:
- Output format preferences
- Level of detail in explanations
- Focus areas (more grammar vs. more vocabulary)
- Styling in the HTML template

## License

Open source and available for personal and educational use.
