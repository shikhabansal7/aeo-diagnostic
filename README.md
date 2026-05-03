# AEO Diagnostic — AI Search Visibility for Amazon Sellers

Built for Pixii's Founding Engineer challenge. Deadline: May 5.

## The problem

When a shopper asks Claude, ChatGPT, or Gemini "best magnesium for seniors", 
does your product show up? Most Amazon sellers have no idea. 
That's the AEO gap — and it's costing them revenue they can't see.

## What it does

1. Enter a shopper query and your product name
2. The tool queries Claude (live) and simulates GPT-4 + Gemini responses
3. Get an AEO score (0–100) per engine
4. See who beats you, why, and exactly how to fix it

## APIs used

- Claude API (`claude-sonnet-4-20250514`) — real shopper response + report card generation
- Simulated GPT-4 and Gemini via Claude (production: wire up OpenAI + Google AI SDKs)

## How to run

Open `pixii_aeo_diagnostic.html` in any browser. No server. No setup.

## If I had more time

- Real OpenAI + Gemini API calls
- Weekly score tracking (did your AEO improve?)
- Shareable score card image → viral in Amazon seller communities
- "Fix this with Pixii" CTA wired to Pixii onboarding

## Why this for Pixii

The growth role is about making 1M people see Pixii every month.
A seller sharing their AEO score card is free distribution.
Beautiful Pixii listings aren't just prettier — they contain the 
trust signals (rich content, lifestyle imagery, social proof) 
that make AI engines more likely to recommend you.

Built by Shikha Bansal · linkedin.com/in/shikhabansal7
