# Pathophysiology
``` dot
digraph G {
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
- Contraindicated in patients with: 2nd/3rd degree blocks w/out pacemakers, concurrent afib
- Make sure to monitor electrolytes
# $\beta$-blockers
(-lol)
Typically treats CV diseases, but also more uncommon things like long QT syndrome, hypertophic obstructive cardiomyopathy. 
### Mechanism of Action
```dot
digraph G {
	A [label="beta-receptors", style=filled, color=lightgrey];
	B [label="epinephrine"];
	C [label="norepinephrine"];
	D [label="renin"];
	E [label="lowers BP, HR, CO, renin, and oxygen demand", shape=box];
	F [label="also lowers melatonin secretion"];

	B -> A [label="binds to"];
	C -> A
	A -> D [label="also\nreleases"];
	A -> E -> F 
}
```
