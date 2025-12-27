### DIANA inner structure

DIANA divides the data analysis and visualization process in four* (data analysis also included in the full version) well differentiated parts, each related to a different step inside the data visualization process. These are: data processing, charts generation,
dashboards and report generation.
<img width="1291" height="331" alt="datavis" src="https://github.com/user-attachments/assets/a532283c-1a00-46ce-92f8-0186d7abd337" />

### Data processing

As mentioned in the general read me file, DIANA accepts multiple input formats. Preferibly CPACS (XML aircraft design schema) to perform the different aircraft design charts, as a predefined structure is needede for that level of detail. Nevertheless, csv data can
also be used as an input for the remaining functinalities within the app. Of course a previous DIANA project can al so be used as an input.

The application is able to deal with missing elements within the data, even whole structures (e.g. no tail geometry) due to the different aircraft architectures. Of ocurse cleaning and safety measures are applied in general to all files. The application has also been further developed considering big datasets, including techniques such as hashing to improve performance.

Once the files have been read and processed, a table is generated in the data section to allow a first superficial glance to the data. Users can here add new variables trough expressions, intervals,... and even adjust the variables and their order within the table.

<img width="1913" height="910" alt="image" src="https://github.com/user-attachments/assets/0f3e2d63-0068-401d-8e08-397b532130d7" />

It is also here where the user can generate the aircraft design charts, just by clicking on the aircraft involves and the type of chart. The different avialable charts can be shown in the picture below (when a chart cannot be generated for a certain aircraft selection, the option is gray out)

<img width="2525" height="204" alt="doc_kit" src="https://github.com/user-attachments/assets/46b12700-49f2-4d7d-8d55-c538b97c98ac" />

### Charts

To get better insights of the data, it is necessary to visualize it. Two main options exist within DIANA, the previously mentioned kits (there is one for aircraft design, another for ATC, ...) and the personalized plots, which allow user to find their own insights (GUI is shown below)

<img width="2559" height="1249" alt="doc_markers" src="https://github.com/user-attachments/assets/944d773a-777c-4b75-aa3f-bfb76c0cebd5" />

The GUI of each personalized plot can be observed in the picture below. First in the top we have the axes. To generate a chart in DIANA is really simple, you just need to select the variables to be included in the chart and automatically it will be generated (more information on how is found in the variables section). Once the chart has been generated, the GUI allows to add additional markers, filter the data, change the plot type and change additional settings.

This section includes the possiblity to add markers as colour, size or shape. Also dynamic filters can be added, and basis settings can be modified. FInally, if the data selected can be plotted in a different chart type, all the different options will appear coloured (as observed below). To change to a different plot type, it is only necessary to click ojn the corresponding picture. In this example a filter for the wing span has been applied and the chart type has been changed to a parallel coordinate chart.

<img width="2557" height="1266" alt="doc_filters_plot_type" src="https://github.com/user-attachments/assets/7065e1cb-9ba2-444f-9e2e-65252b2ef670" />

Some of the available charts: Scatter, bar, multibar, parallel coordinate, box plot, correlation matrix, radar, scatter metrix,...

### Dashboard

Once all the necessary charts have been generated, these can be combined together for decision-making in the dashboard tab, as shown below. The process to generate a dashboard is really simple. There is a selector in the top of the GUI with all the charts that have been generated, either aircraft design charts or personalized ones. The user just needs to click on the desired charts and they will be incorporated into the dashboard. To maintain an optimal balance between information density and readability needed for decision-making, users can generate new dashboards by clicking the blue addition button on the top left

<img width="2552" height="1232" alt="doc_dash1" src="https://github.com/user-attachments/assets/9a7270dc-3e79-4a6e-ba40-ad48c004194d" />

Each dashboard is a white canvas, where the user can add as many charts as desired. Moreover, the user has full control over each chart size and positioning, through drag-and-drop functionality. The chart can be moved by clicking on the top right and its dimensions can be modified by clicking on the bottom right.

Dashboards also allow to add text and images. In the case of texts, a drag and drop element with modifiable text will be added. For images, an expandable asking for a picture to be uploaded will appear.

Finally, it is important to mention that the different charts within the app are interconnected. This means if one or more design points are filtered or selected in one chart, the same will happen in the other charts, as shown below.

<img width="2556" height="1224" alt="doc_dash2" src="https://github.com/user-attachments/assets/6fafe94b-de0a-45e2-bf31-8cc7474d6749" />

## Report generation

Finally, an automatic report can be obtained. For more information, user is related to the AIAA paper.












