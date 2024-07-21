# Uncertain Damage Ontology
The Uncertain Damage Ontology (UDO) is designed to represent uncertainties in damage assessment. In its current state, UDO supports the representation of undetect damage (<a href="https://w3id.org/udo#UndetectedDamage">udo:UndetectedDamage</a>) as well as ambigious damage (<a href="https://w3id.org/udo#AmbigiousDamage">udo:AmbigiousDamage</a>). Furthermore, fuzzy values can be represented and assigned to instances of <a href="https://w3id.org/udo#UndetectedDamage">udo:UndetectedDamage</a> by utilizing instances of <a href="https://w3id.org/udo#UncertainValue">udo:UncertainValue</a>.

The namespace for UDO terms is <span class="repeated" style="font-family: courier;">https://w3id.org/udo#</span>

The suggested prefix for the UDO namespace is <span class="repeated" style="font-family: courier;">udo</span>

UDO is an extension of the existing ontology <a href="https://w3id.org/dot">DOT</a> and therefore reuses various classes and properties from it.

## Examples for inferring undetected damages
Examples for SHACL rules that utilize UDO can be found in the example/example_rules directory. A corresponding test-case can be found in the example/testcase directory. There, ABoxes are deployed on which the SHACL rules can be applied.