# Replace Default with lc1 in .JSON files

# Replace ports in controllers:

/home/ubuntu/work/emco-base/scripts/integration_test/inputs/data/full_api_test/controller_registration/test_postControllerRegistration.json
16:                      "port": 9031,
32:                      "port": 9031,


Replace 30441 everywhere with 9031

/home/ubuntu/work/emco-base/scripts/integration_test/inputs/data/full_api_test/controller_registration/test_putControllersByName.json
16:            "port": 9031,
32:            "port": 9031,




emco-base/scripts/integration_test/inputs/data/full_api_test/controller_registration/test_postTrafficControllerRegistration.json

16:                      "port": 9048,
32:                      "port": 9048,


Replacing 30483 with 9048
