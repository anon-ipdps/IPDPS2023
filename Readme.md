## File names and their descriptions are provided below:

1. **Exp.1-configs_ecephys.txt** - List of all ecephys configurations/chunk shapes tested for Exp.1
2. **Exp.1-configs_ophys.txt** - List of all ophys configurations/chunk shapes tested for Exp.1
3. **Exp.1-ophys_writes.txt** - Details from generating or writing ophys files using configurations in Exp.1. 'FAILED' indicates the configuration did not complete writing. The file sizes indicate very little variability across configurations.
4. **Exp.1-ecephys_writes.txt** - Details from generating or writing ecephys files using configurations in Exp.1
5. **Exp.2-configs_ecephys.txt** - List of all ecephys configurations/chunk shapes tested for Exp.2. Configuration number 93 - 96 represent baseline configuration options using uncompressed data and chunking.
6. **Exp.2-configs_ophys.txt** - List of all ophys configurations/chunk shapes tested for Exp.2. Configuration number 70 - 72 represent baseline configuration options using uncompressed data and chunking.
7. **Exp.2-ophys_writes.txt** - Details from generating or writing ophys files using configurations in Exp.2. The file sizes indicate very little variability across configurations.
8. **Exp.2-ecephys_writes.txt** - Details from generating or writing ecephys files using configurations in Exp.2
9. **Exp.2-ecephys_comprRatio.txt** - Lists computed compression ratios for different algorithms across chunk sizes for ecephys data, in Exp.2.
10. **Exp.2-ecephys_reads.txt** - Lists the median read times (from multiple trials) for each configuration, across all three uses cases for ecephys Exp.2. Also, provides the ranks of read times and compromises within every use case and span. Configurations are sorted by increasing order of read times for every use case and spans in the time dimension (t). Failed configurations were removed prior to ranking.
11. **Exp.2-ophys_reads.txt** - Lists the median read times (from multiple trials) for each configuration, across all three uses cases for ophys Exp.2. Also, provides the ranks of read times and compromises within every use case and span. Configurations are sorted by increasing order of read times for every use case and spans in the (t, x, y) dimension. Failed configurations were removed prior to ranking.
