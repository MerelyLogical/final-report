# Final Report

- [ ] Fibonacci vs Galois LFSRs
- [ ] Vertical vs Horizontal LFSRs
- [ ] LSFRs and drivers fixed on `clk_dut` vs complex driver filter on `clk_tb`
- [ ] Sub monitors on `clk_tb` vs on a divided `clk_dut`
- [ ] Not actually an arbiter, more like an inverse multiplexer since there is no request or grant signals
- [ ] Sub monitors designed to be identical to DUT. This way monitor module can just do the inverse multiplexer and comparisons other wrapping functions.
- [ ] Latency of each module should be analysed, especially the consistency. If not consistent, how robust is the system?
