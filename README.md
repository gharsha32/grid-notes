# grid-notes
### To create rows and size them
```bash
grid-template-rows: sizeOfFristRowpx sizeOfSecondRowpx sizeOfThirdRowpx ...
```

### To create coloumns and size them
```bash
grid-template-coloumns: sizeOfFristColoumnpx sizeOfSecondColoumnpx sizeOfThirdColoumnpx ...
```

### To give a gap between rows and coloumns
```bash
grid-gap: amountOfGapInNumberspx
```

### To view the gap
Inspect element/layout

### To modify autometically created rows
```bash
grid-auto-rows: sizeOfFristRowpx sizeOfSecondRowpx sizeOfThirdRowpx ...
```

### To make an element in a row into an element of a column
```bash
grid-auto-flow: column
```

### To adjust the size of a newly created elemnt [*From above step]
```bash
grid-auto-column: sizeOfFristColumnpx sizeOfSecondColumnpx sizeOfThirdColumnpx ...
```

### To build a No. rows with same size
```bash
grid-template-rows: repeat(n, sizeOfTheRow) [*n is the number of times you want to repeat the column]
```
### To span 1 entair column
```bash
grid-column:1/-1
```

### Unit to be used to take up full free space
```bash
fr unit
```

### To spacify names to grid areas
```bash
grid-template-areas: "nameOfArea"
```

### 
