# ripekeys
RIPE keywords

Having been inspired by Christopher Marcum's methodology (http://chrismarcum.com/wikka.php?wakka=PublicASRMethods) for visualising the top keywords in the American Sociological Review over the past decade, I produced a similar figure for the Review of International Political Economy.

I extracted the raw data - all published articles in RIPE from 1994 to today, with full bibliometric data - from Web of Science, 895 records in total from January 1, 1994 to September 24, 2017. Keywords were extracted from the ID and DE fields in the database, respectively the author and publisher keywords. However, keywords are only systematically (if at all) available from January 1, 2010, which is then naturally the lower bound for my timeline and dataset. I structured the data, recording year and keyword with my cleaning and stemming (punctuation and immediate analogs). This gave a list of 2371 non-unique, 1150 unique keywords. The top 50 keywords were truncated to the nearest-lowest frequency tie (n=8) (as per Marcum). This gave a final top list of 42 keywords, the 97% quantile of the frequency distribution.

In addition, I visualised the relative frequency of the top 10 keywords (count>19) over time. Here, I gathered the year, keyword, annual count and annual global percentage (as a fraction of all RIPE keywords in the given year) of each of the top10. This data was loaded and visualised in R with also using ggplot.

All code and visualisations is available in this repository.
