# Ghost One 
A custom flipper-inspired multi-tool device - **built from scratch.**

I designed and built this project during **Hackclub's Forge program** - [project link](https://forge.hackclub.com/projects/373), to learn more about Embedded electronics, Radio frequency & Infrared communication & soldering, and hardware assembly.


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) ![KiCad](https://img.shields.io/badge/kicad-%2300578F.svg?style=for-the-badge&logo=kicad&logoColor=white)  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)   ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

  <a href="#BOM">BOM</a> •
  <a href="#1">1</a> •
  <a href="#2">2</a> •
  <a href="#3">3</a> •
  <a href="#4">4</a> 

---

# Key Features
- **Powered by an ESP32-S3 N16R8 microcontroller**
- **Built in Infrared & Sub-GHz modules**
- **WiFi 2.4 GHz and Bluetooth LE 5.0 capabilities**
- **Custom designed PCB & 3D Printed Case**
- **Simple menu UI on a 0.96" OLED display**
- **Can emulate Rubber Ducky payloads via bluetooth**
- **Supports microSD for efficient file management**
- **Rechargable 3.7V LiPo battery system (2000mAh)**
- **ESP-NOW communication protocol & messaging**

---

[<img width="859" height="242" alt="image" src="https://github.com/user-attachments/assets/3f53e825-7cd0-4578-a861-d0d30ef59b8a" />](https://forge.hackclub.com/projects/373)

---








# BOM
| Component | Type | Price (£) | Price ($) | Link | Notes |
|-----------|------|-----------|-----------|------|-------|
|ESP32-S3 N16R8 | Microcontroller | £5.93 | $7.96 | [AE](https://www.aliexpress.com/item/1005008802548399.html?spm=a2g0o.productlist.main.4.16805b8bLcQC9c&aem_p4p_detail=2026051300061364889836946000001286645&algo_pvid=065022e8-42c5-42b5-aaff-ecf169ed9b74&algo_exp_id=065022e8-42c5-42b5-aaff-ecf169ed9b74-3&pdp_ext_f=%7B%22order%22%3A%22353%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.02%213.02%21%21%2120.38%2120.38%21%40211b6c1917786559729193403ec478%2112000046724186220%21sea%21UK%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=Hasi70aH9CrQ&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008802548399%7C_p_origin_prod%3A&search_p4p_id=2026051300061364889836946000001286645_1) | N16R8 |
|SSD1306 0.96" OLED | Display | £1.36 | $1.83 | [AE](https://www.aliexpress.com/item/1005006141235306.html?spm=a2g0o.productlist.main.4.6ac2A1PzA1Pz7K&aem_p4p_detail=202605160157441981153121645250002007770&algo_pvid=5e010ee2-f9b9-40bb-a6b3-d520f102246d&algo_exp_id=5e010ee2-f9b9-40bb-a6b3-d520f102246d-3&pdp_ext_f=%7B%22order%22%3A%2225831%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.78%212.78%21%21%2118.77%2118.77%21%40211b81a317789218646164082e51dc%2112000035944225408%21sea%21GB%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=XjqX7L4WBeyV&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006141235306%7C_p_origin_prod%3A&search_p4p_id=202605160157441981153121645250002007770_1) | White 1pcs |
|IR Transceiver TXRX | Infrared | £0.94 | $1.26 | [AE](https://www.aliexpress.com/item/1005010362757450.html?spm=a2g0o.productlist.main.5.74a29dbdDrE3g7&algo_pvid=8444df11-41fb-4403-a919-f1ebd7b2ae92&algo_exp_id=8444df11-41fb-4403-a919-f1ebd7b2ae92-4&pdp_ext_f=%7B%22order%22%3A%22248%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%214.67%212.02%21%21%2131.56%2113.64%21%40210388c917786567925653381e6157%2112000052135552561%21sea%21UK%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895%3BpisId%3A5000000206478089&curPageLogUid=l7yP3v1vi2wo&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010362757450%7C_p_origin_prod%3A) | IR TxRx Kit |
|CC1101 Transceiver | Sub-GHz | £2.62 | $3.52 | [AE](https://www.aliexpress.com/item/1005009014782065.html?spm=a2g0o.productlist.main.33.29a126Nn26Nn5i&algo_pvid=200dabdf-5f6b-46fe-923c-f5ae6292cd1e&algo_exp_id=200dabdf-5f6b-46fe-923c-f5ae6292cd1e-30&pdp_ext_f=%7B%22order%22%3A%221356%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.34%213.34%21%21%213.34%213.34%21%40211b804117787756526547448e72c8%2112000047585219577%21sea%21UK%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=92D53Q8LJe1c&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009014782065%7C_p_origin_prod%3A) | Type-C3 |
|MicroSD Card Reader | Storage | £0.56 | $0.75 | [AE](https://www.aliexpress.com/item/1005006457603056.html?spm=a2g0o.productlist.main.8.13a2IOwOIOwOQD&aem_p4p_detail=202605140014173180347383696490001496921&algo_pvid=2c32a5f8-1e22-4aac-9e0b-b72aefc79eb3&algo_exp_id=2c32a5f8-1e22-4aac-9e0b-b72aefc79eb3-7&pdp_ext_f=%7B%22order%22%3A%221986%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.73%210.73%21%21%214.94%214.94%21%40211b815c17787428571406267e1cac%2112000037267934125%21sea%21UK%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=Ri7MiaIDFzec&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006457603056%7C_p_origin_prod%3A&search_p4p_id=202605140014173180347383696490001496921_2) | TF SPI |
|MicroSDHC Card | Storage | £9.99 | $13.41 | [Amazon](https://www.amazon.co.uk/PNY-Performance-Plus-microSDHC-Class/dp/B07R8GSQ4J/ref=sr_1_4?crid=1MLNYG558KHP7&dib=eyJ2IjoiMSJ9.DoJECtIYiG6EH3_FkuKqDFl6HBaBemGUEYUfVmWQ04rJxPUahgsPHaeEQFbzTGqzc_YFi8mlEZLiNNh8GvIjnYOOd4NhjuSIWKJ7xVu6TrfbydzFE0IcE2uf1e8_ThJ3PmSdwVZA5KiRurI5H8-xOQODgOqIQF_iDWFsM3_qWOQJqupYFAO2JGkwIJaFBwC8Ui63EXUNVfucJI1WmpRgkm9qyWMICH-3laQmt3AW5yU.raiA6fF2bLWx9IHUQwBZ72NEwFv6GeqBE2_M9jbzTRg&dib_tag=se&keywords=16GB%2BmicroSDHC&qid=1778774561&sprefix=16gb%2Bmicrosdhc%2Caps%2C180&sr=8-4&th=1) | 16GB Performance Plus |
|5D Nav Button | Controls | £0.76 | $1.02 | [AE](https://www.aliexpress.com/item/1005006140659397.html?spm=a2g0o.productlist.main.1.5801xSCxxSCxI7&algo_pvid=ce8190de-08c8-411c-9a3c-7ce4be544dc9&algo_exp_id=ce8190de-08c8-411c-9a3c-7ce4be544dc9-0&pdp_ext_f=%7B%22order%22%3A%221517%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%210.85%210.85%21%21%211.12%211.12%21%4021038e1e17787769944346538eb75e%2112000035941501876%21sea%21UK%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=vqkbyCj1ARne&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006140659397%7C_p_origin_prod%3A) | 25mm x 20mm |
|3.7V LiPo Battery | Power | £8.07 | $10.84 | [AE](https://www.aliexpress.com/item/1005011813548879.html?spm=a2g0o.productlist.main.8.6496WgJZWgJZ4T&aem_p4p_detail=202605160223382997468762533900002001148&algo_pvid=e6c0c5d8-9926-4268-8cc0-09854f26855b&algo_exp_id=e6c0c5d8-9926-4268-8cc0-09854f26855b-7&pdp_ext_f=%7B%22order%22%3A%228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2121.17%2110.58%21%21%21143.17%2171.58%21%40210390c217789234182662989eb181%2112000056648025026%21sea%21GB%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=D75Wy2TYyCX9&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011813548879%7C_p_origin_prod%3A&search_p4p_id=202605160223382997468762533900002001148_2) | 1pcs (2000mAh) |
|TP4056 LiPo charger | Power | £0.14 | $0.19 | [AE](https://www.aliexpress.com/item/1005009921928740.html?spm=a2g0o.productlist.main.11.19682GHS2GHSJc&algo_pvid=d4b17916-3253-4984-bbaa-6a3feeac220a&algo_exp_id=d4b17916-3253-4984-bbaa-6a3feeac220a-10&pdp_ext_f=%7B%22order%22%3A%22313%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.20%210.19%21%21%211.36%211.29%21%402103835c17789236069525962edd34%2112000050583215216%21sea%21GB%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=j6CcTLFakjAF&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009921928740%7C_p_origin_prod%3A#nav-description) | Type-C 1pcs |
|DD0403MB 3.3V LDO Module | Power | £2.21 | $2.97 | [AE](https://www.aliexpress.com/item/33054550198.html?spm=a2g0o.productlist.main.2.31eegP4ugP4uoZ&algo_pvid=c6b2fa6d-d6c6-4f60-b363-b4918f14f556&algo_exp_id=c6b2fa6d-d6c6-4f60-b363-b4918f14f556-1&pdp_ext_f=%7B%22order%22%3A%22815%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.80%213.80%21%21%213.80%213.80%21%402103894417789244828817565e26fa%2167459833680%21sea%21GB%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=8U80IYDtGI2M&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A33054550198%7C_p_origin_prod%3A#nav-specification) | Output 3V3 No Pin |
|SS-12D00G 5mm switch | Power | £0.76 | $1.02 | [AE](https://www.aliexpress.com/item/1005007585395420.html?spm=a2g0o.productlist.main.3.3a11rYu6rYu6AY&algo_pvid=3c9a1384-d88a-4988-92dc-b33baa922f93&algo_exp_id=3c9a1384-d88a-4988-92dc-b33baa922f93-2&pdp_ext_f=%7B%22order%22%3A%22847%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%212.08%211.17%21%21%2118.53%2110.38%21%40211b813f17787776971403762e05ff%2112000042242296593%21sea%21UK%217850874718%21X%211%210%21n_tag%3A-29919%3Bd%3Ac7b67d0a%3Bm03_new_user%3A-29895&curPageLogUid=5G2ubWLAgnKZ&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007585395420%7C_p_origin_prod%3A) | 20pcs SS-12D00G 5mm |
|Jumper Wires (Dupont) | Electronics | £3.30 | $4.43 | [AE](https://www.aliexpress.com/item/1005006616309305.html?spm=a2g0o.order_list.order_list_main.65.bf9918023CsPue) | 20cm M-M F-M F-F |
|Custom PCB | Electronics | £ | $ | [JLCPCB](https://jlcpcb.com) | (+ shipping) |
|3D Print Case Filament | Reimbursement | £ | $ | [HCB](https://hcb.hackclub.com) | Rounded to 250g? |
|5D Button Case Print | 3D Print File | N/A | N/A | [Makerworld](https://makerworld.com/en/models/402441-5-way-button-cap-cover?from=search#profileId-304081) | Or make my own? |
|**Total**| **All** | £36.64 | $49.20 | [BOM](https://github.com/gethin101/ghostone/blob/main/BOM.md) | Rest of funds used for upgrades |
