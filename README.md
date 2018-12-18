
 Golang has standard [Benchmark Data Format](https://github.com/golang/proposal/blob/master/design/14313-benchmark-format.md), and [several tools](https://godoc.org/golang.org/x/perf) for performance testing whis supports this output format.

This package helps to use performance testing in continous intergation pipline.

## Golang perf tools

- `localperf` tool runs local [Go Performance Dashboard for benchmark analysis](https://perf.golang.org/)
- `localperfdata` runs local [Go Performance Data Server](https://perfdata.golang.org/) for benchmark results data upload