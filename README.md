# Aluminium Extrusion Die Design Knowledge Graph Instruction








## Preface

This Knowledge Graph（KG） focuses on die design optimisation in the aluminium extrusion process, a significant industry that contributes more than 40% of the market capitalization in metal-forming processes. Because traditional die designs are imprecise and heavily rely on past experiences and analogy engineering, they constantly lead to longer development cycles. By compiling information from multiple engineering standards and existing die designs, a comprehensive KG that captures the essence of our understanding of aluminium extrusion die design will be created.

This instruction will introduce the main functions of KG and explain in detail how to use it. I hope you find this product helpful :>



## Functions

### Flowchart
For those new to Neo4j, starting with an embedded flowchart in the KG is an excellent way to begin. Beginners can initially familiarize themselves with the software through this flowchart and then progressively move towards more flexible usage as they gain confidence.
![Flowchart](https://github.com/limulusoma/limulusoma.github.io/assets/127602400/d3b78eb8-edfa-4914-8a5a-1229dc7a6f03)

### Flowchart cheat sheet
This cheat sheet includes various Neo4j query commands. Copy and paste these into the query box and hit 'Run' to explore specific nodes and their next levels within a flowchart.
<img width="965" alt="query box" src="https://github.com/limulusoma/limulusoma.github.io/assets/127602400/f8e1712f-300b-444d-9c2e-7b304a2c968b">

___
**Start**
```
MATCH p=(:Start)-[:Next]->(a)
RETURN p AS path
```
___
**Advanced**
```
MATCH p=(:Advanced)-[:Next]->(a)
RETURN p AS path
```
___
**Beginner**
```
MATCH p=(:Advanced)-[:Next]->(a)
RETURN p AS path
```
___
**Background Knowledge**
```
MATCH p=(:Background_Knowledge)-[:Next]->(a)
RETURN p AS path
```
___
**Guidelines**
```
MATCH p=(:Guidelines)-[:Next]->(a)
RETURN p AS path
```
___
**Material Selection Guide**
```
MATCH p=(:Material_Selection_Guide)-[:Next]->(a)
RETURN p AS path
```
___
**Product Profile Guide**
```
MATCH p=(:Product_Profile_Guide)-[:Next]->(a)
RETURN p AS path
```
___
**Die Design Guide**
```
MATCH p=(:Die_Design_Guide)-[:Next]->(a)
RETURN p AS path
```
___
**Forward**
```
MATCH p=(:Forward)-[:Next]->(a)
RETURN p AS path
```
___
**Improve Die Design**
```
MATCH p=(:Improve_Die_Design)-[:Next]->(a)
RETURN p AS path
```







