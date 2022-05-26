# XDTesting Validate JSON
This action can check the syntax of a JSON file that is constructed to represent the expected results of a SPARQL query. The SPARQL query is needed to construct test cases for competency question verification and for inference verification. These test cases are conceptualized based an [eXtreme Design](extremedesign.info) methodology. 

# Usage 
Add the following entry to your Github workflow YAML file:

```
steps:
  - name: XDTesting Validate JSON
    uses: FiorelaCiroku/XDTesting-ValidateJSON@v1.0.0
  
```
