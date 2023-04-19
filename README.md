Three options for a snake (from the his perspective)
1. straight [1,0,0]
2. turn right [0,1,0]
3. turn left [0,0,1]

state: 11 values: [danger straight, danger right, danger left,
                    direction left, direction right,
                    direction up, direction down,
                    food left, food right,
                    food up, food down]


model: neural network 11 -> 3