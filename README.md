# cl_st1_renata
Corpus Linguistics - Study 1 - Renata Lamberti

## Phase 2
### Results
Right-click on the link and choose `Open link in a new tab` to download the corresponding file.
- [CL_St_Ph2_Renata_Results.tar.gz](https://pucsp-my.sharepoint.com/:u:/g/personal/ra00341729_pucsp_edu_br/Ed1CYky7XSdBrI1DU1Az9F4Bfu9-dIAHR3WYZkv8zZ9rog?e=gB7EsB)

Proceed as follows to extract the files from the archive `CL_St1_Ph2_Renata_Results.tar.gz`:

```
eyamrog@Rog-ASUS:/mnt/c/Users/eyamr/Downloads$ tar xzvf CL_St1_Ph2_Renata_Results.tar.gz
<omitted>
eyamrog@Rog-ASUS:/mnt/c/Users/eyamr/Downloads$ 
```

### Analysis of `words loading` and `factor score` in `examples`

The results of `examples.sh` seem to be consistent. In `examples_f1_neg_000006.txt`, `words loading` = 4 because there are 4 lemmas the loaded on the factor. In `examples_f1_neg_000007.txt`, `words loading` = 5 because there are 5 lemmas the loaded on the factor. Notice that the posts were written by distinct users.

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

The examples of **factor 1, positive pole** are polarised by texts of user `maxjett12` who appears to make heavy use of the same set of 24 hashtags. Those hastags stand out in the dimension because of repeated use despite the fact that the text in the posts being different from each other.

##### examples_f1_pos_000001.txt
```
file = t060272
date = 2024-05-07
user = maxjett12
conversation = 108319249994754560
URL = https://truthsocial.com/@maxjett12/112400228788246078

word count = 99
words loading = 24
factor score = 23

The FBI improperly performed warrantless searches on more than a 
quarter-million U. S. citizens in a single year, a 127-page court filing 
unsealed Friday by the Foreign Intelligence Surveillance Court ( FISA ) , in 
the latest instance of FBI abuse of its powers to make the FBI conducted more 
than 278 , 000 illegitimate queries on citizens, including some George Floyd 
protestors and more than nineteen thousand donors to a Congressional campaign, 
in the 12 months ending November 2021 . **#xteam_h** **#dt47_h** 
**#truthtrain_h** **#phpnews_h** **#tcd_h** **#nightshift_h** 
**#lilypadlounge_h** **#fhfnews_h** **#rpn_h** **#ratpack_h** **#twgrp_h** 
**#thefungicrew_h** **#5dnews_h** **#wtpafu_h** **#trump2024_h** 
**#murchmadness_h** **#ncswic_h** **#maga2024_h** **#maga_h** **#fbj_h** 
**#truth_h** **#trumpwon_h** **#wethepeople_h** **#trump_h** 

Lemmas in this text that loaded on the factor:

5dnews_h 
dt47_h 
fbj_h 
fhfnews_h 
lilypadlounge_h 
maga2024_h 
maga_h 
murchmadness_h 
ncswic_h 
nightshift_h 
phpnews_h 
ratpack_h 
rpn_h 
tcd_h 
thefungicrew_h 
trump2024_h 
trump_h 
trumpwon_h 
truth_h 
truthtrain_h 
twgrp_h 
wethepeople_h (secondary)
wtpafu_h 
xteam_h 

```

##### examples_f1_pos_000002.txt
```
file = t060270
date = 2024-05-07
user = maxjett12
conversation = 108319249994754560
URL = https://truthsocial.com/@maxjett12/112400509393007470

word count = 97
words loading = 24
factor score = 23

Senator John Judas Thune of South Dakota, the #2_h Republican in the Senate and 
career politician voted to confirm these six Biden cabinet nominations: Merrick 
Brian Garland, of Maryland, attorney general Gina Marie Raimondo, of Rhode 
Island, secretary of James Austin, of Georgia, secretary of John Blinken, of 
New York, secretary of Paul Montgomery Buttigieg, of Indiana, secretary of 
Louise Yellen, of California, secretary of friends like Judas Thune who needs 
enemies? **#xteam_h** **#dt47_h** **#truthtrain_h** **#phpnews_h** **#tcd_h** 
**#nightshift_h** **#lilypadlounge_h** **#fhfnews_h** **#rpn_h** **#ratpack_h** 
**#twgrp_h** **#thefungicrew_h** **#5dnews_h** **#wtpafu_h** **#trump2024_h** 
**#murchmadness_h** **#ncswic_h** **#maga2024_h** **#maga_h** **#fbj_h** 
**#truth_h** **#trumpwon_h** **#wethepeople_h** **#trump_h** 

Lemmas in this text that loaded on the factor:

5dnews_h 
dt47_h 
fbj_h 
fhfnews_h 
lilypadlounge_h 
maga2024_h 
maga_h 
murchmadness_h 
ncswic_h 
nightshift_h 
phpnews_h 
ratpack_h 
rpn_h 
tcd_h 
thefungicrew_h 
trump2024_h 
trump_h 
trumpwon_h 
truth_h 
truthtrain_h 
twgrp_h 
wethepeople_h (secondary)
wtpafu_h 
xteam_h 

```

### Maintenance required in `wcount.py`

`NLTK` now requires `punkt_tab` instead of `punkt`

- From: `nltk.download('punkt')`
- To: `nltk.download('punkt_tab')`
