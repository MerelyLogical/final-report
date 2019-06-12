# Final Report

- [x] Fibonacci vs Galois LFSRs
- [x] Vertical vs Horizontal LFSRs
- [ ] ~LSFRs and drivers fixed on `clk_dut` vs complex driver filter on `clk_tb`~
- [ ] ~Sub monitors on `clk_tb` vs on a divided `clk_dut`~
- [x] Not actually an arbiter, more like an inverse multiplexer since there is no request or grant signals
- [ ] Sub monitors designed to be identical to DUT. This way monitor module can just do the inverse multiplexer and comparisons other wrapping functions.
- [ ] ~Latency of each module should be analysed, especially the consistency. If not consistent, how robust is the system?~
- [ ] Figure out what to do with new motivation
- [ ] Post-synth simulation
- [ ] On the fly reconfiguration for driver to monitor delay. have a shift register holding inputs. then once ready signal up from delay tester, start feeding that one to the monitor, also sets the ready signal for scoreboard to start counting.


some time next week send james report
hardware debugging -> there's an IP block for it

debugging -> cyclic behaviour in design
but none matches that of the error rate

design described in chronological order, but implementation is in logical order

What to do with stuff not actually implemented at report submission but already designed and can be easily implemented before demo?

Use of colors in the report

afterburner FPGA card in Mac pro?

1515 start

no sip file from qsys?
note for qsys refreshing

define a|b -> its not m|a

1717 end
