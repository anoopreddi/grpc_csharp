# grpc_csharp

Built a simple gRPC service and client in C# by creating a Calculator-microservice. I then secured the service by creating a CA certificate/private key pair
to issue and sign certificates, creating a service certificate/private key pair for the service, and deploying CA’s certificate to the client.
Next, I added bi-directional streaming support through gRPC by streaming "temperature readings" to the client.
