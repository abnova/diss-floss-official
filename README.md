diss-floss-official
===================

## Description

Research software for quantitative analysis of open source software ecosystem using structural equation modeling. Implements reproducible research framework for data collection, analysis and reporting results, using `R` statistical language and environment.

Related information can be found in the repository's wiki at https://github.com/abnova/diss-floss/wiki.

## Citation

Please cite this software as follows:

Blekh, A. (2014). Research software for quantitative analysis of open source software ecosystem using structural equation modeling. Version 1.0.2. [Software] Retrieved from https://github.com/abnova/diss-floss-official. doi:10.5281/zenodo.13143

[![DOI](https://zenodo.org/badge/7586/abnova/diss-floss-official.svg)](http://dx.doi.org/10.5281/zenodo.13143)

## License

MIT License

## Installation Notes

Path to the *project's home directory*, where it's installed should be specified in R environment file, either system-wide (requires corresponding permissions), or, better, local (file ".Renviron" in user's home directory), as follows:

```bash
DISS_FLOSS_HOME = <path to project home directory>
```

Successful import of open source software repositories' data and startup companies data requires specifying corresponding data sources' credentials as values of environment variables. This also should be done via R environment file, preferably the same ".Renviron" file, as above:

```bash
# SourceForge Research Data Archive (SRDA)
SRDA_USER  = <SRDA user name>
SRDA_PASS  = <SRDA password>

# CrunchBase
CB_API_KEY = <CrunchBase API key>
```
