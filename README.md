# cl_st1_renata
Corpus Linguistics - Study 1 - Renata Lamberti

## Phase 3
### Results
Right-click on the link and choose `Open link in a new tab` to download the corresponding file.
- [CL_St_Ph3_Renata_Results.tar.gz](https://pucsp-my.sharepoint.com/:u:/g/personal/ra00341729_pucsp_edu_br/EeHXICjmK4BGlFduzPkig1cBtlZxODWsplqU5ST1g25cPQ?e=AM2JL9)

Proceed as follows to extract the files from the archive `CL_St1_Ph3_Renata_Results.tar.gz`:

```
eyamrog@Rog-ASUS:/mnt/c/Users/eyamr/Downloads$ tar xzvf CL_St1_Ph3_Renata_Results.tar.gz
<omitted>
eyamrog@Rog-ASUS:/mnt/c/Users/eyamr/Downloads$ 
```

### Maintenance required in `wcount.py`

`NLTK` now requires `punkt_tab` instead of `punkt`

- From: `nltk.download('punkt')`
- To: `nltk.download('punkt_tab')`
