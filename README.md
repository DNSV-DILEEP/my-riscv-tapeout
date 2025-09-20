# my-riscv-tapeout
My RISC-V SoC Tapeout Journey (Inspired by VSD Program)
# My RISC-V SoC Tapeout Journey

This repository documents my journey of designing and experimenting with a RISC-V based SoC using open-source tools.  
It contains weekly updates, RTL design files, simulation scripts, synthesis outputs, and documentation.

---

## 📅 Weekly Progress

| Week | Task | Status | Notes |
|------|------|--------|-------|
| Week 0 | Environment setup (Icarus Verilog, Yosys, GTKWave, OpenLane) | ✅ Done | Added screenshots in `docs/week0/` |
#| Week 1 | RTL design + testbench creation | ⏳ In Progress | |
#| Week 2 | Simulation and waveform analysis | ⏳ Pending | |
#| Week 3 | Synthesis with Yosys | ⏳ Pending | |
#| Week 4 | Floorplanning and placement (OpenLane) | ⏳ Pending | |
#| Week 5 | Routing, STA, and reports | ⏳ Pending | |
#| Week 6 | Final GDSII generation for tapeout | ⏳ Pending | |

---

## 📂 Repository Structure


---

## ▶️ How to Run

### Simulation
```bash
cd sim
./run_sim.sh



cd synth
yosys -p "read_verilog ../rtl/*.v; synth -top top_module; write_verilog -noattr synth_out.v"
