Until the API is implemented, the app is attempting to retrieve the kyc-kyb info from the 
static file below hosted on github.
https://raw.githubusercontent.com/UkrainianSoftware/orion.mobile-qa-blobs/feature/xm-1131-kyb-mock-packets/kyb-mock-json-body/qa/get_basic_info_with_kyb.json


In order to test the mobile logic scenarios, you should follow these steps
1. Get read-write access to the repository with mock data 
https://github.com/UkrainianSoftware/orion.mobile-qa-blobs.git. Please contact Alex D. or 
Ivan C. 
2. clone the experimental branch (that would be `master` or `main` in future) `git clone 
-b feature/xm-1131-kyb-mock-packets 
https://github.com/UkrainianSoftware/orion.mobile-qa-blobs.git`
3. edit the `.../kyb-mock-json-body/qa/get_basic_info_with_kyb.json` file according to the 
desired scenario. You can copy some of them from this directory 
https://github.com/UkrainianSoftware/orion.mobile-qa-blobs/tree/feature/xm-1131-kyb-mock-packets/kyb-mock-json-body
4. `git commit` the file changes and `git push` the branch
5. restart the mobile app


Happy testing.
