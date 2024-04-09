# learning-cicd
private notes/workflows to learn ci/cd


### How to add secrets

- Go to Settings
- Secrets and Variables
- Add a respository secret

add workflow_dispatch to enable manual actions startup(check secret.yaml file)

Check the io.yaml file on how to set output for jobs

To enable branch protection, go to -

1. Settings/branches/ add branch protection rule
2. branch name
3. require status check
4. enter the job name


Use ghapi.yaml to use github api