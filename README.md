# Databricks Git folder debugging aids

## What is this repository?

This repository is built to help you resolve issues with Databricks Git folders (a.k.a. Repos, see [AWS doc](https://docs.databricks.com/aws/en/repos/)) and related features. 

**Customers** - Please explore the repository contents to learn how to use the debugging notebooks.

**Support team** - First refer to the Repos Pre-ES evaluation guide
which is the current
source of information on how to handle Repos related issues. That guide should lead you back 
to this repository in certain cases.


## Repository contents

* `folder/`
    - Contains notebooks used for `sys.path` (importing) issues verification.
      These notebooks are placed in a subfolder to check for correct imports from
      neighboring folders.
    - `importing-notebook` ([link in GitHub](./folder/importing-notebook.ipynb))
        - Simplest notebook that checks imports. **Go there** for direct module import testing.
    - `workspace-file-access-with-udf` ([link in GitHub](./folder/workspace-file-access-with-udf.ipynb))
        - **Go there** for overall `sys.path`, Workspace files and importing issues diagnosis and data collection.
* `libraries/`
    - Contains files supporting the `folder/importing-notebook`

