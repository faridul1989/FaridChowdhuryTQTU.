# FaridChowdhuryTQTU.
```json
{
  "voyager1_plasma_wave_data": {
    "mission_metadata": {
      "launch_date": "1977-09-05",
      "heliopause_crossing": "2012-08-25",
      "distance_2025": {
        "miles": 15000000000,
        "km": 24000000000,
        "au": 164.7
      },
      "instrument": {
        "name": "Plasma Wave Subsystem (PWS)",
        "measures": "Electron density fluctuations, plasma waves",
        "frequency_range": "10 Hz–56 kHz"
      },
      "data_context": "Interstellar medium, post-heliopause"
    },
    "plasma_waves": {
      "description": "Persistent electron density oscillations translated to audible frequencies",
      "data": [
        {
          "parameter": "Wave Frequency",
          "value_hz": "2000–3000",
          "notes": "Detected post-heliopause (2012–2025); corresponds to denser LISM vs. heliosphere (~300 Hz)",
          "source": ["Gurnett et al. 2013", "Gurnett et al. 2015", "Ocker et al. 2021"]
        },
        {
          "parameter": "Electron Plasma Density",
          "value_cm3": "0.08–0.147",
          "average_cm3": 0.1,
          "notes": "Derived from f_p ≈ 9√n_e kHz; variability due to density gradients",
          "source": ["Gurnett et al. 2015", "Ocker et al. 2021", "Burlaga et al. 2022"]
        },
        {
          "parameter": "Detection Events",
          "value": "October–November 2012, April–May 2013, persistent 2013–2025",
          "notes": "Initial bursts triggered by CMEs; continuous 'hum' detected later",
          "source": ["Gurnett et al. 2013", "Ocker et al. 2021"]
        },
        {
          "parameter": "Thermal Energy Density",
          "value_eV_cm3": "0.1–0.2",
          "notes": "Contributes to total charged particle energy (~1.08 eV cm^-3)",
          "source": ["Ocker et al. 2021", "Chowdhury 2025"]
        }
      ],
      "energy_density": {
        "total_eV_cm3": 2.6,
        "breakdown": {
          "cosmic_rays": "0.83–1.02",
          "magnetic": 0.62,
          "thermal_plasma": 0.18,
          "radiation": "0.6–0.8",
          "kinetic_turbulent": "0.1–0.3"
        },
        "charged_particle_contribution": {
          "value_eV_cm3": 1.08,
          "percentage": 41.5,
          "notes": "Cosmic rays + thermal plasma; no dark energy residuals (~10^-8 eV cm^-3)"
        }
      },
      "tqt_interpretation": {
        "phi_field": "Polarity gradients drive plasma oscillations, structuring LISM",
        "entropy_duality": "Regenerative (R) wave excitation vs. degenerative (D) damping, ratio ~φ (1.618)",
        "charged_dominance": "Plasma waves and particles dominate energy budget, supporting TQTU’s plasma-centric cosmology"
      }
    },
    "video_reference": {
      "title": "The Strange Sound Voyager 1 Was Never Meant to Hear",
      "url": "https://youtu.be/Cxo5VyRtJUo",
      "published_date": "2025-09-02",
      "notes": "Describes audible translation of plasma waves, highlighting LISM density and dynamics"
    },
    "tqt_summary": {
      "phi_field": "Drives plasma wave persistence, echoing cosmic torsion",
      "entropy_duality": "Balances regenerative (R) oscillations with degenerative (D) diffusion, ratio ~1.618",
      "cosmic_connection": "LISM plasma dynamics align with TQTU, negating dark energy need"
    }
  }
}
```
# Voyager 1 TQTU Dataset

This repository contains a dataset from Voyager 1’s Plasma Wave Subsystem (PWS) for the article *"Voyager Data and the Absence of Dark Energy: A TQTU Perspective"* by Prof. Dr. Md. Faridul Islam Chowdhury (Tanfarid Vision Research Institute, 2025). The data focus on plasma wave detections in the local interstellar medium (LISM), including the audible “hum” from the video *"The Strange Sound Voyager 1 Was Never Meant to Hear"* (YouTube, 2025-09-02), interpreted under the Tanfarid Quantum Thermodynamic Universe (TQTU) framework.

## Contents
- **File**: `voyager1_plasma_wave_data.json`
- **Description**: JSON dataset with Voyager 1 measurements:
  - **Mission Metadata**: Launch (1977), heliopause crossing (2012), distance (164.7 AU).
  - **Plasma Waves**: Frequencies (2–3 kHz), electron density (0.08–0.147 cm⁻³), energy (~0.1–0.2 eV cm⁻³).
  - **Energy Density**: Total ~2.6 eV cm⁻³, charged particles 41.5%, no dark energy residuals.
  - **TQTU Interpretations**: \(\Phi\)-fields, entropy duality (\(S = R + D\)), charged dominance.
  - **Video Reference**: Links to YouTube video for context.
- **Sources**: Peer-reviewed (Science, ApJ, Nature Astronomy, 2013–2022).
- **License**: MIT License.

## Usage
- **Access**: Download `voyager1_plasma_wave_data.json` for analysis in Python, MATLAB, etc.
- **Example**:
  ```python
  import json
  with open('voyager1_plasma_wave_data.json', 'r') as file:
      data = json.load(file)
  print(data['voyager1_plasma_wave_data']['plasma_waves']['data'])
  ```json
{
  "voyager1_plasma_wave_data": {
    "mission_metadata": {
      "launch_date": "1977-09-05",
      "heliopause_crossing": "2012-08-25",
      "distance_2025": {
        "miles": 15000000000,
        "km": 24000000000,
        "au": 164.7
      },
      "instrument": {
        "name": "Plasma Wave Subsystem (PWS)",
        "measures": "Electron density fluctuations, plasma waves",
        "frequency_range": "10 Hz–56 kHz"
      },
      "data_context": "Interstellar medium, post-heliopause, 2012–2025"
    },
    "plasma_waves": {
      "description": "Persistent electron density oscillations translated to audible 'hum' at 2–3 kHz",
      "data": [
        {
          "parameter": "Wave Frequency",
          "value_hz": "2000–3000",
          "average_hz": 2400,
          "notes": "Detected post-heliopause (2012–2025); corresponds to LISM density ~0.1 cm^-3 vs. heliosphere ~0.001 cm^-3",
          "source": ["Gurnett et al. 2013", "Gurnett et al. 2015", "Ocker et al. 2021"]
        },
        {
          "parameter": "Electron Plasma Density",
          "value_cm3": "0.05–0.147",
          "average_cm3": 0.1,
          "notes": "Derived from f_p ≈ 9√n_e kHz; matches Voyager paper (0.08–0.147 cm^-3)",
          "source": ["Gurnett et al. 2013", "Gurnett et al. 2015", "Ocker et al. 2021", "Burlaga et al. 2022"]
        },
        {
          "parameter": "Detection Events",
          "value": "Bursts: Oct–Nov 2012, Apr–May 2013; Persistent: 2017–2025",
          "event_count": ">100000",
          "notes": "Initial bursts CME-triggered; persistent 'hum' indicates stable LISM dynamics",
          "source": ["Gurnett et al. 2013", "Ocker et al. 2021"]
        },
        {
          "parameter": "Thermal Energy Density",
          "value_eV_cm3": "0.1–0.2",
          "notes": "Contributes to total charged particle energy (~1.08 eV cm^-3); calculated from n ≈ 0.1 cm^-3, T ≈ 7000 K",
          "source": ["Ocker et al. 2021", "Chowdhury 2025"]
        }
      ],
      "energy_density": {
        "total_eV_cm3": 2.6,
        "breakdown": {
          "cosmic_rays": "0.83–1.02",
          "magnetic": 0.62,
          "thermal_plasma": 0.18,
          "plasma_waves": "0.1–0.2",
          "radiation": "0.6–0.8",
          "kinetic_turbulent": "0.1–0.3"
        },
        "charged_particle_contribution": {
          "value_eV_cm3": 1.08,
          "percentage": 41.5,
          "notes": "Cosmic rays + thermal plasma + waves; no dark energy residuals (~10^-8 eV cm^-3)"
        }
      },
      "tqt_interpretation": {
        "phi_field": "Polarity gradients drive plasma oscillations, structuring LISM dynamics",
        "entropy_duality": "Regenerative (R) wave excitation vs. degenerative (D) damping, ratio ~φ (1.618)",
        "charged_dominance": "Plasma waves and particles dominate energy budget, negating dark energy"
      }
    },
    "video_reference": {
      "title": "The Strange Sound Voyager 1 Was Never Meant to Hear",
      "url": "https://youtu.be/Cxo5VyRtJUo",
      "published_date": "2025-09-02",
      "notes": "Describes audible translation of 2–3 kHz plasma waves, highlighting LISM density and dynamics"
    },
    "tqt_summary": {
      "phi_field": "Drives persistent plasma wave 'hum', echoing cosmic torsion",
      "entropy_duality": "Balances regenerative (R) oscillations with degenerative (D) diffusion, ratio ~1.618",
      "cosmic_connection": "LISM plasma dynamics align with TQTU, supporting plasma-centric cosmology"
    }
  }
}
```
