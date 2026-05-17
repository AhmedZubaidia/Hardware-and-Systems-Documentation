# Hardware and Systems Documentation

> A **technical-writing portfolio** of six formal engineering lab reports spanning **microcontroller interfacing**, **digital / analog electronics**, **signals and systems**, and **communications**. Curated from coursework at Birzeit University's Electrical & Computer Engineering department to demonstrate documentation skills alongside the hands-on lab work.

---

## Why this repo exists

Code-only portfolios tell hiring managers what you can build; documentation portfolios tell them whether you can explain what you built. Every engineer eventually has to write a design doc, an experiment report, a runbook, or a post-incident review — and most candidates have no public artifacts that prove they can. The reports in this repository do.

Each PDF follows the same disciplined structure: stated objective, theoretical background with cited equations, experimental setup with circuit diagrams or MATLAB code listings, observed results with tables and figures, and a discussion that ties the results back to theory. They are coursework, not industry deliverables, but they are the closest thing in my archive to the technical writing my future employer will want to see.

---

## Tech Stack Documented Across the Reports

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![I2C](https://img.shields.io/badge/I2C-FF6F00?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-3776AB?style=for-the-badge)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Multisim](https://img.shields.io/badge/Multisim-007ACC?style=for-the-badge)
![Oscilloscope](https://img.shields.io/badge/Oscilloscope-FCC624?style=for-the-badge)

---

## Repository Layout

```
.
├── README.md
├── .gitignore
└── reports/
    ├── arduino_uart_i2c_interfacing_realtime_systems_lab_report.pdf
    ├── digital_lab_encoders_decoders_mux_demux_exp3_report.pdf
    ├── circuits_electronics_first_second_order_rlc_response_exp3_report.pdf
    ├── circuits_electronics_passive_active_filters_exp5_report.pdf
    ├── signals_matlab_step_pulse_generation_project_report.pdf
    └── communication_systems_fourier_series_ssb_modulation_report.pdf
```

---

## Report Index

### Microcontroller and Embedded Interfacing

| Report | Course | What it covers |
| --- | --- | --- |
| [`arduino_uart_i2c_interfacing_realtime_systems_lab_report.pdf`](reports/arduino_uart_i2c_interfacing_realtime_systems_lab_report.pdf) | **ENCS5140** — Real-Time Systems & Interfacing Techniques Lab | Combined write-up of three Arduino experiments: hardware/software interrupt-driven light detection, UART serial communication between Arduino and host (also Arduino-to-Arduino), and I2C protocol communication for LCD output and inter-device messaging. Includes wiring diagrams, code listings, scope captures, and a comparison of UART vs I2C trade-offs. Co-authored. |

### Digital Electronics

| Report | Course | What it covers |
| --- | --- | --- |
| [`digital_lab_encoders_decoders_mux_demux_exp3_report.pdf`](reports/digital_lab_encoders_decoders_mux_demux_exp3_report.pdf) | **ENCS2110** — Digital Laboratory | Experiment 3: practical use of combinational logic ICs — encoders, decoders, multiplexers, and demultiplexers — to implement Boolean functions on breadboard, with truth tables, IC pinouts, and observed-vs-expected output comparisons. Co-authored. |

### Analog Circuits and Filter Theory

| Report | Course | What it covers |
| --- | --- | --- |
| [`circuits_electronics_first_second_order_rlc_response_exp3_report.pdf`](reports/circuits_electronics_first_second_order_rlc_response_exp3_report.pdf) | **ENEE2103** — Circuits & Electronics Laboratory | Experiment 3: time-domain response of RL, RC, and series RLC circuits to step inputs. Quantifies overdamped / underdamped / critically damped regimes, extracts time-constant and damping-ratio parameters from oscilloscope traces, and compares measured values against theoretical predictions. Co-authored. |
| [`circuits_electronics_passive_active_filters_exp5_report.pdf`](reports/circuits_electronics_passive_active_filters_exp5_report.pdf) | **ENEE2103** — Circuits & Electronics Laboratory | Experiment 5: characterisation of first-order high-pass / low-pass passive filters, second-order band-pass / band-stop filters, and active low-pass filters built with op-amps. Bode plots from measured frequency-sweep data alongside theoretical curves. Co-authored. |

### Signals and Communications

| Report | Course | What it covers |
| --- | --- | --- |
| [`signals_matlab_step_pulse_generation_project_report.pdf`](reports/signals_matlab_step_pulse_generation_project_report.pdf) | Signals & Systems — Course Project | Four-section MATLAB project on continuous-time signal generation and analysis: rectangular pulses via `rectangularPulse`, step signals via `heaviside`, signal-arithmetic combinations parameterised by student-ID digits, and visual verification with `fplot` / `plot`. Solo work. |
| [`communication_systems_fourier_series_ssb_modulation_report.pdf`](reports/communication_systems_fourier_series_ssb_modulation_report.pdf) | **ENEE3309** — Communication Systems | Assignment on Fourier-series decomposition of a periodic message signal followed by single-sideband (SSB) amplitude-modulation analysis: numerical Fourier coefficients, spectrum plotting, single-sideband spectrum derivation, and bandwidth comparison vs DSB. Solo work. |

---

## Co-Author Consent

Four of the six reports are co-authored. They are published here with the explicit consent of every co-author listed below.

| Report | Co-authors |
| --- | --- |
| `arduino_uart_i2c_interfacing_realtime_systems_lab_report.pdf` | Jana Herzallah (1201139), Lana Badwan (1200071) |
| `digital_lab_encoders_decoders_mux_demux_exp3_report.pdf` | Mohammad Makhamri (1200227) |
| `circuits_electronics_first_second_order_rlc_response_exp3_report.pdf` | Jana Herzallah (1201139), Lana Badwan (1200071), Jana AbuNasser (1201110) |
| `circuits_electronics_passive_active_filters_exp5_report.pdf` | Jana Herzallah (1201139), Lana Badwan (1200071) |

The remaining two (`signals_matlab_step_pulse_generation_project_report.pdf`, `communication_systems_fourier_series_ssb_modulation_report.pdf`) are solo work.

---

## A note on academic provenance

Every PDF in this repository is preserved as it was submitted — including the original Birzeit University cover page, my student ID, instructor name, and submission date. That is intentional: tampered-with PDFs are a credibility risk; original PDFs prove the work is mine and indexable by anyone who wants to verify the courses and grades against my transcript.
