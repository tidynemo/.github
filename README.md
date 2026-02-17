# nemo-verse

This is the nemo-verse organization profile repository. Below is an overview of our key projects.

## 🐢 nemo - Tidy and Explore Bioinformatic Pipeline Outputs

[nemo](https://github.com/umccr/nemo) is an R package that contains the building blocks for parsing, tidying, and writing bioinformatic pipeline results in a more consistent structure.

**Key Features:**
- Traverses directories containing bioinformatic tool results
- Parses and tidies recognized files (data reshaping, normalization, column cleanup)
- Writes output in various formats (Apache Parquet, PostgreSQL, TSV, RDS)
- Extensible through child packages that define tool-specific schemas via YAML configuration files

**Links:**
- 📚 Documentation: https://umccr.github.io/nemo
- 📦 Conda package: https://anaconda.org/umccr/r-nemo
- 🔧 GitHub: https://github.com/umccr/nemo

## 🧬✨ tidywigits - Tidy WiGiTS Outputs

[tidywigits](https://github.com/umccr/tidywigits) is an R package that parses and tidies outputs from the [WiGiTS (hmftools)](https://github.com/hartwigmedical/hmftools) suite of genome and transcriptome analysis tools for cancer research and diagnostics, created by the Hartwig Medical Foundation.

**Key Features:**
- Parses outputs from the hmftools suite (WiGiTS tools)
- Tidies cancer genomics analysis results
- Supports multiple output formats (Apache Parquet, PostgreSQL, TSV, RDS)
- Comprehensive coverage of hmftools suite outputs

**Links:**
- 📚 Documentation: https://umccr.github.io/tidywigits
- 📦 Conda package: https://anaconda.org/umccr/r-tidywigits
- 🔧 GitHub: https://github.com/umccr/tidywigits

---

Both packages are part of the nemo-verse ecosystem for working with bioinformatic pipeline outputs in a tidy, reproducible manner.
