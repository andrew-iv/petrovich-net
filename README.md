NPetrovich
==========

NPetrovich is C#/.NET port of [Petrovich](https://github.com/rocsci/petrovich) ruby gem.

## Installation

Just reference NPetrovich dll to your project. Nuget package coming soon

##

Basic usage

```csharp
var petrovich = new Petrovich() { FirstName = "����", LastName = "", MiddleName = "", Gender = Gender.Male };
petrovich.InflectTo(Case.Dative);

// petrovich.FirstName = �����
// petrovich.LastName = �������
// petrovich.MiddleName = ���������
```

## To be done

* Add documentation
* Add comments to the code
* Nuget package
* Add tests
* Add different rules format support
* Do some refactorings
