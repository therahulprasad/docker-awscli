# AWSCLI on Alpine
It provides clean AWSCLI installation without setting any entrypoint or CMD,  
Which gives you flexibility to run own bash and do whatever the hell you want to do.  

I use it to test permissions of IAM keys.  

Run:  
`docker run -it therahulprasad/awscli:alpine bash` to access terminal. Then run   
`aws configure` to configure awscli. Then proceed with any awscli command you want to test.  
