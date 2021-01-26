In this repository you will find the instances (Instances), graphs (Grafos) and the results (Resultados_Lineal, Resultados_Lineal_Def, Resultados_Lineal_Exc, Resultados_Lineal_eps, Resultados_Lineal_vol) corresponding to the proyect: Updating origin-destination matrices and route choice probabilities in public transportation networks.

Below we explain the content of each folder.

- Grafos: contains png figures that represent the graph of the generated networks. So, figure 5Nodes.png represents the netwoks with 5 nodes and 1, 2 or 3 lines. In particular,
          figure 5Nodes_5Lines.png reprsents a transit network with 5 nodes and 2 transit lines.

- Instances: contains csv files with the numeric characteristics of the generated instances. Each instance consists on 4 csv files. For example, the instance with 5 Nodes and 2
          lines is composed by the files matrizobsoleta5Nodes2Lines.csv, matrizreal5Nodes2Lines.csv, proporciones5Nodes2Lines.csv and vobs5Nodes2Lines.csv. Next we describe each
          file:
          - matrizobsoleta5Nodes2Lines.csv. These data correspons to the target demand matriz. Column 1 and row 1 are indexes that can be ignored. Columns 2 and 3 represents 
            the origin and destination nodes, respectively, and column 4 represents the number of trips. So we can se that from node 1 to node 4, 4872 trips are carried out.
          - matrizreal5Nodes2Lines.csv. These data correspons to the exact demand matriz. Column 1 and row 1 are indexes that can be ignored. Columns 2 and 3 represents the
            origin and destination nodes, respectively, and column 4 represents the number of trips. So we can se that from node 1 to node 2, 10296 trips are carried out.
          - proporciones5Nodes2Lines.csv. These data correspons to the probabilities to travel from the origins to the destinations taking each line wich connect two nodes. Column
            1 and row 1 are indexes that can be ignored. Columns 2 and 3 represents the origin and destination nodes, respectively, column 4 represents the identifier of the line,
            columns 5 and 6 represent the nodes connected by a transit segment and column 7 represents the probabilities. So we can se that to go from the origin 4 to the 
            destination 2, the probability of takin line 1 to go from node 3 to node 2 is 0.5.
          - vob5Nodes2Lines.csv. These data correspons to the observed flows in the transit segments. Column 1 and column 1 are indexes that can be ignored. Column 2 is the line
            identifier, columns 3 and 4 represents the beginnig and the end of the transit segment, respectively, and column 5 represents the observed flow. So we can see that in
            the transit segment of line 1 that connects nodes 3 and 2, beginning in 3 and ending in 2, 12308 trips were observed. 

