CI=true : tests will run only once.
-- --coverage

npm run build: generates an optimized folder for production

surge: deployment of static websitesn

prettier - check thar code

npx prettier --check "\*_/_.js"

master and develop - protected branches
master branch - code that will be deployed to prod

in case of npm, we don't push the node modules folder to the repository, we install them

CODEOWNERS - defines who owner certain files in your reporsitory. this person will be required on reviews when files matching the pattern are changed.
Read more: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
