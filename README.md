index.js with an exports.handler and node_modules

create lambda

configure private key in env vars

zip and push code

increase timeout

test

zip -r function.zip .

aws lambda update-function-code --function-name EthTest --zip-file fileb://function.zip