# Web-Client-development-WDC02-Tugas 1

Project built using the JavaScript programming language

## Tugas

**1. Write a code to find area of rectangle**
- **input**: length = 5, width = 3
- **output**: 15
  
```sh
// Declaration variable
let length = 5
let width = 3

// calculate area of rectangle
let area = length * width

// print
console.log("Area of Rectangle = " + area )
```

**2. Write a code to find diameter, circumference and area of a circle**
- **input**: radius = 5
- **output**: diameter = 10, circumference = 31.4159, area = 78.539
  
```sh
// Declaration variable
let radius = 5

// calculate diameter
let diameter = 2 * radius

// calculate circumference
let circumference = 2 * Math.PI * radius

// calculate area of circle
let area1 = Math.PI *Math.pow(radius, 2)

// print
console.log("Diameter lingkaran adalah: " + diameter)
console.log("Keliling lingkaran adalah: " + circumference.toFixed(4))
console.log("Luas lingkaran: " + Math.floor(area1 * 1000) / 1000)
```

**3. Write a code to find angles of triangle if two angles are given**
- **input**: a = 80, b = 65
- **output**: 35
  
```sh
// Declaration angle
let angleA = 80
let angleB = 65

// Calculate angleC
let angleC = 180 - (angleA + angleB)

// Print
console.log("Sudut ketiga adalah: " + angleC)
```

**4. Write a code to get difference between dates in days**
- **input**: date1 = 2024-03-19, date2 = 2024-03-21
- **output**: 2
  
```sh
// Declaration two date
let date1 = new Date('2024-03-19')
let date2 = new Date('2024-03-21')

// Calculate
let daysDifference = date2.getDay() -date1.getDay()

// Print
console.log("days difference: " + daysDifference)
```

**5. Write a code to print your name initial in uppercase**
- **input**: John Doe
- **output**: JD
  
```sh
// Declaration name
let fullName = "John Doe"

// separating name
let nameParts = fullName.split(" ")

// taking initial
let initial1 = nameParts[0].charAt(0).toUpperCase();
let initial2 = nameParts[1].charAt(0).toUpperCase();

//combining
let initial = initial1 + initial2

// print
console.log("inisial nama anda: " + initial)
```
