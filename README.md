# Resonance — Therapeutic Sound Frequencies

An interactive web app and open knowledge base for therapeutic sound frequencies, grounded in peer-reviewed research, ancient traditions, and cymatics.

**[Live Demo](https://jtruax.github.io/resonance-sound-frequencies)** &nbsp;|&nbsp; **[Knowledge Base](Sound_Frequencies_Knowledge_Base.md)** &nbsp;|&nbsp; **[Sources](SOURCES.md)**

---

## The App

[Resonance](index.html) is a single-file, zero-dependency web app that lets you play therapeutic frequencies directly in your browser using the Web Audio API.

**Features:**
- 10 frequency categories, including timed Journeys and shamanic drumming
- Brainwave-rate tones play as binaural beats or isochronic pulses; audible tones can carry an optional beat
- 40 Hz click train modelled on the GENUS stimulus (1 ms pulses, 40 per second)
- Single-tone and layer modes with per-layer volume
- Procedural nature ambiance: rain, ocean, wind, fire, thunder and forest
- Ambiance adapts to the session: eventful sounds step back during focus, gamma, Journeys and drum sessions, and everything steps back under the drum
- Session timer with fade-out, plus pause/resume for tones and ambiance together
- Output limiter and loudness matching across frequencies
- Each card shows what actually plays, its source and an evidence level
- Real-time waveform visualizer

**Frequency categories:**
| Category | Frequencies | What plays |
|---|---|---|
| Journeys | 10→6, 10→4.5, 10→16, 10→2 Hz; 10 + 40 Hz | Beat-rate glides over 25–45 min; alpha beat with a 40 Hz click train |
| Deep Sleep & Restoration | 2–3.5 Hz | Delta beats |
| Meditation & Trance | 3.7–7 Hz | Shamanic frame drum (220–270 BPM) and theta beats |
| Relaxation & Stress Relief | 8–12 Hz | Alpha beats |
| Focus & Cognition | 14–20 Hz | Beta beats |
| Neural Coherence & Brain Health | 40 Hz | GENUS-style click train |
| Vibroacoustic | 26–100 Hz | Plain sines for vibroacoustic transducers or bass shakers |
| Chakra Frequencies | 144–475 Hz | Bands from a spectral analysis of chanted OM, mapped to chakras by tradition |
| Solfeggio Frequencies | 396–963 Hz | Modern numerological scale (Puleo & Horowitz, 1999) |
| Earth & Cosmic Resonance | 7.83–33.8 Hz | Beats at the Schumann resonance values |

---

## The Knowledge Base

[`Sound_Frequencies_Knowledge_Base.md`](Sound_Frequencies_Knowledge_Base.md) is the real heart of this project — **a freely available, structured research synthesis you are encouraged to use in your own projects.**

It distills 29 source documents spanning:

- Peer-reviewed clinical studies (fibromyalgia, Alzheimer's, pain, bone healing)
- EEG / brainwave entrainment research
- Schumann resonance and geomagnetic biology
- Vedic sound philosophy and Nāda Brahma
- Cymatics and the physics of resonance
- Shamanic drumming and trance research
- Singing bowl therapy
- Solfeggio frequency history and analysis
- Gamma entrainment (40 Hz) neuroscience

### What's inside

| Section | Contents |
|---|---|
| Earth's Schumann Resonance | Frequencies, harmonics, health effects, key researchers |
| Brainwave States | Delta through Gamma — ranges, mental states, applications |
| Therapeutic Frequencies | Full clinical reference table with evidence and mechanisms |
| Sacred Sound Systems | Vedic Nāda Brahma, OM/AUM frequency analysis, chakra mapping |
| Solfeggio Scale | Historical origins, frequencies, associations |
| Cymatics & Physical Resonance | Chladni figures, water memory, matter organization |
| Shamanic Frequencies | Drumming tempos, cross-cultural trance induction |
| Singing Bowl Therapy | Frequency measurements, clinical outcomes |
| Gamma Entrainment | 40 Hz neuroscience deep-dive, Alzheimer's protocols |
| Frequency Index | Master reference of all frequencies with sources |

### Highlighted findings

- **40 Hz** — Fibromyalgia impact scores fell 81% with 40 Hz body vibration in an open-label pilot of 19 women with no control group (Naghdi et al., 2015). In mice, 40 Hz light flicker cut amyloid-beta by roughly 40–67% depending on the measure (Iaccarino et al., 2016), though a 2023 study failed to replicate this; a 15-person pilot of 40 Hz light and sound found slower brain-volume loss (Chan et al., 2022).
- **50 Hz** — Five minutes of 50 Hz vibration on the forearm raised nitric oxide 374% in healthy adults (Maloney-Hinds et al., 2009).
- **7.83 Hz** — Earth's fundamental Schumann resonance. Isolation experiments by Wever suggested extremely-low-frequency fields can influence human circadian rhythms.
- **Shamanic drumming** at 220–255 BPM (3.7–4.2 Hz) — with journey instructions, listeners reported dreamlike states far more often than with relaxation instructions (Gingras et al., 2014), and experienced practitioners showed higher gamma power while drumming (Huels et al., 2021).
- **OM chanting** — a spectral analysis found 7–8 peaks, which the authors mapped to traditional chakra bands (Wani et al., 2021).

---

## Use the Knowledge Base in Your Project

The knowledge base text is **MIT licensed** — take it, adapt it, build on it. The source papers it draws on belong to their authors; see [SOURCES.md](SOURCES.md).

Some ideas:

- Build your own frequency app
- Train or prompt an AI model with the research synthesis
- Create a meditation or binaural beat generator
- Build a data visualization of frequency-effect relationships
- Use it as a research starting point for a wellness or neuroscience project

If you build something with it, feel free to open an issue or discussion — I would love to see what you make.

---

## Running Locally

No build step required. Just open `index.html` in a browser:

```bash
git clone https://github.com/JTruax/resonance-sound-frequencies.git
cd resonance-sound-frequencies
open index.html   # macOS
# or: xdg-open index.html (Linux) / start index.html (Windows)
```

---

## Sources

[SOURCES.md](SOURCES.md) lists the 29 documents behind the knowledge base, with DOIs and links where available, plus the other studies the app cites. They include:

- Naghdi et al., 2015 (fibromyalgia / 40 Hz vibration)
- Iaccarino et al., 2016 and Chan et al., 2022 (gamma stimulation and Alzheimer's)
- Stolc et al., 2021 and Schlegel & Füllekrug (Schumann resonance)
- Stapleton et al., 2020 (meditation EEG, 223 participants)
- Gingras et al., 2014 and Huels et al., 2021 (shamanic drumming and trance)
- Hungerford, 2017 (a critical look at the solfeggio frequencies)

---

## License

[MIT](LICENSE) for the code and the knowledge base text — use freely, attribution appreciated but not required. The third-party works in [SOURCES.md](SOURCES.md) aren't covered.
