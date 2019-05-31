# Final Report

- [ ] Fibonacci vs Galois LFSRs
- [ ] Vertical vs Horizontal LFSRs
- [ ] LSFRs and drivers fixed on `clk_dut` vs complex driver filter on `clk_tb`
- [ ] Sub monitors on `clk_tb` vs on a divided `clk_dut`
- [ ] Not actually an arbiter, more like an inverse multiplexer since there is no request or grant signals
- [ ] Sub monitors designed to be identical to DUT. This way monitor module can just do the inverse multiplexer and comparisons other wrapping functions.
- [ ] Latency of each module should be analysed, especially the consistency. If not consistent, how robust is the system?
- [ ] Figure out what to do with new motivation
- [ ] Post-synth simulation

some time next week send james report
hardware debugging -> there's an IP block for it

debugging -> cyclic behaviour in design
but none matches that of the error rate
