# annotationFiles_LIBD001

Common annotation files we re-use in projects

## Internal

JHPCE location: `/dcs04/lieber/lcolladotor/annotationFiles_LIBD001`

## Set permissions

```bash
find . -type d | xargs chmod g+s
chmod o+rx -R .
```


### FUSION TWAS reference files

```bash
rsync -rltgvh --chown=:lieber_lcolladotor /dcs04/lieber/lcolladotor/BrainSEQ_LIBD001/brainseq_phase2/twas/reference_hg38/LDREF_hg38/ /dcs04/lieber/lcolladotor/annotationFiles_LIBD001/fusion_twas_LDREF_hg38/
mv /dcs04/lieber/lcolladotor/BrainSEQ_LIBD001/brainseq_phase2/twas/reference_hg38/LDREF_hg38 /dcs04/lieber/lcolladotor/BrainSEQ_LIBD001/brainseq_phase2/twas/reference_hg38/LDREF_hg38_original
ln -s /dcs04/lieber/lcolladotor/annotationFiles_LIBD001/fusion_twas_LDREF_hg38 /dcs04/lieber/lcolladotor/BrainSEQ_LIBD001/brainseq_phase2/twas/reference_hg38/LDREF_hg38
```