# dataset info

Japanese dialog act analysis/people-related information detect dataset

We conducted a labeling work on a spoken Japanese dataset (I-JAS) for the text classification, which contains 53 interview dialogues of two-way Japanese conversation that discuss the participants' past present and future. Each dialogue is 30 minutes long. From this dataset, we selected the interview dialogues of native Japanese speakers as the samples. Given the dataset, we annotated sentences with **16 labels [updated!!]**. The labeling work was conducted by native Japanese speakers who have experience with data annotation.


    labels[updated!!] :

    ssi:self-subjective information
    osi:others-subjective information
    soi:self-objective information
    ooi/kn:others-bjective information
    op:other-plan
    sp:self-plan
    qu:question
    ap:apology
    th:thanking
    cc:topic changing/closing
    ag:agreement
    ds:disagreement
    re:request
    pr:proposal
    su:summarize/reformulate
    th:other



training:I-JAS_JJJ01-10-I, I-JAS_JJJ11-20-I, I-JAS_JJJ21-30-I, I-JAS_JJJ31-39-I

development: I-JAS_JJJ43-50-I

testing:I-JAS_JJJ51-57-I


Please kindly cite this dataset when you use it.

Changzeng Fu, Chaoran Liu, Carlos Toshinori Ishi, & Hiroshi Ishiguro. (2021). JPS-daprinfo: A Dataset for Japanese Dialog Act Analysis and People-related Information Detection (Version v1.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.4590253

    @dataset{changzeng_fu_2021_4590253,
      author       = {Changzeng Fu and
                      Chaoran Liu and
                      Carlos Toshinori Ishi and
                      Hiroshi Ishiguro},
      title        = {{JPS-daprinfo: A Dataset for Japanese Dialog Act 
                       Analysis and People-related Information Detection}},
      month        = mar,
      year         = 2021,
      publisher    = {Zenodo},
      version      = {v1.0},
      doi          = {10.5281/zenodo.4590253},
      url          = {https://doi.org/10.5281/zenodo.4590253}
    }

link for I-JAS (original): https://chunagon.ninjal.ac.jp/static/ijas/about.html
