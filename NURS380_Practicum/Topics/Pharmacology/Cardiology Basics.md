# Pathophysiology
``` dot
digraph G {
	subgraph cluster_0 {
		graph [linelength=5];
		node [style=filled,color=grey];
		label="Contraction"
		A [label="Right atrium"];
		B [label="SA node"];
		C [label="AV node"];
		D [label="His & Purkinje fibers"];
		E [label="Ventricles"];
		F [label="Ventricular contraction", color="white"];
		A -> B
		B -> C [label="conducts an\n electrical signal"];
		C -> D -> E -> F;
	}
}
```
# Antiarrhythmics
## Amiodarone
### Type
Class III Antiarrhythmic
Inhibits potassium receptor responsible for repolarizing the heart $\rightarrow$ $K^+$ CCB effect
### Results
$\uparrow$ action potential duration, prolonged effective refractory period.
### Administration
| IV | Oral |
| ---- | ---- |
| 150mg/10min<br>1mg/min/6hrs<br>0.5mg/min/18hrs | 800-1600mg/daily |
### Considerations
