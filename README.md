# SimpleMinMaxSlider for Unity

![](Demonstration.gif)

# Installation

  1. Open package manager
  2. Add package from git URL
  3. Paste: https://github.com/ivan-coder/SimpleMinMaxSlider.git#upm (remember the #upm at the end)
  4. Let Unity do its thing
  5. Done.

# Usage

Include namespace at the top of your script:
```C#
using GD.MinMaxSlider;
```

Code for the demonstration above:
```C#
[MinMaxSlider(0,10)] 
public Vector2 floatTest = new Vector2(2f, 8f);

[MinMaxSlider(0,10)]
public Vector2Int intTest;
```

Very simple and very handy!
