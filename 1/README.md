# Input

Given a sample files whose column names are in `colnames.txt`

```sh
GENE_ID	PREFIX1/ST1_1038_1_BM_0	PREFIX2/ST1_1033_1_BM_1	PREFIX1/ST1_1053_1_BM_0 ...
```

and a sample manifest file where the data looks like:

```sh
biosample_id original_sample_name
1 ST1_1053_1_BM
2 ST1_1038_1_BM
3 ST1_1033_1_BM
...
```

# Output

We want the output to look like

```sh
GENE_ID	2	3	1 ...
```
