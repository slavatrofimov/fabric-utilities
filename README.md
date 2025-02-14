# Microsoft Fabric Utilities
This repository contains miscellaneous utilities to facilitate management and administration of Microsoft Fabric.

## [Fabric Capacity Metrics Long Term Retention](/Fabric%20Capacity%20Metrics%20Long%20Term%20Retention.ipynb)
This notebook can be used as a solution accelerator for importing summaries of Fabric Capacity metrics from the Fabric Capacity Metrics App for long term storage and analysis. The data is imported at the granularity of one record per item per operation type per hour. The data is stored in a Fabric Lakehouse for long-term storage and analysis.

## [Moving Power BI Semantic Models in Large Semantic Model Storage Format Across Regions](/Large%20Semantic%20Model%20Storage%20Format%20assessment.ipynb)
This notebook is intended to help you identify semantic models that use the large semantic model storage format across your Fabric tenant when you are considering moving certain workspaces to capacities in different regions. Furthermore, this notebook offers remediation suggestions to help you complete the cross-region move.

## [Analyze OneLake Storage Usage in a Fabric Workspace](/Analyze%20OneLake%20Storage%20Usage.ipynb)
This notebook recursively traverses folders and files in a given Workspace or OneLake path, returns a list of all files within the path broken out by path segment and provides a few basic summaries about the number and size of files.
