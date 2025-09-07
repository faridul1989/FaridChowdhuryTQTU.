```json
{
  "voyager_data": {
    "mission_metadata": {
      "spacecraft": [
        {
          "name": "Voyager 1",
          "launch_date": "1977-09-05",
          "mass_kg": 825,
          "power_source": "Radioisotope Thermoelectric Generators (RTGs)",
          "initial_power_W": 470,
          "power_2025_W": 205,
          "current_distance_2025": {
            "au": 164.7,
            "km": 24000000000,
            "miles": 15000000000
          },
          "velocity_km_s": 17,
          "direction": "35° north of ecliptic, toward Ophiuchus (RA 17h28m, Dec -12°)",
          "heliopause_crossing": "2012-08-25 at 121.6 au",
          "data_volume": "67 kB per transmission, ~1 GB/year",
          "communication": "X-band (8.4 GHz, ~20 W), S-band (2.3 GHz, backup)",
          "notes": "Farthest human-made object; operational despite thruster issues (2024)"
        },
        {
          "name": "Voyager 2",
          "launch_date": "1977-08-20",
          "mass_kg": 825,
          "power_source": "RTGs",
          "initial_power_W": 470,
          "power_2025_W": 205,
          "current_distance_2025": {
            "au": 137.1,
            "km": 20500000000,
            "miles": 12700000000
          },
          "velocity_km_s": 15.4,
          "direction": "48° south of ecliptic, toward Telescopium",
          "heliopause_crossing": "2018-11-05 at 119 au",
          "data_volume": "67 kB per transmission, ~1 GB/year",
          "communication": "X-band (8.4 GHz), S-band (backup)",
          "notes": "Only probe to visit Uranus and Neptune"
        }
      ],
      "instruments": [
        {
          "name": "Plasma Wave Subsystem (PWS)",
          "function": "Measures electric field oscillations",
          "range_Hz": "10–56000",
          "notes": "Detects plasma density via f_p ≈ 9√n_e kHz"
        },
        {
          "name": "Cosmic Ray Subsystem (CRS)",
          "function": "Measures high-energy particles",
          "range_MeV": "0.5–500",
          "notes": "Active in LISM for cosmic ray flux"
        },
        {
          "name": "Low-Energy Charged Particle (LECP)",
          "function": "Measures low-energy ions/electrons",
          "range_keV": "10–11000",
          "notes": "Tracks solar wind and LISM particles"
        },
        {
          "name": "Magnetometer (MAG)",
          "function": "Measures magnetic fields",
          "range_nT": "0.01–100",
          "notes": "LISM field ~0.47–0.52 nT"
        }
      ],
      "sources": ["NASA Science 2025", "Voyager Program 2025", "TheSkyLive.com 2025"]
    },
    "trajectory": {
      "description": "Hyperbolic escape path set by gravity assists; no turns in LISM",
      "data": [
        {
          "spacecraft": "Voyager 1",
          "events": [
            {
              "event": "Jupiter Flyby",
              "date": "1979-03-05",
              "distance_au": 5.2,
              "closest_approach_km": 349000,
              "velocity_gain_km_s": 10,
              "direction_change": "~90° toward Saturn",
              "notes": "Gravity assist, hyperbolic path",
              "source": ["NASA Science 2025", "TheSkyLive.com 2025"]
            },
            {
              "event": "Saturn/Titan Flyby",
              "date": "1980-11-12",
              "distance_au": 9.5,
              "closest_approach_km": "Titan: 4000, Saturn: 124000",
              "velocity_gain_km_s": 7,
              "direction_change": "35° north of ecliptic",
              "notes": "Set interstellar path; Titan science priority",
              "source": ["NASA Science 2025", "TheSkyLive.com 2025"]
            },
            {
              "event": "Heliopause Crossing",
              "date": "2012-08-25",
              "distance_au": 121.6,
              "velocity_km_s": 17,
              "direction_change": "None",
              "notes": "Entered LISM; no solar wind influence",
              "source": ["Gurnett et al. 2013"]
            },
            {
              "event": "2017 TCM",
              "date": "2017-12",
              "distance_au": 140,
              "delta_v_m_s": "<0.01",
              "direction_change": "None (attitude only)",
              "notes": "Antenna pointing; hydrazine ~0.1 kg",
              "source": ["NASA 2017"]
            }
          ],
          "current_status_2025": {
            "position_au": 164.7,
            "velocity_km_s": 17,
            "direction": "Fixed toward Ophiuchus",
            "notes": "No trajectory changes; ballistic escape"
          }
        },
        {
          "spacecraft": "Voyager 2",
          "events": [
            {
              "event": "Jupiter Flyby",
              "date": "1979-07-09",
              "distance_au": 5.2,
              "closest_approach_km": 570000,
              "velocity_gain_km_s": 10,
              "direction_change": "~90° toward Saturn",
              "notes": "Gravity assist",
              "source": ["NASA Science 2025"]
            },
            {
              "event": "Saturn Flyby",
              "date": "1981-08-25",
              "distance_au": 9.5,
              "closest_approach_km": 161000,
              "velocity_gain_km_s": 7,
              "direction_change": "Toward Uranus",
              "notes": "Set path for Uranus/Neptune",
              "source": ["NASA Science 2025"]
            },
            {
              "event": "Uranus Flyby",
              "date": "1986-01-24",
              "distance_au": 19.2,
              "closest_approach_km": 81500,
              "velocity_gain_km_s": 4,
              "direction_change": "Toward Neptune",
              "notes": "Extended mission",
              "source": ["NASA Science 2025"]
            },
            {
              "event": "Neptune Flyby",
              "date": "1989-08-25",
              "distance_au": 30.1,
              "closest_approach_km": 5000,
              "velocity_gain_km_s": 3,
              "direction_change": "48° south of ecliptic",
              "notes": "Set interstellar path",
              "source": ["NASA Science 2025"]
            },
            {
              "event": "Heliopause Crossing",
              "date": "2018-11-05",
              "distance_au": 119,
              "velocity_km_s": 15.4,
              "direction_change": "None",
              "notes": "Entered LISM",
              "source": ["NASA Science 2025"]
            }
          ],
          "current_status_2025": {
            "position_au": 137.1,
            "velocity_km_s": 15.4,
            "direction": "Fixed toward Telescopium",
            "notes": "No trajectory changes; ballistic escape"
          }
        }
      ],
      "no_turns_in_lism": {
        "solar_wind_influence": {
          "force_N": "10^-20",
          "notes": "Negligible beyond heliopause; solar wind stops at ~121 au",
          "source": ["Ocker et al. 2021"]
        },
        "magnetic_field_influence": {
          "strength_nT": "0.47–0.52",
          "force_N": "10^-18",
          "notes": "Too weak to deflect 825 kg at 17 km/s",
          "source": ["Gurnett et al. 2015"]
        }
      },
      "tqt_interpretation": {
        "phi_field": "Gravity assists as Φ-field torsion; no LISM deflection",
        "entropy_duality": "Regenerative (R) momentum gain vs. degenerative (D) solar drag, ratio ~φ (1.618)"
      }
    },
    "plasma_waves": {
      "description": "Persistent electron density oscillations in LISM, audible as 'hum'",
      "data": [
        {
          "spacecraft": "Voyager 1",
          "parameters": [
            {
              "name": "Wave Frequency",
              "value_hz": "2000–3000",
              "average_hz": 2400,
              "bandwidth_kHz": "0.2–0.4",
              "notes": "Persistent 2017–2025; denser LISM vs. heliosphere (~300 Hz)",
              "source": ["Gurnett et al. 2013", "Gurnett et al. 2015", "Ocker et al. 2021"]
            },
            {
              "name": "Electron Plasma Density",
              "value_cm3": "0.05–0.147",
              "average_cm3": 0.1,
              "notes": "Derived from f_p ≈ 9√n_e kHz; au-scale fluctuations ~0.001–0.01 cm^-3/au",
              "source": ["Gurnett et al. 2015", "Ocker et al. 2021", "Burlaga et al. 2022"]
            },
            {
              "name": "Detection Events",
              "value": "Bursts: Oct–Nov 2012, Apr–May 2013; Persistent: 2017–2025",
              "event_count": ">100000",
              "notes": "CME-triggered bursts; persistent hum maps turbulence",
              "source": ["Gurnett et al. 2013", "Ocker et al. 2021"]
            },
            {
              "name": "Thermal Energy Density",
              "value_eV_cm3": "0.09–0.18",
              "notes": "u_thermal ≈ (3/2) n k T, T ~7000 K",
              "source": ["Ocker et al. 2021", "Chowdhury 2025"]
            }
          ]
        },
        {
          "spacecraft": "Voyager 2",
          "parameters": [
            {
              "name": "Electron Plasma Density",
              "value_cm3": "0.039–0.12",
              "average_cm3": 0.08,
              "notes": "Derived post-heliopause (2018); consistent with V1",
              "source": ["Burlaga et al. 2022"]
            },
            {
              "name": "Thermal Energy Density",
              "value_eV_cm3": "0.07–0.15",
              "notes": "u_thermal ≈ (3/2) n k T, T ~7000 K",
              "source": ["Burlaga et al. 2022"]
            }
          ]
        }
      ],
      "energy_density": {
        "total_eV_cm3": 2.6,
        "breakdown": {
          "cosmic_rays": "0.83–1.02",
          "magnetic": 0.62,
          "thermal_plasma": 0.18,
          "plasma_waves": "0.09–0.18",
          "radiation": "0.6–0.8",
          "kinetic_turbulent": "0.1–0.3"
        },
        "charged_particle_contribution": {
          "value_eV_cm3": 1.08,
          "percentage": 41.5,
          "notes": "No dark energy residuals (~10^-8 eV cm^-3)"
        }
      },
      "tqt_interpretation": {
        "phi_field": "Polarity gradients drive plasma oscillations, structuring LISM",
        "entropy_duality": "Regenerative (R) wave excitation vs. degenerative (D) damping, ratio ~φ (1.618)",
        "charged_dominance": "Plasma waves and particles dominate, negating dark energy"
      }
    },
    "outer_surface_materials": {
      "description": "Materials for structural integrity and environmental protection",
      "data": [
        {
          "component": "Main Bus and Frame",
          "material": "Aluminum 7075-T6 alloy",
          "properties": {
            "density_g_cm3": 2.81,
            "yield_strength_MPa": 503,
            "thickness_mm": "2–5",
            "purpose": "Structural integrity, radiation resistance"
          },
          "source": ["NASA JPL 1977", "Wikipedia Voyager 1"]
        },
        {
          "component": "Thermal Blanket",
          "material": "Aluminized Kapton film (MLI)",
          "properties": {
            "layers": "25–50",
            "thickness_mm": "2–5",
            "aluminum_coating_um": "0.05–0.1",
            "emissivity": "0.03–0.05",
            "purpose": "Thermal protection"
          },
          "source": ["NASA Voyager Fact Sheet"]
        },
        {
          "component": "High-Gain Antenna Dish",
          "material": "Aluminum honeycomb panels, gold-plated",
          "properties": {
            "diameter_m": 3.7,
            "skin_thickness_mm": 0.5,
            "gold_coating_um": 0.1,
            "conductivity_S_m": "4.1e7",
            "purpose": "RF reflection, corrosion protection"
          },
          "source": ["NSSDCA Voyager Details"]
        },
        {
          "component": "Plasma Wave Antennas",
          "material": "Graphite-epoxy rods, gold-plated beryllium-copper",
          "properties": {
            "length_m": 10,
            "purpose": "Conductive sensitivity"
          },
          "source": ["NASA Instruments"]
        }
      ],
      "tqt_interpretation": {
        "phi_field": "Aluminum-gold polarity aids wave detection, no trajectory deflection",
        "entropy_duality": "Regenerative (R) charge interactions vs. degenerative (D) sputtering, ratio ~φ"
      }
    },
    "video_reference": {
      "title": "The Strange Sound Voyager 1 Was Never Meant to Hear",
      "url": "https://youtu.be/Cxo5VyRtJUo",
      "published_date": "2025-09-02",
      "notes": "Describes audible 2–3 kHz plasma wave hum"
    },
    "tqt_summary": {
      "phi_field": "Drives gravity assists and plasma waves, no LISM turns",
      "entropy_duality": "Balances regenerative (R) dynamics with degenerative (D) dissipation, ratio ~φ",
      "cosmic_connection": "LISM plasma mirrors PSP/IBEX/SDSS, negating dark energy"
    }
  }
}
```
