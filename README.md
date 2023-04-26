# disease-searcher

## Description
This is a project made by some friends and me. Using some natural language processing, you can detect diseases in a text.

Using some NLP libraries, we can detect all those terms related to medicine, thanks to the search for disease prefixes and suffixes (hypo, hyper...). Based on them, we can classify the diseases found in their different types (Pain, Infection...). Subsequently, a Spanish medical dictionary (https://www.cun.es/diccionario-medico/terminos/) is accessed to find its definitions. Once searched, the output is generated: a .txt document with all the medical terms found, with their definition and type, as well as their invariable form (lexema). In addition, if specific variations of a disease are found (ductal carcinoma, squamous cell carcinoma...), only the definition of the general disease will be given and a section will be added for its variations.

Example:  
carcinoma: m. Neoplasia maligna constituida por celulas epiteliales anáplasicas con capacidad metastásica.  
Tipo: Cáncer  
Forma invariable: carcin  
Variaciones: carcinoma basocelular, carcinoma ductal, carcinoma escamoso, carcinoma metastásico, carcinoma tiroideo
