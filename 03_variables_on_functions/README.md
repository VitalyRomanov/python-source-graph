`wc -l var_use_edges.csv`
Output: 3784121

`cat var_use_edges.csv| awk -F"," '{print $4}' | sort | uniq | wc -l`
Output:  141584

