# The CNV-UI
This collection of scripts uses Bokeh to create portable, interactive plots for improved visualisation and interpretation of copy-number and loss-of-heterozygosity (CNV-LOH) results. It was originally designed for use for GATK outputs but can be used for any copy-number data if coerced into the proper JSON format.

## Getting Started

## Usage

cnvloh2json.py: Called via main function. Requires GATK CNV denoised counts file, GATK CNV modeled segments file, and can optionally take GATK's LOH hets.tsv file.

```
python cnvloh2json.py \
--cnvloh-dir /path/to/output_dir/ \
--counts-file /path/to/input_dir/sample_name.counts.tsv.denoisedCR.tsv \
--modelsegs-file /path/to/input_dir/sample_name.modelFinal.seg \
--hets-file /path/to/input_dir/sample_name.hets.tsv
```

## Deployment

Additional notes on how to deploy this on a live or release system. Explaining the most important branches, what pipelines they trigger and how to update the database (if anything special).

### Branches

Currently just the one

## Additional Documentation and Acknowledgments

Acknowledge people here
