# Pipeline process

We use CircleCI to deploy our application to AWS. It triggers every time we push to main branch
   
## Commands order
1. Install node and AWS cli and EB cli
2. checkout the code
3. frontend dependencies installation
4. api dependencies installation
5. frontend build
6. backend build
7. frontend deploy
8. api deploy