# INDX-CAD

Reverse engineered CAD of Prusa's INDX toolhead, with internal geometry.

<img width="809" height="553" alt="INDX assembly" src="https://github.com/user-attachments/assets/29ac0a60-3e2b-4966-8189-d21959907e90" />

## About

The geometry here was reverse engineered from Prusa's printable model, which was licensed
under CC BY-SA 4.0. That model and its remixes were later removed from Printables; the
original 3MF is included in this repository for archival purposes.

Prusa's mesh was clean enough for parametric geometry to be extracted and converted to
STEP. The mechanism is complete: fillets, internal geometry, and the moving assemblies are
all modeled.

<img width="485" height="671" alt="INDX detail" src="https://github.com/user-attachments/assets/5aeaa665-9ed7-467b-a163-218ffc47b127" />

<img width="764" height="567" alt="INDX section view" src="https://github.com/user-attachments/assets/301a60b8-3b15-4db1-89bb-ff787620c988" />

## Files

| File | Description |
| --- | --- |
| `INDX.f3z` | Fusion 360 archive — full parametric assembly |
| `INDX.step` | STEP export for use in other CAD packages |
| `indx_toolhead_8t.3mf` | Prusa's original printable mesh, archived |

## Viewer

A live 3D viewer and download links are published as a static site from `index.html`.

## License

CC BY-SA 4.0. See [license.md](license.md).
