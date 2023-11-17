Fork of the gatk git for reference and adapting for running with para clarabricks given the documentation for that isn't always clear. The docs here include links to the current broad institute reference, gtf and known variant files which need to be built off of the same version of each other to ensure compatibility. It is therefore possible that updates to the grch38 refs are available but without a corresponding known reference they are not much use.

# gatk4-rnaseq-germline-snps-indels
Workflows for processing RNA data for germline short variant discovery with GATK v4 and related tools

### Requirements/expectations :
 - uBAM 

### Output :
 - A BAM file and its index.
 - A VCF file and its index. 
 - A Filtered VCF file and its index. 

 Runtime parameters are optimized for Broad's Google Cloud Platform implementation.
 For program versions, see docker containers.

### Important Notes :
- Runtime parameters are optimized for Broad's Google Cloud Platform implementation.
- The provided JSON is a ready to use example JSON template of the workflow. Users are responsible for reviewing the [GATK Tool and Tutorial Documentations](https://gatk.broadinstitute.org/hc/en-us/categories/360002310591) to properly set the reference and resource variables. 
- For help running workflows on the Google Cloud Platform or locally please
view the following tutorial [(How to) Execute Workflows from the gatk-workflows Git Organization](https://gatk.broadinstitute.org/hc/en-us/articles/360035530952).
- Relevant reference and resources bundles can be accessed in [Resource Bundle](https://gatk.broadinstitute.org/hc/en-us/articles/360035890811).

### Contact Us :
- The following material is provided by the Data Science Platforum group at the Broad Institute. Please direct any questions or concerns to one of our forum sites : [GATK](https://gatk.broadinstitute.org/hc/en-us/community/topics) or [Terra](https://support.terra.bio/hc/en-us/community/topics/360000500432).

### LICENSING :
 This script is released under the WDL source code license (BSD-3) (see LICENSE in
 https://github.com/broadinstitute/wdl). Note however that the programs it calls may
 be subject to different licenses. Users are responsible for checking that they are
 authorized to run all programs before running this script. Please see the docker
 page at https://hub.docker.com/r/broadinstitute/genomes-in-the-cloud/ for detailed
 licensing information pertaining to the included programs. 
