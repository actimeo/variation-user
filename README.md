[![npm version](https://badge.fury.io/js/variation-user.svg)](https://badge.fury.io/js/variation-user)
# variation-user
An ng2 service to store user information in the browser localstorage

## Usage

    npm install variation-user --save

If you are using systemJS as your module loader, your configuration should look like:

    System.config({
      packages: {
        [...]
        'vendor/variation-user': {
          format: 'cjs',
          defaultExtension: 'js'
        }        
      },
      map: {
        [...]
        'variation-user': 'vendor/variation-user'
      }
    });


Then, import the UserService into your files:

    import {UserService} from 'variation-user/services';

## Developers

    npm install
    typings install
    npm test
    npm run coverage
