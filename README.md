# vscode-assets

This repository serves as a centralized public storage for static assets (images, GIFs, icons, and documentation resources) used across different **Cegid Peoplenet** Visual Studio Code extensions.

## Repository Structure

The assets are organized by project to maintain a clean workspace:

- `/common`: Shared branding, logos, and generic icons used by multiple tools (if necessary).
- `/peoplenet-ln4`: Visual resources, demos, and GIFs for the LN4 language extension (extension name as directory).
- `/...`: Resources for another VS Code extensions.

## How to use in READMEs

To reference these assets in other private or public repositories, use the GitHub **Raw** URL:

`https://raw.githubusercontent.com/<USER>/vscode-assets/main/<EXTENSION_NAME>/<RESOURCE_NAME>`

For Azure DevOps, the URL format should be:

`https://dev.azure.com/cegid/PS_Peoplenet/_apis/git/repositories/vscode-assets/items?path=/<EXTENSION_NAME>/<RESOURCE_NAME>&versionDescriptor.version=main&versionDescriptor.versionType=branch&$format=octetStream`

---
*Note: This is a resource-only repository. For source code, please refer to the specific extension projects.*
