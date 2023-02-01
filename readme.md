# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [
      0.0005000500050005,
      0.00010001000100010001
    ],
    "translate": [
      100,
      0
    ]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {
            "prop0": "value0"
          },
          "coordinates": [
            4000,
            5000
          ]
        },
        {
          "type": "LineString",
          "properties": {
            "prop0": "value0",
            "prop1": 0
          },
          "arcs": [
            0
          ]
        },
        {
          "type": "Polygon",
          "properties": {
            "prop0": "value0",
            "prop1": {
              "this": "that"
            }
          },
          "arcs": [
            [
              1
            ]
          ]
        }
      ]
    }
  },
  "arcs": [
    [
      [
        4000,
        0
      ],
      [
        1999,
        9999
      ],
      [
        2000,
        -9999
      ],
      [
        2000,
        9999
      ]
    ],
    [
      [
        0,
        0
      ],
      [
        0,
        9999
      ],
      [
        2000,
        0
      ],
      [
        0,
        -9999
      ],
      [
        -2000,
        0
      ]
    ]
  ]
}
```
