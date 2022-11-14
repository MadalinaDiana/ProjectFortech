# ProjectFortech
###Jules page functionality test

This project aims to test the functionality of the Jules pages.
The pages tested are "sign-up", "sign-in" and "forgot-password".

For the testing I use the POM structure for a better organization 
of the files.

### Pre-requisites
Everything needed to run the project can be found in the file ``` .requirements.txt ```

## Folder and file structure
```bash
/features
    /pages # here we have defined the methods used
              # in the testing steps
        /base_page.py
        /complete_signup.py
        /form_page.py
        /verify_url.py
    /steps #here we implement steps to be executed,
            # using the methods defined in pages
        /complete_signup.py 
        /form_page.py
        /verify_url.py
    /browser.py #here is where test execution is initialized
    /complete_signup.feature #here are the tests in Gherkin language
    /environment.py #here we set hooks that put the browser in context
    /form_error.feature
    /verify_url.feature
/behave.ini
```
### Report tests
After running the tests, we will get an html page showing the test results.

## Results displayed
<img width="1440" alt="Screenshot 2022-11-14 at 10 23 41" src="https://user-images.githubusercontent.com/48148610/201623654-c5eeff55-63bf-47f5-bb14-70a8bcc2bf8e.png">

