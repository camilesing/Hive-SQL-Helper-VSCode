# 1 Prerequisites

- npm
- vsce

# 2 Build

- Run ```npm install --dependencies``` to install dependencies.
- Run ```vsce package``` to build extension.

# 3 If you want add or update grammar rule
- Edit `*SQL.g4`
- Run `npm run antlr4ts_spark && npm run antlr4ts_hive` generate for ts code then move to src directory. 
- Copy ./gen ts file to src directory
