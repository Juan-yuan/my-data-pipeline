# my-data-pipeline
### Python

```bash
# 1. Install or update python to version 3.10
# 2. cd to the directory where requirements.txt is located
# 3. Optional: activate your virtualenv
# 4. Run the following command to install required python packages
pip3 install -r requirements.txt
```

### Serverless
```bash
# Install serverless plugin prune
# 1. Install with npm
sudo npm install --save-dev serverless-prune-plugin
# 2. Alternatively, install with the Serverless plugin command (Serverless Framework 1.22 or higher)
cd ${PROJECT_FOLDER}
sls plugin install -n serverless-prune-plugin
# Install serverless python requirements
# https://github.com/UnitedIncome/serverless-python-requirements
cd ${PROJECT_FOLDER}
sls plugin install -n serverless-python-requirements
# Install serverless dotenv plugin
sudo npm i -D serverless-dotenv-plugin
```