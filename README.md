# SweetSafe

![SweetSafe](./images/3drt_rotated.png)

Este repositório contém os arquivos do esquemático e da PCB do projeto SweetSafe, um "cofre" de doces com Raspberry Pi Pico. Inclui uma descrição dos componentes utilizados e instruções para montagem.

## Pastas e Arquivos

- **kicad/**: Contém os arquivos de esquemático e PCB do projeto, bem como o principal do KiCad

  - `SweetSafe.kicad_pro`: Arquivo do KiCad
  - `SweetSafe.kicad_sch`: Esquemático do projeto
  - `SweetSafe.kicad_pcb`: Layout para a PCB do projeto

- **BOM.csv**: Lista de materiais do projeto.

- **images/**: Contém as imagens do projeto

## Imagens

### Esquemático

![Esquemático](./images/sch.png)

### PCB

![PCB](./images/pcb.png)

### Visão 3D

![3D](./images/3d.png)

3D com RayTracing (porque é maneiro)
![3D RayTracing](./images/3drt.png)

## BOM (Bill of Materials)

| Designator           | Footprint                                          | Quantity |
| -------------------- | -------------------------------------------------- | -------- |
| Switch fim de curso  | SW_MS0850502F030P1A                                | 1        |
| Resistor 220 ohms    | R_Axial_DIN0414_L11.9mm_D4.5mm_P15.24mm_Horizontal | 2        |
| Resistor 10k ohms    | R_Axial_DIN0414_L11.9mm_D4.5mm_P15.24mm_Horizontal | 1        |
| Buzzer               | Buzzer_15x7.5RM7.6                                 | 1        |
| Transistor NPN BC337 | TO-92_Inline_Wide                                  | 1        |
| Raspberry Pi Pico W  | RPi_Pico_SMD_TH                                    | 1        |
| Conector Barrel Jack | BarrelJack_Horizontal                              | 1        |
| Header Fêmea 1x02    | PinSocket_1x02_P2.54mm_Horizontal                  | 3        |

## Gerbers

Os arquivos Gerber estão disponíveis na última release e na pasta `/kicad/gerbers`
