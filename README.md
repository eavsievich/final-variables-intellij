Variables finalizator for IntelliJ IDEA
============================

Inspection for IntelliJ IDEA to find variables which may safely be made final

Instruction:

1. Go to Analyze -> Inspect Code
2. Import 'finalized_variables_idea' in Inspection profile section
3. Apply inspection
4. There is 2 different Code Style issues:
    * Field may be final
    * Local variable or parameter can be final
5. Right-click on each of them, and select "Apply fix" or anything similar option
