# convert-RecordList-to-DictList

converts recordlist generated by Neo4j cypher to a list of dictionaries
each dictionary contains all data from each record in property:value format
and contains id(node) data in the node_id key pair
it takes input in form : Graph.cypher.execute('WHATEVERHAPPENS-IN-THE-QUERY return n, keys(n)')
