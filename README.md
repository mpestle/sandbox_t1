# Rakeiora Workflow Template: `Germline`

[![Rakeiora](http://rakeiora.ac.nz)](http://rakeiora.ac.nz)

A template workflow for Rakeiora - this is workflow 1 - Germline

## Usage

- the sandbox and portal will put retrieved input data into the /resources directory
- ensure any datafiles/results that you want to inspect are created in the results directory
- the sandbox and portal copy /results and /logs to the jupyter hub for your inspection
- any environment settings ($TMP, JVM parameters, etc) go into the config/env file
- Note that this workflow would not be acceptable in Rakeiora, since it produces
vcf.gz files in the results directory. So this workflow would probably be rejected -
it should do the actual analysis and only place the results in the results directory.
