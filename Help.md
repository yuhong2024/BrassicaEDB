# How to use

**1 Home**

**2 Browse**

**3 Search**

* 3.1 Gene Expression
* 3.2 Gene Homologous
* 3.3 Gene eFP-seq
* 3.4 Gene Regulatory Network
* 3.5 Gene Pantranme

* 3.6 Gene Alternative Splicing

**4 Analysis**

* 4.1 Deseq2
* 4.2 WGCNA

* 4.3 GO enrichment
* 4.4 KEGG enrichment

**5  Tools**

* 4.1 qPrimer
* 4.2 Seq-fetch
* 4.5 Blast
* 4.6 Jbrowse

## 1 Home

* **The Top Menu**

This is the navigation bar at the top of the BrassicaEDB, which contains Gene Feature (by six *Brasscia* species), Search(by Gene Expression, by Interspecific Homologous, by eFP-seq, by TF Regulatory Network, by Co-expression Network, by Alternative Splicing), Tools(qPrimer, Seq fetch, Go Enrichment, KEGG Enrichment, Blast, Jbrowse), Analysis, Download, More module

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092159089.png" width="100%" />

* **Main page**

Quick search for a gene to obtain all the data profiles of the gene in the database, supporting genes of six *Brassica* species

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092235764.png" width="100%" />

* **Statistical information**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092235446.png" width="100%" />

* **Module introduction**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182020131.png" width="100%" />

* **Result table**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092235397.png" width="100%" />

> On this page, result contains 5part
>
> In Basic Information,  including chromosomes, start and end sites, Arabidopsis homologous gene, common name and description
>
> In Gene Structure,  contains the structure of the gene
>
> In Functional Information, GO, KEGG, kinase, and PFAMs information can be obtained
>
> In Protein Information, physicochemical properties of the protein corresponding to the gene can be obtained

## 2 Browse

* **Summary**

Summary contains the data information of each module in the database

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092208421.png" width="100%" />



* ***Brassica*. L introduction**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092206490.png" width="100%" />

* **Species information**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182020525.png" width="100%" />

## 3 Search

The Search included analysis of 2,992 transcriptome data from 178 items in six brassica species, They are Transcriptome Expression, Interspecific Homologous ologous, eFP-seq, TF Regulatory Network, Co-expression Network, Alternative Splicing: Users can click to enter the corresponding module, select species and input corresponding genes to obtain analysis results.

* **Module introduction**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202501092205927.png" width="100%" />

### 3.1 Gene Expression

In `Gene Expression` module, 2992 transcriptome data of 178 projects in six brassica species were evaluated by 1. Quality control, 2. Trimming, 3. Mapping, 4. Counting, obtained the expression amount of each gene in each transcriptome data.

> First select the species you are looking for(red box 1), such as choosing `Brassica napus`
>
> Enter genes in the Genes field, or submit a list of genes. Below are examples of gene ids for the respective species(red box 2), for example, select `Bna1`, `Bna2` and `Bna3`
>
> Select the project you want to find in the selection(red box 3), here we select `Project`. And then click `Submit` to get the results.

* **Search part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021530.png" width="100%" />

> User can get the TPM expression of the input genes(red box 4)
>
> Click on the display page to switch between different display pieces of the presentation data(red box 5). User can download the image by clicking `Download` in the upper right corner(red box 5)
>
> In the final table contains the homologous genes of the input gene in the other five species(red box 6). By clicking on species, the corresponding gene is automatically filled into the gene field, such as `Brassica carinata`(red box 7). Similarly, clicking on the item of the species corresponding to the selected gene will automatically fill the item bar, such as `Project`. Finally, click `Submit` to get the expression data

* **Results part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021519.png" width="100%" />

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021747.png" width="100%" />

### 3.2 Gene Homologous

In `Interspecific Homologous` module, a total of 1,046,324 pairs of homologous genes between *Arabidopsis thaliana* and six species of *Brassica* L. were obtained through comparison and analysis, among which there were 23,629 direct homologous genes in six species of *Brassica* L.

> By entering or submitting a list of genes in the Genes field(red box 1). Take for example the `Bna1`, `Bna2` and `Bna3`

* **Search part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021071.png" width="100%" />

> The homologous gene information of the input gene in *Arabidopsis thaliana* and *Brassica* L. can be obtained by clicking `Submit`(red box 2)

* **Rusult part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021377.png" width="100%" />

### 3.3 Gene eFP-seq

In `eFP-seq` module, we conducted transcriptome data analysis on 103 tissue periods of brassica napus, and obtained the corresponding TPM value. The vector map of the expression pattern of selected genes was displayed through the tissue represented by the pictograms of dynamically colored plants, and the gene expression pattern could be visually displayed at the tissue level.

> User can enter the gene ID of *Brassica napus* in the gene input field(red box 1). Take for example the `BnaA01G0000100ZS`

* **Search part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021299.png" width="100%" />

> Click `Submit` to get the tissue expression profile of this gene(red box 2)

* **eFP map**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021321.png" width="100%" />



### 3.4 Gene Regulatory Network

In `Gene Regulatory Network` module, we collected Arabidopsis transcription factor members in PlantTFDB, and identified a total of 26781 transcription factor members in 58 transcription factor families of six species of *Brassica* L.. And transcriptome data were used to predict the transcription factor regulatory networks of six species. At the same time, we used the same data to conduct weighted gene co-expression regulatory network analysis to obtain the coexpression regulatory network of core genes, and then merged the two gene networks to obtain the transcription factor-coexpression regulatory network, while combining the homology data between species to obtain the gene regulatory network of six species, providing a direction for gene regulation research.

> First select the species you want to query(red box 1). For example, choose `Brassica napus`
>
> Next enter the gene id of the query(red box 2). Such as `Bna1`
>
> Then click `Submit` to get the result

* **Search part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182021175.png" width="100%" />

> In the result, the homologous gene of the input gene in *Brassica* L. can be obtained(red box 3)
>
> Click on the species name in the card to get the regulatory network of that species(red box 4)
>
> `BrassicaL` is a common regulatory network of *Brassica* L.(red box 5)
>
> The table contains the transcription factor-target gene relationship(red box 6)

* **Result part**







### 3.5 Gene Pantranme

In the `Gene Pantranme module`, we conducted homologous comparison among the genomes of each brassica species collected, and obtained homologous gene information among each genome of each species, providing clues for the evolution of each species.

>

* **Search part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022458.png" width="100%" />

>

* **Result part**





### 3.6 Gene Alternative Splicing

In the `Alternative splicing module`, we conducted variable splicing analysis for six brassica species, and found a total of 143,688 genes with variable splicing, and obtained a total of 29,527,576 variable splicing events in different tissues and processes. At the same time, we found that the homologous genes of 17,311 genes were variably spliced in all *Brassica* L.

> First select the species you want to query(red box 1). For example, choose `Brassica napus`
>
> Next enter the gene id of the query(red box 2). Such as `Bna1`
>
> Then click `Submit` to get the result

* **Search part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022922.png" width="100%" />

> In `General Results`, user can switch to a alternative splicing event by clicking on the event's name(red box 3)
>
> The first part is the details of the alternative splicing event(red box 4)
>
> The image below are the PSI values under organization and processing respectively(red box 5)
>
> In `Expression Results`
>
> Users can obtain sequences of different transcripts of the gene(red box 6)
>
> And the expression levels of each transcript under different tissues and treatments(red box 7)

* **Result part**

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022848.png" width="100%" />

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022102.png" width="100%" />

## 4 Analysis

### 4.1 Deseq

According to the input expression matrix and the sample classification file, Deseq analyzed the differential genes in the modified expression file.



### 4.2 WGCNA

WGCNA analyzed the gene co-expression regulatory network according to the phenotypic data of the corresponding samples with the significance of the input gene expression matrix.



### 4.3 GO enrichment

GO enrichment checks the input genes for enrichment of the genetic ontological entries in the gene collection and outputs the results into an easy-to-view display image

> Select the genome in `Select Species`(red box 1)
>
> Paste the gene list in the sequence box or upload the gene list file(red box 2)
>
> Click `Submit` to get results

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022035.png" width="100%" />

> Results of GO enrichment analysis.
>
> Switch the category of GO by clicking BP, MF and CC above(red box 3), and click `Download` in the upper right to download(red box 4)
>
> The dot plot and bar plot of GO enrichment analysis results(red box 5)



### 4.4 KEGG enrichment

KEGG enrichment will analyze the input genes for their role in metabolic pathways and signal transduction pathways, and output the results into easy-to-view display images

> Select the genome in `Select Species`(red box 1)
>
> Paste the gene list in the sequence box or upload the gene list file(red box 2)
>
> Click `Submit` to get results.

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022814.png" width="100%" />

> Results of KEGG enrichment analysis(red box 3), click `Download` in the upper right to download(red box 4)
>
> The dot plot and bar plot of KEGG enrichment analysis results(red box 5)



## 5 Tools

### 4.1 qPrimer

The qPrimer pis a versatile Python toolset designed for the design, verification, annotation, and visualization of qPCR primers, aiding researchers in optimizing genetic analysis and PCR workflows.

> Paste the sequence to be queried in the sequence box below(red box 1) or submit a genetic sequence file(red box 2)
>
> Modify parameters on the Parameter Settings
>
> Click `Submit` to get results.

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022890.png" width="100%" />

>

### 4.2 Seq-fetch

Seq-fetch can obtain the gDNA, CDS, PEP and Promoter sequences of the corresponding genes through the input genes, the selected species and the promoter length

> Select the genome in `Select Species`(red box 1)
>
> Enter the promoter length in box(red box 2)
>
> Enter the name of the output(red box 3)
>
> Paste the gene list or upload the gene list file to be extracted(red box 4)
>
> Click `Submit` to get results

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182022056.png" width="100%" />

> Switch the category by clicking gDNA, cds, pep, promoter(red box 3), and click `Download` in the below to download(red box 4)



### 4.3 Blast

Blast retrieves similar data from a selected sequence database based on sequence similarity of input genes and outputs the results. The 40 genome assemblies were provided, their cds, protein were used to construct the blast library.

> Select the species in the species box(red box 1) and select the form of comparison(red box 2)
>
> Paste the sequence to be queried in the sequence box below(red box 3) or submit a genetic sequence file(red box 4)
>
> Click `Submit` to get results.

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182023010.png" width="100%" />

>



### 4.4 Jbrowse

Jbrowse can visually display genomes in the database, annotate files, compare results and other data. The 40 genome assemblies were provided

> User clicks the circle in front of the genome assembly to select the genome(red box 1)
>
> Then in the Jbrowser, the local track file can be uploaded in Track module(red box 2)

<img src="https://cdn.jsdelivr.net/gh/LmtBeyul/swu1019.Beyul/202412182023232.png" width="100%" />