# Pathophysiology
``` dot
digraph G {
	subgraph cluster_0 {
		node [style=filled,color=grey];
		label="Contraction"
		A [label="Right atrium"];
		B [label="SA node"];
		C [label="AV node"];
		D [label="His&Purkinje fibers"];
		E [label="Ventricles"];
		F [label="Ventricular contraction", color="white"];
		A -> B
		B -> C [label="conducts an electrical signal"];
		C -> D -> E -> F;
	}
}
```
# Antiarrhythmics
## Amiodarone
