# cesm2_on_arc4
usually CESM2 has supported and unsupported platforms as part of the repository infrastructure.
Currently the University of Leeds HPC system (ARC3 and ARC4) use a batch scheduler called "SGE" and thus CESM is unaware of how to submit jobs.
the current working practice is for users to indicate no batch scheduler and then to write their own SGE scripts for submission.

this project is aiming to train CESM2 in the art of SGE submission and then commit back to their trunk after comleting their validation suite.

The optional method for running CESM2 is to edit some XML files and place then in the ${USER}/.cime directory. 
Those are files named: config_batch.xml, config_macine.xml and config_compiler.xml
Examples are vailable in the repo source code at:
   cime/config/scripts/ withthe same names
   
TBC
   
# end of doc
