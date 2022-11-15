
# About easydb
I share some processed dbs here which I think useful.

# Getting Started
`Baidu Netdisk` is enough.

# GTEx eQTL full statistics of 48 tissues
Download of [GTEx eQTL full statistics](https://www.gtexportal.org/home/datasets) is chargeable.  
So I download BESD files from [GCTA](https://yanglab.westlake.edu.cn/data/SMR/GTEx_V8_cis_eqtl_summary.html), and convert them to txt files, for saving money. 
They look like:
```
SNP           Chr   BP      A1      A2      Freq    Probe    Probe_Chr  Probe_bp  Gene  Orientation     b         SE         p
rs554008981   1     13550   A       G       NA   ENSG00000227232 1      14363     WASH7P    -        0.580378   0.359124   0.106074
rs201055865   1     14671   C       G       NA   ENSG00000227232 1      14363     WASH7P    -       -0.480434   0.442039   0.277099
rs201327123   1     14677   A       G       NA   ENSG00000227232 1      14363     WASH7P    -       -0.0541866   0.287179   0.850339
``` 
Note that they are in hg19  
[Baidu Netdisk link](https://pan.baidu.com/s/1Q9z7RV4jNdGOshdxOI1uRA?pwd=xvz8)

# BBJ GWAS
[BBJ GWAS](http://jenger.riken.jp/en/result) are from different papers and their format are not in consistency.  
So I merge then to [1000g EAS ref](https://alkesgroup.broadinstitute.org/LDSCORE/), remove MHC region, and unifiy their format. 
They look like:
```
CHR   POS   SNP        A1   A2      FRQ                  BETA                   SE                 P                N
1   751343  rs28544273  A  T   0.140717059373856   -0.0507868871873078   0.0283610544163367   0.0733372206268269   202308
1   751756  rs143225517  C  T   0.139962390065193   -0.0506247620315559   0.0282495043254527   0.0731236087846628   202308
1   752566  rs3094315  A  G   0.842458665370941 0.044740991635669   0.0244692517100391   0.0674808889339898   202308
``` 
Note that they are in hg19  
[Baidu Netdisk link](https://yanglab.westlake.edu.cn/data/SMR/GTEx_V8_cis_eqtl_summary.html)


# Gene range
Some times I want to check the range of a gene.  
So I download GFF3 files from [GENCODE](https://www.gencodegenes.org/human/) and extract these information.  
They look like:
```
chr,start,end,gene_id,gene_type,gene_name,level
1,11869,14409,ENSG00000223972.5_5,transcribed_unprocessed_pseudogene,DDX11L1,2
1,14404,29570,ENSG00000227232.5_5,unprocessed_pseudogene,WASH7P,2
1,29554,31109,ENSG00000243485.5_11,lncRNA,MIR1302-2HG,2
1,34554,36081,ENSG00000237613.2_6,lncRNA,FAM138A,2
```
Note that `gencode.v40_gene.csv` is hg38, `gencode.v41lift37_gene.csv` is hg 19  
[Baidu Netdisk link](https://pan.baidu.com/s/13RvdH_8EUZzyvyWwzojwOw?pwd=5odb)

# Feedback and comments
Add an issue or send email to zhanghaoyang0@hotmail.com