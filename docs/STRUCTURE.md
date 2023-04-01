# Project folder structure

```
📦src
 ┣ 📂ann
 ┃ ┣ 📂src
 ┃ ┃ ┣ 📂main
 ┣ 📂ci             -> Continuous integration
 ┣ 📂cr-mixer       -> 
 ┃ ┃ ┣ 📂apidoc
 ┃ ┃ ┣ 📂users
 ┃ ┃ ┗ 📂utilities
 ┣ 📂config
 ┃ ┣ 📂v1
 ┃ ┃ ┗ 📜index.js - Documentation about Swagger Tags for API V1
 ┃ ┣ 📂v2
 ┃ ┃ ┗ 📜index.js - Documentation about Swagger Tags for API V2
 ┃ ┣ 📜i18n.js - Configuration for multiple languages supports
 ┃ ┗ 📜index.js - 
 ┣ 📂docs - General documentations
 ┃ ┣ 📜knowErrors.md
 ┃ ┣ 📜recommendedLinksToStudy.md
 ┃ ┣ 📜vsCodeFrameworks.md
 ┃ ┗ 📜vsCodeRecommendedExt.md
 ┣ 📂libs - Libraries for common usages
 ┣ 📂locales - Translations for messages and errors
 ┣ 📂routes - Endpoints for API versions (one file for each version)
 ┃ ┣ 📂v1
 ┃ ┃ ┗ 📜index.js - Version 1
 ┃ ┗ 📂v2
 ┃ ┃ ┗ 📜index.js - Version 1
 ┣ 📂schemas - YML Files for schemas
 ┃ ┣ 📂generic - Generic schemas usable for multiple API versions
 ┃ ┗ 📂v1 - Schemas for V1
 ┗ 📜app.js - 
```
