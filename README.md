# Product-Information-Parser-RegEx
For example, the textual description of a set of products
example='''
P1 is a product composed of P2 and P3
P2 is an elementary product
P5 is a product composed of P1 and P4
P4 is an elementary product
P9 is a product composed of P1, P6 and P4
P10 is a product composed of P3 and P5
P11 is a product composed of P5 and P3 '''
Use regular expressions to:
1. Find all the elementary products
2. Products composed of three products
3. Products composed only of P3 and P5 products
4. Compound products that do not have P2 in their compositions
5. The products that make up P9
