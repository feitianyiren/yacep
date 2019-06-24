# This file was generated by [Azure Pipelines](https://dev.azure.com/tupac-amaru/yacep/_build/latest?definitionId=5&branchName=master)

## AtomicValue.Decimal

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method | ValueLength | WarmUp |     Mean |    Error |    StdDev |   Median |
|---------------- |------------ |------- |---------:|---------:|----------:|---------:|
| **EvaluateDecimal** |           **5** |  **False** | **82.63 ns** | **2.202 ns** |  **9.299 ns** | **81.25 ns** |
| **EvaluateDecimal** |           **5** |   **True** | **71.10 ns** | **1.555 ns** |  **5.810 ns** | **75.00 ns** |
| **EvaluateDecimal** |          **10** |  **False** | **89.14 ns** | **2.172 ns** |  **9.172 ns** | **87.50 ns** |
| **EvaluateDecimal** |          **10** |   **True** | **76.44 ns** | **2.218 ns** |  **9.392 ns** | **75.00 ns** |
| **EvaluateDecimal** |          **15** |  **False** | **78.14 ns** | **3.015 ns** | **12.732 ns** | **75.00 ns** |
| **EvaluateDecimal** |          **15** |   **True** | **84.33 ns** | **2.201 ns** |  **9.249 ns** | **87.50 ns** |
| **EvaluateDecimal** |          **50** |  **False** | **86.65 ns** | **2.070 ns** |  **8.536 ns** | **87.50 ns** |
| **EvaluateDecimal** |          **50** |   **True** | **84.56 ns** | **2.198 ns** |  **9.087 ns** | **87.50 ns** |

## AtomicValue.Identifier

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|             Method | IdentifierCount | WarmUp |      Mean |     Error |    StdDev |    Median |
|------------------- |---------------- |------- |----------:|----------:|----------:|----------:|
| **EvaluateIdentifier** |               **5** |  **False** |  **2.429 us** | **0.0362 us** | **0.1393 us** |  **2.350 us** |
| **EvaluateIdentifier** |               **5** |   **True** |  **2.433 us** | **0.0387 us** | **0.1477 us** |  **2.375 us** |
| **EvaluateIdentifier** |              **10** |  **False** |  **4.092 us** | **0.0625 us** | **0.2419 us** |  **3.938 us** |
| **EvaluateIdentifier** |              **10** |   **True** |  **4.155 us** | **0.0966 us** | **0.3658 us** |  **4.000 us** |
| **EvaluateIdentifier** |              **20** |  **False** |  **8.149 us** | **0.2683 us** | **1.1123 us** |  **7.638 us** |
| **EvaluateIdentifier** |              **20** |   **True** |  **8.081 us** | **0.2873 us** | **1.1944 us** |  **7.475 us** |
| **EvaluateIdentifier** |              **30** |  **False** | **11.615 us** | **0.3362 us** | **1.4012 us** | **10.700 us** |
| **EvaluateIdentifier** |              **30** |   **True** | **11.306 us** | **0.3246 us** | **1.3348 us** | **10.344 us** |

## AtomicValue.Integer

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method | ValueLength | WarmUp |     Mean |    Error |   StdDev |   Median |
|---------------- |------------ |------- |---------:|---------:|---------:|---------:|
| **EvaluateInteger** |           **1** |  **False** | **31.66 ns** | **1.968 ns** | **8.311 ns** | **25.00 ns** |
| **EvaluateInteger** |           **1** |   **True** | **17.25 ns** | **1.862 ns** | **7.882 ns** | **12.50 ns** |
| **EvaluateInteger** |           **2** |  **False** | **17.46 ns** | **1.704 ns** | **7.197 ns** | **12.50 ns** |
| **EvaluateInteger** |           **2** |   **True** | **22.30 ns** | **1.781 ns** | **7.523 ns** | **25.00 ns** |
| **EvaluateInteger** |           **3** |  **False** | **21.71 ns** | **1.414 ns** | **5.521 ns** | **25.00 ns** |
| **EvaluateInteger** |           **3** |   **True** | **18.94 ns** | **1.647 ns** | **6.975 ns** | **12.50 ns** |
| **EvaluateInteger** |           **4** |  **False** | **28.25 ns** | **1.923 ns** | **8.143 ns** | **25.00 ns** |
| **EvaluateInteger** |           **4** |   **True** | **19.28 ns** | **1.675 ns** | **7.072 ns** | **25.00 ns** |
| **EvaluateInteger** |           **5** |  **False** | **30.75 ns** | **1.821 ns** | **7.709 ns** | **25.00 ns** |
| **EvaluateInteger** |           **5** |   **True** | **22.53 ns** | **1.275 ns** | **4.993 ns** | **25.00 ns** |
| **EvaluateInteger** |           **6** |  **False** | **20.60 ns** | **1.752 ns** | **7.399 ns** | **25.00 ns** |
| **EvaluateInteger** |           **6** |   **True** | **33.75 ns** | **1.801 ns** | **7.624 ns** | **37.50 ns** |
| **EvaluateInteger** |           **7** |  **False** | **18.75 ns** | **1.800 ns** | **7.623 ns** | **18.75 ns** |
| **EvaluateInteger** |           **7** |   **True** | **23.63 ns** | **2.003 ns** | **8.480 ns** | **25.00 ns** |
| **EvaluateInteger** |           **8** |  **False** | **22.36 ns** | **1.823 ns** | **7.700 ns** | **25.00 ns** |
| **EvaluateInteger** |           **8** |   **True** | **19.32 ns** | **1.757 ns** | **7.403 ns** | **25.00 ns** |

## AtomicValue.Literal

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method | LiteralCount | WarmUp |     Mean |      Error |    StdDev |   Median |
|---------------- |------------- |------- |---------:|-----------:|----------:|---------:|
| **EvaluateLiteral** |            **5** |  **False** | **477.0 ns** |  **11.493 ns** |  **44.06 ns** | **481.3 ns** |
| **EvaluateLiteral** |            **5** |   **True** | **474.7 ns** |  **11.086 ns** |  **41.82 ns** | **475.0 ns** |
| **EvaluateLiteral** |           **10** |  **False** | **462.3 ns** |   **7.144 ns** |  **27.90 ns** | **450.0 ns** |
| **EvaluateLiteral** |           **10** |   **True** | **457.0 ns** |   **6.872 ns** |  **25.84 ns** | **443.8 ns** |
| **EvaluateLiteral** |           **20** |  **False** | **980.4 ns** | **157.502 ns** | **663.43 ns** | **500.0 ns** |
| **EvaluateLiteral** |           **20** |   **True** | **462.5 ns** |   **6.972 ns** |  **26.05 ns** | **456.3 ns** |
| **EvaluateLiteral** |           **30** |  **False** | **997.6 ns** | **158.538 ns** | **669.53 ns** | **537.5 ns** |
| **EvaluateLiteral** |           **30** |   **True** | **478.3 ns** |   **9.573 ns** |  **36.58 ns** | **475.0 ns** |

## AtomicValue.NakedFunction

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|                Method | FunctionCount | WarmUp | Cacheable |       Mean |      Error |    StdDev |     Median |
|---------------------- |-------------- |------- |---------- |-----------:|-----------:|----------:|-----------:|
| **EvaluateNakedFunction** |             **1** |  **False** |     **False** | **1,322.2 ns** | **168.329 ns** | **709.03 ns** |   **887.5 ns** |
| **EvaluateNakedFunction** |             **1** |  **False** |      **True** |   **429.8 ns** |   **6.952 ns** |  **27.06 ns** |   **425.0 ns** |
| **EvaluateNakedFunction** |             **1** |   **True** |     **False** |   **860.8 ns** |  **11.275 ns** |  **44.30 ns** |   **837.5 ns** |
| **EvaluateNakedFunction** |             **1** |   **True** |      **True** |   **440.0 ns** |   **6.479 ns** |  **24.60 ns** |   **425.1 ns** |
| **EvaluateNakedFunction** |             **5** |  **False** |     **False** | **1,402.3 ns** |  **21.448 ns** |  **83.50 ns** | **1,356.3 ns** |
| **EvaluateNakedFunction** |             **5** |  **False** |      **True** |   **513.4 ns** |   **7.566 ns** |  **28.82 ns** |   **500.0 ns** |
| **EvaluateNakedFunction** |             **5** |   **True** |     **False** | **1,409.5 ns** |  **21.694 ns** |  **83.68 ns** | **1,362.5 ns** |
| **EvaluateNakedFunction** |             **5** |   **True** |      **True** |   **468.2 ns** |   **7.784 ns** |  **29.37 ns** |   **462.5 ns** |
| **EvaluateNakedFunction** |            **10** |  **False** |     **False** | **2,116.9 ns** |  **31.558 ns** | **120.98 ns** | **2,050.1 ns** |
| **EvaluateNakedFunction** |            **10** |  **False** |      **True** |   **461.0 ns** |   **6.703 ns** |  **26.02 ns** |   **450.0 ns** |
| **EvaluateNakedFunction** |            **10** |   **True** |     **False** | **2,543.6 ns** | **186.923 ns** | **783.25 ns** | **2,093.8 ns** |
| **EvaluateNakedFunction** |            **10** |   **True** |      **True** |   **509.6 ns** |   **6.524 ns** |  **25.94 ns** |   **500.0 ns** |
| **EvaluateNakedFunction** |            **20** |  **False** |     **False** | **4,067.9 ns** | **218.086 ns** | **918.62 ns** | **3,487.5 ns** |
| **EvaluateNakedFunction** |            **20** |  **False** |      **True** |   **516.5 ns** |   **6.407 ns** |  **25.47 ns** |   **512.5 ns** |
| **EvaluateNakedFunction** |            **20** |   **True** |     **False** | **3,521.9 ns** |  **54.821 ns** | **203.44 ns** | **3,412.5 ns** |
| **EvaluateNakedFunction** |            **20** |   **True** |      **True** |   **446.0 ns** |   **5.724 ns** |  **22.69 ns** |   **437.5 ns** |
| **EvaluateNakedFunction** |            **30** |  **False** |     **False** | **5,048.7 ns** | **113.149 ns** | **428.26 ns** | **4,850.0 ns** |
| **EvaluateNakedFunction** |            **30** |  **False** |      **True** | **1,107.6 ns** | **158.728 ns** | **668.59 ns** |   **525.0 ns** |
| **EvaluateNakedFunction** |            **30** |   **True** |     **False** | **5,811.0 ns** | **232.851 ns** | **957.57 ns** | **5,412.6 ns** |
| **EvaluateNakedFunction** |            **30** |   **True** |      **True** |   **467.7 ns** |   **7.964 ns** |  **29.45 ns** |   **456.3 ns** |

## AtomicValue.String

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|         Method | StringLength |     Mean |    Error |    StdDev |   Median |
|--------------- |------------- |---------:|---------:|----------:|---------:|
| **EvaluateString** |           **10** | **103.5 ns** | **2.517 ns** | **10.602 ns** | **100.0 ns** |
| **EvaluateString** |           **20** | **103.3 ns** | **2.734 ns** | **11.428 ns** | **100.0 ns** |
| **EvaluateString** |           **30** | **103.9 ns** | **2.301 ns** |  **9.642 ns** | **100.0 ns** |
| **EvaluateString** |           **40** | **111.4 ns** | **3.420 ns** | **14.444 ns** | **112.5 ns** |
| **EvaluateString** |          **100** | **120.8 ns** | **2.358 ns** |  **9.931 ns** | **125.0 ns** |
| **EvaluateString** |         **1000** | **167.7 ns** | **2.952 ns** | **12.071 ns** | **162.5 ns** |

## CompoundValue.Array

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
| Method | NumberCount |        Mean |      Error |     StdDev |    Median |
|------- |------------ |------------:|-----------:|-----------:|----------:|
|    **Len** |           **5** |    **21.70 ns** |   **1.856 ns** |   **7.798 ns** |  **25.00 ns** |
|    Max |           5 |   600.63 ns |   9.433 ns |  37.716 ns | 587.50 ns |
|    Min |           5 |   615.50 ns |  13.246 ns |  48.825 ns | 593.69 ns |
|    Sum |           5 |   657.88 ns |   9.942 ns |  38.112 ns | 637.50 ns |
|    Avg |           5 |    89.44 ns |   2.217 ns |   9.386 ns |  87.50 ns |
|    **Len** |          **10** |    **27.26 ns** |   **1.649 ns** |   **6.964 ns** |  **25.00 ns** |
|    Max |          10 |   585.58 ns |   8.966 ns |  34.799 ns | 575.00 ns |
|    Min |          10 | 1,013.76 ns | 145.548 ns | 616.258 ns | 675.00 ns |
|    Sum |          10 |   627.62 ns |  10.557 ns |  40.722 ns | 612.50 ns |
|    Avg |          10 |    79.19 ns |   2.352 ns |   9.804 ns |  81.25 ns |
|    **Len** |          **20** |    **23.37 ns** |   **1.841 ns** |   **7.775 ns** |  **25.00 ns** |
|    Max |          20 |   638.69 ns |   9.591 ns |  38.351 ns | 625.00 ns |
|    Min |          20 |   633.73 ns |  10.981 ns |  42.227 ns | 625.00 ns |
|    Sum |          20 |   954.86 ns | 143.840 ns | 605.883 ns | 612.50 ns |
|    Avg |          20 |    85.78 ns |   2.177 ns |   8.952 ns |  87.50 ns |
|    **Len** |          **30** |    **20.63 ns** |   **1.641 ns** |   **6.949 ns** |  **25.00 ns** |
|    Max |          30 |   627.59 ns |  11.954 ns |  47.105 ns | 625.00 ns |
|    Min |          30 |   625.47 ns |   9.324 ns |  35.516 ns | 612.50 ns |
|    Sum |          30 |   576.72 ns |   8.714 ns |  34.440 ns | 562.50 ns |
|    Avg |          30 |    84.79 ns |   2.393 ns |   9.975 ns |  87.50 ns |
|    **Len** |         **100** |    **22.20 ns** |   **1.364 ns** |   **5.229 ns** |  **25.00 ns** |
|    Max |         100 | 1,162.13 ns | 155.577 ns | 657.024 ns | 700.00 ns |
|    Min |         100 |   590.15 ns |  10.324 ns |  38.443 ns | 575.00 ns |
|    Sum |         100 | 1,252.58 ns | 165.586 ns | 699.295 ns | 662.50 ns |
|    Avg |         100 |    85.37 ns |   2.174 ns |   9.060 ns |  87.50 ns |
|    **Len** |        **1000** |    **20.19 ns** |   **1.768 ns** |   **7.485 ns** |  **25.00 ns** |
|    Max |        1000 |   585.35 ns |   9.868 ns |  38.183 ns | 568.75 ns |
|    Min |        1000 |   593.36 ns |  10.611 ns |  39.770 ns | 575.00 ns |
|    Sum |        1000 |   596.19 ns |  10.681 ns |  39.104 ns | 575.00 ns |
|    Avg |        1000 |    84.08 ns |   2.254 ns |   9.520 ns |  81.25 ns |

## CompoundValue.Dictionary

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method | ItemCount |        Mean |     Error |    StdDev |      Median |
|---------------- |---------- |------------:|----------:|----------:|------------:|
|      **DirectRead** |        **10** |   **151.57 ns** |  **3.285 ns** | **13.872 ns** |   **150.00 ns** |
|     UseDelegate |        10 |   165.61 ns |  3.089 ns | 12.424 ns |   162.50 ns |
|      UseDynamic |        10 |   437.03 ns |  7.602 ns | 31.091 ns |   425.00 ns |
|   UseReflection |        10 | 1,031.84 ns | 16.405 ns | 64.256 ns | 1,012.50 ns |
|        UseYacep |        10 |   783.70 ns | 12.195 ns | 45.711 ns |   762.50 ns |
| UseTypedCompile |        10 |    56.95 ns |  2.207 ns |  9.295 ns |    50.00 ns |
|      **DirectRead** |       **100** |   **139.59 ns** |  **3.767 ns** | **15.869 ns** |   **137.50 ns** |
|     UseDelegate |       100 |   172.63 ns |  3.642 ns | 15.419 ns |   175.00 ns |
|      UseDynamic |       100 |   425.00 ns |  6.932 ns | 28.192 ns |   425.00 ns |
|   UseReflection |       100 |   956.66 ns | 14.271 ns | 55.051 ns |   925.00 ns |
|        UseYacep |       100 |   701.89 ns | 11.302 ns | 44.666 ns |   681.25 ns |
| UseTypedCompile |       100 |    50.94 ns |  2.253 ns |  9.538 ns |    50.00 ns |
|      **DirectRead** |      **1000** |   **142.24 ns** |  **3.123 ns** | **12.880 ns** |   **137.50 ns** |
|     UseDelegate |      1000 |   166.50 ns |  3.511 ns | 14.749 ns |   162.50 ns |
|      UseDynamic |      1000 |   443.95 ns | 10.753 ns | 40.700 ns |   437.50 ns |
|   UseReflection |      1000 | 1,043.61 ns | 15.002 ns | 58.762 ns | 1,012.50 ns |
|        UseYacep |      1000 |   698.15 ns | 10.861 ns | 42.024 ns |   681.31 ns |
| UseTypedCompile |      1000 |    58.92 ns |  2.172 ns |  9.173 ns |    62.50 ns |

## CompoundValue.Object.Field.Field

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method |      Mean |    Error |    StdDev |    Median |
|---------------- |----------:|---------:|----------:|----------:|
|      DirectRead |  30.59 ns | 1.872 ns |  7.905 ns |  25.00 ns |
|     UseDelegate |  57.60 ns | 2.160 ns |  9.121 ns |  62.50 ns |
|      UseDynamic | 344.17 ns | 5.080 ns | 21.120 ns | 337.50 ns |
|   UseReflection | 359.99 ns | 5.910 ns | 23.287 ns | 356.25 ns |
|        UseYacep | 628.92 ns | 9.462 ns | 36.727 ns | 612.50 ns |
| UseTypedCompile |  72.25 ns | 2.370 ns |  9.799 ns |  75.00 ns |

## CompoundValue.Object.Method.NoArguments.NoArgumentsMethod

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method |        Mean |      Error |     StdDev |      Median |
|---------------- |------------:|-----------:|-----------:|------------:|
|      DirectRead |    75.25 ns |   2.342 ns |   9.889 ns |    75.00 ns |
|     UseDelegate |    94.20 ns |   2.443 ns |  10.236 ns |    87.50 ns |
|      UseDynamic |   933.05 ns | 167.166 ns | 705.965 ns |   400.00 ns |
|   UseReflection | 1,690.54 ns | 156.901 ns | 653.984 ns | 2,037.50 ns |
|        UseYacep | 1,827.66 ns | 159.875 ns | 673.424 ns | 2,375.00 ns |
| UseTypedCompile |    82.20 ns |   2.181 ns |   9.185 ns |    75.00 ns |

## CompoundValue.Object.Method.WithArguments.WithArgumentsMethod

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method |       Mean |     Error |   StdDev |     Median |
|---------------- |-----------:|----------:|---------:|-----------:|
|      DirectRead |   311.5 ns |  4.465 ns | 18.46 ns |   306.3 ns |
|     UseDelegate |   327.1 ns |  4.668 ns | 19.40 ns |   325.0 ns |
|      UseDynamic |   454.0 ns |  7.798 ns | 30.91 ns |   450.0 ns |
|   UseReflection |   955.2 ns | 12.351 ns | 47.94 ns |   937.5 ns |
|        UseYacep | 1,140.3 ns | 16.617 ns | 66.44 ns | 1,112.5 ns |
| UseTypedCompile |   100.3 ns |  2.813 ns | 11.88 ns |   100.0 ns |
|    OnlyFunction |   423.2 ns |  7.075 ns | 27.55 ns |   412.5 ns |

## CompoundValue.Object.Property.Property

``` ini

BenchmarkDotNet=v0.11.5, OS=ubuntu 16.04
Intel Xeon CPU E5-2673 v3 2.40GHz, 1 CPU, 2 logical and 2 physical cores
.NET Core SDK=2.2.204
  [Host] : .NET Core 2.2.5 (CoreCLR 4.6.27617.05, CoreFX 4.6.27618.01), 64bit RyuJIT

Toolchain=InProcessEmitToolchain  InvocationCount=8  IterationCount=200  
LaunchCount=1  RunStrategy=Throughput  UnrollFactor=4  
WarmupCount=1  

```
|          Method |      Mean |     Error |    StdDev |    Median |
|---------------- |----------:|----------:|----------:|----------:|
|      DirectRead |  22.56 ns |  1.350 ns |  5.158 ns |  25.00 ns |
|     UseDelegate |  48.15 ns |  2.011 ns |  8.492 ns |  43.75 ns |
|      UseDynamic | 336.84 ns |  5.597 ns | 23.018 ns | 337.50 ns |
|   UseReflection | 486.01 ns |  7.965 ns | 31.571 ns | 475.00 ns |
|        UseYacep | 609.27 ns | 10.053 ns | 39.612 ns | 587.63 ns |
| UseTypedCompile |  66.29 ns |  1.936 ns |  8.154 ns |  62.50 ns |


## Thanks
Powerful .NET library for benchmarking-[BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet)
