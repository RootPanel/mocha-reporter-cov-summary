## mocha-reporter-cov-summary
Print a summary of coverage after finished all tests.

### Usage

In `package.json`:

    "scripts": {
        "test": "./node_modules/.bin/mocha --reporter node_modules/mocha-reporter-cov-summary test",
    }

Will print as:

    Coverage Summary: 1094 lines of 1253 lines, 87.3% covered
