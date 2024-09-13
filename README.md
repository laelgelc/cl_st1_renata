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

#### examples_f1_neg_000007.txt
```
file = t034973
date = 2023-11-11
user = JewelsJones
conversation = 107834595014675536
URL = https://truthsocial.com/@JewelsJones/111389357957191503

word count = 97
words loading = 5
factor score = -4

1 . **police_car_light_e** **police_car_light_e** **police_car_light_e** 
Exciting news alert! Nashville is currently being taken by storm! A vibrant 
group of America First, freedom-loving patriots, proudly calling themselves 
#littermates_h, are making their mark! You know what they say, If you can ' t 
beat them, join them! Well, guess what? You can do just that! Get ready for the 
incredible Turdstock ' 23 , broadcasting LIVE from the fantastic Redneck 
Riviera, @rnrbarnas. Although tickets are sold out, don ' t fret, because we ' 
ll be live-streaming everything straight from @rnrbarnash! Brace yourself for 
an electrifying lineup featuring the incredible talents of @Catturd2 and 
@JohnRich, with a mind-blowing performance by Big$Rich 

Lemmas in this text that loaded on the factor:

live_jj 
news_nn 
patriot_nns 
police_car_light_e 
storm_nn (secondary)

```


### Maintenance required in `wcount.py`

`NLTK` now requires `punkt_tab` instead of `punkt`

- From: `nltk.download('punkt')`
- To: `nltk.download('punkt_tab')`
