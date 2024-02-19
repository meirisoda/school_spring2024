# Pathophysiology
``` dot
digraph G {
	subgraph cluster_0 {
		style=filled;
		color=lightgrey;
		node [style=filled,color=white];
		hello -> a1 -> a2 -> a3;
		label = "process #1";
	}
	start -> hello;
	start -> b0;
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
