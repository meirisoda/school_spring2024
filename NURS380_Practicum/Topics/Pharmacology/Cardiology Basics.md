# Pathophysiology
``` dot
digraph G {
	subgraph cluster_0 {
		style=filled;
		color=lightgrey;
		node [style=filled,color=white];
		A [label="Right atrium"];
		A -> a1 -> a2 -> a3;
		label = "Contraction";
	}
	start -> A;
	a1 -> b3;
	b2 -> a3;
	a3 -> a0;
	a3 -> end;
	b3 -> end;
	start [label=Contraction, shape=diamond];
	end [shape=Msquare];
}
```
# Antiarrhythmics
## Amiodarone
