# Pathophysiology
``` dot
digraph G {
	subgraph cluster_0 {
		style=filled;
		color=lightgrey;
		node [style=filled,color=white];
		A [label="Right atrium"];
		B [label="SA node"];
		C [label="AV node"];
		D [label="His&Purkinje fibers"];
		E [label="ventricles"];
		A -> B -> C -> D -> E;
	}
	start -> A;
	E -> end;
	start [label=Contraction, shape=diamond];
	end [label="Ventricular contraction", shape=diamond];
}
```
# Antiarrhythmics
## Amiodarone
