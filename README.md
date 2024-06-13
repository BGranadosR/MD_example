# Typora Example

## To-do List

- [x] task 1

- [ ] task 2
- [x] task 3

## Math Equations

$$
A = \frac{5}{3}
$$

## Code Blocks

### Python

```python
a = 0
for i in range(1:11):
	a += i
print(a)
```

### Verilog

```verilog
module top (
    input	[3:0]	a,
    input 	[3:0]	b,
    output 	[3:0]	c
);

assign c = a + b;

endmodule
```

## Block Diagram

```sequence
Alice -> Bob: Hello Bob, how are you?

Note right of Bob: Bob thinks

Bob -- Alice: I am good thanks !

Charly -> Bob: Hello
Note right of Charly: Charly thinks
```

## Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-99,19],
              [-99,19.1],
              [-99.1,19.1],
              [-99.1,19],
              [-99,19]
          ]
        ]
      }
    }
  ]
}
```
