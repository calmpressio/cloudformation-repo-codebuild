# Cloudformation template:

## Specs

- Autocreate / autodelete Log Group with logretention
- Source Github, asks token to access private repos OR Source Codecommit (autocreaste repo with RetainOnDelete)
- Buildspec autodetect
- node_modules cache enabled
- Enviroment latest ubuntu, Large (15 GB RAM, 8 VCPUs)
- Envs to ask CDK Project name
