# tslint-config-angular

## Dependencies

1. Angular for specific rules
2. RXJS for specific rules
3. Existing linters (rxjs-tslint, tslint-config-airbnb and tslint-config-prettier) to extend their existing rules

## How to use

1. Delete the entire contents of your `tslint.json` file.
2. Copy and paste the following code block to your `tslint.json` file:
````
{
      "extends": ["tslint-config-angular/tslint.json"]
}
````