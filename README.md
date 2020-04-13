# Setup ssh reverse tunnel
1. In Mac preferences go to "Shared" and enable "Remote login"
2. Create reverse ssh tunnel to remote server:
`ssh remoteuser@1.2.3.4 -R 5544:localhost:22 -N` and type password
3. On remote server connect to Mac by this command:
`ssh macuser@localhost -p 5544` and type password for Mac user

Enjoy.
