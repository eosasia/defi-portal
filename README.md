# defi-portal

## JSON Instructions

Add projects with the following required data:

- `id` : this needs to be exactly the same as provided by the following package if claim is supported https://github.com/EOS-Nation/defi

- `title`: represent the name of the project

- `link`: the site's URL

- `group`: link that redirects to the project's community

- `description`: description of the project. Can't be too long.

- `image`: for this, upload a png image in the `./logos` folder and use the same link format seen from the other objects `https://raw.githubusercontent.com/eosasia/defi-portal/main/logos/LOGO_NAME.png`

- `subInfos`: this is an Array of tags for the project.
  - `{"label": 'audited'}` supports an additional info `link` that redirects to the audit report.
  - `{"label": 'msig'}` indicates the contract was MSIGed and it also supports the `link` property that redirects to the keys section of the contract on EOSX.io.
  - `{"label": 'higher risk'}` this is the tag that **MUST** be given if the projects wasn't audited or msiged.

## Additional

It would be helpful to add the translation information for each project using the following properties:

- `chineseDesc`: add the Chinese Description of the project

- `koreanDesc`: add the Korean Description of the project
