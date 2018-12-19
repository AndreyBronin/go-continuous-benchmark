
 Golang has standard [Benchmark Data Format](https://github.com/golang/proposal/blob/master/design/14313-benchmark-format.md), and [several tools](https://godoc.org/golang.org/x/perf) for performance testing which supports this output format.

This package helps to embed Golang performance tests in continuous integration pipeline.

## Golang perf tools

- `localperf` tool runs local [Go Performance Dashboard for benchmark analysis](https://perf.golang.org/)
- `localperfdata` runs local [Go Performance Data Server](https://perfdata.golang.org/) for benchmark results data upload
- `benchsave` uploads benchmark results to perfdata server