# autoLIM-Excel

Latest version: autoLIM-Excel 4node Winter ** Testing version

Excel-based automatic translation of network input data into LIM declaration file format. 
Outputs both unweighted and weighted LIM declaration files for one static network.
For use with R packages LIM (v 1.4.6 Van Oevelen et al., 2010), limSolve (v 1.5.1 Soetaert et al., 2009), and FlowCAr (v 1.1.1 Waspe et al., 2018)

News!

v 4node Winter Updates:
- Added a small, theoretical four node example called "Winter"
- Updates for LIM decaration files to match those exactly from autoLIMR

v1.20.01.22 Updates:
- Adjacency Matrix automatically pulls in compartment names form "Network Data", but includes zeros for blank cells. Replaced formulas to exclude blank cells

v1.16.12.21 Updates:
- Changed name of "LIM Input" sheet to "Network Data"
- Adjacency Matrix - A check to see if all compartments have flows to them 

v1.10.12.21 Updates:
- Added in code to change decimal separators from commas to decimals in LIM Input
- Rearranged NLNodes to end of list (Required by enaR::enaTroAgg function (Lau et al.,2017))
- Added in Power Query function to return LIM sections as one merged table.
- Added in intentionally blank lines at the end of each LIM file to negate the error of "incomplete final line"

v1.06.12.21 Updates
- Now supports up to 100 compartments!

