A python script that colapse similar markers into one line in order to simplify further analyses.

python merger.py input.csv output.csv  

Input: Comma separated Values
Columns: Id,chromosme, position (if any), marker values or missing data ('-')
1040965*_1A,1A,1627778,-,A,A,B,B,-,-,A

Output: Tab separated values
Columns: Collapsed Ids,chromosme, position of first marker (if any), marker name of first position (if any), marker values or missing data ('-')
{1121398_6B}    6B      96329366        1121398_6B      B       A       A       A       A       A       B       B       B       A     A