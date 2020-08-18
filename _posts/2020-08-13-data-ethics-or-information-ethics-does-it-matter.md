---
layout: post
title: Data ethics or information ethics
subtitle: Does it matter and why is it important?
tags: [data ethics, information ethics, self regulation]
---

The underlying principles related to information and data ethics are broadly compliant with the same principles. In the era of big data and automated decision support tools, there are some subtle differences.

## Key difference

The most notable arguments for me for making the case of moving to a data centric view of ethics are digitisation (making use of cloud computing), and decision support tools.

In the case of a written letter, as long as that remains as a written letter in storage you have information (if we're thinking of how humans would initially make use of it). The steps a human takes typically to understand that letter would be to:

1. Read the letter.
2. Tell you what the letter says in complete context of all the words.
3. File the letter.

There is a case for data ethics at this stage if you were thinking more abstractly.

1. Breakdown the whole document into the words alone.
2. Ignore the stop words.
3. Count the remaining words.
4. Maybe you could determine what this letter is about based on the counts.

### Digitisation
But in the day and age we live in, why would we not digitise it?

When you think in terms of that written letter being copied to a computer system, you now apply several processes to convert that down to data itself much like the second argument.

1. Scan the document in.
2. Perform optical character recognition so the text is machine readable.
3. Apply natural language processing to break the document into a hash table.
4. You're now working at the data level as it isn't information humans could make sense of.

Let's now say you're a very popular individual you have lots of letters. Probably too many to read at this stage, you need to filter out the ones so you're only dealing with the most interesting to you, you could employ lots of people to read the letters and tell you what the letters say - but honestly who's doing that these days. (Some might argue who's sending you all these written letters).

You train a machine learning model to only tell you about the ones you're interested in. This decision support tool operates at a high level of accuracy so you trust it, knowing that it has the probability of throwing out 3% of letters you would find interesting.

For the sender(s) the letters are information, but you'll never read them so they are meaningless. The approach you've decided to take is that of the model. The approach the model has taken is one of data, and hash functions.

## Data decisions

The decision support tool then is no longer making decisions on information, as whilst you're understanding of the model (broadly) is information; you ensured it was behaving correctly and you understand the mechanisms at play - you could never understand how the system made the on-the-fly decisions for each letter.

The decision support tool creates information for you, but it's decision making isn't in the realms of information. How it decides never enters into itself as information.

So is the ethical decision to use it based on information or data?

{: .box-note}
**Note:** Under the GDPR, there are some situations where you could never have a fully automated decision being made. A reasonable system must still be in place so that the decision is still ultimately down to human judgement.