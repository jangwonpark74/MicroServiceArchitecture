# MicroServiceArchitecture

- [Microservice Application Tracing : Dapper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36356.pdf)



## gRPC user tracing request end-to-end


## Example 

- Import the tracing package: 
```
  import "cloud.google.com/go/trace"
```

- Initiate a trace client
```
  ctx := context.Background()
  tc, err := trace.NewClient(ctx, "project-id")
  if err != nil {
	log.Fatal(err)
  }
```
