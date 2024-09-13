# cl_st1_renata
Corpus Linguistics - Study 1 - Renata Lamberti

## Phase 2
### Results
Right-click on the link and choose `Open link in a new tab` to download the corresponding file.
- [CL_St_Ph2_Renata_Results.tar.gz](https://pucsp-my.sharepoint.com/:u:/g/personal/ra00341729_pucsp_edu_br/Ed1CYky7XSdBrI1DU1Az9F4Bfu9-dIAHR3WYZkv8zZ9rog?e=gB7EsB)

Proceed as follows to extract the files from the archive `CL_St1_Ph2_Renata_Results.tar.gz`

```
eyamrog@Rog-ASUS:/mnt/c/Users/eyamr/Downloads$ tar xzvf CL_St1_Ph2_Renata_Results.tar.gz
<omitted>
eyamrog@Rog-ASUS:/mnt/c/Users/eyamr/Downloads$ 
```

### Analysis of `words loading` and `factor score` in `examples`

#### examples_f1_neg_000006.txt
```
file = t032294
date = 2022-10-10
user = JennaEllisEsq
conversation = 107810042577943552
URL = https://truthsocial.com/@JennaEllisEsq/109146334490900260

word count = 26
words loading = 4
factor score = -4

BREAKING: No one believes PayPal. Ever wonder why errors always seem to only go 
one direction — AGAINST conservatives and free speech? @JackPosobiec today 
with more: 

Lemmas in this text that loaded on the factor:

breaking_nn 
conservative_nns 
free_jj 
speech_nn 
```



### Maintenance required in `wcount.py`

`NLTK` now requires `punkt_tab` instead of `punkt`

- From: `nltk.download('punkt')`
- To: `nltk.download('punkt_tab')`
