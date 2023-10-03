# @onediversified/DIV.Template.Crestron.SIMPL

This is a project template for Crestron SIMPL Windows code.

## Install and Usage

1. Create a new project and select `OneDiversified/DIV.Template.Crestron.SIMPL` as the repository template. 

2. Clone the newly created project to your system.

3. Open a command prompt in the cloned directory and run `npm update`

4. Next run `npm install` to update any files in the base template.

5. Update the package.json `name`, `version number`, `description`, and `author` fields as well as any web link with project specific info.

6. Update the contents of the `PROJECT-README.md` file with appropriate project info. Delete any sections that are not pertinent to your project type and and make sure to update all links, names, etc. where appropriate. Go through this file line-by-line to ensure all values get updated/removed correctly.

7. Delete this `README.md` file and then rename `PROJECT-README.md` to `README.md`

## Troubleshooting

### Failed to authenticate with GitHub Packages service

Make sure to login with `npm login --scope=@onediversified --registry=https://npm.pkg.github.com` before running the `npm update` command

You will need to create a personal access token in GitHub and assign it permissions to read / write packages. The token is used as your password during the `npm login` process.