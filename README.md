# excelLIM v1.0.0

Excel-based automatic translation of network input data into LIM declaration file format. 
Outputs both unweighted and weighted LIM declaration files for one static network.
For use with R packages LIM (v 1.4.6 Van Oevelen et al., 2010), limSolve (v 1.5.1 Soetaert et al., 2009)

View the user guide here: https://gemmagerber.github.io/excelLIM/

## News!

### excelLIM v1.0.0
- NEW RELEASE: 15 March 2023
- Updated application name
- Updated assimilation efficiency translation to include only absolute values

### (development) autoLIM-Excel v0.20.01.22
- Bug fixes
- Added a small, theoretical four node example called "Winter"
- Updates for LIM decaration files to match those exactly from autoLIMR
- Adjacency Matrix automatically pulls in compartment names form "Network Data", but includes zeros for blank cells. Replaced formulas to exclude blank cells

### (development) autoLIM-Excel v0.16.12.21 Updates:
- Changed name of "LIM Input" sheet to "Network Data"
- Adjacency Matrix - A check to see if all compartments have flows to them 

### (development) autoLIM-Excel v0.10.12.21 Updates:
- Added in code to change decimal separators from commas to decimals in LIM Input
- Rearranged NLNodes to end of list (Required by enaR::enaTroAgg function (Lau et al.,2017))
- Added in Power Query function to return LIM sections as one merged table.
- Added in intentionally blank lines at the end of each LIM file to negate the error of "incomplete final line"

### (development) autoLIM-Excel v0.06.12.21 Updates
- Now supports up to 100 compartments!
