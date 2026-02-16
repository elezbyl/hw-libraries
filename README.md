# HW Libraries
This project is just set of libraries for EDA tools. Currently the following EDA are supported:
* KiCAD

## Symbols
### KiCAD 6 plus
* ESP-12S:
  * description:
  * url: https://www.lcsc.com/product-detail/WIFI-Modules_ESP-12S_C82898.html
  * package: RF_Module
* AT24C04-SSHM:
  * description: Two-wire Serial EEPROM
  * url: https://ww1.microchip.com/downloads/en/DeviceDoc/doc0180.pdf
  * package: Memory_EEPROM
* TUSB8020B:
  * description: Two-Port USB 3.0 Hub
  * url: https://www.ti.com/lit/ds/symlink/tusb8020b.pdf
  * package: Interface_USB
* TPS54531:
  * description: SWIFT Step-Down Converter With Eco-mode, 5-A, 28-V Input
  * url: https://www.ti.com/lit/ds/symlink/tps54531.pdf
  * package: Regulator_Switching
* USB3_B:
  * description: USB 3.0 B connector, copy of the internal KiCAD symbol and electrical type for SSTX and SSRX signals changed - SSTX: input, SSRX: output
  * url:
  * package: Connector
* ULN2803C:
  * description: Darlington Transistor Arrays
  * url: https://www.ti.com/lit/ds/symlink/uln2803c.pdf
  * package: Transistor_Array
* SN74AVC4T774PW:
  * description: 4-Bit Dual-Supply Bus Transceiver With Configurable Voltage-Level Shifting and 3-State Outputs With Independent Direction Control Inputs
  * url: https://www.ti.com/lit/ds/symlink/sn74avc4t774.pdf
  * package: Logic_LevelTranslator
* SN74AXCH8T245:
  * description: 8-Bit Dual-Supply Bus Transceiver with Configurable Voltage Translation, Tri-State Outputs, and Bus-Hold CircuitryDirection Control Inputs
  * url: https://www.ti.com/lit/ds/symlink/sn74axch8t245.pdf
  * package: Logic_LevelTranslator
* Bus_PCI_Express_x1_raw:
  * description: Raw version of the Bus_PCI_Express_x1. This symbol does not include PCIe related signals names
  * url: n/a
  * package: Connector

## Footprints
### KiCAD 6 plus
* ESP-12S:
  * description:
  * url: https://www.lcsc.com/product-detail/WIFI-Modules_ESP-12S_C82898.html
  * package: RF_Module
* SO-4_6.5x4.6mm
  * description: DC Optocoupler, Vce 35V, CTR 50-300%, DIP-4
  * url: Datasheet	http://www.soselectronic.cz/a_info/resource/d/pc817.pdf
  * package: Package_SO
* TE_282834-2
  * description: Header, Wire-to-Board, 2 Position, 2.54 mm [.1 in] Centerline, 1 Row, 90° Wire Entry Angle, 30 – 16 AWG Wire Size, PCB Terminal Blocks
  * url: https://www.te.com/en/product-282834-2.html
  * package: Connector_TE-Connectivity
* HTQFP-48-7x7mm-P0.5mm-EP7x7mm
  * description: TUSB8020B, two-port USB 3.0 Hub
  * url: https://www.ti.com/lit/ds/symlink/tusb8020b.pdf
  * package: Package_QFP
* Oscillator_SMD_ECS-xxx-x-36B2-xxx-4Pin_2.5x2.0mm
  * description: Miniature Crystal Clock Oscillator ECS 2236B2 series
  * url: https://ecsxtal.com/store/pdf/ECX-2236B2.pdf
  * package: Oscillator
* L_Bourns_SRP6540_7.2x6.5mm, L_Bourns_SRP6540_7.2x6.5mm_HandSolder
  * description: SRP6540 Series - Shielded Power Inductors
  * url: https://www.bourns.com/docs/product-datasheets/srp6540.pdf
  * package: Inductor_SMD
* USB_A_Amphenol_GSB3111xxxHR
  * description: USB 3.2, Type A, Receptacle, Right Angle, 9 Pins
  * url: https://cdn.amphenol-cs.com/media/wysiwyg/files/drawing/gsb3111xxxhr.pdf
  * package: USB_Connector
* USB_B_Amphenol_GSB3211xxxWEU
  * description: USB 3.2, Type B, Receptacle, Upright Reverse, 9 Pins
  * url: https://cdn.amphenol-cs.com/media/wysiwyg/files/drawing/gsb3211xxxweu.pdf
  * package: USB_Connector
* LED_Wurth_155124RV73200
  * description: LED, Red, Green, SMD, 120°, Dome, R 20mA, G 20mA
  * url: https://www.we-online.com/components/products/datasheet/155124RV73200.pdf
  * package: LED_SMD
* Relay_DPDT_AXICOM_IMSeries_ShortGullWings
  * description: General Purpose Signal Relay, DC, Polarized, Monostable, 2 Form C DPDT-CO, 2 A Contact Rating, 250 VAC Contact Voltage, Axicom IM
  * url: https://www.te.com/en/product-1462037-1.html
  * package: Relay_SMD
* Samtec_PCIE-036-02-X-D-EMS3
  * description: 1.00 mm PCI Express 3.0 Edge Card Connector
  * url: https://www.samtec.com/products/pcie-036-02-f-d-ems3
  * package: Connector_PCBEdge

## 3D Models
### KiCAD 6 plus
* TE_282834-2
  * description: Header, Wire-to-Board, 2 Position, 2.54 mm [.1 in] Centerline, 1 Row, 90° Wire Entry Angle, 30 – 16 AWG Wire Size, PCB Terminal Blocks
  * url: https://www.te.com/en/product-282834-2.html
  * package: Connector_TE-Connectivity
* HTQFP-48-7x7mm-P0.5mm-EP7x7mm
  * description: TUSB8020B, two-port USB 3.0 Hub
  * url: https://www.te.com/en/product-282834-2.html
  * package: Package_QFP
* USB_A_Amphenol_GSB3111xxxHR
  * description: USB 3.2, Type A, Receptacle, Right Angle, 9 Pins
  * url: https://cdn.amphenol-cs.com/media/wysiwyg/files/drawing/gsb3111xxxhr.pdf
  * package: USB_Connector
* USB_B_Amphenol_GSB3211xxxWEU
  * description: USB 3.2, Type B, Receptacle, Upright Reverse, 9 Pins
  * url: https://cdn.amphenol-cs.com/media/wysiwyg/files/drawing/gsb3211xxxweu.pdf
  * package: USB_Connector
