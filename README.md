<!-- Yes, this was AI generated lol -->

# Un-Bait Bot

[![Twitter Follow](https://img.shields.io/twitter/follow/unbaitbot?style=social)](https://twitter.com/unbaitbot)

**Twitter Handle:** [@unbaitbot](https://twitter.com/unbaitbot)

---

## Overview

**Un-Bait Bot** is a Twitter bot designed to help users verify the truthfulness of posts that contain text and a link to an external website. Whenever someone tags [@unbaitbot](https://twitter.com/unbaitbot) in a tweet containing a claim and a link, the bot automatically:

1. Reads the content of the linked website.
2. Analyzes whether the text in the tweet accurately reflects the content of the linked page.
3. Replies to the tweet indicating if the claim is true, misleading, or bait.

The goal is to reduce misinformation and clickbait by providing quick, automated fact-checking on Twitter.

---

## Features

- **Automatic content retrieval:** Fetches and parses the linked webpage.
- **Text verification:** Compares the tweet’s claim against the actual content.
- **Real-time replies:** Responds publicly to tagged tweets with a fact-check summary.
- **User-friendly:** Simply tag [@unbaitbot](https://twitter.com/unbaitbot) in your tweet with a claim and a link.

---

## How It Works

1. A user tweets something like:

   > "This new study proves coffee cures all diseases! https://example.com/article"  
   > @unbaitbot

2. Un-Bait Bot detects the mention, extracts the claim and the URL.
3. It scrapes and analyzes the linked page content.
4. It determines if the claim matches the content or if it’s misleading.
5. The bot replies with a summary, e.g.:

   > @user The linked article does not support the claim that coffee cures all diseases.  
   > Be cautious of exaggerated headlines!

---

## Getting Started

### Prerequisites

- Twitter Developer account with API access
- Bun

### Installation

Clone the repository:

```bash
git clone https://github.com/pulgueta/unbaitbot.git
cd unbaitbot
bun install
```
