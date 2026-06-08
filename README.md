# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## `test` Lightning Web Component

This project contains a minimal LWC located at `force-app/main/default/lwc/test/`. It renders static text inside an SLDS box and is exposed to App, Record, and Home pages.

### Changelog

**v2 (current)**

- **Display text:** changed from `test` to `test case` in `test.html`.
- **API version:** lowered from `67.0` to `66.0` in `test.js-meta.xml` and in `sfdx-project.json` (`sourceApiVersion`) so the component deploys to the target org, which supports a maximum API version of 66.0.

**v1 (initial)**

- Created the `test` LWC bundle (`test.html`, `test.js`, `test.js-meta.xml`) displaying the text `test` at API version 67.0.


## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
