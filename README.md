# alexa-ramdass


### May 24, 2017 

This is a dirty oneoff. Dirty because it relied on the AWS GUI for the "metadata" for the Lambda function, for example things like the Invocation name were set this way. 

I was thinking maybe ansible can handle this (https://docs.ansible.com/ansible/lambda_module.html) but upon further reflection, no, the "invocation name" is an Alexa Skills specific thing. 

2 - maybe check this out: 


https://www.google.com/search?q=ansible+alexa+skills 

> https://github.com/jhotta/repositories

> https://github.com/jhotta/ask-alexa-pykit 
> https://devpost.com/software/rapbattlealexa


