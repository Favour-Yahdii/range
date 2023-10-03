# range
This contains code to solve the range problem. LIDA data workshop 23

## scenario 1 - no overlap/ touching at a point
- params: [[-3, 0], [0, 4.5]]
- result: 'point' 

## scenario 2 - not touching at all
- params: [[-3, 0], [1, 4.5]]
- result: 'no overlap' 

## scenario 3: insufficient params
- params: [-3, 1]
- result: 'enter at least 2 ranges'

## equal ranges
- params: [[0, 5], [0, 5]]
- result: [-3, 2]

## scenario 5: example
- params: [[-3, 5], [0, 4.5], [-1, 2]]
- result: [0, 2]