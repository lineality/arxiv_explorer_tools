#### arxiv_explorer_tools
https://medium.com/@GeoffreyGordonAshbrook/search-with-non-generative-ai-d0a3cc77164b


# Arxiv Explorer Tools

alpha version of tool to run locally to inspect daily arxiv articles for topics of interest

- runs locally
- uses gguf local embedding models that should be broadly compatible with cpu hardware
- adjustable and customizable with a variety of vector-distance measures:
-- adjustable thresholds per measure
-- adjustable overall threshold
- saves a json of search-match article data
- saves html of search-match article data

## Best performance appears to be: 
- Very approximately on average as times and file-sizes vary.
1. BM25 2 sec
2. Weighted Match 5 sec
3. Embedding Model: 5 min
4. TF-IDF 10 min


## Weighted Match is very portable and configurable.
- arxiv_tool_minimal_weighted_match_vN.ipynb
