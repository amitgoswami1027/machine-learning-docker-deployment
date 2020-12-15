# Deploying Machine Learning Models
### Environment Varible in CircleCI
* KAGGLE_USERNAME=
* KAGGLE_KEY=
* PIP_EXTRA_INDEX_URL= https://<gemfurt_token>.pypi.fury.io/<gemfury_username>
* HEROKU_API_KEY = 257a8cba-5a27-4c05-95aa-2c5f51a521af
* HEROKU_APP_NAME =

### DIFFERENTIAL TESTS
* Type of test that compares the difference in execution from one version to another version of model when the inputs are same.
* Sometime differential tests are also called back-to-back testing.
* Suppose we forgot to include one pre-processing steo in the code or add the incorrect feature and other test will pass but the predictions that is made will change, so differential test are to catch these type of problems. 



