# Estimating Direct and Indirect CO2 Emission Coefficients by Economic Sector

---

- With the advancement of the carbon market, one pertinent information for investors will be the quantity of CO2 emissions produced by a given economic sector. It's essential to determine how much CO2 a specific sector (e.g., Mining and quarrying) emits when producing a certain amount of goods by value. It's also important to understand how much CO2 the sector indirectly consumes in its production process. One way to ascertain this is by utilizing Input-Output matrix data and the Leontief inverse matrix.

- This code demonstrates how to estimate the direct and indirect emission coefficients (Gg/mi euros) for 64 economic sectors in Spain.

- To derive these coefficients, we've utilized the 2019 production (in million euros) and emission (in Gg of carbon equivalent) data from Spain.

- The methodology adopted was the one presented by Luis Maza in the article **AN ESTIMATION OF THE CARBON FOOTPRINT IN SPANISH CREDIT INSTITUTIONS’ BUSINESS LENDING PORTFOLIO**. You can find the article [here](https://repositorio.bde.es/bitstream/123456789/29610/4/do2220e.pdf).

- The file 'code1.ipynb' demonstrates how to recreate these calculations using Python.

- The resulting coefficients for 2019 can be found in the file 'results.csv'.

![Alt text](https://raw.githubusercontent.com/fms-1988/datas/main/pic_1.png)

--- 













