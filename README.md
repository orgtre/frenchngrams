# Frequency tables of French n-grams

Available for download above are tables for n = 1, ..., 6, each containing the 10,000 most frequent n-grams in the corpus described below. Note that their quality deteriorates quickly with n, as the effective sample size decreases and idiosyncrasies of the underlying sample become more pronounced.

(If anyone uses these lists and for example filters out those n-grams whose meaning is not clear from the components and/or adds translations, please share your work.)

##On the underlying corpus
The frequency tables are for a language corpus built from the top 400 most popular French books on [Project Gutenberg](https://www.gutenberg.org/ebooks/search/?sort_order=downloads&query=l.french) (as of 2016-12-04),
omitting:

- works not originally in French
- dramas where each character name appears in order to indicate who is speaking
- some works where no correctly encoded text file existed
- short works (<400-500 kB)

Raw corpus: 
136MB, 2.6 million lines, 22,086,575 words, 13,2794,060 characters, 6.01 characters per word.

Corpus stripped of most characters except letters, "'" and "-", plus nonexcessive spaces and newlines:
129MB, 2.0 million lines, 21,858,058 words, 125,679,247 characters, 5.75 characters per word.

Words connected by "'" or "-" are treated as one word when determining n-grams. (The whole corpus can also be shared if somebody actually wants it, but a lot larger corpora are available e.g. from [google] (http://storage.googleapis.com/books/ngrams/books/datasetsv2.html).)



