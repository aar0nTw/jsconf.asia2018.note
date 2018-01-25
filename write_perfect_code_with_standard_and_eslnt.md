Speaker: Feross Aboukhadijeh @feross

## A linter catches bugs
  - Feross talk somthing about "bugs"

  > we could, for instance, begin with cleaning up our language by no longer calling a bug a bug but by calling it an error.
   - Edsger W. Dijkstra

  let see ESLINT

  JSLINT -> JSHINT -> ESLINT

  JSLINT a original linter started at 2002
  
  what eslint checks:
    - Programmer Errors
    - Best Practices
      - avoiding confusing codes.
    - Style issues
      - how your code look
      - code look consistan

### Cath programmer errors = shorten the feedback loop

#### how does one use eslint
    your `.eslintrc` is too long, maybe over 1000 lines
    but you can extends standard
    and use rules property to add more rules, it's more clearly.
    ```
{
  extends: 'standard',
  rules: {
    ...
  }
}
    ```

#### why use standardjs
    ```
    $ npm install standard --save-dev
    $ standard
    ```
    - vibrant community
    - dl 1m times

#### Should one use ESLint directly?
    1. Beware of bikeshedding.
    2. Beware of duplication.

### Best practice
    - talk about like use triple equals blahblah

Event if you don't use standard consider `standard-engine`

### Style issues

patreon.com/feross

