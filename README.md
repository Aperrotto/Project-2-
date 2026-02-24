# Project-2-Automation of Concrete Mix Design.
---
This includes files for Project no. 2
---
## Project goals:  

The Nebraska Department of Transportation (NDOT) has asked this group to convert the information pertaining to concrete mix design from the given Excel sheet into a Python-based system that accomplishes the same task – providing a weight summary chart for given mix design parameters.  

The main goal of this project is to replicate the logic contained in the Mix Design worksheet and automate it so users can enter different variables, such as material properties and other design parameters into it. The program needs to output a weight chart for one cubic yard of concrete. In order to achieve this, we must complete these project tasks which will be addressed in more detail below: 

1. Turn the  logic from the Excel worksheet into Python modular functions. 

2. Put in a user input sequence that works with the design process. 

3. Create a mix weight chart for 1 cubic yard of concrete. 

4. Create 4 concrete mix designs using the NDOT system. 

5. Create the code and document the processes and reports. 
 

## Project Tasks: 

1. Translate the Excel Logic into Python 

- To do this we must first understand the NDOT Mix Design Excel and find the information to convert to Python. Once all the inputs and calculations/equations have been identified, they can be defined in python using the “def” function. Variables for the material weights, ratios, aggregate proportions, air content adjustments, and conversions will all be made in Python and mirror that of the Excel. 

2. Implement Sequential User Inputs 

- To do this we must recreate the design inputs from excel and organize them into categories such as general info, cementitious material inputs, design parameters, etc. These inputs will be collected from the user in Python by utilizing “input()” functions. All inputs will be organized in a manner that mirrors the Excel. 

3. Generate a Final Mix Design Output 

- To do this, the program will take the user defined inputs from the previous task and use them in the defined functions from task 1. Once all calculations have been completed, we can utilize the “print()” function and f-strings to create a table-like output similar to the Excel.  

4. Prepare and Evaluate Four Concrete Mix Scenarios 
 

- For this task we must first research concrete designs using the NDOT documents and specifications, along with other resources, to determine the mix parameters for certain types of concrete. Then we can run them through the python model and compare the outputs for the mixes to ensure that our Python model is producing accurate results. 
## Mix Scenarios Research and Documentation 

In concrete engineering, designing a mix involves proportioning fine and coarse aggregates, cementitious materials, and water to meet specific performance criteria like workability, strength, and durability. State DOT specifications define these classes to standardize construction for varying environments, from high-traffic pavements to structural bridge components. 

1. Class 47BD Concrete (Bridge Decks) 

- This mix is specifically designed for bridge decks, featuring a higher cementitious material content and a lower water-to-cement ratio to increase durability and reduce permeability. 

- Total Cementitious Materials: 658 lb/yd³ (minimum). 

- Total Aggregate: 2,500 lb/yd³ (minimum) to 3,000 lb/yd³ (maximum). 

- Air Content: 6.5% to 9.0%. 

- Maximum Water/Cement Ratio: 0.42 lb/lb (typical NDOT standard for 47BD). 

- Minimum Required Strength: 4,000 psi (at 28 days). 

- Common Use: Bridge decks and bridge approach slabs. 

- Reference: NDOT 2017 Standard Specifications Table 1002.02. 

2. Class 47B-HE Concrete (High Early Strength) 

- This mix is used when rapid strength gain is required, such as pavement repairs or intersections that need to be opened to traffic quickly. 

- Total Cementitious Materials: 752 lb/yd³ (minimum). 

- Total Aggregate: 2,500 lb/yd³ (minimum) to 3,000 lb/yd³ (maximum). 

- Air Content: 6.5% to 9.0%. 

- Maximum Water/Cement Ratio: 0.40 lb/lb. 

- Minimum Required Strength: 3,500 psi (typically required in as little as 48 hours depending on project needs). 

- Common Use: Rapid-entry pavement repairs and "High Early" strength applications. 

- Reference: Nebraska DOT (2017) Standard Specifications, Section 706 (Concrete Bridge Floors) and Table 1002.02 

 

3. Iowa DOT Class C (Structural & Paving) 

- Iowa's primary structural mix used for highway paving and box culverts. 

- Total Cementitious Materials: 611 lb/cy (approximate based on standard Iowa 50/50 split). 

- Total Aggregate: ~3,100 lb/cy (total combined dry weight). 

- Target Air Content: 6.5% (± 1.5%). 

- Maximum Water/Cement (w/c) Ratio: 0.488 lb/lb (Target typically 0.43). 

- Minimum Required Strength: 4,000 psi (at 28 days). 

- Reference: Iowa DOT Standard Specifications Section 2403. 

4. Colorado DOT (CDOT) Class D (Structural) 

- A high-density mix used for bridge decks, rails, and structural elements requiring higher strength. 

- Total Cementitious Materials: 615 lb/cy (minimum). 

- Total Aggregate: ~3,000 lb/cy (total dry weight). 

- Target Air Content: 5.0% to 8.0%. 

- Maximum Water/Cement (w/c) Ratio: 0.44 lb/lb. 

- Minimum Required Strength: 4,500 psi. 

- Reference: CDOT 2023 Standard Specifications Section 601, Table 601-1. 
