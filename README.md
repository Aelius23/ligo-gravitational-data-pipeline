# 🌌 LIGO Gravitational Wave Analysis Toolkit (Colab)

This project is a Colab-powered framework for analyzing gravitational wave data from the LIGO Open Science Center. It features modular analyzers that span from standard signal processing to speculative quantum-coherence and cosmological pattern discovery.

> 🔄 Designed for physicists, artists, and rogue theorists exploring the structure behind the waveform.

---

## 🔗 Features

- Fetch raw strain data from the LIGO Open Science archive
- Perform FFT, bandpass filtering, and coherence analysis
- Detect gravitational memory effects
- Explore possible quantum patterns and mass-spin relationships
- Analyze multiple events and compare frequency structures

---

## 🔨 Analyzer Modules

### Core:
- `LIGODataPipeline` – Downloads and prepares LIGO event data
- `WaveAnalyzer` – Standard tools (filtering, coherence, whitening)

### Extended:
- `MemoryAnalyzer` – Searches for gravitational memory effects
- `QuantumMemoryAnalyzer` – Links memory shifts to coherence peaks
- `FrequencyBandAnalyzer` – Tracks how memory evolves across frequencies
- `SpikeAnalyzer` – Detects temporal spikes and rhythm changes
- `MultiEventAnalyzer` – Compares multiple GW events
- `MassCoherenceAnalyzer` – Analyzes mass vs coherence
- `SpinMassAnalyzer` – Studies spin/mass interactions
- `SpinStateAnalyzer` – Explores spin state patterns
- `ExtremeMassAnalyzer` – Focuses on high-mass event anomalies

### Quantum / Meta-Theory:
- `QuantumLadderAnalyzer` – Detects stepped coherence patterns
- `ModifiedQuantumAnalyzer` – Alternate quantum filters
- `ComprehensiveQuantumAnalyzer` – Aggregates quantum stats
- `PhaseTransitionAnalyzer` – Looks for sudden shifts in the signal
- `UniversalityAnalyzer` – Compares consistency across events
- `UnificationAnalyzer` – Attempts signal synthesis from multiple perspectives
- `PentaUnificationAnalyzer` – Adds complexity with multi-axis comparison
- `QuantumStaircaseAnalyzer` – Scans for quantized structure
- `PentaQuantumAnalyzer` – Higher-dimensional coherence analysis

### Visualization / Wrappers:
- `CoherenceAnalyzer` – Specialized coherence visualization
- `EnhancedLIGOPipeline` – Upgraded data management pipeline

---

## 💡 Class Hierarchy

> Click the diagram to open full-size version.

![Class Hierarchy](./A_flowchart-style_diagram_showcases_class_hierarch.png)

---

## ⚡ How to Run

Open in Google Colab: [Run Notebook](https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK)

You will need:
- A Google account
- A face image (if testing visualizations)
- Optional: event metadata from LIGO Open Science

---

## 📂 Example Workflow

```python
pipeline = LIGODataPipeline()
data = pipeline.fetch_event_data('GW150914')

analyzer = WaveAnalyzer(data)
filtered = analyzer.bandpass_filter()

qmem = QuantumMemoryAnalyzer(filtered)
coh_stats = qmem.analyze_quantum_coherence()
```

## 🪢  Guide to Analyzer Dependencies

<img width="676" alt="ANALYZER DEPENDENCIES" src="https://github.com/user-attachments/assets/2e88e2ba-cdef-4f32-8ff9-580e1987a42b" />


---

## 📜 License

Notebook and analyzers by Spencer Toulouse. LIGO data © LIGO Open Science Center.
Attribution appreciated for reuse or remix.

To be expanded.
