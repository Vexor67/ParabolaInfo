# ParabolaInfo

**Created by Vashishth Patel, 16th Dec 2025**  
For educational/portfolio purposes.  

## Description
ParabolaInfo is a Mathematica command to return relevant information about a **vertical parabola**:
- Equation
- Turning point form (vertex form)
- Domain and range
- X and Y intercepts
- Vertex
- Axis of symmetry
- Focus and directrix
- Derivative
- Bounded total area

This command is designed for learning and experimentation.  


## Usage
```mathematica
ParabolaInfo[x^2 - 4 x + 2, {x, -5, 10}, y]
```

```mathematica
Example output:
Equation: y = x^2-4 x+2
Turning Point Form: (x-2)^2-2
Domain: -5 <= x <= 10
Range: -2 <= y <= 62
X Intercepts: {{2-Sqrt[2], 2+Sqrt[2]}}
Y Intercepts: {2}
Vertex: {2, -2}
Axis of Symmetry: x = 2
Focus: {2, -7/4}
Directrix: y = -9/4
Derivative: 2 (x-2)
Bound Total Area: 8 Sqrt[2]/3
```

## Notes
- Any variable can be used for input or output.
- Code assumes vertical parabolas.
- May not be perfectly optimised, so use at your own discretion.