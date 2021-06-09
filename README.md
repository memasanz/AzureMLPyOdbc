AzureMLPyOdbc
=============

This notebook demonstrates how to use pyodbc within a compute instance to check
for connectivity. After that is established, values are then placed into
key-vault for safe keeping.

After connectivity is established, a computer cluster can be created to leverage
pyodbc. This requires building a custom image. The notebook and links in the
notebook walk through that process.

Finally a training experiment is created an results are printed in the logs.
