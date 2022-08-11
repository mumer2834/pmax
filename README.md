This repo contains ansible plabybooks to perform the following tasks on Dell PowerMax arrays:

-> Create volumes in bulk

-> Add the created volumes in relevant storage groups

Download the repo. Edit the input_file, and add the required information under vol_info in the following format. The fields are explained below: 

-> vname: The volume name

-> vsize: The volume size specified in GBs, this must always be in GBs

-> array: name of the array

-> sg_name: The name of the storage group as present on the array
