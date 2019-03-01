# eslint-config-axonteam
This is the global eslint config for all Axonteam javascript projects.  
This configuration is not meant to be permissive, however, it aims to be fairly strict to guarantee consistent code style.  

The philosophy is to comply to the linter when writing the code. It helps you writing cleaner and more *efficient* code. If there is something you really don't want to do like the linter says, you *explicitly* disable the rule or the line. This way, we make sure to reduce errors as much as possible, and that if you choose to ignore a rule you're fully aware.  

All team projects should be using this configuration, however, everyone is welcome to use it.  

## Installations
This package is availabe on npm [here](https://www.npmjs.com/package/@axonteam/eslint-config-axonteam).  
Install this package with `npm install @axonteam/eslint-config-axonteam` or `yarn add @axonteam/eslint-config-axonteam`.  
Make sure to have eslint already installed in your project.  
Now simply create a `.eslintrc.json` file and add the following: `"extends": "@axonteam/eslint-config-axonteam"`.  


### Contributions
Make sure to PR any rule that could be added using the samecode style idea. Nothing can ensure the pull request will be accepted but contribution is always welcome.   
