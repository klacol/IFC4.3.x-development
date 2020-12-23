# IfcLamp

A lamp is an artificial light source such as a light bulb or tube.

> HISTORY&nbsp; New entity in IFC4

{ .note}
>

## Attributes

### PredefinedType


## WhereRules

### CorrectPredefinedType
Either the _PredefinedType_ attribute is unset (e.g. because an _IfcLampType_ is associated), or the inherited attribute _ObjectType_ shall be provided, if the _PredefinedType_ is set to USERDEFINED.

### CorrectTypeAssigned
Either there is no lamp type object associated, i.e. the _IsTypedBy_ inverse relationship is not provided, or the associated type object has to be of type _IfcLampType_.