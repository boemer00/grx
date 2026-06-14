# Why B2B SaaS Should Be Optimising for Claude First

At Profound's Zero Click event in NYC this week, one finding stood out for anyone working in answer engine optimisation: Claude is the most optimisable LLM on the market right now. Not because it is bigger or smarter, but because its search behaviour is unusually predictable. For a B2B SaaS team trying to earn citations, predictability is the whole game.

Here is the core mechanic. Claude does not re-rank what it retrieves. It pulls directly from Brave's search index and preserves the order. The data shared at the event showed that 79.2% of all Claude citations come from Brave ranks 1–10. Rank in Brave's top ten, and you are in the running to be cited in Claude. There is no opaque re-ranking layer scrambling the results between retrieval and answer. That alone makes Claude easier to reason about than most competitors.

## Claude searches less, but more predictably

Claude does not reach for the web nearly as often as ChatGPT. ChatGPT triggers a web search roughly 90% of the time. Claude does so only 36.6% of the time. The rest is answered from its training data, with no citation opportunity attached.

So the question becomes: what actually makes Claude search? The event data broke it down clearly. Recency prompts such as "best XYZ" trigger a search 81% of the time. Ranking prompts like "top 10" sit at 67%. Location prompts ("restaurants in…") hit 55%, and comparison prompts ("X vs Y") 51%. By contrast, "how does", "what is", and "steps to" mostly get answered from memory, with no search and therefore no citation.

The practical takeaway for content teams is straightforward. If you want to show up in Claude, prioritise ranking for "best", "top", "near me", and comparison queries. Informational and how-to phrasing is largely a dead end for visibility here.

## Your Google work transfers. Your ChatGPT work mostly does not

This was the finding most likely to change how teams allocate effort. The domain overlap between Claude and ChatGPT citations for the same prompts is just 8%. In other words, 92% of what gets cited in ChatGPT would not be cited in Claude. These are effectively two different visibility surfaces, and assuming they behave alike is a mistake.

Claude's citations, however, overlap 64% with Google's rankings, against just 37% for ChatGPT. So the SEO investment you have already made for Google carries over to Claude far better than your ChatGPT-specific work does. That is a useful efficiency for teams with limited resources.

## Two quirks worth building around

Two further details make Claude genuinely testable. First, its query fan-outs are near deterministic: Claude generates the same fan-out 65% of the time across users. This is the detail that matters most for measurement. With a highly variable engine, you cannot cleanly attribute a citation gain to a change you made, because the engine might have queried differently regardless. When behaviour is that consistent, you can run a proper before-and-after test on one query cluster and trust the result. Predictability is what makes measurement possible, and measurement is what makes optimisation a discipline rather than guesswork.

Second, Claude's fan-outs are currently fixated on years. Claude stamps "2026/2025" onto 94% of its fan-outs, compared with 17% for ChatGPT. The implication is direct: put the year in your page titles. It is a small change that aligns your content with how Claude is actually querying right now.

## What to do on Monday

The findings translate into a short, concrete checklist:

1. Audit your Brave and Google rankings for your target "best", "top", "near me", and comparison terms. These are the queries that trigger a Claude search in the first place.
2. Rewrite high-intent page titles to lead with ranking and comparison framing where it fits naturally.
3. Add the current year to those titles to match Claude's year-obsessed fan-outs.
4. Set up a fan-out test on one query cluster, change a single variable, and measure the citation shift. Claude's determinism is what makes this readable.

## One honest caveat

These are current behaviours, not permanent laws. Search-trigger rates, the Brave dependency, and the year-stamping habit are all products of how Claude works today, and any of them could shift with a model update. That is true of every LLM feature, and it is the reason ongoing measurement matters more than a one-off optimisation pass.

## The bottom line

Claude rewards teams who treat it as a system to be understood rather than a black box. Strong Brave and Google rankings, the right query phrasing, year-stamped titles, and a willingness to test against its deterministic fan-outs add up to a real, repeatable visibility advantage. For B2B SaaS, that makes Claude the place to start.
