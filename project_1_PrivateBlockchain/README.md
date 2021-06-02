# Second submittal

Feedback good.  Made all adjustments per feedback.  

One point - in 'BlockchainController.js', I left the endpoint 'getBlockByHeight()' 
the same, but copied it to a function for myself to use in debugging called 'getBlockBodyByHeight()' 
which intentionally returned the decoded body of the block.  

I have since renamed this endpoing to 'getDecodedBodyByHeight()'.  This is not a required function, 
but was helpful for me in this project.  

# Test Results

Genesis Block:

![image](https://user-images.githubusercontent.com/18557655/120386230-3c4a5f00-c2dd-11eb-83a1-99c03cfdfa4b.png)

Request Validation:

![image](https://user-images.githubusercontent.com/18557655/120386317-57b56a00-c2dd-11eb-9da8-f11cc23c23f2.png)

Sign Message With Wallet:

![image](https://user-images.githubusercontent.com/18557655/120386447-7ae01980-c2dd-11eb-86d9-1eb7c13562e4.png)

Submit Star:

![image](https://user-images.githubusercontent.com/18557655/120386490-8df2e980-c2dd-11eb-91f4-35e8e11feb5a.png)

Retrieve Stars Owned by Me:

![image](https://user-images.githubusercontent.com/18557655/120386560-a105b980-c2dd-11eb-8149-a7d1b3859e6d.png)

NOTE:  I legitimately published the same star twice, so this is the correct response - there are two stars of the same "story" and degrees in the chain[]

