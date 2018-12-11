# RestVsGrpcSample

.NET Core 2.0 and 2.1 perf improvements can be seen in benchmarks after upgrading (and running 1000 requests instead of 100):

|    Method |     Mean |    Error |   StdDev |
|---------- |----------|----------|----------|
| RestAsync | 129.9 ms | 1.975 ms | 1.649 ms |
| GrpcAsync | 214.1 ms | 3.213 ms | 3.005 ms |
