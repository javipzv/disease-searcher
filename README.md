# disease-searcher

## Description
This is a project developed by my colleagues and me. Using natural language processing techniques, it can identify diseases mentioned in a text.

The program employs disease prefixes and suffixes (e.g., hypo-, hyper-) to detect relevant medical terms, and then classifies them into various categories (such as pain or infection). Next, it queries a Spanish medical dictionary (https://www.cun.es/diccionario-medico/terminos/) to obtain definitions for the identified terms. The output is generated in the form of a .txt file, which includes a list of all the medical terms found, along with their definitions, types, and lemmas. If the program detects variations of a disease (such as 'carcinoma ductal' or 'carcinoma escamoso'), it only provides the definition of the general disease, while also adding a separate section for its variations.

Example:  
*carcinoma: m. Neoplasia maligna constituida por celulas epiteliales anáplasicas con capacidad metastásica.  
Tipo: Cáncer  
Forma invariable: carcin  
Variaciones: carcinoma basocelular, carcinoma ductal, carcinoma escamoso, carcinoma metastásico, carcinoma tiroideo*
