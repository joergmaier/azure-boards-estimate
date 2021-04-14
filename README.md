# Update 2021-04-15: This is currently a WIP, based on [@cschleiden's original extension](https://github.com/cschleiden/azure-boards-estimate/tree/2e71a099f82e2db6c02526c06936e3a0eccc3799).

# Azure Boards Estimate

[![Build & Deploy](https://github.com/hangy/azure-boards-estimate/actions/workflows/buildAndDeploy.yml/badge.svg)](https://github.com/hangy/azure-boards-estimate/actions/workflows/buildAndDeploy.yml)

## Contributing

If you want to send a PR I'll gladly review and merge it.

### Developing and Testing

<span style="color: green">To test your work, first [follow these steps to set up a DevOps marketplace publisher account](https://docs.microsoft.com/en-us/azure/devops/extend/publish/overview?view=azure-devops) (if you already have an account move on).

1. Run `npm run package-dev` and upload the package as a private extension to your Azure DevOps publisher account
    > Note: You may need to add a directory called `build` to the project root when running the script. The output of the `package-dev` script is there.

-   Be sure to update the `manifest.json` to use your publisher's ID before running the script.

2. Install the private extension on your Azure DevOps oragnization and test your changes.

## Upgrading to current version

When upgrading from the first version, you need to approve additional OAuth scopes:

<img src="https://user-images.githubusercontent.com/2201819/55303550-bc25c780-53fb-11e9-9379-0a64e3fb1014.png" width="400px" />
