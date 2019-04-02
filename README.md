# CORGi x Docker

A Docker take on [CORGi](https://github.com/zstephens/CORGi). 

__Requirements:__
- [ ] Matplotlib 
- [ ] Bokeh 
- [ ] local install of BLAST
- [ ] SAMTools
- [ ] IGV


__Arguments:__
```
python corgi.py \
 -r reference.fa
 -b input.bam
 -c chromosome
 -p start & end coordinates
 -o outputDir/
 --skip-igv skip IGV screenshot
 --skip-bam skip read extraction
```

__Example:__
```
python corgi.py -r hg38.fa -b my.bam -c chr1 -p 1000 2000 -o myOut/
```

__ToDo__

- [ ] Update `Dockerfile` with dependencies 
- [ ] Check if selected tool versions work
- [ ] iter8
