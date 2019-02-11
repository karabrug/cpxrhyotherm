# cpxrhyotherm
**Low-Aluminum Clinopyroxene-Liquid Geothermometer for High-Silica Magmatic Systems**

*This Jupyter Notebook (cpxrhyotherm.ipynb) is a companion to:
Brugman & Till (2019) "A Low-Aluminum Clinopyroxene-Liquid Geothermometer for High-Silica Magmatic Systems".
See instructions and guidelines therein.*

*Please direct questions to the author: kara.brugman@gmail.com*

Requirements:

• Python v3.6 or higher

• Pandas

**For use only with clinopyroxene with Mg# ≤ 65 and Al2O3 ≤ 7 wt% from a bulk rock with SiO2 ≥ 70 wt%**

Enter paired clinopyroxene and liquid oxide compositions via an Excel workbook (inputtemplate.xlsx).

• Ideal scenario: for liquid, please use data from the glass adjacent to your clinopyroxene rim analysis.

• Less idea scenario: if paired clinopyroxene rim and adjacent glass analyses are not available, an average glass composition may be used.

• Desperate scenario: if no glass measurements are available, use whole rock as a last-resort only—whole rock and glass oxides are not the same, particularly in the oxides necessary to use the geothermometer. For example, a temperature calculated for Bishop Tuff samples using whole rock is > 60°C higher (> 3x the SEE) than a temperature calculated correctly with glass.
