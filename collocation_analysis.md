Collocation analysis of Adele’s songs
================
Myung Kyung (Rachel) Hyeon
2022-09-24

## 1. Introduction

Adele’s albums has been critically acclaimed for their personal
connection to Adele’s life and exploration of many different topics such
as “heartache”, “love”, and “tragedy” (Adele Wiki, 2022). Adele has
released four studio albums to this date, *19*, *21*, *25*, and *30*.
This paper will discover the thematic similarities and differences
between her two sets of albums, the first set of albums being album *19*
and *21*, and the second set of albums being album *25* and *30*, as she
progressed in her musical career and in her personal life. We will
attempt to uncover these thematic characteristics by comparing the
collocates of *love* and *you* for Adele’s first set of albums, albums
*19* and *21*, and the second set of albums, albums *25* and *30*, and
conducting log-likelihood test between the two subcorpora and reporting
effect sizes using log ratio. The reason behind choosing *love* was that
it was the most frequent noun and verb in the corpus of her lyrics. 
Also, the topic of love tends to be a popular theme in most pop songs, so we
can see the similarities or differences between how Adele expresses the
concept of *love* in her albums. The reason behind choosing *you* over *i*, which was
the most frequent word and pronoun, was that we wanted to examine how the
feelings she had for her subject of desire changed or remained the same
over time. Log-likelihood (LL) will uncover the differences between the
two subcorpora and report whether the differences between the two
subcorpora are statistically significant.

## 2. Data

We created corpus including all of Adele’s lyrics in her four studio
albums, *19*, *21*, *25*, and *30*. We extracted two subcorpora, the
first subcorpus including albums *19* and *21*, and the second including
albums *25* and *30*, to investigate the thematic similarities and
differences in Adele’s albums.

Album 1 refers to Adele’s first studio album *19*, album 2 refers to
Adele’s second studio album *21*, album 3 refers to Adele’s third studio
album *25*, album 4 refers to Adele’s fourth studio album *30*. We can
see from Table 1 that there are approximately 3000 to 4000 tokens in
each of her albums, with 11 to 12 songs in each album.

<div align="center">
    
**Table 1:** Corpus Composition of Adele’s Four Studio Albums

| Album | Texts | Tokens |
|:-----:|:-----:|:------:|
| 1     |    12 |   3144 |
| 2     |    11 |   3631 |
| 3     |    11 |   3640 |
| 4     |    12 |   4005 |
| Total |    46 |  14420 |

</div>

The data was gathered by manually copying Adele’s lyrics found on Google
for every song into a separate text file, and organizing the text files
into folders for different albums. Manual construction of the corpus was
feasible because Adele only has 46 songs in total in her four studio
albums.

## 3. Methods

First, absolute and relative frequency of top 20 most frequently occurring
tokens in Adele’s lyric corpus were calculated. After deciding
which tokens to examine further, which were *i*, *you*, and *love*, we
calculated common dispersion measures for the three tokens to test
whether they are dispersed evenly throughout her albums.

Next, thematic similarities and differences between Adele’s two subcorpora
were uncovered by comparing the collocates of *love* and *you*
for Adele’s first set of albums, albums *19* and *21*, and the second
set of albums, albums *25* and *30*. Collocation network allows us to
visually view the relationship between the two subcorpora by showing us
shared and distinct collocates between the subcorpora, the frequency of
the collocate using the shade of the color of the collocate, and the
strength of the association between the collocates and the initial node.
A collocation network was created by filtering MI1 values greater than
4, collocate frequency greater than or equal to 4, and span greater than
or equal to 5 in order to discover which collocates appeared exclusively
near the node. The values for MI1, collocate frequency, and span were
chosen after experimenting with different values and finding the values
that produced appropriate sized collocation network. The token *love* is
appropriate as nodes for the two subcorpora as it was the most frequent
noun and verb in the corpus of her lyrics, so the similarities or
differences between how Adele expresses the concept of *love* in her two
sets of albums can be discovered. We chose to analyze *you* over *i* to
create collocation network, which was the most frequent word and
pronoun, because we wanted to examine how the feelings she had for her
subject of desire changed or remained the same over time. Another reason
why we avoided analyzing *i* was that it was expected that most of the closest
collocates of *i* to be linking verbs like *was* and *am*. Also, *i*
would appear most frequently in the beginning of the sentence, which
would make the collocates to the left of *i* appear in the previous
sentence, which could be inaccurate because the previous sentence might
be expressing a different sentiment than the current sentence.

Log-likelihood test and effect sizes using log ratio were reported
between the two corpora. The differences between the two
subcorpora were uncovered using log-likelihood and it was reported whether the 
differences between the two subcorpora are statistically significant. In particular,
we looked at the log-likelihood statistic for *love* and *you* and
determined whether the LL statistic is greater than 3.84, which is the
cut-off point for statistical significance (p \< 0.05). The effect sizes
were reported using log ratio to see what the magnitude of the given
difference is.

## 4. Results

Frequency table (Table 2) including all of Adele’s four albums was created
in order to determine which tokens are most frequently used in
her lyrics. The pronoun *i* is the most frequent item in Adele’s corpus
of lyrics (AF = 749, RF = 0.052 per word). The pronoun *you* is the
second frequent item in Adele’s corpus of lyrics (AF = 569, RF = 0.039
per word). The noun and verb *love* is the fifteenth most frequent item
in Adele’s corpus of lyrics (AF = 157, RF = 0.011 per word).

<div align="center">

**Table 2:** Absolute and relative frequency of top 20 most frequent words in Adele’s
lyric corpus

| Token  | Frequency | Relative Frequency |
|:------:|:---------:|:------------------:|
| i      |       749 |              0.052 |
| you    |       569 |              0.039 |
| the    |       427 |              0.030 |
| me     |       370 |              0.026 |
| to     |       360 |              0.025 |
| it     |       305 |              0.021 |
| my     |       261 |              0.018 |
| and    |       255 |              0.018 |
| that   |       184 |              0.013 |
| your   |       183 |              0.013 |
| a      |       166 |              0.012 |
| be     |       164 |              0.011 |
| in     |       163 |              0.011 |
| i’m    |       159 |              0.011 |
| love   |       157 |              0.011 |
| of     |       141 |              0.010 |
| but    |       129 |              0.009 |
| like   |       127 |              0.009 |
| don’t  |       127 |              0.009 |
| on     |       126 |              0.009 |
| for    |       121 |              0.008 |
| just   |       119 |              0.008 |
| when   |       116 |              0.008 |
| let    |       116 |              0.008 |
| all    |       113 |              0.008 |
| we     |       109 |              0.008 |
| is     |       106 |              0.007 |
| so     |        99 |              0.007 |
| you’re |        88 |              0.006 |
| ain’t  |        87 |              0.006 |

</div>

Looking at Juilland’s D measure in Table 3, we see that all of the three
tokens have values close to 1, which signifies that we have evenly
dispersed tokens. Deviation of Proportions (DP) measure tells us that
all three tokens have DP close to 0, which signifies that we have evenly
dispersed tokens throughout the albums. Out of the three tokens, *love*
is the most unevenly distributed with the lowest Juilland’s D value and
the highest DP value, and *i* is the most evenly dispersed with the
highest Juilland’s D value and the lowest DP value.

<div align="center">

**Table 3:** Dispersion Measures for i, you and love

| Token |  AF | Per_10.4 | Carrolls_D2 | Rosengrens_S |  Lynes_D3 |        DC | Juillands_D |        DP |   DP_norm |
|:-----:|:---:|:--------:|:-----------:|:------------:|:---------:|:---------:|:-----------:|:---------:|:---------:|
| i     | 749 | 519.4175 |   0.9540649 |    0.9195357 | 0.9137127 | 0.9087672 |   0.9212488 | 0.2225919 | 0.2243971 |
| you   | 569 | 394.5908 |   0.9318796 |    0.8564299 | 0.8855290 | 0.8432097 |   0.8919461 | 0.2702648 | 0.2724565 |
| love  | 157 | 108.8766 |   0.8314623 |    0.6044490 | 0.6952716 | 0.5855981 |   0.7982397 | 0.4489744 | 0.4526154 |

</div>

We find collocates of *love*, which can be both noun and a verb in the
Adele’s two subcorpora using the MI statistic (3b-MI1(4), L5-R5, C4-NC4,
no filter applied), which is shown in Figure 1. Both subcorpora share
the collocates *ain’t*, *say*, *if*. The collocate *your* is a high
frequency collocate with *love* in the first subcorpus (albums *19* and
*21*) because of the strength of the color. The collocate *my* is a high
frequency collocate with *love* in the second subcorpus (albums *25* and
*30*). The nodes that are closer to the central nodes *love* have higher
MI values meaning that the strength of the association is higher. The
tokens *treat*, *bridge*, and *under* are some of the most strongly
related collocates with *love* in the first subcorpus. The tokens
*always*, *lasts*, and *again* are some of the most strongly related
collocates with *love* in the second subcorpus.

We find collocates of the pronoun *you* in the Adele’s two subcorpora
using the MI statistic (3b-MI1(4), L5-R5, C4-NC4, no filter applied),
which is shown in Figure 2. Both subcorpora share the collocates *why*,
*think*, *look*, *want*, and *where*. The collocate *don’t* is a high
frequency collocate with *love* in the first subcorpus (albums *19* and
*21*) because of the strength of the color. The collocates *love* and
*for* are high frequency collocates with *you* in the second subcorpus
(albums *25* and *30*). The nodes that are closer to the central nodes
*you* have higher MI values meaning that the strength of the association
is higher. The tokens *left*, *crazy*, *inside*, *remember* and *bless*
are some of the most strongly related collocates with *you* in the first
subcorpus. The tokens *home*, *fool*, and *patient* are some of the most
strongly related collocates with *you* in the second subcorpus.

<div align="center">

![Collocation network of love for two subcorpora (3b-MI1(4), L5-R5,
C4-NC4, no filter
applied)](collocation_analysis_files/figure-gfm/unnamed-chunk-13-1.png)

![Collocation network of you for two subcorpora (3b-MI1(4), L5-R5,
C4-NC4, no filter
applied)](collocation_analysis_files/figure-gfm/unnamed-chunk-14-1.png)

</div>

Finally, we calculate the log-likelihood and log ratio between Adele’s
first set of albums *19* and *21*, and the second set of albums *25* and
*30*. Table 4 shows us that *let*, *river*, *lea* (which is repeated in
Adele’s song “River Lea” in album *25*), *lord* and *miss* are top five
keywords with highest LL values when comparing Adele’s last two albums
(target corpus) and first two albums (reference corpus). Table 5 shows
us that *rumor*, *has*, *up*, *should* and *rolling* are top five
keywords with highest LL values when comparing Adele’s first two albums
(target corpus) and last two albums (reference corpus).

Table 6 shows that the log-likelihood of *love* is found to be
statistically insignificant between Adele’s first two albums (target
corpus) and last two albums (reference corpus) with LL of 1.34. The
log-likelihood of *you* is found to be statistically significant (with
LL \> 15.13, p \< 0.0001) between Adele’s first two albums (target
corpus) and last two albums (reference corpus) with LL of 18.80. The log
ratio is 0.27 for *love* and 0.53 for *you*. This means that *you*, our
statistically significant word, occurs between 1 to 2 times more
frequently in the target corpus (first two albums) than the reference
corpus (last two albums).

<div align="center">

**Table 4:** A keyness comparison between Adele’s last two albums (target corpus) and
first two albums (reference corpus)

| **Token** | **LL** | **LR** |
|:---------:|:------:|:------:|
|    let    | 65.16  |  2.69  |
|   river   | 46.96  |  6.04  |
|    lea    | 41.88  |  5.87  |
|   lord    | 31.73  |  5.47  |
|   miss    | 27.92  |  5.29  |
|  lights   | 25.38  |  5.15  |
|   hold    | 23.60  |  2.12  |
|   cruel   | 22.84  |  5.00  |
|   lows    | 20.31  |  4.83  |
|   pain    | 20.31  |  4.83  |
|   want    | 17.81  |  2.07  |
|    mmh    | 17.77  |  4.63  |
| sweetest  | 17.77  |  4.63  |
|   like    | 16.87  |  1.11  |
|   down    | 16.57  |  1.68  |
|   live    | 16.50  |  4.53  |
|   water   | 16.50  |  4.53  |
|   both    | 15.36  |  3.91  |
|  fooling  | 15.23  |  4.41  |
|   highs   | 15.23  |  4.41  |


**Table 5:** A keyness comparison between Adele’s first two albums (target corpus)
and last two albums (reference corpus)

| **Token** | **LL** | **LR** |
|:---------:|:------:|:------:|
|   rumor   | 92.16  |  7.11  |
|    has    | 37.04  |  3.76  |
|    up     | 27.92  |  1.92  |
|  should   | 27.41  |  3.87  |
|  rolling  | 25.68  |  5.26  |
|    he     | 24.86  |  4.57  |
| whenever  | 24.17  |  5.17  |
|    and    | 23.03  |  0.88  |
|    met    | 22.66  |  5.08  |
|   words   | 21.15  |  4.98  |
|    ay     | 19.64  |  4.87  |
|  forgive  | 19.64  |  4.87  |
|    as     | 19.58  |  2.82  |
|    you    | 18.80  |  0.53  |
|   take    | 18.23  |  2.55  |
|    had    | 18.18  |  1.92  |
|   head    | 18.13  |  4.76  |
|  enough   | 17.83  |  4.17  |
|  nothing  | 17.17  |  2.70  |
|   wish    | 17.17  |  2.70  |

**Table 6:** A keyness comparison between Adele’s first two albums (target corpus)
and last two albums (reference corpus) for love and you

| **Token** | **LL** | **LR** |
|:---------:|:------:|:------:|
|    you    | 18.80  |  0.53  |
|   love    |  1.34  |  0.27  |

</div>
    
## 5. Discussion

The collocation networks show that there are some shared and distinct
collocates for *love* and *you* for her two sets of albums. The shared
collocates for *love* was *ain’t*, *say*, and *if*, which suggests that
Adele is expressing her feelings towards the topic of love in her lyrics
for both songs, perhaps disappointment with love by saying “love ain’t”
what she expected to be or what people “say love” is supposed to be, and
perhaps a desire for a second-chance to remedy her mistakes by a
conditional word, *if*. The shared collocates for *you* is *why*,
*think*, *look*, *want*, and *where*, which suggests that Adele is
perhaps questioning why or where her subject of desire is at, and
discussing her feelings about her lover by using words like *think*,
*look*, and *want*.

Major findings are that the differences in keywords in Adele’s albums
are caused mainly by the repetition of song titles in her lyrics. For
instance, *river* and *lea* were two words with highest log-likelihood
greater than 40 and log ratio greater than 5, which means that they
appeared about 32 times more in her last two albums than the first two
albums. The reason behind this difference is possibly because Adele had
a song titled “River Lea” where she repeated “River Lea” many times in
her lyrics in her third studio album. Same phenomenon was observed when
comparing Adele’s first two albums (target corpus) to the last two
albums (reference corpus), because Adele had a song titled “Rolling in
the Deep” in album *21*, where the title was repeated many times in her
lyrics, and *rolling* had fifth highest log-likelihood value and log
ratio of 5.26, which means that it appeared about 32 times more in her
first two albums than the last two albums.

The difference in using *love* for her two sets of albums were not
statistically significant, but the difference in using *you* was
statistically significant, with *you* occurring about 1 to 2 times more
frequently in the first two albums than the last two albums. Possible
explanation for this is that the theme for *25* is Adele’s personal
reflection when she was 25 years old, where she experienced “nostalgia”
and “melancholia” about the passage of time and her fourth and latest
studio album, *30*, explores the theme of personal reflection, with
focusing on the feelings of “heartache, hope, and acceptance (Hiatt,
2015; Adele Wiki, 2022). This is in contrast to Adele’s first studio
album *19* which received praise from the critics for its exploration of
heartbreak and tragedy, and her subsequent album *21* which contained
mega-hits including”Someone Like You”, “Rolling in the Deep”, and “Set
Fire to the Rain”, where she explore themes of heartbreak and depression
resulting from her breakups (Morley, 2021; Adele Wiki, 2022). Therefore,
she transitioned from discussing her heartbreak and depression resulting
from her breakup in her earlier albums, which contains more frequent
references to her lover by using *you*, to exploring herself and her
personal feelings in her later albums. Since the difference in *love*
was not statistically significant, this suggests that *love* might be a
common theme in all four albums.

Strength of my analysis is that I was able to use all of the songs in
Adele’s studio albums, which means that our results are representative
of Adele’s entire musical career and her developments. Some limitations
of my analysis is that I did not tag part-of-speech for *love*, so we
did not differentiate between *love* being used as a noun or a verb.
Another limitation of my analysis is that I did not calculate dispersion
and frequency measures individually for each of her albums, which would
have given us information about whether the token of interest appeared
in every album of Adele, and how frequent and dispersed the token was in
each of the album of Adele. Other limitation is that I did not extract
sample sentences where *love* and *you* appeared, which would have given
information on what context the words were used in Adele’s lyrics.

In conclusion, there seems to be a change in the theme in Adele’s songs,
with her first two albums containing more references to her lover and
her last two albums containing more references to herself, but there
seems to be a common theme of love which persists throughout her four
albums.

## 6. Sources

Adele Wiki. Fandom. (2022). Retrieved October 2, 2022, from
<https://adele.fandom.com/wiki/Adele_Wiki>

Hiatt, B. (2015, November 3). Adele: Inside Her Private Life and
Triumphant Return. Rolling Stone.

Morley, L. (2021, April 26). How did adele become famous? how was she
discovered? - openmic. Open Mic UK. Retrieved October 2, 2022, from
<https://www.openmicuk.co.uk/advice/how-did-adele-become-famous-get-discovered/>

## 7. Appendix

Below are R code used for this report.

    library(readtext)
    library(quanteda)
    library(cmu.textstat)
    library(quanteda.textstats)
    library(dplyr)
    library(tidyr)
    library(knitr)
    library(ggraph)

    # Use readtext() function from readtext package to create a data.frame object
    rt1 <- readtext("album_19_1/*.txt",
      docvarsfrom = "filenames",
      docvarnames = c("type", "album", "song_rank")
    )

    rt2 <- readtext("album_21_2/*.txt",
      docvarsfrom = "filenames",
      docvarnames = c("type", "album", "song_rank")
    )

    rt3 <- readtext("album_25_3/*.txt",
      docvarsfrom = "filenames",
      docvarnames = c("type", "album", "song_rank")
    )

    rt4 <- readtext("album_30_4/*.txt",
      docvarsfrom = "filenames",
      docvarnames = c("type", "album", "song_rank")
    )

    # Make a corpus object
    album1_corpus <- corpus(rt1)
    album2_corpus <- corpus(rt2)
    album3_corpus <- corpus(rt3)
    album4_corpus <- corpus(rt4)

    rt_12 <- rbind(rt1, rt2)
    rt_34 <- rbind(rt3, rt4)
    rt_all <- rbind(rt1, rt2, rt3, rt4)

    albums_12_corpus <- corpus(rt_12)
    albums_34_corpus <- corpus(rt_34)
    all_albums_corpus <- corpus(rt_all)

    # Create tokens
    album1_tokens <- tokens(album1_corpus, include_docvars = TRUE, 
                            remove_punct = TRUE, remove_numbers = TRUE, 
                            remove_symbols = TRUE, what = "word")
    album1_tokens <- tokens_tolower(album1_tokens)

    album2_tokens <- tokens(album2_corpus, include_docvars = TRUE, 
                            remove_punct = TRUE, remove_numbers = TRUE, 
                            remove_symbols = TRUE, what = "word")
    album2_tokens <- tokens_tolower(album2_tokens)

    album3_tokens <- tokens(album3_corpus, include_docvars = TRUE, 
                            remove_punct = TRUE, remove_numbers = TRUE, 
                            remove_symbols = TRUE, what = "word")
    album3_tokens <- tokens_tolower(album3_tokens)

    album4_tokens <- tokens(album4_corpus, include_docvars = TRUE, 
                            remove_punct = TRUE, remove_numbers = TRUE, 
                            remove_symbols = TRUE, what = "word")
    album4_tokens <- tokens_tolower(album4_tokens)

    all_albums_tokens <- tokens(all_albums_corpus,
      include_docvars = TRUE,
      remove_punct = TRUE,
      remove_numbers = TRUE,
      remove_symbols = TRUE,
      what = "word"
    )

    albums_12_tokens <- tokens(albums_12_corpus,
      include_docvars = TRUE,
      remove_punct = TRUE,
      remove_numbers = TRUE,
      remove_symbols = TRUE,
      what = "word"
    )

    albums_34_tokens <- tokens(albums_34_corpus,
      include_docvars = TRUE,
      remove_punct = TRUE,
      remove_numbers = TRUE,
      remove_symbols = TRUE,
      what = "word"
    )

    # Combine Multi-word expressions
    album1_tokens <- tokens_compound(album1_tokens, 
                                      pattern = phrase(multiword_expressions))
    album2_tokens <- tokens_compound(album2_tokens, 
                                      pattern = phrase(multiword_expressions))
    album3_tokens <- tokens_compound(album3_tokens, 
                                      pattern = phrase(multiword_expressions))
    album4_tokens <- tokens_compound(album4_tokens, 
                                      pattern = phrase(multiword_expressions))

    all_albums_tokens <- tokens_compound(all_albums_tokens, 
                                      pattern = phrase(multiword_expressions))
    albums_12_tokens <- tokens_compound(albums_12_tokens, 
                                      pattern = phrase(multiword_expressions))
    albums_34_tokens <- tokens_compound(albums_34_tokens, 
                                      pattern = phrase(multiword_expressions))

    # Create a dfm object
    album1_dfm <- dfm(album1_tokens)
    album2_dfm <- dfm(album2_tokens)
    album3_dfm <- dfm(album3_tokens)
    album4_dfm <- dfm(album4_tokens)

    all_albums_dfm <- dfm(all_albums_tokens)
    albums_12_dfm <- dfm(albums_12_tokens)
    albums_34_dfm <- dfm(albums_34_tokens)

    # Extract docvars so we can attach them to our corpus_comp
    dv <- docvars(all_albums_dfm)

    # Create a corpus composition table
    corpus_comp <- ntoken(all_albums_dfm) %>%
      data.frame(Tokens = .) %>%
      mutate(Album = dv$album) %>%
      dplyr::group_by(Album) %>%
      summarize(Texts = n(), Tokens = sum(Tokens)) %>%
      janitor::adorn_totals()

    knitr::kable(corpus_comp, 
                  caption = "Corpus Composition of Adele's Four Studio Albums")

    # Next we'll create a **dfm** with proportionally weighted counts.
    # We will create another corpus for all the albums.
    prop_album1_dfm <- dfm_weight(album1_dfm, scheme = "prop")
    prop_album2_dfm <- dfm_weight(album2_dfm, scheme = "prop")
    prop_album3_dfm <- dfm_weight(album3_dfm, scheme = "prop")
    prop_album4_dfm <- dfm_weight(album4_dfm, scheme = "prop")

    prop_all_albums_dfm <- dfm_weight(all_albums_dfm, scheme = "prop")
    prop_albums_12_dfm <- dfm_weight(albums_12_dfm, scheme = "prop")
    prop_albums_34_dfm <- dfm_weight(albums_34_dfm, scheme = "prop")

    # Use textstat_frequency to calculate the frequencies for the entire 4 albums, 
    # for albums 1 and 2, and for albums 3 and 4.
    freq_df <- textstat_frequency(all_albums_dfm) %>%
      data.frame(stringsAsFactors = F) %>%
      dplyr::select(feature, frequency) %>%
      mutate(`Relative Frequency` = round(frequency / 14420, digits = 3)) %>%
      rename("Token" = "feature", "Frequency" = "frequency")

    kable(head(freq_df, n = 30), caption = "Absolute and relative frequency of 
    top 20 most frequent words in Adele's lyric corpus")

    # Now, we calculate dispersion tokens for our two dfm's
    dispersion_all_albums <- all_albums_dfm %>% dispersions_all()
    dispersion_albums_12 <- albums_12_dfm %>% dispersions_all()
    dispersion_albums_34 <- albums_34_dfm %>% dispersions_all()

    dispersion_i_you_love <- dispersion_all_albums %>%
      slice(1, 2, 15)

    kable(dispersion_i_you_love, 
          caption = "Dispersion Measures for i, you and love")

    # Now we create collocates!
    albums_12_love_collocates <- collocates_by_MI(albums_12_tokens, "love") %>% 
      filter(col_freq >= 4 & MI_1 >= 4)
    albums_34_love_collocates <- collocates_by_MI(albums_34_tokens, "love") %>% 
      filter(col_freq >= 4 & MI_1 >= 4)

    albums_12_you_collocates <- collocates_by_MI(albums_12_tokens, "you") %>% 
      filter(col_freq >= 4 & MI_1 >= 4)
    albums_34_you_collocates <- collocates_by_MI(albums_34_tokens, "you") %>% 
      filter(col_freq >= 4 & MI_1 >= 4)

    # Now, we create a graph for love and you
    net <- col_network(albums_12_love_collocates, albums_34_love_collocates)

    ggraph(net, layout = "stress") +
      geom_edge_link(color = "grey80", alpha = 0.75) +
      geom_node_point(aes(alpha = node_weight, size = 3, color = n_intersects)) +
      geom_node_text(aes(label = label), repel = T, size = 3) +
      scale_alpha(range = c(0.2, 0.9)) +
      theme_graph(base_family = "Helvetica") +
      theme(legend.position = "none")

    net <- col_network(albums_12_you_collocates, albums_34_you_collocates)

    ggraph(net, layout = "stress") +
      geom_edge_link(color = "grey80", alpha = 0.75) +
      geom_node_point(aes(alpha = node_weight, size = 3, color = n_intersects)) +
      geom_node_text(aes(label = label), repel = T, size = 3) +
      scale_alpha(range = c(0.2, 0.9)) +
      theme_graph() +
      theme(legend.position = "none")

    # Target: albums 3 and 4, Reference: albums 1 and 2
    albums34_v_albums12 <- keyness_table(albums_34_dfm, albums_12_dfm) %>%
      select(c(Token, LL, LR)) %>%
      slice(1:20)

    kableExtra::kbl(albums34_v_albums12, 
      caption = "A keyness comparison between Adele's last two albums 
      (target corpus) and first two albums (reference corpus)", 
      digits = 2, 
      linesep = "", 
      booktabs = T) %>%
      kableExtra::kable_styling(latex_options = "HOLD_position") %>%
      kableExtra::kable_classic()

    # Target: albums 1 and 2, Reference: albums 3 and 4
    albums12_v_albums34 <- keyness_table(albums_12_dfm, albums_34_dfm) %>%
      select(c(Token, LL, LR)) %>%
      slice(1:20)

    kableExtra::kbl(albums12_v_albums34, 
      caption = "A keyness comparison between Adele's first two albums 
      (target corpus) and last two albums (reference corpus)", 
      digits = 2, 
      linesep = "", 
      booktabs = T) %>%
      kableExtra::kable_styling(latex_options = "HOLD_position") %>%
      kableExtra::kable_classic()

    # LL and LR of love and you
    albums12_v_albums34_loveyou <- keyness_table(albums_12_dfm, albums_34_dfm) %>%
      select(c(Token, LL, LR)) %>%
      filter(Token == "you" | Token == "love")

    kableExtra::kbl(albums12_v_albums34_loveyou, 
      caption = "A keyness comparison between Adele's first two albums 
      (target corpus) and last two albums (reference corpus) 
      for love and you", 
      digits = 2, 
      linesep = "", 
      booktabs = T) %>%
      kableExtra::kable_styling(latex_options = "HOLD_position") %>%
      kableExtra::kable_classic()
