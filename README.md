# Databricks Git folder debugging aids

## What is this repository?

This repository is built to help you resolve issues with Databricks Git folders (a.k.a. Repos, see [AWS doc](https://docs.databricks.com/aws/en/repos/)) and related features. 

**Customers** - Please explore debugging notebooks in `folder/`.

**Databricks Support team** - Please refer to the internal Repos Pre-ES guide.

## Repository contents

* `folder/`
    - Contains notebooks used for `sys.path` (importing) issues verification.
      These notebooks are placed in a subfolder to check for correct imports from
      neighboring folders.
    - `importing-notebook` ([link in GitHub](./folder/importing-notebook.ipynb))
        - Simplest notebook that checks imports. **Start here** for direct module import testing.
    - `workspace-file-access-with-udf` ([link in GitHub](./folder/workspace-file-access-with-udf.ipynb))
        - **Start here** for overall `sys.path`, Workspace files and importing issues diagnosis and data collection.
* `libraries/`
    - Contains files supporting the `folder/importing-notebook`

