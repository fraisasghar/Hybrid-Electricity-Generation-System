yghvggdsgcmkhjz
<!--------|---------|---------|------------------- Main Banner  -------------------------------------------------------------->


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:7a2e2e,100:c17817&height=210&section=header&text=Swirled%20Tubes%20Heat%20Exchanger&fontSize=46&fontAlign=50&fontAlignY=38&animation=fadeIn&fontColor=ffffff&desc=CAD%20Design%20|%20Conjugate%20Heat%20Transfer%20|%20Turbulent%20CFD%20|%20Hybrid%20Nanofluid%20|%20COMSOL%20Multiphysics&descAlign=50&descAlignY=68&descSize=18&descColor=e8d8c3&shadow=true" alt="Header" />
</div>

<h3 align="center">CAD Design and CFD Simulation of a Helically Swirled Tube Heat Exchanger Cooled by a Hybrid Nanofluid</h3>


<p align="center">
  <img src="https://img.shields.io/badge/CFD-COMSOL%20Multiphysics-7a2e2e?style=for-the-badge&labelColor=1c1c1c&logo=comsol&logoColor=f2c9c9" />
  <img src="https://img.shields.io/badge/Turbulence-k--%CE%B5%20RANS-1e4620?style=for-the-badge&labelColor=1c1c1c&logo=windowsterminal&logoColor=bfe0c2" />
  <img src="https://img.shields.io/badge/Coupling-Conjugate%20Heat%20Transfer-4a2c6d?style=for-the-badge&labelColor=1c1c1c&logo=thunderbird&logoColor=d8c6ea" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Coolant-Hybrid%20Nanofluid-1b3a5c?style=for-the-badge&labelColor=2b2b2b&logo=molecule&logoColor=bcd4ea" />
  <img src="https://img.shields.io/badge/Effectiveness-75.3%25-1e4620?style=for-the-badge&labelColor=2b2b2b&logo=speedtest&logoColor=bfe0c2" />
  <img src="https://img.shields.io/badge/Domains-12-4a2c6d?style=for-the-badge&labelColor=2b2b2b&logo=googleearth&logoColor=d8c6ea" />
  <img src="https://img.shields.io/badge/License-MIT-8a6d1d?style=for-the-badge&labelColor=2b2b2b&logo=opensourceinitiative&logoColor=f0dfa8" />
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:2b2b2b,100:7a2e2e&height=3">

<br>



<br>

## Overview

This Project is a complete CAD-to-CFD study of a compact double pipe heat exchanger whose inner tube follows a helical, swirled centreline instead of a straight axis. A hybrid **Al₂O₃–CuO–CNT nanofluid** flows through the swirled core as the hot stream, exchanging heat through a steel tube wall with plain water flowing countercurrently in the annular shell space.

The full assembly, imported from SolidWorks, was solved in COMSOL Multiphysics as a steady, three dimensional, **conjugate heat transfer** problem: turbulent RANS flow (standard k–ε model) coupled to the energy equation across both fluid domains and the surrounding solid, with no assumed film coefficient anywhere in the model. Every reported performance number, heat duty, log mean temperature difference, overall conductance, and effectiveness, is either a direct field output or a hand calculation built on top of it and cross validated by two independent thermal design methods.

<br>

## Results at a Glance

<div align="center">

| Heat Duty | Effectiveness | Overall Conductance | Pressure Penalty |
|:---:|:---:|:---:|:---:|
| **4.14 kW** | **75.3 %** | **220 W/K** | **≈ 2 Pa** |

</div>

<br>




<table>
  <tr>
    <td align="center">
      <img width="395" height="169" alt="image" src="https://github.com/user-attachments/assets/8ec93907-c0d5-4de6-9eeb-56abdf75739a" />
      <br />
      <b>CAD Model</b>
    </td>
    <td align="center">
      <img width="484" height="167" alt="image" src="https://github.com/user-attachments/assets/abc6853b-ed05-4055-9c75-aaadbe52b35e" />
      <br />
      <b style="color:white;">CAD Inner View</b>
    </td>
  </tr>
  
  <tr>
    <td align="center">
      <img width="377" height="200" alt="image" src="https://github.com/user-attachments/assets/7c478337-4680-4b32-92bf-d21efb4777fd" />
      <br />
      <b>Mesh</b>
    </td>
    <td align="center">
      <img width="392" height="202" alt="image" src="https://github.com/user-attachments/assets/f6483409-689c-4c4a-af5c-dafffd06d269" />
      <br />
      <b style="color:white;">Mesh Inner View</b>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img width="396" height="198" alt="image" src="https://github.com/user-attachments/assets/106f3aed-3b34-4474-90bd-6bf50b132f6e" />
      <br />
      <b>Temperature</b>
    </td>
    <td align="center">
      <img width="365" height="199" alt="image" src="https://github.com/user-attachments/assets/76bce2f7-3b4e-4ec2-be98-6871fe2e0253" />
      <br />
      <b style="color:white;">Temperature Inner View</b>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img width="353" height="194" alt="image" src="https://github.com/user-attachments/assets/1bf69fea-4d3d-4a1f-b852-6f92c9b0d7d6" />
      <br />
      <b>Velocity</b>
    </td>
    <td align="center">
      <img width="359" height="192" alt="image" src="https://github.com/user-attachments/assets/63406857-489e-4b0f-aa00-d4f8a3ddd2ad" />
      <br />
      <b style="color:white;">Velocity Streamline</b>
    </td>
  </tr>
    <tr>
    <td align="center">
      <img width="365" height="191" alt="image" src="https://github.com/user-attachments/assets/c80aa756-dee7-4d5d-b582-0587ede11dd0" />
      <br />
      <b>Inner Fluid Velocity</b>
    </td>
    <td align="center">
      <img width="368" height="197" alt="image" src="https://github.com/user-attachments/assets/9326aa31-18ca-4e27-8725-0efd0de500dd" />
      <br />
      <b style="color:white;">Outer Fluid Velocity</b>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img width="365" height="194" alt="image" src="https://github.com/user-attachments/assets/cb68e385-199f-4ff0-b0e7-6785622d88bc" />
      <br />
      <b>Pressure</b>
    </td>
    <td align="center">
      <img width="371" height="199" alt="image" src="https://github.com/user-attachments/assets/d9288931-214c-4b61-9dbe-74900f1d8ddc" />
      <br />
      <b style="color:white;">Pressure Inner View</b>
    </td>
  </tr>
    <tr>
    <td align="center">
      <img width="391" height="194" alt="image" src="https://github.com/user-attachments/assets/1d2eff2c-997e-46a6-89f3-06ad38bd95f8" />
      <br />
      <b>Temp & Fluid Flow</b>
    </td>
    <td align="center">
      <img width="394" height="191" alt="image" src="https://github.com/user-attachments/assets/789bb199-0b87-42e9-9151-8717cf292db2" />
      <br />
      <b style="color:white;">Temp & Inner Fluid Flow</b>
    </td>
  </tr>
      <tr>
    <td align="center">
      <img width="334" height="194" alt="image" src="https://github.com/user-attachments/assets/3724ae6f-79e0-4212-ac3d-15b084d6b2b6" />
      <br />
      <b>Velocity Field</b>
    </td>
    <td align="center">
      <img width="365" height="194" alt="image" src="https://github.com/user-attachments/assets/5d5d40cc-1710-4231-8fc5-8811480b2863" />
      <br />
      <b style="color:white;">Temp & Inner Fluid Flow</b>
    </td>
  </tr>
</table>

















## How It Works

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryTextColor':'#e7ded4', 'lineColor':'#7a2e2e', 'fontFamily':'"Segoe UI", Helvetica, Arial, sans-serif', 'fontSize':'15px'}}}%%
flowchart LR
    A(["Geometry"]) --> B{{"Materials"}}
    B --> C[["Physics"]]
    C --> D[("Mesh")]
    D --> E[["Solve"]]
    E --> F(["Post-process"])

    classDef charcoal fill:#14181f,stroke:#3a3f4a,stroke-width:2px,color:#e7ded4
    classDef darkred fill:#7a2e2e,stroke:#4a1c1c,stroke-width:2px,color:#f4ede4
    classDef navy fill:#1b263b,stroke:#0e1522,stroke-width:2px,color:#e7ded4
    classDef darkblue fill:#2c4870,stroke:#182a44,stroke-width:2px,color:#f4ede4
    classDef darkyellow fill:#8a6d1d,stroke:#5a4712,stroke-width:2px,color:#f4ede4

    class A charcoal
    class B navy
    class C darkred
    class D darkyellow
    class E darkred
    class F darkblue
```

Every stage feeds the next: geometry defines where materials sit, materials and physics define the mesh resolution needed, and the solved fields are what every hand calculation in this repository is built from.

<br>

## Domain Breakdown

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'pieOuterStrokeColor':'#e7ded4', 'pieSectionTextColor':'#f4ede4', 'pieTitleTextColor':'#14181f', 'pieStrokeColor':'#14181f', 'pieLegendTextColor':'#ffffff', 'pieOpacity':'1', 'pie1':'#f28c28', 'pie2':'#1b263b', 'pie3':'#7a2e2e', 'pie4':'#2c4870'}}}%%
pie showData
    title 12 Domains by Material
    "Steel AISI 4340" : 7
    "Acrylic Plastic" : 3
    "Al2O3-CuO-CNT Nanofluid (hot)" : 1
    "Water (cold)" : 1
```

**Hot stream**: Al₂O₃–CuO–CNT hybrid nanofluid, 1.2% concentration, swirled inner tube
**Cold stream**: Water, annular shell passage
**Structure**: Steel AISI 4340 tube wall and baffles, acrylic outer shell and headers

<br>

## Governing Equations

| Equation | Expression |
|---|---|
| Continuity | ∇·(ρ **u**) = 0 |
| Momentum (RANS) | ρ(**u**·∇)**u** = −∇p + ∇·[(μ + μₜ)(∇**u** + ∇**u**ᵀ)] |
| k–ε Turbulence | μₜ = ρ Cμ k² / ε |
| Conjugate Energy | ρ Cp **u**·∇T = ∇·(k∇T)  in fluid, ∇·(kₛ∇T) = 0 in solid |

The fluid and solid energy equations are coupled at every internal boundary through continuity of temperature and heat flux, no convective film coefficient is prescribed anywhere, the wall to fluid heat transfer coefficient is an emergent result of the coupled solution.

<br>

## Coupled Solver Loop

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryTextColor':'#e7ded4', 'lineColor':'#7a2e2e', 'fontFamily':'"Segoe UI", Helvetica, Arial, sans-serif', 'fontSize':'15px'}}}%%
flowchart TD
    A(["Solve RANS Momentum"]) --> B[["Update k-e Turbulence"]]
    B --> C[("Update T-dependent Properties")]
    C --> D[["Solve Conjugate Energy"]]
    D --> E{"Residual below<br/>1e-4 tolerance?"}
    E -- No --> A
    E -- Yes --> F(("Converged<br/>Solution"))

    classDef navy fill:#1b263b,stroke:#0e1522,stroke-width:2px,color:#e7ded4
    classDef darkyellow fill:#8a6d1d,stroke:#5a4712,stroke-width:2px,color:#f4ede4
    classDef darkred fill:#7a2e2e,stroke:#4a1c1c,stroke-width:2px,color:#f4ede4
    classDef darkblue fill:#2c4870,stroke:#182a44,stroke-width:3px,color:#f4ede4

    class A,D navy
    class B,C darkyellow
    class E darkred
    class F darkblue
```

<br>

## Materials

| Property | Steel AISI 4340 | Acrylic Plastic | Water (cold) | Al₂O₃–CuO–CNT 1.2% (hot) |
|---|---|---|---|---|
| Density (kg/m³) | 7850 | 1190 | 997 | 1021.7 |
| Specific heat, Cp (J/(kg·K)) | 475 | 1470 | 4182 | 3997 |
| Thermal conductivity, k (W/(m·K)) | 44.5 | 0.18 | 0.613 | 1.003 |

<sub>The 1.2% nanofluid raises thermal conductivity by ≈ 35% over the base fluid across the 0.3–1.2% concentration range defined in the model library.</sub>

<br>

## Boundary Conditions

| Boundary | Flow Condition | Thermal Condition |
|---|---|---|
| Hot inlet | Mass flow = 8 L/min | 65.0 °C |
| Hot outlet | Pressure = 0 Pa (gauge) | Convective outflow |
| Cold inlet | Mass flow = 2 L/min | 25.0 °C |
| Cold outlet | Pressure = 0 Pa (gauge) | Convective outflow |
| Tube wall | No slip, wall functions | Conjugate, continuity of T and flux |
| External casing | Not applicable | Thermally insulated |

<br>

## Performance Summary

| Metric | Value | Method |
|---|---|---|
| Heat duty, Q | 4.14 kW | Average of hot/cold energy balance (1.4% closure) |
| Log mean temperature difference | 18.83 K | Counter current LMTD |
| Overall conductance, UA | 220.0 W/K | Q / ΔT_lm |
| Overall conductance, UA (cross check) | 221.7 W/K | ε–NTU method (0.8% agreement) |
| Effectiveness, ε | 75.3% | ε = Q / Q_max |
| Hot side pressure change | ≈ 2.39 Pa | Boundary averaged, CFD |
| Cold side pressure change | ≈ 1.22 Pa | Boundary averaged, CFD |

<br>

## Roadmap

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryTextColor':'#e7ded4', 'lineColor':'#8a6d1d', 'fontFamily':'"Segoe UI", Helvetica, Arial, sans-serif', 'fontSize':'14px'}}}%%
flowchart TB
    P1(["Phase 1 — CAD Assembly and Conjugate CFD Model"]) --> P2(["Phase 2 — Hand-Calculated Performance Validation"])
    P2 --> P3(["Phase 3 — Nanofluid Concentration Sweep, 0.3 to 1.2%"])
    P3 --> P4(["Phase 4 — Wetted Area and True U Coefficient"])
    P4 --> P5(["Phase 5 — Mesh Independence Study"])

    classDef done fill:#1b263b,stroke:#0e1522,stroke-width:2px,color:#f4ede4
    classDef done2 fill:#2c4870,stroke:#182a44,stroke-width:2px,color:#f4ede4
    classDef active fill:#7a2e2e,stroke:#4a1c1c,stroke-width:2px,color:#f4ede4
    classDef future fill:#8a6d1d,stroke:#5a4712,stroke-width:2px,color:#f4ede4

    class P1 done
    class P2 done2
    class P3 active
    class P4,P5 future
```

<br>

## Tech Stack

Built in **COMSOL Multiphysics** using the Heat Transfer Module and CFD Module: Heat Transfer in Solids and Fluids, Turbulent Flow (k–ε), and the Nonisothermal Flow multiphysics coupling, solved on a physics controlled tetrahedral mesh with five layer boundary layers at every fluid wall. Geometry authored in SolidWorks and imported as a parasolid CAD file. Post-processing and hand calculations documented in the full report.

<br>

## Getting Started

1. Clone the repo and open `model/vortherm.mph` in COMSOL Multiphysics (Heat Transfer Module + CFD Module required).
2. Review the Global Definitions node for the four operating parameters: `m_hot`, `T_hot`, `m_cold`, `T_cold`.
3. Run the Mesh sequence, then run the Stationary study under Study 1.
4. Open the Results node to reproduce the temperature, velocity, and pressure plots.
5. Cross check the boundary values against Section 6 and Section 7 of `docs/report.pdf`.

<br>

## Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes
4. Open a pull request

<br>

## References

Incropera, F. P., DeWitt, D. P., Bergman, T. L., and Lavine, A. S. *Fundamentals of Heat and Mass Transfer.* John Wiley and Sons.
COMSOL Multiphysics. *Heat Transfer Module and CFD Module User's Guides.* COMSOL AB.
Launder, B. E., and Spalding, D. B. "The Numerical Computation of Turbulent Flows." *Computer Methods in Applied Mechanics and Engineering.*
Kakac, S., Liu, H., and Pramuanjaroenkij, A. *Heat Exchangers: Selection, Rating, and Thermal Design.* CRC Press.

<br>

## License

Distributed under the MIT License. See `LICENSE` for details.

<br>

<div align="center">
<p>Built by <a href="https://github.com/fraisasghar">Frais Asghar</a></p>
</div>

<div align="center">
If this project was useful to you, consider giving it a star. ⭐

<p3 align="center"><sub>Built for the Thermal Engineering &amp; Simulation community &nbsp;&middot;&nbsp; Happy building</sub></p3>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:14181f,100:7a2e2e&height=3">



