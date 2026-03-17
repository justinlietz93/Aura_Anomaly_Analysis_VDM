# **Areas for further investigation:**

1. **`events_parsed.csv` (18.6 MB)** — The full parsed event stream with actual text content. This is where the deep NLP analysis lives: discourse structure, semantic coherence metrics, syntactic complexity progression, and the passage-by-passage role materialization you specifically asked for in your working notes. I never cracked this open.

2. **`utd_text_by_tick.csv` (121 KB)** — Text mapped to ticks. This is where you'd do the operator-vs-corpus input differentiation analysis (D5.1), motif frequency tracking, and the boundary/canal/naming attractor quantification. Untouched.

3. **`say_event_composer_audit_metrics.csv` (65 KB)** — Composer-level audit of every say event. This likely contains the data needed to quantify what the decoder was doing to the output — the gap between what the substrate was processing internally and what got forced through the mouth. Could spawn an entire family on decoder-masking artifacts.

4. **`node_embedding_metrics` (1 MB × 5 snapshots)** — Per-neuron metrics across all 5,000 neurons at five time points. This is where you'd find individual neuron specialization, functional differentiation, whether specific neurons became "dedicated" to specific roles over time. Five million data points I never looked at.

5. **`baseline_projection_grids` (32×32 state-space maps × 5 snapshots)** — These map how the system's state space is organized at each snapshot. Could reveal attractor basin migration, state-space topology changes, and whether the system's "geometry of thought" reorganized across epochs.

6. **`tick_table_full.csv.gz` (833 KB compressed)** — Full tick-level telemetry. Higher resolution than anything I've been working with. Could contain microstructure signatures invisible at the epoch level.

7. **`mapping_graphsig` files (68 KB each, compressed)** — Graph-signature mappings between consecutive snapshots. These would show *which specific structural features* are being preserved vs. reorganized at the individual-node level.

8. **`rolling_var_autocorr_entropy.csv` and `rolling_var_autocorr_pca_speed.csv` (354 KB + 339 KB)** — I got summary stats but never did the deeper time-series analysis: where do the variance and autocorrelation *change character*? Are there sharp transitions that correspond to behavioral events?
