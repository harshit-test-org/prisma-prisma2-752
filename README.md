# Introduction

Reproduction for https://github.com/prisma/prisma2/issues/752

## Steps

1. Clone the repo
2. Run `prisma2 lift save` to see first error
3. add `@relation` directive to relatedGames field and validate the datamodel (you can use Prisma extension for vscode) to see the second error
