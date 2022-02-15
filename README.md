# StavangerStatuar
Døme på sem.web. tech

Ein mal for å konvertere data frå ei excel fil RDF.

"The Resource Description Framework is a World Wide Web Consortium standard originally designed as a data model for metadata. It has come to be used as a general method for description and exchange of graph data. -Wikipedia"

Bruk Lutra til å ekspandere: https://ottr.xyz/event/2018-10-08-iswc/#3_Lutra 
java -jar lutra/lutra.jar \
--mode expand \
-L stottr \
-l lib/library.stottr \
-f \
-o output \
-I tabottr \
data/skulpturer-i-stavanger.xls
