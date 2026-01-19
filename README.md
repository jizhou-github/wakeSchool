# WakeSchool (MATLAB App) — Agent-Based Fish Schooling Model Coupling Realtime Hydrodynamics

WakeSchool is a **MATLAB App Designer** interface for an agent-based fish schooling simulator that couples:
- **Social/behavioral interaction rules** (agent-based model), and
- **Hydrodynamic interactions**, including **wake effects** (and optional potential-flow effects).

Please _**Watch**_ 👀 and _**Star**_ 🌟 to keep updated!! Thank you~ 

This repository is currently a **preliminary public release**. Several UI options are intentionally **disabled at runtime** (e.g., in `Save & Replay`) because those functions are not fully validated yet. I am sharing the app early to make it easier for others to test, give feedback, and help shape the next development steps.

## Quick Start
0. You can directly download the **wakeSchool_noColorPicker.mltbx** and drag into your Matlab. (If you have the newest version, 2025b, you can download **wakeSchool.mltbx** as well, as only the newer versions of Matlab have _colorPicker_ feature).
---

## Reference (Paper + PDF included in this repo)

The model and key results are described in the paper below. A copy is included in this repository as:

- `school+model+AAM.pdf`

Paper link:  
https://pubs.aip.org/aip/pof/article-abstract/37/1/011912/3330027/Effect-of-hydrodynamic-wakes-in-dynamical-models?redirectedFrom=PDF

If you use this code in your work, please cite the paper above.

---

## Current status

### What works today
- Launching and running the simulator via the MATLAB App
- Fish motion visualization in periodic or bounded domain (including a circular tank option)
- Realtime statistics plotting (e.g., speed, nearest-neighbor distance, polarization) depending on toggles
- Wake visualization options (when enabled) consistent with the current implementation

### What is still under development
Some features are present in the UI but **not fully functional yet** and may be disabled at runtime, including (but not limited to):
- Parts of **Save & Replay** (especially replay logic and file I/O consistency)
- Some advanced display controls and quality-of-life UI interactions

These will be progressively enabled once they are stable and documented.

---

## Python version (coming soon)

🚧 A **Python version is coming soon**.  
The goal is to provide a Python implementation with the same core model logic and comparable visualization workflows, to improve accessibility for a broader community.

---

## Getting started

0. You can directly download the **wakeSchool_noColorPicker.mltbx** and drag into your Matlab. (If you have the newest version, 2025b, you can download **wakeSchool.mltbx** as well, as only the newer versions of Matlab have _colorPicker_ feature).
  
To keep fish model updated through GitHub, do the following steps:
1. Clone this repository:
   ```bash
   git clone <https://github.com/jizhou-github/wakeSchool>
   ```
2. Open the `.mltbx` file in MATLAB (App Designer) and click **Run**.
3. Use the **Setup / Display / Fish / Save & Replay** tabs to configure a run.
---

## Issues, feature requests, and collaborations

Feedback is welcome and encouraged.

- Please use **GitHub Issues** to report bugs, request new features, or suggest improvements.
- New feature requests are welcome (including new species presets, new statistics, new interaction rules, replay/export workflows, etc.).
- You can also send questions or issues to my email directly, **jzhou96@jhu.edu.**
- I am also open to **potential collaborations** (model development, validation against experiments, extensions to new species, etc.). If you have an idea, feel free to reach out.

---

## Support / Contact

For questions, support, or collaboration inquiries:

**jzhou96@jhu.edu**

---

## Acknowledgements

We acknowledge useful discussions with **Dr. Ashley Peterson** (University of California at Irvine), **Dr. Matt McHenry** (University of California at Irvine) and **Dr. Eva Kanso** (University of Southern California).

---

## Disclaimer

This code is provided as-is for research and educational use. Some components are preliminary and may not be fully validated yet. Please use appropriate care when interpreting results, and refer to the accompanying paper for model scope and assumptions.

---

## License

MIT
