# qSTORM
Quantitative profiling of STOichiometry by Resolvable Mass tags

## tutorial
```
cd examples/
python ../scripts/pcp_data_paraser.py ../database/uniprot_sprot_HUMAN_160504.fasta > results.txt
python ../scripts/processing_data.py results.txt ../database/molecular_weight.txt > data.txt
python ../scripts/find_the_stoichiometry.py data.txt ../database/molecular_weight.txt > stoichiometry.txt
`
