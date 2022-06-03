# Systèmes de recommandations

Il s'agit d'un répertoire contenant le code en Python pour mon mémoire « Réalisation d’un système de recommandation à l’aide des graphes de connaissance » de Master 1 Langue et Informatique à Sorbonne Université. Ce mémoire est Sous la direction de Monsieur Vincent LULLY.

J'ai réalisé les Systèmes de recommandations dans 3 domaines : cusine, film et ville (tourisme). donc pour les 3 répertoires, chacun contient tous les codes et toutes les données déjà traitées dans un domaine.

# Démonstration 

Pour chaque domaine, il y a 3 systèmes de recommandations. 

Je vous montre un exemple, si vous aimez Lisbonne et Lille et vous n'aimez pas Lausanne, vous voulez trouver les villes qui sont potentiellement vous intéressées. Vous pouvez utiliser ``recommander(["Lisbonne","Lille"],["Lausanne"]) `` dans le systèmes créé avec les plongements générés par l'apporche RDF2vec.

Et Vous allez voir le résultat :
```
Je vous conseille de visiter les villes suivantes :


==================================================


Numéro 1 : Rotterdam
Pour plus de l'information, cliquez :  http://www.wikidata.org/entity/Q34370


Numéro 2 : Maputo
Pour plus de l'information, cliquez :  http://www.wikidata.org/entity/Q3889


Numéro 3 : Funchal
Pour plus de l'information, cliquez :  http://www.wikidata.org/entity/Q25444


Numéro 4 : Praia
Pour plus de l'information, cliquez :  http://www.wikidata.org/entity/Q3751


Numéro 5 : Rio_de_Janeiro
Pour plus de l'information, cliquez :  http://www.wikidata.org/entity/Q8678
```


# Ressources

Contenant aux plongements (embedding), vous pouvez trouver directement les plongements deja récupérés au format Word2vec dans chaque répertoire, ils sont sous format txt. Et pour les ressources originales qui sont trop volumineuses, vous pouvez cliquer sur

[Les plongments des Wikipedia générés par l'apporche PyTorch-BigGraph](https://dl.fbaipublicfiles.com/torchbiggraph/wikidata_translation_v1.tsv.gz)

[Les plongments des Wikipedia générés par l'apporche RDV2vec](http://data.dws.informatik.uni-mannheim.de/rdf2vec/models/Wikidata/4depth/skipgram)

[Les plongments des DBpedia générés par l'apporche RDV2vec](http://data.dws.informatik.uni-mannheim.de/rdf2vec/models/DBpedia/2015-10/4depth/skipgram)

