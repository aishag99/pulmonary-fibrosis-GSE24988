# pulmonary-fibrosis-GSE24988

GSE24988
what does the .CEL file contain?
The unzipped .CEL files contain the raw microarray intensities straight from the scanner for one array (one sample) per file. inside the .CEL file is a big table of probe-level measurements: Each probe has coordinates on the chip (x,y) and an intensity value.there's also metadata: scanner settings, dates, etc.For Affymetrix arrays, a “gene” is measured by a set of probes (probe set). So CEL = probe-level, while expression matrix = summarized gene/probeset-level.
