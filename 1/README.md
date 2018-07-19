# Input

Given a sample files whose column names are in `colnames.txt`

```sh
GENE_ID	PREFIX1/Jack2_0	PREFIX2/Mary1_1	PREFIX1/Jack1_0 ...
```

and a sample manifest file where the data looks like:

```sh
biosample_id original_sample_name
1 Jack1
2 Jack2
3 Mary1
...
```

# Output

We want the output to look like

```sh
GENE_ID	2	3	1 ...
```
