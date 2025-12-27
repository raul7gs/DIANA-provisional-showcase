# DIANA inner structure

DIANA divides the data analysis and visualization process in four* (data analysis also included in the full version) well differentiated parts, each related to a different step inside the data visualization process. These are: data processing, charts generation,
dashboards and report generation.
<img width="1291" height="331" alt="datavis" src="https://github.com/user-attachments/assets/a532283c-1a00-46ce-92f8-0186d7abd337" />

# Data processing

As mentioned in the general read me file, DIANA accepts multiple input formats. Preferibly CPACS (XML aircraft design schema) to perform the different aircraft design charts, as a predefined structure is needede for that level of detail. Nevertheless, csv data can
also be used as an input for the remaining functinalities within the app. Of course a previous DIANA project can al so be used as an input.

The application is able to deal with missing elements within the data, even whole structures (e.g. no tail geometry) due to the different aircraft architectures. Of ocurse cleaning and safety measures are applied in general to all files. The application has also been further developed considering big datasets, including techniques such as hashing to improve performance.

Once the files have been read and processed, a table is generated in the data section to allow a first superficial glance to the data. Users can here add new variables trough expressions, intervals,... and even adjust the variables and their order within the table.

<img width="1913" height="910" alt="image" src="https://github.com/user-attachments/assets/0f3e2d63-0068-401d-8e08-397b532130d7" />

It is also here where the user can generate the aircraft design charts, just by clicking on the aircraft involves and the type of chart. The different avialable charts can be shown in the picture below (when a chart cannot be generated for a certain aircraft selection, the option is gray out)

<img width="2525" height="204" alt="doc_kit" src="https://github.com/user-attachments/assets/46b12700-49f2-4d7d-8d55-c538b97c98ac" />








