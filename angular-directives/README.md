`closure-compiler --compilation_level ADVANCED_OPTIMIZATIONS --externs angular-1.4-externs.js --js main.js lp-directives.js --js_output_file lp-all-compiled.js`
or better
`uglifyjs main.js lp-directives.js -o lp-all-compiled.js --mangle --lint -c`
