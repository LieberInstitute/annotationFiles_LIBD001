# SPEAQeasy

`SPEAQeasy` is a Nextflow-based Scalable RNA-seq Pipeline for Expression Analysis and Quantification. It's documented in detail at http://research.libd.org/SPEAQeasy/.

These files are a combination of version-controlled files from the `SPEAQeasy` GitHub repository at https://github.com/LieberInstitute/SPEAQeasy/tree/master/Annotation and files that get created when running `SPEAQeasy`.

## Initial file creation

```bash
rsync -avh /dcl01/lieber/ajaffe/Nick/SPEAQeasy/Annotation /dcs04/lieber/lcolladotor/annotationFiles_LIBD001/SPEAQeasy
date
# Wed Aug 25 15:59:51 EDT 2021

## Update permissions
chgrp lieber_lcolladotor -R .
find . -type d | xargs chmod 775
find . -type f | xargs chmod 764
```