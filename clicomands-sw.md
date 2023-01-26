SHOPWARE Developer Version
```
       _
      | |
   ___| |__   ___  _ ____      ____ _ _ __ ___
  / __| '_ \ / _ \| '_ \ \ /\ / / _` | '__/ _ \
  \__ \ | | | (_) | |_) \ V  V / (_| | | |  __/
  |___/_| |_|\___/| .__/ \_/\_/ \__,_|_|  \___|
                  | |
                  |_|

Using .psh.yaml.dist 

Available commands:


default:
 - cache                                                  clears all caches
 - demo-data                                              creates a demo data set
 - fix-cs                                                 fix code style in src folder
 - init-composer                                          
 - init-database                                          
 - init-shopware                                          initialization of shopware
 - init-test-databases                                    
 - init                                                   Install database and dependencies with default data set
 - install                                                Everything from "init" + demo data generation + administration build/deploy
 - mysql                                                  Open the mysql cli
 - static-analyze                                         Run static code analysis on core
 - unit                                                   execute unit tests and generate coverage information

docker:
 - docker:ssh-mysql                                       
 - docker:ssh-root                                        
 - docker:ssh                                             
 - docker:start                                           
 - docker:stop                                            

administration:
 - administration:analyze-bundle                          build administration for production and runs the webpack bundle analyzer
 - administration:build                                   build administration for production and run assetic
 - administration:component-library-install               installs the dependencies for the component library tests using npm
 - administration:component-library                       build the component library for production
 - administration:generate-api-docs                       generates the api documentation using jsdoc
 - administration:init                                    init administration dependencies for docker setups
 - administration:install-dependencies                    installs the dependencies for the administration using npm
 - administration:lint-scss-fix                           runs scss stylelint
 - administration:lint-scss                               runs scss stylelint
 - administration:security-check                          runs an automated security check of vulnerabilities based Node Security Platform
 - administration:unit-watch                              runs & auto watch files to re-run unit tests automatically on change
 - administration:unit                                    runs unit tests with karma for the administration
 - administration:watch                                   starting administration dev server for hot module reloading. Disable linting with the parameter ESLINT_DISABLE=true

e2e:
 - e2e:cleanup                                            
 - e2e:dump-db                                            
 - e2e:init-docker                                        installs the dependencies for the e2e tests using npm in cypress container
 - e2e:init-local                                         installs the dependencies for the e2e tests using npm in cypress container
 - e2e:init                                               installs the dependencies for the e2e tests using npm in cypress container
 - e2e:open-docker                                        
 - e2e:open-local                                         
 - e2e:open                                               opens e2e tests runner
 - e2e:prepare-container                                  
 - e2e:restore-db                                         
 - e2e:run-docker                                         
 - e2e:run-local                                          
 - e2e:run                                                

storefront:
 - storefront:build                                       Builds the project for production
 - storefront:dev                                         Builds the project for development
 - storefront:hot                                         Starts the hot module reloading server
 - storefront:init                                        install dependencies and build for production
 - storefront:install-dependencies                        Installs the node.js dependencies
 - storefront:prod                                        (Deprecated, use build instead) Builds the project for production
 - storefront:watch                                       Starts the webpack watcher

docs:
 - docs:build                                             
 - docs:deploy                                            
 - docs:install-plugins                                   
 - docs:load-plugins                                      
 - docs:unit-plugins                                      
 - docs:update  
```