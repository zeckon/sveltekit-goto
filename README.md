goto doing page refresh 

## Run App

Run the app
```bash
npm i
npm run dev
```

## Test 1
# Call Directly
Visit: `/test1` 
Result: Refresh, outputs `ssr` to console (also outputs `client` to browser)

## Test 2
# Call onMount
Visit: `/test2` 
Result: Refresh, outputs `ssr` to console (also outputs `client` to browser)

## Test 3
# Wrap with setTimeout
Visit: `/test3` 
Result: No Refresh, only outputs `client` to console

## Test 4
# Call on sveltekit:start
Visit: `/test4` 
Result: Refresh, outputs `ssr` to console (also outputs `client` to browser)