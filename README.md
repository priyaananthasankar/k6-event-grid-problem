# k6-event-grid-problem
Reproducing the webpack issue with k6 and event grid

# Issue
k6 hangs and does not execute the test run.
Trying to import azure event grid module
`npm install azure-eventgrid`

# Steps

Run the following commands

```
npm install .

npm run-script webpack

k6 run build/app.bundle.js
```