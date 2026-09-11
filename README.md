# Anchore Security CVE 5 Control Dataset

> [!WARNING]  
> The data in this repo is generated from https://github.com/anchore/dataset-security-cve5-upstream-snapshot.  Do not raise pull requests for changes to data here.  If you are requesting a change to data today, https://github.com/anchore/vulnerability-index-spec-files is currently the place for that.  Eventually it will transition to https://github.com/anchore/dataset-security-cve5-enriched
>

The data in this repo serves as the control dataset for the Anchore curation efforts of the [upstream CVE 5 dataset](https://github.com/CVEProject/cvelistV5/).

The dataset is generated off of specific snapshots of the upstream data stored at https://github.com/anchore/dataset-security-cve5-upstream-snapshot.

Currently curation efforts are focused on a few elements from the json files (description, affected products, references links, and disputes/rejection reasons), so only those fragments are extracted here.  This simplifies the records looked at for curation purposes and reduces the chance of merge conflicts arising from changes to other data upstream.  It is intended that the actual curation efforts will then happen over at https://github.com/anchore/dataset-security-cve5-enriched which is a fork of this control set; however, the current place to request changes for CVE5-derived data is at https://github.com/anchore/vulnerability-index-spec-files.