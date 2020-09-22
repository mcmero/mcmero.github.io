---
title: My PhD explained using the 1,000 most common English words
categories:
  - Blog
tags:
  - bioinformatics
  - PhDs
  - cancer
  - structural variation
  - tumour heterogeneity
---

After listening to an [Intelligence Squared](http://www.intelligencesquared.com/) podcast episode on [making complicated stuff simple](https://intelligencesquared.com/events/randall-munroe-on-making-the-complicated-simple/), I was inspired to explain my recently submitted PhD thesis using the 1,000 most common words of the English language (ala [Randall Munroe](https://en.wikipedia.org/wiki/Randall_Munroe)'s [Thing Explainer](https://xkcd.com/thing-explainer/)). I have used [this list](http://www.ef-australia.com.au/english-resources/english-vocabulary/top-1000-words/) (which thankfully includes the word cell!), allowed pluralisation, contractions and past participles.

------

### How large changes in the structure of cell information affects groups of cancer cells

Your body is made up of billions of cells. Cells are very small bags of stuff. Every cell has information inside it that tells it how it works, just like a computer. This information is like a set of orders that is read by little machines, which go on to make stuff that builds the cell and talks to other cells. This information is made up of four letters: A, C, T and G, which we call bases. There are about three billion bases in every cell.

Cells continue to make more of themselves to maintain your body. Every time a cell makes more of itself, it passes on its information to its daughter cells. Sometimes, this information changes as it is passed on. This can make the cell do things that are not in your body's interests. Cells usually make more of themselves a certain number of times and then die. The information inside each cell tells it how many times it can make more of itself. But some changes to a cell's bases can turn this off. This might change a cell's orders so that it continues to live and make more of themselves. We call this 'cancer'. There are many ways that this can happen, and we often see lots of base changes in cancer cells, but we don't always know which ones are the bad changes and which ones make little difference.

We do know that there are several kinds of base changes. Changes can happen to a single, or many, bases. Big changes can remove, add or change the order of lots of bases. It is hard to read the bases of many single cells (and it costs a lot!), so we put many cells together and read all their information at once. We also can't read each cell's bases from start to finish in one go, but we can break them up into small pieces of about a hundred bases that can be read by special machines. This means we must put all the bases in the right order again -- just as if we cut up the pages of a book and wanted to read it again. But we don't have to do this by hand because we have computer programs that put the bases back in the right order for us.

We still don't know which bases came from which cells, but we can figure out how many times we see certain base changes compared to a cell that has not changed. Because cells pass on their base changes to their daughter cells, we can assume that cells with similar changes come from the same mother cell. Using this information, we can put these similar cells into groups. These groups are interesting because some cells with certain base changes will grow more and others less. The base changes might give cells different abilities that change how they work. For example, some may be more easily killed by drugs that we use to treat cancer, while others might be more tough. We want to know which base-changes the tough cells have so that we can find ways to better treat these cancers.

We already have a few different ways to figure out these groups of cells with single base-changes, but we did not have any ways to figure out which groups of cells have very large changes in their base structure. I came up with a method to do this using a computer program. To test it, I took the base information from two real cancers and put them back together in different amounts, and had my program guess the right amounts for each group.

I then used a collection of many hundreds of cancers to see if I could find interesting patterns of changes that happened in only some of the cancer's cells. I could see that different types of cancer had quite different patterns, but the most interesting thing was that some cancers had special changes to the order of their bases in only a small number of their cells. The people that had these cancers did not live as long as those that did not, which means we have to study these changes more to figure out how they they affect cancers. The new thing about this approach is that we could not have found this out if we only looked at single base changes. This new approach will help us learn more about cancer cell group behaviour when they get these large, base order changes. This will help us to better treat cancers that have many of these changes, and maybe even predict the future of how some of these cancers will change. This will help people get less sick from cancer and live long lives in good health.

------

If you are interested in reading about this in scientific jargon and all, please see my [thesis](https://minerva-access.unimelb.edu.au/handle/11343/215901).
