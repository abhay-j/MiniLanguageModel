# MiniLanguageModel

- This project is an attempt to implement my own large (small) language model.
- The resouces I am using to learn and implement this project are:
- - [Vizuara.ai](https://youtube.com/playlist?list=PLPTV0NXA_ZSgsLAr8YCgCwhPIJNNtexWu&si=nTvRa4IjmgpZRVvK) has a series of lectures on youtube that walk you through the process of building a language model from scartch.
- - The textbook used in the course is [Build a Large Language Model](https://www.amazon.com/Build-Large-Language-Model-Scratch/dp/1633437167/ref=sr_1_1?dib=eyJ2IjoiMSJ9.q3WeOkx6696LPZ7jiBJZnw89-QuZspcIsdQYa5mAp6ItUgF4esAZ5_mt4qyhI_EKsWRL5yzjFwtf4ot4PBto4xZDtYt0C_X5XruVP42d3IpoeQY18BpJ53Gln6fLreLx2v4QEr7cutenp1w-uIKObwdBRDbIq4z2NhXL1DKq1ZNxNORG2Wqr4RrFnLAChuQj1fXDa3L7bEdzGif6JXldqJGFleB5NrotXdff2Wrka4c.QSzOMmLSnQjvxZhYG0RExfttl5s_TUk4DURIxBLGsag&dib_tag=se&hvadid=739148786151&hvdev=c&hvexpln=67&hvlocphy=1027217&hvnetw=g&hvocijid=97073064143075459--&hvqmt=e&hvrand=97073064143075459&hvtargid=kwd-2298649989310&hydadcr=16406_13457168&keywords=building+llms+from+scratch&mcid=20e075892e5d3fa6bbf5a3bf182f6967&qid=1743623045&sr=8-1) by [Sebastian Raschka](https://sebastianraschka.com/).

### Things that I have implemented so far:

- A basic [Tokenizer](https://github.com/abhay-j/MiniLanguageModel/blob/main/SimpleTokenizer.ipynb), the vocabulary for tokenization is created using 'The Prophet' by Kahlil Gibran.
- Learnt how to tokenize the input text using [Byte Pair Encoding](https://github.com/abhay-j/MiniLanguageModel/blob/main/BytePairEncoding.ipynb) algorithm from TikToken
- Learnt what vector embeddings and positional embeddings are and implemented a simple [data pre-processing](https://github.com/abhay-j/MiniLanguageModel/blob/main/DataPreProcessingV1.ipynb) pipeline to create input embeddings for the llm.
- Implemented a simplified version of [attention](https://github.com/abhay-j/MiniLanguageModel/tree/main) mechanism with out trainable weights
- Implemented [Self-attention](https://github.com/abhay-j/MiniLanguageModel/blob/main/SelfAttention.ipynb) with trainable Query, Key, Value weights
- Implemented [Causal Attention](https://github.com/abhay-j/MiniLanguageModel/blob/main/CausalAttention.ipynb) with Dropouts
- Implemented a [Multi-head Attention class]
