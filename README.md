# CEUR-WS-LOD

It's an effort to convert existing data from [CEUR-WS.org](http://ceur-ws.org/) to Linked Data dataset. The work is done in the framework of [Semantic Publishing Challenge 2015](https://github.com/ceurws/lod/wiki/SemPub2015) co-located with [ESWC 2015](http://2015.eswc-conferences.org/) conference.

## Semantic Publishing Challenge 2015's Tasks

### Task 1

The goal is to extract information from a set of HTML tables of contents published in the CEUR-WS.org workshop proceedings. The extracted information is expected to answer queries about the quality of these workshops, for instance by measuring growth, longevity, etc.

The source code is available in [ceur-ws-crawler]( https://github.com/ailabitmo/ceur-ws-lod/tree/master/ceur-ws-crawler) folder.

### Task 2

The goal is to extract information from the textual content of the papers (in PDF). That information should provide a deeper understanding of the context in which it was written. In particular, the extracted information is expected to answer queries about authors’ affiliations and research institutions, research grants and funding bodies, and related works (papers presented in the same venue, addressing similar issues, etc.).

The source code is available in [ceur-ws-pdfs](https://github.com/ailabitmo/ceur-ws-lod/tree/master/ceur-ws-pdfs) folder.

## How to cite

If you want to (re)use our work in the next challenge or our project, feel free to do that, it's open source after all :) But please cite our paper:

```
﻿@Inbook{Kolchin2015,
  author="Kolchin, Maxim and Cherny, Eugene and Kozlov, Fedor and Shipilo, Alexander and Kovriguina, Liubov",
  editor="Gandon, Fabien and Cabrio, Elena and Stankovic, Milan and Zimmermann, Antoine",
  chapter="CEUR-WS-LOD: Conversion of CEUR-WS Workshops to Linked Data",
  title="Semantic Web Evaluation Challenges: Second SemWebEval Challenge at ESWC 2015, Portoro{\v{z}}, Slovenia, May 31 - June 4, 2015, Revised Selected Papers",
  year="2015",
  series = {Communications in Computer and Information Science},
  volume = {568},
  publisher="Springer International Publishing",
  pages="142--152",
  isbn="978-3-319-25518-7",
  doi="10.1007/978-3-319-25518-7_12",
  url="http://dx.doi.org/10.1007/978-3-319-25518-7_12"
}
```

## License

The source code and all data is licensed under the [MIT License](https://github.com/ailabitmo/ceur-ws-lod/blob/master/LICENSE).
