Baking acoustics on a local PC is an option that many customers utilize when scene sizes are small and getting familiar with the technology is the goal.  As scene sizes increase, using a service like Azure Batch will reduce the time it takes to complete a bake.

After creating a local bake directory via the Prepare Local Bake button, select the Download Local Bake Tools button to download the bake tools package and place the tools in the chosen local bake directory.

Once the tools and the configuration files are co-located in the local bake directory, execute the "RunLocalBake.bat" script to start a bake that runs serially on your local PC in a working directory matching the timestamp of the starting time for the bake. Upon completion of the bake process, an ACE file will be generated which needs to manually imported into the project content directory.  Consult the documentation on https://aka.ms/acoustics for more documentation about importing ACE files into a project.
