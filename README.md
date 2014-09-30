# Sample Api
Sample Api application demonstrating CRUD with oAuth2 

## How to use
1. Clone repo to your computer
2. Run `npm install`
3. Start service `gulp serve`

## Test * Requires mocha
Run `npm test`
```
  Setting Up
    ✓ should clear the TEST database
    ✓ should start the SERVER
    ✓ should have respond to ECHO

  Authentication
    Register, Login and Fetch my Profile
      ✓ should register a new user and return a token (174ms)
      ✓ should login as user and return new a token (84ms)
      ✓ should forbid access without a token
      ✓ should allow access with a Bearer token
    Failed Registration Scenarios
      ✓ empty data set, should return 412

  User Note Tests
    CRUD Tests
      ✓ should create a new note and return the note
      ✓ should return our new note
      ✓ should update our note
      ✓ should delete our note


  12 passing (403ms)
```
- Returns 12 passing tests 

## TODO
TBD
