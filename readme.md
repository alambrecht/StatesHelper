# States Helper

Simple library for returning collection of US states and Canadian Provinces

```
public class States
{
    public string Name { get; set; }
    public string Abbreviation { get; set; }
    public string Country { get; set; }
}
```

Usage:

```
var states = States.GetStatesFromXml();
```