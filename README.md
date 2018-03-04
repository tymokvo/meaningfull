# meaningfull
### every word is a [library, dictionary, lexicon, ...]

meaningfull is a way to write that explores the space of all possible documents

## Does this:

Take some statement and rewrite it without using the original words.

```
"science is fun"

=

"
knowledge as distinguished from ignorance or misunderstanding
equals
what provides amusement or enjoyment
"
```

## Purpose

When we write, our writing bears the traces of all that we have read and all that we have written before. Meaningfull is a way to write that exposes this.

For those from the humanities, this can be thought of as a literation of the critical project.

For those who write code, you can think of this as the inheritance graph.

For those who think about topology, this can be thought of as a way to explore the manifold of adjacent possible documents.

## Idea

Thoughts are exchanged through documents. A document is a collection of statements is a collection of words. Every document can be thought of as a vector of some length. That length is the number of statements in the document. Each statement is a vector where the length is the number of words. However, words are not stable. Words can have very different meanings in different contexts. Even within the same context it may not always be clear what the meaning of a word is at that particular instance. Even in mathematical notation, symbols may mean somthing different in that context.

This is where meaningfull comes in. Meaningfull allows you to enumerate the other possible meanings of a particular word interactively. You can source definitions from particular sources (Wikipedia, Merriam-Webster, etc.) or authors (Ta-Nahesi Coates, Deleuze, etc.) or define your own. The full list of definitions is explorable in the document itself.

If you think of a document as a vector of statements which are vectors of words which describe a set of ideas, then you can think of it as a point in the space which has the dimensionality of the number of words. It follows that the points adjacent to it communicate similar ideas. Thus writing/editing/thinking can be thought of as walking along the manifold of possible documents to find the one that best commnicates your ideas. Meaningfull exposes this space by reducing the distance from the terms that we use and the documents/authors from where we take them.

## Structure

```
Libraries
    Documents
        Statements
            Words
                Alphabet
                Libraries
                    ...
            Syntax
                Grammar
                Punctuation
```

Words are the atoms of ideas. However, there is a recursive structure that arises wherein words are constructed by the world in which they are written. Ergo, every word is a library. That is to say, every word is constructed by the documents that define it.
