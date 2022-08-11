This repo contains ansible plabybooks to perform the following tasks on Dell PowerMax arrays:

-> Create volumes in bulk

-> Add the created volumes in relevant storage groups

Download the repo. Edit the input_file, and add the required information under vol_info in the following format. The fields are explained below: 

-> vname: The volume name

-> vsize: The volume size specified in GBs, this must always be in GBs

-> array: name of the array

-> sg_name: The name of the storage group as present on the array

In "create_vol_pmax.yml" file, add path to your Dell EMC ansible collections against "ANSIBLE_COLLECTIONS_PATHS"

In the "inc_create_vol_pmax.yml" file, Copy and paste a new "set_fact" module for every array in your enviornment.
