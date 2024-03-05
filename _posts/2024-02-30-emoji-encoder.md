---
layout: post
title: Encoding with Emojis
subtitle: There's lots to learn!
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
author: Bill Smith
---

# Encoding in emojis

Look at this python code pretty funny right? 

```
def text_to_emoji(text):
    # Dictionary mapping keywords to emojis
    emoji_map = {
        "I": "👤",  # A generic person symbol
        "am": "",
        "a": "",
        "villain": "😈",  # A devil face, representing a villain
        "and": "🔗",  # Link symbol, representing 'and'
        "will": "will",
        "always": "♾️",  # Infinity symbol, representing 'always'
        "be": "be",
        "the": ""
    }

    # Split the text into words
    words = text.split()

    # Convert each word to its corresponding emoji
    emoji_sentence = " ".join([emoji_map.get(word, word) for word in words])

    return emoji_sentence

text = "I am a villain and will always be the villain"
encoded_text = text_to_emoji(text)
print(encoded_text)
```

Since I'm a villain I won't explain it.