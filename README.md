# detection_random_domain_name_generation
In this project, three different language models: perplexity of bigram language model, K-L distance with bigram distribution and K-L distance with unigram distribution, are applied to detect random generated malicious domain names. We only focus on the domain name without contextual information. In addition, we do not need to figure out how the DGA works and the time to detect DGA is fast since all of the analysis is based on the domain name itself. The assumption of this approach is that DGA tends to not use the well-formed and pronounceable language words since the domains are generated randomly. Most of the registered domains are constructed by the legitimate words. Therefore, the DGA domain names will use characteristics with a different distribution as the legitimate domain names.
