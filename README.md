# AwesomeAbbreviations
This is an effort to make symbol naming more consistent. It is highly inspired by the [fast.ai style](https://github.com/fastai/fastai/blob/master/docs/style.md).

Like the MIT Professor *Patrick Henry Winston* once said: when we put a name on a concept, we have a power over it. And I believe the short the name, the
more power we have. To achieve that, we use abbreviation.

We should thing about abbreviation as **a way of compression**. We want to compress name of a concept
so that we can refer to it more easily. However, the human decoding algorithm takes time to train, especially when names are too similar.
We get confused easily if there are too many short names, since the distance between them get smaller. Therefore, the rule of 
thumb is: the more frequent-used a name is, the shorter name it should have. I guess that's why we use `I` (or very short word in language other than English) to refer to ourself,
or we use first letters of our friends' name to call them. This rule should remind you about the *Huffman coding*. In short,

> The Huffman Coding for naming a concept: commonly used things should have shorter names. 

The level of compression depends on how often a concept is used, which depends on a specific application. Some concepts are meaningful in wide-range of contexts (like `i` for index, `fn` for function), 
some are used only in a very domain-specific context (like `nll` for negative-log-likelihood in machine learning).

This project provides a curated lists of common abbreviations for common concepts at different compression level.
When the concept is context-dependent, it is listed in its seperate context.

| Concept                                   | lvl 0  | lvl 1 | lvl 2 |
|-------------------------------------------|--------|-------|-------|
| abbreviation                              | abbr   |       |       |
| list                                      | lst    | ls    | l     |
| sequence                                  | seq    |       |       |
| register                                  | reg    |       |       |
| internationalization                      | i18n   |       |       |
| global                                    |        |       | g     |
| dataframe                                 |        |       | df    |
| select                                    |        | sel   |       |
| location of ok elements                   |        | which |       |
| namespace                                 |        |       | ns    |
| identity                                  |        |       | id    |
| manual                                    |        |       | man   |
| dictionary                                | dict   |       | d     |
| key                                       |        |       | k     |
| value                                     |        | val   | v     |
| queue                                     |        |       | q     |
| set                                       |        |       | s     |
| regular expression                        |        |       | re    |
| table                                     |        | tbl   | t     |
| length                                    |        | len   | l     |
| concatenate                               | concat | cat   | +     |
| extend                                    |        | ext   |       |
| append                                    |        |       |       |
| expression                                |        | exp   |       |
| request                                   |        | req   |       |
| return                                    |        | ret   |       |
| object                                    |        | obj   | o     |
| percentage                                |        |       | p     |
| catalog                                   |        |       | cat   |
| description                               |        | desc  |       |
| class                                     |        | cls   | c     |
| delete                                    |        | del   |       |
| remove                                    |        | rm    |       |
| make                                      |        | mk    |       |
| get first elements                        |        | head  |       |
| get last elements                         |        | tail  |       |
| longtitude                                | long   |       |       |
| latitude                                  |        | lat   |       |
| location                                  |        | loc   |       |
| position                                  |        | pos   |       |
| coordinate                                |        | coord |       |
| size                                      |        | sz    |       |
| number of elements                        |        |       | n m   |
| function                                  | func   | fn    | f     |
| input                                     |        |       | x     |
| output                                    |        |       | y     |
| image                                     |        | img   | im    |
| figure                                    |        | fig   |       |
| background                                |        |       | bg    |
| foreground                                |        |       | fg    |
| plot                                      |        | plt   |       |
| library                                   |        | lib   |       |
| index                                     |        | idx   | i j   |
