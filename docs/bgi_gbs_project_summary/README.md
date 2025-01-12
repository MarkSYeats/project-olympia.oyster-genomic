### Project summary folder provided by BGI.

All files (except this one) and sub-directories were provided by BGI. 

Here's a list of informative files:

- ```Data.stat.xls```: Spreadsheet detailing number of reads generated, number of bases sequenced, GC percentage, Q20 percentage, and Q30 percentage for each individual.

- ```Genotype.xls```: Spreadsheet providing consensus sequences of genomic regions containing SNPs across individuals; effectively provides a genotype for each individual.

- ```SNP.readme_en.txt```: A readme file describing the columns in the ```SNP.stat.csv``` file.

- ```SNP.stat.xls```: Spreadsheet summarizing total number of SNPs identified in each individual, as well as breakdown of homozygous/heteroyzgous SNP composition in each individual.

- ```genotype.noref.readme_en.txt```: A readme file describing the columns in the ```Genotype.xls``` file.

- ```nj_tree.out.tre.png```: A low resolution PNG image of phylogenetic tree of all individual oysters, generated using the Neighbor-Joining method.

- ```nj_tree.out.tre.svg```: A scalable SVG of phylogenetic tree of all individual oysters, generated using the Neighbor-Joining method. Can be used to create higher resolution image (compared to the ```nj_tree.out.tre.png``` file) of the phylogenetic tree. The tree was generated using the software [TreeBeST](https://github.com/Ensembl/treebest) with the following parameters: ```nj -b 100 snp.fa```    
    ````nj````: build neighbour-joining tree, SDI, rooting    
    ```-b 100```: bootstrapping times
